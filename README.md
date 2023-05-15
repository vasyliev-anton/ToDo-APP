# ToDo App with API 
Among the core goals of this project was to create a single-page application with React Router. Furthermore, the form of registration and validation of the user with the server response were implemented by React-hook form. By using React Transition Group, I improved basic animation techniques, including the creation and removal of React components.

# [DEMO LINK](https://vasyliev-anton.github.io/react_todo-app/)

# Technologies used
- React.js
- React Form
- React Router(v6)
- React TRANSITION GROUP
- TypeScript
- JavaScript
- Fetch, REST API
- Sass (SCSS)
- Bulma
- FontAwesome

## Authentication
- The app supports user registration and login functionality.
- User data is retrieved from the server and displayed in the app.
- The app allows users to log out of their account.
- The user's ID is displayed in the URL.
- The app stores user ID data locally to improve user experience.

## ToDos
- The app stores all ToDos in the server, which are fetched on login.
- Users can create, delete, and edit ToDos as well as mark them as completed.
- The app allows users to mark all ToDos as completed or delete all completed ToDos at once.
- All changes made to ToDos are automatically saved in the server.
- The app uses the `Wait` function to simulate server requests and demonstrate the loader.
- Users can filter ToDos by all, active, or completed categories, with the selected filter saved in the URL.
- The app displays the number of active ToDos to keep users informed.
- In case of a server error, the app promptly notifies the user.

![todoapp](https://github.com/vasyliev-anton/react_todo-app/blob/master/description/todoapp.gif)
