# Todo application

- Click the link to see [DEMO LINK](https://FaiHamid.github.io/todo_application/)

## Description

This is an application, where you can add, remove, update and change completed status of todos. 
Here I've used React(react-dome, react-transition-group), TypeScript, SCSS, bulma and other technologies.

The application fetches and manages todo data from an [API](https://mate-academy.github.io/fe-students-api/) using the fetch API.

### Data Fetching
The application utilizes the fetch API to retrieve and manage todo data from a remote server. The following operations are supported:

- Fetching Todos: Retrieves the list of todos from the API.
- Adding Todos: Sends a request to the API to add a new todo.
- Updating Todos: Sends updates to existing todos to the API.
- Deleting Todos: Sends a request to the API to remove a todo.
- Changing Completed Status: Updates the completed status of todos via API requests.

This approach ensures that the todo data is dynamically fetched and synchronized with the backend.

### Dependencies
* Node v14.16.3 and higher
* NPM v6.14.4 and higher

### Installing
* Fork and clone this repository
* Run `npm install` in your terminal
* Run `npm start`