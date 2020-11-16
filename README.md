# **Note Taker**

![GitHub license](https://img.shields.io/badge/Made%20by-%40mrmathews08-orange)
![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

## Description 

 https://desolate-inlet-61882.herokuapp.com/

Create an application that can be used to write, save, and delete notes. This application will use an express backend and save and retrieve note data from a JSON file.

* The application frontend has already been created, it's your job to build the backend and connect the two.

* The following HTML routes should be created:

  * GET `/notes` - Should return the `notes.html` file.

  * GET `*` - Should return the `index.html` file

* The application should have a `db.json` file on the backend that will be used to store and retrieve notes using the `fs` module.

* The following API routes should be created:

  * GET `/api/notes` - Should read the `db.json` file and return all saved notes as JSON.

  * POST `/api/notes` - Should receive a new note to save on the request body, add it to the `db.json` file, and then return the new note to the client.

  * DELETE `/api/notes/:id` - Should receive a query parameter containing the id of a note to delete. This means you'll need to find a way to give each note a unique `id` when it's saved. In order to delete a note, you'll need to read all notes from the `db.json` file, remove the note with the given `id` property, and then rewrite the notes to the `db.json` file.


## Table of contents
- [Description](#Description)
- [Installation](#Installation)
- [Usage](#Usage)
- [License](#License)
- [Contributors](#Contributors)
- [Test](#Test)
- [Repository Link](#Repository)
- [GitHub Info](#GitHub) 
## Installation
       Use the heroku link for a functioning app.
       or
       npm i  
       node server.js 
       to run locally
## Usage

AS A user, I want to be able to write and save notes

I WANT to be able to delete notes I've written before

SO THAT I can organize my thoughts and keep track of tasks I need to complete

<img width="1680" alt="Screen Shot 2020-11-16 at 12 12 10 PM" src="https://user-images.githubusercontent.com/65747246/99297063-f62c2300-2804-11eb-8f42-df8ddfc0015e.png">


## License
![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
## Contributors
Tyler Mathews
## Test
Null
## Repository
- [Project Repo](https://github.com/mrmathews08/notes)
## GitHub
![Image of me](https://avatars1.githubusercontent.com/u/65747246?v=4)
- Tyler  Mathews
- [GitHub Profile](https://github.com/mrmathews08)
- <null>