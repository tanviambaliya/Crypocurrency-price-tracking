Cryptoplace

Cryptoplace is a web application built using Vite. This project allows users to interact with cryptocurrency data using the CoinGecko API. Below are detailed steps for setting up and running the project.


Prerequisites:

Install Node.js

Before starting, ensure you have Node.js installed on your system. If not, follow these steps:

Visit the official Node.js website.

Download the appropriate Node.js installer for your operating system.

Run the installer.

Follow the prompts to complete the installation process.

You can check if Node.js is installed by running the following command in your terminal:

node -v

Setup and Run the Project

1. Open the Project in VS Code

Open the project folder in Visual Studio Code.

To open the terminal, right-click on the sidebar and select "Open In Integrated Terminal".

2. Install Dependencies

Run the following command in the terminal to install the necessary dependencies:

npm install

Wait for the installation to complete. After successful installation, you will see a new node_modules folder in the project directory.

Additionally, install the coingecko-api package by running:

npm install coingecko-api

3. Create an API Key

You need to create an API key to fetch cryptocurrency data. Follow these steps:

Visit the CoinGecko API page.

Register for an account and generate your API key.

4. Add the API Key to the Project

Navigate to the src/context folder.

Open the CoinContext.jsx file.

Paste your API key into the file as instructed.

5. Start the Development Server

Run the following command to start the development server:

npm run dev

6. Access the Application

After running the development server, copy the localhost URL provided in the terminal (e.g., http://localhost:3000).

Open the URL in your web browser to access the application.

Resources

For API documentation, visit the CoinGecko API documentation.

Enjoy exploring Cryptoplace!

