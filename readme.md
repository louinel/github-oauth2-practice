# GitHub OAuth2 Practice Project

This project was created as part of the Full-Stack Engineer career path on Codecademy. Its main goal is to provide a hands-on practice experience with OAuth2 authentication using the GitHub API.

## Project Description

The GitHub OAuth2 Practice Project is a simple web application that allows users to authenticate with their GitHub account. It demonstrates the OAuth2 authentication process and utilizes the GitHub API for this.

The view project is built using EJS - Embedded JavaScript, and for the backend, it leverages the GitHub API to authenticate users and retrieve repository information. The OAuth2 flow is implemented using the client-side implicit grant flow, where the user is redirected to the GitHub authentication page and then back to the application with an access token.

## Prerequisites

To run the project locally, you need the following:

- Web browser (Google Chrome, Mozilla Firefox, MS Edge, etc.)
- GitHub account 

## How to Run the Project

1. Clone the project repository to your local machine:

   ```bash
   git clone https://github.com/louinel/github-oauth2-practice.git
   ```

2. Open the project folder in a text editor of your choice.

3. Rename the `.env.test.local` file to `.env`.

4. Edit the `.env` file and replace the placeholder values with your GitHub OAuth2 credentials (GITHUB_CLIENT_ID and the GITHUB_CLIENT_SECRET). You can create an OAuth application in your GitHub account settings.

5. Save the `.env` file.

6. After that, install the depencies running `npm install` file in the terminal of your editor's choice.

7. Click on the "Login with GitHub" button.

8. You will be redirected to the GitHub authentication page. Enter your GitHub credentials and authorize the application.

9. After successful authentication, you will be redirected back to the application, and some information of your repositories will be displayed.

## Dependencies

The project has the following dependencies:

- dotenv
- ejs
- express
- express-partials
- express-session
- passport
- passport-github2


## Project Structure

The project structure is as follows:

```
.
├── node_modules
│   └── dependencies
├── public/css
│   ├── normalize.css
│   ├── skeleton.css
│   └── style.css
├── views
│   ├── account.ejs
│   ├── index.ejs
│   ├── layout.ejs
|   └── login.ejs
├── .env
├── .env.test.local
├── .gitignore
├── app.js
├── package-lock.json
├── package.json
└── README.md
```

- The `views` folder contains `ejs` JavaScript files.
  - `.env.local` is the configuration file. Rename it to `.env` and update with your GitHub OAuth2 credentials.
- The `.gitignore` file specifies files and directories that should be ignored by version control.
- The `README.md` file provides information about the project.

## License

The project is licensed under the [MIT License](LICENSE).

## Acknowledgements

This project was developed as part of the Full-Stack Engineer career path on Codecademy. It builds upon the OAuth2 and GitHub API lessons provided by Codecademy.

## Contact

For any questions or feedback, please feel free to contact me at [https://github.com/louinel](https://github.com/louinel)..

Thank you and enjoy practicing OAuth2 authentication with the GitHub API!