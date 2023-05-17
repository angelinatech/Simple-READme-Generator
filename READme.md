# READme generator

## Description

This is a command line application that dynamically generates a professional README.md from a user's input. You can save a little time by conveniently automating this process and keeping it simple.

User inputs are collected via the Inquirer package and output sent to an .md file on your local system. The project creator can now devote a little extra time to working on the project at hand.

## **Table of Contents**

- [Installation](##Installation)
- [Usage](##Usage)
- [Credits](##Credits)
- [License](##license)
- [Contributing](##Contributing)

## Installation

To use the READme generator, first clone this repository and navigate to it in your chosen CLI.

You will need to have installed node (which you can find at 'nodejs.org').

You can install dependencies by running 'npm i' in your command line terminal, or install inquirer directly via 'npm i inquirer'.

Ensure that you are in the correct folder and start the application by entering 'node index.mjs'.  You will be prompted to add the READme information via questions in the terminal.

After answering the prompts as needed, a READme.md file will appear in the output folder ready to be used and incuded in your project.

## Usage

The user upon cloning and installing the aplication will need to run 'node index.mjs' in their terminal to start the application.

When a user is prompted for information about the application repository, a high-quality, professional README.md will be generated from their answers with:

The Project Title,

Description

Table of Contents

Installation

Usage

License

Contributing

Tests

Questions

When a user enters the project title, it's displayed as the title of the README.

When a user enters a description, installation instructions, usage information, contribution guidelines, and test instructions, this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests.

When a user chooses a license for their application from a list of options, a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under.

When a user enters their GitHub username, it's added to the section of the README entitled Questions, with a link to their GitHub profile.

When a user enters their email address, it's added to the section of the README entitled Questions, with instructions on how to reach them with additional questions.

When a user clicks on the links in the Table of Contents, they are taken to the corresponding section of the README.

The URL to a sample READme file is below:
https://github.com/angelinatech/Simple-READme-Generator/blob/bf207733a29cbdcd82eb4dc4a03aec73a7e26283/output/README.md

A video walkthrough of the working application can be seen below:

https://drive.google.com/file/d/1RFaEaRnVfpENbxlnntSXjmlDsrjYCas5/view?usp=sharing

## Credits

This web application was made using:

- Node.js https://nodejs.org/en
- Inquirer.js https://www.npmjs.com/package/inquirer

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

The license will be MIT open source, please see documentation for further details.
https://opensource.org/license/mit/

## Contributing

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

This project will use the open source contributer covenant. Please see below:

https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md
