# 19-TextScribe

## Description
TextScribe is a  text editor that runs in the browser as a Progressive Web Application (PWA). It allows users to create, edit, and manage text documents seamlessly. The app incorporates data persistence techniques using IndexedDB, ensuring data redundancy and offline functionality.

## Table of Contents

- [Installation](#installation)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Preview](#preview)
- [Features](#features)
- [Technology Used](#technologies-used)


## Installation
To run TextScribe, follow these steps:

1. Clone this repository to your local machine.
2. Open the terminal and navigate to the project's root directory.
3. Install dependencies using npm install or yarn install.
4. Start the development server with npm start.
5. Open your browser and visit http://localhost:3000 to access TextScribe.

## User Story
```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria
```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Preview
View TextScribe hosted on [Heroku](https://textscribe-a44a925d489a.herokuapp.com/)

![alt text](/media/HomeScreenshot.png)
Project Homescreen to allow text to be typed

![alt text](/media/InstallApp.png)
Option to install the application as a PWA

## Features
The TextScrbe API has the following features:
- Create new text documents
- Save documents to IndexedDB for data persistence
- Supports markdown syntax for formatting

## Technologies Used
- IndexedDB: Local data storage
- idb: IndexedDB wrapper for simplified data handling
- Service Workers: Enabling PWA capabilities
