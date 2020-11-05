# README-Generator
This is a small console application that will generate a README.md file based on given user information


## User Story
``````
AS A developer
I WANT a README generator
SO THAT I can quickly create a professional README for a new project

GIVEN a command-line application that accepts user input
WHEN I am prompted for information about my application repository
THEN a high-quality, professional README.md is generated with the title of my project and sections entitled Description, Table of Contents, Installation, Usage, License, Contributing, Tests, and Questions
WHEN I enter my project title
THEN this is displayed as the title of the README
WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README
``````

## Check out a demo

https://drive.google.com/file/d/1x9BsnFwVauNf9PleU1mP64B91HCYw3af/view?usp=sharing

## Instructions

This application is run in the console. Copy the application folder onto your machine, and make sure all dependencies are installed by running "npm install" in the command line. When that is finished, run "node index.js" command in the command line. You will recieve prompts in the console, and the application will render a new README.md file for you.
