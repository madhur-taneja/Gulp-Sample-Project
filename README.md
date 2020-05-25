# Gulp-Sample-Project

[Gulp.js](https://gulpjs.com/) is a toolkit to automate & enhance your workflow. 

In this project, I've made a small gulp task to convert the scss files to css files. 

Open and view the Project using the `.zip` file provided or at my [Github Repository](https://github.com/madhur-taneja/Gulp-Sample-Project)

## Table of Contents
- [Getting Started](#getting-started)
	- [Tools Required](#tools-required)
	- [Installation](#installation)
- [Development](#development)
- [Running Tasks](#running-tasks)
- [References](#references)

## Getting Started

### Tools Required

You would require the following tools:

* [node.js](https://nodejs.org/en/)
* [npm](https://www.npmjs.com/)
* A text-editor of your choice. 

### Installation

* Open CMD and run the following command to globally install gulp:
  ```
  npm install gulp-cli -g
  ```
* Change directory to your project folder and run the following command to initialise a new node project
  ```
  npm init
  ```
  
* Run the following command to install gulp locally in this project 
  ```
  npm install gulp -D
  ```

## Development
  
* Run the following command to create a gulpfile for the project
  ```
  touch gulpfile.js
  ```
  NOTE: `touch` works only for MAC OS, but a work-around for this is running the command in `Git-Bash` on a windows system or alternatively use the following commnand:
  ```
  type NUL > gulpfile.js
  ```
  
* Install different npm packages that are available for gulp as per your requirement. For example:
  ```
  npm install gulp-sass --save-dev
  ```
  
* Require them in the `gulpfile.js` and start creating tasks using them. 

## Running Tasks

* To run the task that you've created, use the following command:
  ```
  gulp <task-name>
  ```
  Replace `<task-name>` with the name of your task

## References

* [Gulp Documentation](https://gulpjs.com/docs/en/getting-started/quick-start)
* [Free Code Camp](https://www.youtube.com/watch?v=LYbt50dhTko)
