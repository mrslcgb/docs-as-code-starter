# Docs-as-Code Starter Project

## Description
This is a simple web application built with HTML, CSS, and JavaScript. Its purpose is to practice going from issues to
documentation to pull requests. It is used for demonstrating how documentation can be integrated into the standard 
development lifecycle using GitHub Issues and Pull Requests.

## Features
- Time Tracking: A button that updates the status with the current time.
- Mini API: A built-in function for testing developer interactions.
- Docs-as-Code Workflow: Designed specifically to practice the integration of documentation and code.

## Requirements
- A modern web browser (Chrome, Firefox, or Edge).
- No external dependencies are required.
- A GitHub account for forking and managing the repository.

## Installation
1.  Fork the Repository to your GitHub account: Click the 'Fork' button on the GitHub account where the repository is 
located to create a copy in your account.
2.  Clone to local machine: Open your terminal and use the command:
    ```bash
    git clone https://github.com/YOUR-USERNAME/docs-as-code-starter.git
    ```
    *Alternatively, go to the top of your IDE, select **File > New > Project From Version Control**, and paste the 
     repository's URL to access it that way.*
3.  Run the Website: Locate the project folder and open *index.html* in any web browser to view the project.

## Usage Examples
- Click the **"Click me"** button on the main page of the website. This would update the status text with the current time.
    ```text
        Status: clicked at 9:56:14 AM
    ```
- You can also interact with the project via the browser console by using the following command:
    ```javascript
        window.fakeApi.ping("hello")
   ```

## Contribution Guidelines
Team members must follow these steps for all updates to ensure documentation stays up-to-date with the code:
- Issues: All new features and improvements must be added to the project as an issue first.
- Branching: Create a new branch (e.g., features) for your work rather than committing to main.
- Commit Messages: Use clear commit messages that describes the change.
- Linking: When submitting a Pull Request (PR), you must link it to the issue by including the
  keyword "Closes #issue-number" in the PR description.
- Review: All PRs must be reviewed and merged to maintain the "single source of truth" for the project.

## Contributors
- Leiah Charles