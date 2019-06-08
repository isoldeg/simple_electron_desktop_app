# simple_electron_desktop_app
A simple Electron desktop app that changes the changes the window

# INSTALL
Install Node.js first
* npm install -g electron
* npm install electron --save

# SETUP
* make a directory - mkdir dir_name
* go into the directory - cd dir_name
* create a package.json file - npm init
* install electron globally and locally (to save it as a dependency)
* create a start script so change "test" to "start" in package.json and let the value be "electron ."
* make sure "main" in package.json is "main.js"

# RUN
* electron .
OR
* npm start

# FILES
* package.json - stores all of our project dependencies (To skip all of the prompts use: npm init -y) and points to the app's main file
* main.js - main entry point/process
* index.html - a web page to be rendered
* pageTwo.html - a web page to be rendered

# NOTES
* Main process - package.json is the main script. Creates BrowserWindow instances to run web pages
* Renderer process - each web page runs its own isolated process
