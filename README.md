# GitHub User Creation Date

## Description

This project is a simple, static web application that allows users to fetch the creation date of a GitHub account. It uses the GitHub API to retrieve user data and displays the account creation date in YYYY-MM-DD UTC format.

## Features

- Fetches GitHub user information using the GitHub API.
- Displays the account creation date in a user-friendly format (YYYY-MM-DD UTC).
- Provides error handling for invalid usernames or API issues.
- Uses a clean and modern design with Bootstrap for responsive layout.
- Supports optional authentication using a GitHub API token passed as a URL parameter (`?token=`).
- Fully self-contained with embedded CSS and JavaScript for easy deployment on GitHub Pages.

## How to Use

1.  Open the `index.html` file in your web browser.
2.  Enter the GitHub username in the input field.
3.  Click the "Get Creation Date" button.
4.  The application will display the account creation date below the form.
5.  Optionally, you can provide a GitHub API token via the `token` query parameter (e.g., `index.html?token=YOUR_GITHUB_TOKEN`).

## Technologies Used

-   HTML
-   CSS (Bootstrap, Embedded)
-   JavaScript (Vanilla JS, Embedded)
-   GitHub API
```