# PWA-Challenge

## Description

J.A.T.E is a Progressive Web Application (PWA) that runs in the browser, offline and can be installed locally to your machine. This application features a number of data persistence techniques, insuring the application runs regardless of browser supported function. J.A.T.E uses an IndexedDB database and the idb package. This application is deployed to Heroku, to access it in production continue reading the documentation!

## Table of Contents
1. [Description](#description)
2. [Table of Contents](#table-of-contents)
3. [Usage](#usage)
4. [User Story](#userstory)
5. [Acceptance Criteria](#acceptancecriteria)
6. [Installation](#installation)
7. [Credits](#credits)
8. [License](#license)


## Usage
This application is deployed to [Heroku](https://pwa-challenge1-b508091ee337.herokuapp.com/).


### User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

### Acceptance Criteria 

```md
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

## Installation

1. Create a new repository on your GitHub account and clone it to your computer.

2. When you're ready to deploy, use `git add`, `git commit`, and `git push` commands to save and push your code to your GitHub repository.

3. Navigate in your browser to your GitHub repository and then navigate into your repository's `Settings` tab on the right side of the repository's page.

4. From the settings page, scroll down to the GitHub Pages section and then, in the section labeled `Source`, select that you would like to use the `main` branch as your source.

5. Navigate to `<your-github-username>.github.io/<your-repo-name>` and you will find that your new web page has gone live! (For example, if your GitHub username is `lernantino` and the project is `css-demo-site`, your URL would be `lernantino.github.io/css-demo-site`)

6. Next, use the terminal to run the command npm i to install the dependencies associated with this application (developers may need to install dependencies directly from the command line).


## Credits
Thank yo for viewing my project! Along side TA's and team mates I was able to successfully build this app! (https://github.com/tfkjosh/PWA-Challenge/blob/main/README.md)


##License

MIT License

Copyright (c) [2023] [Joshua King]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

