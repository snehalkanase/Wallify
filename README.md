
## 🚀 **Getting Started with Wallify**

Welcome to Wallify! This guide will walk you through the steps to get started with the Wallify project.

## Prerequisites

Before you begin, make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en/download/): Make sure to install the LTS version of Node.js. 📥

# How to Create a Developer Account on Spotify

If you're interested in integrating Spotify features into your applications or projects, you'll need to create a developer account on Spotify. Follow the steps below to get started:

1. Go to the [Spotify Developer Dashboard](https://developer.spotify.com/) in your web browser. 🌐
2. Click on the "Log In" button located in the top-right corner of the page. 🔐
3. If you already have a Spotify account, you can log in using your existing credentials. Otherwise, click on the "Sign Up" button to create a new account. 🆕
4. Once you're logged in, you'll be redirected to the Spotify Developer Dashboard. Here, you'll find various tools and resources for developing with Spotify's APIs.
    ![image](https://github.com/cokelemonice/thewalls/assets/58532371/7ed06bc3-ba81-4866-9dbd-7488829bba8c)

    
5. To create a new app, click on the "Create an App" button. You'll be prompted to provide some details about your app, such as its name and description.
    
    ![image](https://github.com/cokelemonice/thewalls/assets/58532371/86b3d597-17ee-43d0-80d5-b769b46ac840)

    
    **NOTE**: For Wallify to work on your local machine, the redirect URI should be **http://localhost:3000/api/auth/callback/spotify**. This is done to make sure we can use Next Auth with the Spotify OAuth. To ensure proper functionality, please make sure to enable the **Spotify Web API** in your Spotify Developer App settings.
    
6. After filling out the necessary information, click on the "Create" button to complete the app creation process. 🚀
7. Once your app is created, you'll be taken to its dashboard. Here, you can find your app's Client ID and Client Secret, which you'll need for authentication and API usage.

That's it! You've successfully created a developer account on Spotify and created your first app. You can now explore the various APIs and features available to developers and start integrating Spotify into your projects.

Remember, when using Spotify's APIs, make sure to comply with their terms of service and API usage guidelines.

## Running the app locally

To clone the project from GitHub and run it locally, follow these steps:

1. Open your terminal or command prompt. 💻
2. Navigate to the directory where you want to clone the project.
3. Run the following command to clone the project repository
    
4. Once the cloning process is complete, navigate into the project directory
    
5. Install the project dependencies by running the following command:
    
    ```bash
    npm install
    
    ```
    
    This command will install all the required packages and dependencies specified in the project's `package.json` file.
    
6. Create a `.env` file, you can use the provided sample `.env.example` file as a template. Copy the contents of the `.env.example` file and create a new `.env` file in the project directory.
7. Open the `.env` file in a text editor and replace the placeholder values with the appropriate credentials from your Spotify app. For example, replace `YOUR_CLIENT_ID` with your actual Client ID and `YOUR_CLIENT_SECRET` with your actual Client Secret.
8. We recommend using `http://localhost:3000` as the value for `NEXTAUTH_URL` in order to run the project locally.
9. After the installation is complete, start the local development server by running the following command:
    
    ```bash
    npm run dev
    
    ```
    
    This command will start the Next.js development server, and you should see output indicating that the server is running.
    
10. Open your web browser and visit `http://localhost:3000` to access the locally running Next.js application.

That's it! You have successfully cloned a Next.js project from GitHub and are running it locally on your machine. You can now make changes to the project, experiment, and test it as needed.

Remember to refer to the project's documentation or README file for any specific instructions or additional setup steps that may be required.

Thank you for choosing wallify! We hope you enjoy using it and look forward to your contributions. 🎉

---

*This getting started guide is inspired by the [Appwrite](https://github.com/appwrite/appwrite) project's [README.md](http://readme.md/) file.* 📚
