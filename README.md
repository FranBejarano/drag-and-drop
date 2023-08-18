# Project Management App

This repository contains a simple project management application that allows you to manage and categorize your projects. The app utilizes TypeScript and HTML5's drag-and-drop functionality to provide an interactive user experience.

## Table of Contents

- [Project Management App](#project-management-app)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Features](#features)
  - [Contributing](#contributing)
  - [License](#license)

## Installation

To use this project, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/project-management-app.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd project-management-app
    ```

3. **Install dependencies using npm:**

    Make sure you have Node.js and npm installed. If not, you can download them from the [official website](https://nodejs.org/).

    ```bash
    npm install
    ```

4. **Start the development server:**

    ```bash
    npm start
    ```

    This will build the TypeScript files and serve the application locally.

5. **Access the application:**

    Open your web browser and navigate to `http://localhost:3000` to access the project management app.

## Usage

Upon accessing the app, you'll be able to manage your projects in two categories: "Active" and "Finished." You can perform the following actions:

- **Add a Project:**
  - Enter the title, description, and number of people required for the project.
  - Click the "Add Project" button to add the project to the active projects list.

- **Drag and Drop:**
  - Projects in the "Active" list can be dragged and dropped into the "Finished" list and vice versa.

## Features

- **TypeScript:** The application is written in TypeScript, providing type safety and enhanced code organization.

- **Drag-and-Drop Functionality:** Projects can be dragged and dropped between the "Active" and "Finished" lists.

- **Validation:** User inputs are validated before adding a project, ensuring that the required fields are filled and the data meets certain criteria.

- **Project State Management:** The `ProjectState` class manages the state of projects, ensuring that changes are reflected across the application.

## Contributing

Contributions to this project are welcome! Feel free to submit issues and pull requests to improve the application.

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
