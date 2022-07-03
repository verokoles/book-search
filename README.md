# Book Search:book:

### RESTful API :arrow_right: GraphQL API

## Purpose:heavy_exclamation_mark:

To take a fully functioning Google Books API search engine built with a RESTful API, and refactor it to be a GraphQL API built with Apollo Server.<br>

### USER STORY:

`"AS AN avid reader I WANT to search for new books to read SO THAT I can keep a list of books to purchase"`

When running `npm start`, the first page showed this:
![Initial book search in RESTFUL API](client/public/first-search.png)

## Table of Contents::mag:

1.  [ HEROKU DEPLOY:heavy_plus_sign: ](#heroku)
2.  [ Installation:hammer: ](#installation)
3.  [ Contributing:handshake: ](#contributing)

## Heroku

[Click Here to view the application live!](https://fast-ocean-62926.herokuapp.com/) <br>
Log In successful, and books are saving:
![Log In successful, and books are saving](client/public/saved-books.png) <br>
Deleted books, logged out, logged back in and the one saved book appears:
![Deleted books, logged out, logged back in and the one saved book appears](client/public/deleted.png)

## Installation

To install dependancies, run the following commands:

     ```
     `npm install` to create node_modules in client, server and root
     ```
     I made sure to delete the package-lock.json file in the root first, and downgrade react & react-dom  to 17.0.2 in the client directory.

     `npm install --save apollo-server apollo-server-core apollo-server-express graphql npm install --save-dev @types/graphql @types/express typescript` in root to install Apollo connection and grapql API
     ```
     run `mongod` to start MONGODB service in another terminal
     ```
     ```
     `npm start` to run from client directory, `npm run watch` from server directory, and `npm run develop` from the root:
     These will run the app with the all functionality to log in, search for, save, and delete books, and log out with saved information with the next login.
     ```
     ```
     `npm i heroku` and `heroku create` to create URL of app in Heroku.com
     ```
     I used GitHub Actions to connect my Heroku application to my account and save all progress.

## Contributing:

Please be kind and professional when adding to or accessing this repository. Thank you!
[More on Contribution Guidelines](https://github.com/verokoles/readme-generator/blob/f57cf6a98bf276960885496059df4b039247c985/contributing.md)
