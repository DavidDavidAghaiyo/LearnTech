LEARN TECH

This project is a simple clone of the Gemini API using JavaScript, HTML, and CSS. It allows you to interact with the Gemini API and generate content with the Gemini model.

Prerequisites
Before you start, you'll need:
A code editor (like VS Code)
A web browser (Chrome, Firefox, etc.)
Node.js (optional, if you plan to run the project with a local server)
A Google Cloud API Key for the Gemini model (this is required to use the API)
Setting Up the Project

1. Clone the Repository
   First, clone this repository to your local machine:

git clone https://github.com/DavidDavidAghaiyo/LearnTech.git
cd Gemini Clone 2. Set Up the API Key
The API key for the Gemini API is stored securely in a separate config.js file. This file is not included in this repository for security reasons. Here's how to set it up:

Create a file named config.js in the root directory of the project.

Go to Google Cloud to generate your own API Key
Add your Google Cloud API Key inside the config.js file:

// config.js
const API_KEY = 'your-actual-api-key-here';  
export { API_KEY };

Important: Make sure that config.js is listed in your .gitignore to avoid accidentally pushing it to GitHub.

3. Open the Project in Your Browser
   Once you've set up the config.js file, you can open the index.html file directly in your browser to start using the app.
