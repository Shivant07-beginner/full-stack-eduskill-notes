MERN Full Stack Development Project
This repository serves as the foundation for the MERN Full Stack Development course. It documents the initial steps taken to set up a professional development environment and build the first server-side application using Node.js.

🛠 Tech Stack
Runtime Environment: Node.js

Code Editor: VS Code

Package Management: npm or yarn

Version Control: Git

🚀 Getting Started
1. Prerequisites
Ensure you have the following installed on your machine:

Node.js (LTS version recommended)

Git

2. Project Initialization
To start a new project and generate the package.json file:

Bash
# Initialize with default settings
npm init -y
# OR
yarn init -y
3. Running Your First Script
Create a file named index.js.

Add the following code:

JavaScript
console.log('Hello, World!');
Execute the script in your terminal:

Bash
node index.js
📦 Managing Dependencies
This project utilizes external packages to extend functionality.

Installing Packages
To install a package (e.g., Lodash):

Bash
npm install lodash
# OR
yarn add lodash
Using Packages
Import and use the package in your index.js:

JavaScript
const _ = require('lodash');

const numbers = [1, 2, 3, 4, 5];
const sum = _.sum(numbers);

console.log(`The sum of the numbers is: ${sum}`);
📂 Key Files
index.js: The main entry point of the application.

package.json: The manifest file containing project metadata, scripts, and dependency definitions.

node_modules/: Directory containing installed packages.

package-lock.json / yarn.lock: Locks dependency versions to ensure reproducible builds across environments.

This project is currently under development as part of the MERN Full Stack curriculum.
