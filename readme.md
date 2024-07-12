# ASELab Dashboard

Welcome to the ASELab Dashboard project! This document contains guidelines for contributing to this project, including how to submit commits, create pull requests, debug, and build for production. Additionally, it includes naming conventions for branches, variables, and functions.

## Table of Contents
1. [Getting Started](#getting-started)
2. [Running Project Debugging](#running-project-debugging)
3. [Submitting Commits](#submitting-commits)
4. [Creating Pull Requests](#creating-pull-requests)
5. [Naming Conventions](#naming-conventions)
   - [Branch Naming](#branch-naming)
   - [Variable and Function Naming](#variable-and-function-naming)

## Getting Started
1. **Clone Repository:**
   First, clone this repository to your computer.
   ```bash
   git clone https://github.com/F201/ASELab-dashboard.git
   ```

2. **Install Dependencies:**
   Then, install the required dependencies.
   ```bash
   npm install
   ```

3. **Start the Development Server:**
   Run the development server to start working.
   ```bash
   npm start
   ```

## Running Project Debugging
1. **Go to Repository:**
   Navigate your terminal to the repository directory.
   ```bash
   cd [path to your repository]
   ```

2. **Run the Project Locally:**
   Run the project in your local environment. Typically, using the following commands:
   - **Frontend only:**
     ```bash
     cd [front end path] 
     npm run dev
     ```
   - **Backend only:**
     ```bash
     cd [back end path] 
     npm run dev
     ```
   - **Both:**
     ```bash
     start.bat
     ```
   - **Production:**
     ```bash
     npm run build
     npm run start
     ```

## Submitting Commits
When contributing to this project, follow these guidelines for submitting commits:

1. **Create a New Branch:**
   For each feature or bug fix, create a new branch with a descriptive name.
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make Changes:**
   Implement your changes according to the project standards and guidelines.

3. **Commit Your Changes:**
   Write clear and concise commit messages. Follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.
   ```bash
   git add .
   git commit -m "feat: add new feature description"
   ```

4. **Push Your Changes:**
   Push your changes to the remote repository.
   ```bash
   git push origin feature/your-feature-name
   ```

## Creating Pull Requests
After you have pushed your changes, follow these steps to create a pull request:

1. **Navigate to the Repository:**
   Open the GitHub repository in your browser.

2. **Create a Pull Request:**
   Click the "New Pull Request" button and select your branch.

3. **Provide a Description:**
   Fill out the pull request template with a clear description of the changes you have made and any relevant issue numbers.

4. **Request Reviews:**
   Request reviews from team members or relevant contributors.

5. **Respond to Feedback:**
   Address any feedback or requested changes from reviewers.

6. **Merge the Pull Request:**
   Once your pull request has been approved, merge it into the main branch.

## Naming Conventions

### Branch Naming
Use the following format for naming branches:
- **Feature Branches:** `name/feature/short-description`
- **Bug Fix Branches:** `name/bugfix/short-description`
- **Hotfix Branches:** `name/hotfix/short-description`

### Variable and Function Naming
Use camelCase for variable names.
Use descriptive names that convey the purpose of the variable/function.

Example:
```javascript
let userName = "WahyuKakap";
const maxRetries = 5;
let isLoggedIn = true;
```