# cybervest-testnet
Setup your application
This section will walk you through the steps to create your application, install the necessary dependencies, and write the boilerplate code you'll need to integrate Embedded Accounts!

Create your app
First, create a NextJS React application by running npx create-next-app from your terminal in a project directory of your choice. Select the default configuration for each question the create-next-app CLI.

Also, at the root of this new application directory, add a .env file.

Configure the Embedded Accounts
First, create an Alchemy API key, an Embedded Accounts Config, and a Gas Manager Policy. You will use these to send UOs, authenticate logins, and sponsor gas respectively.

Alchemy API Key
The Alchemy API Key will allow you to read and write to blockchains through Alchemy's reliable infrastructure. In this context, the API Key will let you create Embedded Accounts onchain for your users, and send UserOperations on behalf of those accounts.

To create an API Key, go to https://dashboard.alchemy.com, sign up for an account, and go through the onboarding. Then on the apps page, click "Create new app" button.
