# Book-Search-Engine

## Description

An app to query and save books from the google books API.

This app was originally designed using a RESTful API, and was refactored with graphql API and Apollo server.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

Installation requires the user to run "npm i" to install all neccessary packages, and then run "npm run develop" to launch the server. Dependencies used include: express, mongoose, morgan, compression,concurrently, graphql, bcrypt, apollo-server-express, and jsonwebtoken.

## Usage

To use the app, visit [link to deployed app](https://dashboard.heroku.com/apps/rocky-cove-15007).

Click login or signup in the top right to create an account or login. Enter the name of a book in the search bar to view books from the google books API.When logged in, users can click a button under queried books to save the book, and view all saved books by clicking "see your books" in the top right.

[gif of usage](./assets/budget-tracker.gif)

## Credits

My study group helped me troubleshoot my application: Alex Jrugs, Chip Long, Jared Sutch, Lauren Gabaldon, Tarik Maggio, and Josh Lee.

## License

MIT License

Copyright (c) [2021] [Lacey Pape]

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
