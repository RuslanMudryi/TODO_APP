# React Todo App

This project is application using React and an external API. The app allows users to manage a list of tasks (todos) with features such as adding, deleting, toggling status, and editing task titles.
Key Features

    Adding a New Todo:

        Users can add a new task via an input form.

        After successful addition, the todo appears in the list.

    Deleting a Todo:

        Each task can be deleted using the "×" button.

        After successful deletion, the todo is removed from the list.

    Toggling Todo Status:

        Users can change the status of a task (completed/not completed) using a checkbox.

        While waiting for the API response, the todo is covered with a loader overlay.

        If an error occurs during status update, an error notification is displayed.

    Toggling Status for All Todos:

        The "Toggle All" button allows changing the status of all tasks to the opposite.

        The button is active only when all tasks are completed.

        API requests are sent only for tasks whose status has actually changed.

    Editing a Todo Title:

        Users can edit the title of a task by double-clicking on it.

        During editing, an input form is displayed instead of the title and delete button.

        Changes are saved on form submission (pressing Enter) or when the input field loses focus (onBlur).

        If the new title is the same as the old one, editing is canceled.

        Editing is canceled on the Esc key keyup event.

        If the new title is empty, the todo is deleted (similar to the "×" button).

        While waiting for the API response, the todo is covered with a loader overlay.

        If the title is successfully updated, the todo is refreshed.

        If an error occurs during update or deletion, an appropriate error message is displayed.

Technologies Used

    React: A JavaScript library for building user interfaces.

    TypeScript: A typed superset of JavaScript for better code quality and maintainability.

    API Integration: Fetching and updating data from an external API.

    Cypress: End-to-end testing framework for ensuring the app works as expected.

    Prettier: Code formatting tool to maintain consistent code style.

    SCSS: Styling the application with a more powerful and maintainable CSS preprocessor.

Installation and Setup

    Clone the repository:
    bash
    Copy

    git clone https://github.com/<your_account>/react-todo-app.git

    Navigate to the project directory:
    bash
    Copy

    cd react-todo-app

    Install dependencies:
    bash
    Copy

    npm install

    Start the project:
    bash
    Copy

    npm start

Testing

To run tests using Cypress:

    Open the cypress/integration/page.spec.js file.

    Replace describe.skip with describe for the root block.

    Run the tests:
    bash
    Copy

    npx cypress open

Demo

DEMO LINK
