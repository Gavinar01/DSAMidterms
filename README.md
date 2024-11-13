# REACT.JS

## What is React.js?
React.js is an open-source JavaScript library created by Facebook in 2011, designed to simplify the process of building interactive user interfaces (UIs).

### History
In 2011, Facebook sought to create a richer user experience through a more dynamic and responsive user interface. Jordan Walke, a software engineer at Facebook, addressed this need by developing React. This library introduced a systematic approach to building dynamic UIs through reusable components.

### Key Features
**One-way Data Binding**: Data flows in a single direction—from parent components to child components. Child components cannot send data back to their parents, but they can communicate with them to modify state based on inputs.

**Optimized Performance**: React uses a virtual DOM to efficiently update only the parts of the UI that have changed, resulting in faster performance, especially in large applications.

**Extensibility**: React supports various extensions for comprehensive UI development, including mobile app development and server-side rendering. Popular extensions like Flux, Redux, and React Native enhance its capabilities.

**Component-Based Architecture**: The UI is broken down into reusable components, each encapsulating its own logic and design.

**Simplicity**: The component-based structure promotes easy understanding, debugging, and maintenance, leading to cleaner code.

## How to Install React.js
Follow these steps to set up React.js on your machine:

### Step 1: Install Node.js
Download Node.js: Visit the Node.js download page and download the latest version.
Install Node.js: Run the installer and click Next until the installation is complete.

### Step 2: Verify Node.js Installation
Open your command prompt (Windows) or terminal (macOS/Linux).
Type the following command and press Enter:
```bash
node -v
```
**Note**: You should see the installed version of Node.js displayed in the terminal.

### Step 3: Install Create React App (CRA)
In the terminal, run the following command to install Create React App globally:
```bash
npm install -g create-react-app
```
To verify the installation, run:
```bash
create-react-app --version
```
The terminal should display the version of Create React App you installed.

### Step 4: Create a Directory for Your React Projects
Create a new folder for your React app:
```bash
mkdir newfolder
```
**Note**: You can replace newfolder with your preferred folder name.

Navigate into the newly created folder:
```bash
cd newfolder
```

### Step 5: Create Your React App
Inside the folder, run the following command to create a new React app:
```bash
npx create-react-app reactfirst
```
Note: The app name must consist of only lowercase letters due to npm naming conventions.

### Step 6: Open the Project in a Code Editor
Open your project folder in your preferred code editor (e.g., Visual Studio Code).
In the terminal, navigate to your app's directory:
```bash
cd reactfirst
```
### Step 7: Run Your React App
Start the development server by running:
```bash
npm start
```
A new tab will open in your default web browser, displaying the React logo. Congratulations! You are now ready to start building applications with React.
Screenshot of a successful creation of React App.

## References:
-**HubSpot**: What is React.js?
-**GeeksforGeeks**: Features of React.js
-**GeeksforGeeks**: How to Install React.js on Windows
