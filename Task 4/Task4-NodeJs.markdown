# Task 4 - Node.js Ecosystem Setup

## Objectives
1. Install Node.js and NVM
2. Practice using NPM commands
3. Install Nodemon

## Solution:

### 1. Installations NVM and Node.js

   #### Used Commands for NVM
   ![alt text](image.png)

   #### Node.js Setup
   ![alt text](image-1.png)

   #### Both NVM and Node.js Successfully Installed
   ![alt text](image-2.png)




### 2. NPM Commands
### 1. Initialize a new Node.js project
`npm init -y`

 👉 Creates a default package.json file without asking interactive questions.

 📦 Use when starting any new Node.js project.

### 2. Install a package locally
`npm install express`

 👉 Installs the 'express' package to the current project.

 📦 Use when your project depends on third-party libraries.

### 3. Install a package globally
`npm install -g nodemon`

 👉 Installs 'nodemon' globally so you can use it from any directory.

 🌐 Use for CLI tools you want available system-wide.

### 4. Install all dependencies listed in package.json
`npm install`

 👉 Installs all packages listed in dependencies and devDependencies.

 🔄 Use when cloning a project or after deleting node_modules.

### 5. Uninstall a package
`npm uninstall express`

 👉 Removes 'express' from the node_modules and package.json.

 🧹 Use to clean up unused or unwanted packages.

### 6. List installed packages
`npm list --depth=0`

 👉 Shows all top-level packages installed in your project.

 🔍 Use to review which dependencies are currently used.

### 7. Update all outdated packages
`npm update`

 👉 Updates all outdated packages to the latest safe version (respecting semver).

 🔄 Use regularly to keep your dependencies up-to-date.

### 8. Install a specific version of a package
`npm install express@4.18.2`

 👉 Installs exactly version 4.18.2 of Express.

 🎯 Use when your app requires a known stable version.

### 9. Run a custom script from package.json
`npm run start`

 👉 Runs the script defined as "start" in package.json.

 ⚙️ Use to run build, start, test, or other custom project scripts.

### 10. Check for outdated packages
`npm outdated`

 👉 Lists packages with newer versions available.

 🔧 Use to see which dependencies you might want to update.

 ### 3. Instal Nodemon
  #### Successful
  ![Installed Nodemon](image-3.png)

  #### Verification
  ![verify](image-4.png)

