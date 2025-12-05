# ToDo List Web Application

A task-management application to create, track, update, and organize tasks. 

---

## Features

### User Management

- **User Registration**  
  Capture mandatory information such as _username_, _password_, and _email_.  
  Optional fields include _mobile number_, _date of birth_, and _address_.
- **User Login**  
  Secure authentication using registered _username_ and _password_.

### Task Operations

- **Add New Task**  
  Create tasks with ease from the dashboard.

- **Edit Existing Tasks**  
  Inline editing to update task details quickly.

- **Update Task Status**  
  Toggle between **To Do** and **Completed**.

- **Soft Delete Tasks**  
  Removed tasks are not permanently deleted — users can ask admin to restore deleted items.

---

## Tech Stack

| Layer        | Technology                  |
| ------------ | --------------------------- |
| **Frontend** | Angular                     |
| **Backend**  | .NET (C#)                   |
| **Database** | Microsoft SQL Server (SSMS) |

---

# TodoAppFrontend

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 20.3.8.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
