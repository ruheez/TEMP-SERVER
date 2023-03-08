## Getting Started

### Fork the Repo

First, you'll need to fork this repository to your GitHub account. You can do this by clicking the "Fork" button at the top right corner of this page.

### Start a New Project on raliway

Next, sign up for an account on [raliway.app](https://raliway.app) and create a new project.

![Create a new project on raliway](https://i.imgur.com/qheflkW.png)

Choose "GitHub" as the deployment option and select the forked repository.

![Choose GitHub as the deployment option and select the forked repository](https://i.imgur.com/9XJSDwh.png)

## Add Variables

Once your project is set up, go to the "Variables" section and add two variables:

- `ngrok_token`: This is your ngrok authentication token.
- `password`: This is the password you want to set for the Kali Linux VPS.

![Add variables in raliway](https://i.imgur.com/8Bue5V5.png)

## Deploy the App

Click the "Deploy" button to deploy the app. raliway will automatically build and deploy the Kali Linux VPS.

![Deploy the app in raliway](https://i.imgur.com/UgHkyMs.png)

Once the deployment is complete, you can access your Kali Linux VPS by logging in with your ngrok account credentials and the password you set in the variables.
