# ratesOFmine
Places Rates

## Install Node
Install using winget 

```sh
winget node.js
```

## Init NPM project
- <b> ONLY if it doesn't exist</b> create a project folder.


- Launch NPM using:
```sh
npm init
```

## Install Server As a dependency in your npm package
Use: 
```sh
npm install http-server
```

## Create static Folder & index HTML
After init the npm project we will find at the root project we should find the following files and dirs:

- node_modules/
- package.json
- package-lock.json
- .git/
- .gitignore
- readme.md


Now we will create a new dir called static where we will add all of our static files.
Inside we will create the start-page index.html

- static/index.html


Optional:

- Add a hello-world content for the index.html

## Write Script
http-server [path] [options]
[path] defaults to ./public if the folder exists, and ./ otherwise.

Now you can visit http://localhost:8080 to view your server

Note: Caching is on by default. Add -c-1 as an option to disable caching.

## Start server
Run script from terminal

```sh
npm run start
```