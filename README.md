# Todos with Angular 4 and Redux
Welcome to Todos with Angular 4 and Redux! This project is a simple todo list application built with Angular 4 and Redux, providing a scalable and maintainable architecture for managing state and data flow. With Todos with Angular 4 and Redux, users can create, read, update, and delete tasks while benefiting from the predictability and flexibility of Redux state management.

## Features
1. **State Management with Redux:** Utilizes Redux for managing application state, ensuring a single source of truth and predictable data flow throughout the application.

2. **Todo CRUD Operations:** Supports CRUD (Create, Read, Update, Delete) operations for managing todo tasks, allowing users to add new tasks, view existing tasks, edit task details, and remove tasks.

3. **Redux DevTools Integration:** Integrates Redux DevTools for debugging and inspecting application state changes, enabling developers to visualize and track state mutations in real-time.

4. **Angular 4 Framework:** Leverages the Angular 4 framework for building dynamic and interactive user interfaces, with features such as component-based architecture, data binding, and dependency injection.

5. **Responsive Design:** Implements responsive design principles to ensure optimal user experience across different devices and screen sizes, providing a seamless todo management experience.

### Dependencies
  - Make sure you install json-server globally `npm install json-server -g`
  - Make sure you install chrome redux dev tools when using the application in dev mode. 
  - If you want to use the project without the redux dev tools edit the enhancers in the app.module.ts file

### How to Run (dev server)
- npm install
- npm run start
- json-server db.json (run from root in another tab)

## Usage
1. **Add Todos:** Use the provided interface to add new todos by entering a title and optional description for each task.

2. **View Todos:** Review the list of todos displayed on the screen, including details such as title, description, completion status, and creation/update timestamps.

3. **Edit Todos:** Click on a todo item to edit its details, such as title or description, directly within the interface.

4. **Delete Todos:** Remove unwanted todos from the list by clicking on the delete icon next to each todo item.

5. **Mark Todos as Completed:** Toggle the completion status of todos by clicking on the checkbox next to each todo item, indicating whether the task is completed or pending.

## Customization
You can customize Todos with Angular 4 and Redux by modifying aspects such as the user interface design, todo item components, state management logic, Redux store configuration, and integration with external services or APIs. Additionally, you can add new features, optimize performance, or extend functionality based on your specific requirements.




