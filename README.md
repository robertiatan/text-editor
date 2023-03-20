# Just Another Note Taker

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Contributing](#contributing)

## Description

This is an application that allows the user to create, save, and delete notes. The application uses an express server to store the notes in a JSON file. The application is deployed on Heroku and can be accessed at the link below. The application is also a Progressive Web Application (PWA) that can be installed on a device and used offline. The application uses a service worker to cache the files and a web manifest to allow the user to install the application on their device.

## Installation

To install the application, clone the repository to your local machine. Then, run 'npm install' to install the required dependencies.

## Usage

After installing dependencies, run `npm run build`, followed by `npm run start:dev` to build the application and start the server. The application will be available at localhost:3000.

## Demo

Here are screenshots of the application in use:
The application as a PWA, downloaded to a device

![Alt text](public/Screenshot%202023-03-14%20212818.png)

The application's manifest.json file

![Alt text](public/Screenshot%202023-03-14%20213040.png)

The application's registered service worker

![Alt text](public/Screenshot%202023-03-14%20213109.png)

The application's IndexedDB database

![Alt text](public/Screenshot%202023-03-14%20213145.png)

This is a link to the deployed application on Heroku: https://text-editor19-challenge.herokuapp.com/

## Contributing
Big thanks to my TA's Jeremey and Sachin for help on this assignment.