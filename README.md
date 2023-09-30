# MERN Stack Quiz Application

Welcome to the MERN Stack Quiz Application GitHub repository!
 This project is a full-stack web application built using the MERN stack, which includes MongoDB, Express.js, React.js, Node.js along with Mongoose, and CSS. 
 The application allows users to play quizzes, supports Create and Read operations on data fetched from a RESTful backend API, and offers a range of features for an engaging quiz experience.

 ![App Image](https://github.com/CHEEMS-1206/QUIZ_APP_MERN_PROJECT/blob/master/projectImages/landingPage.png)

## Features

- **UI with React**: The user interface is built using React.js, providing a responsive and interactive experience, and used CSS for styling.

- **Routing with React Router**: React Router is used to manage routes to different pages within the application, ensuring a smooth navigation experience.

- **State Management with Redux**: Redux is employed for state management, enabling efficient data flow and updates across components.

- **React Hooks**: Modern React hooks are used for various functionalities, enhancing the application's maintainability.

## Backend Architecture

The project follows a Model-Route-Controller architecture to create a RESTful API for the backend:

- **Model**: Defines the structure and schema for data storage in MongoDB using Mongoose.

- **Routes**: Handle the HTTP routes for the API, defining how clients can interact with the server.

- **Controller**: Contains the logic and functions that control the application's behavior.

## Technologies Used

- **Frontend**:
  - React.js
  - CSS
  - React Router
  - Redux
  - React Hooks

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose
  - Axios

## Pages

The MERN Stack Quiz Application consists of the following pages:

1. **Home Page**: Users are greeted with a home page where they are prompted to enter their name before starting the quiz.

   ![App Image](https://github.com/CHEEMS-1206/QUIZ_APP_MERN_PROJECT/blob/master/projectImages/landingPage.png)

3. **Question Page**: Once a user enters their name, they are directed to the question page. Here, multiple questions are displayed one after another, along with answer options. Users can navigate through questions using buttons provided on the page.

  ![Questions Page](https://github.com/CHEEMS-1206/QUIZ_APP_MERN_PROJECT/blob/master/projectImages/questionsPage.png)


4. **Results Page**: After completing the quiz, users are presented with a results page that displays previous player details and final quiz results.

     ![Results Page](https://github.com/CHEEMS-1206/QUIZ_APP_MERN_PROJECT/blob/master/projectImages/resultsPage.png)

## Getting Started

To get started with the MERN Stack Quiz Application, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/CHEEMS-1206/QUIZ_APP_MERN_PROJECT/new/master.git
   ```

2. Navigate to the project directory:

   ```bash
   cd QUIZ_APP_MERN_PROJECT
   ```

3. Set up the backend server, configure MongoDB, and start the server.

4. Navigate to the `client` directory and install frontend dependencies:

   ```bash
   cd client
   npm install
   ```

5. Start the frontend development server:

   ```bash
   npm start
   ```

6. Access the application in your web browser at `http://localhost:3000`.

7. Customize the quiz questions and options to create your own quizzes.

## Contributing

Contributions to the MERN Stack Quiz Application project are welcome! If you have ideas for improvements, new features, or bug fixes, please feel free to submit pull requests or open issues on the GitHub repository.

## License

This project is open-source and available under the [MIT License](LICENSE). You are free to use, modify, and distribute this project according to the terms of the license.

Thank you for using the MERN Stack Quiz Application. If you have any questions or need further assistance, please don't hesitate to contact us.

Happy quizzing! 🧠📚
