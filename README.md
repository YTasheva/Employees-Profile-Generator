<h1 align="center">Employees-Profile-Generator</h1>
  <br>
  <a href="https://github.com/YTasheva">
      <img src="https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg?style=for-thebadge" alt=""></a>
  <a href="https://github.com/YTasheva/Employees-Profile-Generator/graphs/contributors">
      <img src="https://img.shields.io/github/contributors/YTasheva/Employees-Profile-Generator.svg?style=for-the-badge" alt=""></a>
  <a href="https://github.com/YTasheva/Employees-Profile-Generator/issues">
      <img src="https://img.shields.io/github/issues/YTasheva/employees-profile-generator.svg?style=for-the-badge" alt=""></a>
  <a href="https://github.com/YTasheva/Employees-Profile-Generator/network/members">
      <img src="https://img.shields.io/github/forks/YTasheva/employees-profile-generator.svg?style=for-the-badge" alt=""></a>
</p>


## Table of contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Mock-up](#mock-up)
- [Screenshot](#screenshot)
- [Links](#links)
- [Tests](#tests)
- [Installation](#installation)
- [Licence](#licence)
- [Author](#author)

## Overview

- This application will take in information about employees on a software engineering team, and then generate an HTML webpage that displays summaries for each person. 

### The Challenge

- As a manager a user wants to generate a webpage that displays my team's basic info so that a user has quick access to their emails and GitHub profiles.
- Make sure every part of your code passes each provided test.
- Convert the files into a working Node.js command-line application.
-   
### Acceptance Criteria

* Create a command-line application that accepts user input using the provided starter code.   
  * Create classes for each team member provided and export them. The tests for these classes (in the `_tests_` directory) must ALL pass.     
    * The first class is an `Employee` parent class with the following properties and methods:       
      * `name`
      * `id`
      * `email`
      * `getName()`
      * `getId()`
      * `getEmail()`
      * `getRole()`&mdash;returns `'Employee'`     
    * The other three classes will extend `Employee`.      
    * In addition to `Employee`'s properties and methods, `Manager` will also have the following:
      * `officeNumber`
      * `getRole()`&mdash;overridden to return `'Manager'`
    * In addition to `Employee`'s properties and methods, `Engineer` will also have the following:
      * `github`&mdash;GitHub username
      * `getGithub()`
      * `getRole()`&mdash;overridden to return `'Engineer'`
    * In addition to `Employee`'s properties and methods, `Intern` will also have the following:
      * `school`
      * `getSchool()`
      * `getRole()`&mdash;overridden to return `'Intern'`
    * Finally, although it’s not a requirement, consider adding validation to ensure that user input is in the proper format.   
  * Write code in `index.js` that uses inquirer to gather information about the development team members and creates objects for each team member using the correct classes as blueprints.
    * When a user starts the application then they are prompted to enter the **team manager**’s:
      * Name
      * Employee ID
      * Email address
      * Office number
    * When a user enters those requirements then the user is presented with a menu with the option to:
      * Add an engineer
      * Add an intern 
      * Finish building the team
    * When a user selects the **engineer** option then a user is prompted to enter the following and then the user is taken back to the menu:
      * Engineer's Name
      * ID
      * Email
      * GitHub username
    * When a user selects the intern option then a user is prompted to enter the following and then the user is taken back to the menu:
      * Intern’s name
      * ID
      * Email
      * School
    * When a user decides to finish building their team then they exit the application, and the HTML is generated.
  * Call the `render` function (provided for you) and pass in an array containing all employee objects; 
    * The `render` function will generate and return a block of HTML including templated divs for each employee!
  * Create an HTML file using the HTML returned from the `render` function. 
    * Write it to a file named `team.html` in the `output` folder. 
    * You can use the provided variable `outputPath` to target this location.

---

### Mock-Up

The following image shows a mock-up of the generated HTML’s appearance and functionality:

![HTML webpage titled “My Team” features five boxes listing employee names, titles, and other key info.](./assets/14-object-oriented-programming-challenge-demo.png)

The styling in the image is just an example, so feel free to add your own.

---


## Screenshot



## Links

- Solution URL: https://github.com/YTasheva/Employees-Profile-Generator
- Live Site URL:https://ytasheva.github.io/Employees-Profile-Generator/
  
## Tests

- To run tests for the project, first open the root project directory in your terminal. If you haven’t already, run `npm install` to install all necessary testing dependencies. Finally, run `npm test` in your terminal. This command will run the code in your test script in the package JSON for your project.

## Installation

* Download or clone the repository.

* Open the `.HTML` file through your web browser to view.

* Use Visual Studio Code or a similar source-code editor to run the code.
* Run `npm install`. To use [Jest](https://www.npmjs.com/package/jest) for running the unit tests and [Inquirer](https://www.npmjs.com/package/inquirer) for collecting input from the user. The application will be invoked by using the following command:

```bash
node index.js
``` 
## Licence

<a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt=""></a>

## Author

- Github - [Yuliya Tasheva](https://github.com/YTasheva)

> [YTasheva.com](#) &nbsp;&middot;&nbsp;
> LinkedIn [@YTasheva](https://github.com/YTasheva) &nbsp;&middot;&nbsp;
> Email [ytashevagit@gmail.com](#) &nbsp;&middot;&nbsp;
  
