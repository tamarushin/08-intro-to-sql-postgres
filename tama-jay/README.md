

## User Stories and Feature Tasks
*As a user, I want to store my articles in a database so that my articles are available for users from an external source.*
- Install and require the NPM PostgreSQL package `pg` in your server.js file.
- Make sure to complete the connection string.
  - Windows and Linux users: You should have retained the user/password from the pre-work for this course. Your OS may require that your connection string is composed of additional information including user and password. For example: `const conString = 'postgres://USER:PASSWORD@HOST:PORT/DBNAME'`;
  - Mac users: `const conString = 'postgres://localhost:5432'`;
- Pass the appropriate argument when instantiating a new Client.
- The articleView.js methods are different now that we are not accessing the JSON file directly, and instead retrieving the articles from a database. Therefore, we no longer need to export the JSON, so remove all code that was involved in performing this action.
*As a developer, I want to review my code base so that I have a deep understanding of its overall functionality.*
- Study each of the new routes in your server.js file by examining the SQL statements and any associated data being handed through the request.
- For each of the `COMMENT` items in server.js, provide a brief description of what that function immediately below is doing. Be sure to indicate, where applicable, details such as:
  - Which method of article.js is interacting with this particular piece of server.js?
  - What part of ***CRUD*** is being enacted/managed by this particular piece of code?
  - As applicable, an additional sentence or two of explanation about what the code is doing, what NPM packages are involved, etc. The goal is to demonstrate that you understand what is going on in the code without glossing over details, but also without writing a novel about it.
## Documentation
_Your README.md must include:_
```md
#Into to SQL-postgres
**Author**: Tama Rushin
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)
## Overview
<!-- The first thing we did was a npm init -y inside of the starter code folder. This creates a package.json with meta data about my project. Next we did a (npm i -S), this saves all of the project's dependencies to the package.json. Next we created a gitignore at the root of the repo itself so node and environment modules dont get uploaded to github. Next we created a new branch and duplicated the start-code in a new folder, then we did a git init and a initial commit up to our github repo.
From Here a user needs to npm i -S pg (postgres) and require it in the server.js, then create a connection string and update the client constant. Then remove the line of code exporting the json. -->
## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->
## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples:
01-01-2001 4:59pm - Application now has a fully-functional express server, with GET and POST routes for the book resource.
## Credits and Collaborations
<!-- Jay Adams. -->
-->