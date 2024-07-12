# Simple To-do app

## Overview

This project is focused on creating a simple to-do application where user can add, mark as completed, edit, and delete tasks. In addition, each task can have commentary added to it, which can also be edited and deleted. Utilizing json-server to simulate a backend database provides a realistic environment for performing CRUD (Create, Read, Update, Delete) operations, enhancing the learning experience in handling data.

## Application Features

- **Add task:** User can add new notes to the application. Each note should have a title and content.

- **Edit task:** User have the ability to edit existing notes.

- **Delete task:** User can delete notes they no longer need.

- **Mark as Completed:** User can mark tasks as completed.

- **Add commentary to task:** Each note can have multiple commentaries added to it. This feature allows user to add additional thoughts or updates to their notes.

- **Edit commentary:** User can edit the commentary on a note.

- **Delete commentary:** User can delete any commentary attached to a note.

## Technical Requirements

- **Do Not Use Axios:** For this project, you should not use Axios for making HTTP requests. Instead, use the native `fetch` API for interacting with the `json-server`.

- **Use BEM for Class Naming:** To maintain consistency and readability in your SCSS, use the Block Element Modifier (BEM) methodology for naming your classes.

## Project Structure

- Your project should include at least the following files:
    - `src/index.html` - The main HTML document.
    - `src/style.scss` - The SCSS stylesheets.
    - `src/main.ts` - The TypeScript file containing the logic for your application.
    - `db.json` - The JSON file that will act as your database with `json-server`.

## Getting Started

1. **Install Dependencies:**

    Run the following command to install the necessary packages:

    ```
    npm install
    ```

2. **Start dev server:**

    Run the following command to start the dev server:

    ```
    npm run dev
    ```

3. **Start JSON Server:**

    To simulate the backend database for your app, start the `json-server` by running:

    ```
    npm run db
    ```

    This command will start the server and host your database on a local port. Keep this running in a separate terminal window or tab.
