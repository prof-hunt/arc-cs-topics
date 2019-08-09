# Programming Environment

In this class we will be writing code both from a "client-side"
and "server-side" point of view. For this we will be using a
"text-editor", which is a program that allows us to edit
plain-text files that contain the HTML, CSS, JavaScript, or
whatever else is needed.

## Checklist

Here is a checklist of the things needed to set up the environment.

### Client-side (running on your laptop)

* Atom - Text Editor with additional packages:
    * `remote-ftp`
        * allows remote editing of files
    * `linter-jshint`
        * realtime detection of JavaScript warnings/errors
* Terminal program
    * Mac OSX: **Terminal**
    * Windows 10: **Powershell**
* SSH (Secure Shell)
    * To be able to log into the linux server

### Server-side (running on _power.arc.losrios.edu_)

* Linux Server Account
    * `user@power.arc.losrios.edu` account
    * `~/public_html/cisw-410/`
        * `~/public_html/cisw-410/project1/`
        * `~/public_html/cisw-410/project2/`
* FTPD - File Transfer Protocol server
    * To allow Atom file uploads/downloads
* NodeJS
    * Server-side JavaScript Engine
    * Version v10.15.2
* NPM - Node Package Manager
* Installed Node Modules
    * `express` - Express
    * `express-handlebars` - Handlebars (templating engine)
    * `sqlite3` - SQLite relational database integration
    * `mocha` - Unit testing framework (dev)
    * `chai` - Assertions library (dev)
    * `zombie` - Headless browser library (dev)
* Sample package.json:
```
{
  "name": "moviedb",
  "version": "1.0.0",
  "repository": "none",
  "description": "Movie Database Project Website",
  "main": "moviedb.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "Prof.Hunt",
  "license": "ISC",
  "dependencies": {
    "express": "^4.17.1",
    "express-handlebars": "^3.1.0",
    "sqlite3": "^4.0.9"
  },
  "devDependencies": {
    "chai": "^4.2.0",
    "mocha": "^6.2.0",
    "zombie": "^6.1.4"
  }
}
```


## Topics

* Back to [List of Topics](000-topic-list.md)
