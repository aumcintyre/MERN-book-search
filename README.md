# graphql-book-search-engine

![License badge](https://img.shields.io/badge/license-MIT-blue)

## Description
The Google Book Search Engine is a simple web application built on the MERN Stack that allows users to search for any book that exists on the Google Book Library. Users are also able to save books that they are interested in to their profile so that they can keep track of what books they would like to read.

## Usage
To use the application go to https://graphql-google-book-search.herokuapp.com/ and begin by creating an account (create a username, provide an email, and create a unique password) so that you can access all of the sites features. Once logged in you can search for any book using its title or any keywords that may be in the description. You can save books from the search results page, and then see those books on the /saved page. Books can also be removed from your favorites on the /saved page using the 'remove book' button.


## Installation

1. Run this in a command line at whatever file path you want this program exist at:
```bash
git clone https://github.com/aumcintyre/MERN-book-search
```
2. If you want a development version to personally edit run this command at the root level of the repo in the integrated terminal:
```bash
npm install && npm run develop
```
3. If instead you want a production version for personal use at the root level of the repo run:
```bash
npm install && npm run build
```


## Features 
This application features the use of mongoose-atlasDB to store and save books from the Google Book Search API. JSON Web Tokens are used to authenticate users, prevent unauthorized users from accessing cetian features of the site, and making sure that all requests being made on the site are done by legitmate users. The graphql-book-search-engine makes use of GraphQL quereies, mutations, typeDefs, and resolvers to handle all requests made to the mongoose database and the server. 

## Contributing
If you would like to contribute in any way to this project, feel free to contact me at aumcintyre@gmail.com.

## license
MIT


## Deployed Application
https://book-search-engine-mcintyre.herokuapp.com/
