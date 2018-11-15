# Crana

CReate A Node Application

> A CLI tool to create React + Node apps with just one command (batteries included)

# Quick Start

💡 To get up and running with your first Crana app, fist install Crana globally:

```bash
npm i -g crana
```
Then initialize your app:

```bash
crana init <projectName> [projectFolder]
```

Now fire up the frontend and the backend concurrently in development mode:

```bash
crana dev
```

# Project structure

The interesting files for you are all located in the *src folder*:

```
- assets
    * index.html
- src
    - client
        - components
            * index.css
            * index.jsx
            * logo.png
        * index.jsx
    - server
        * index.js
        * start-server.js
    - shared
        * index.js
* .npmignore
* jsconfig.json
* package.json
* Procfile
* README.md

```

As you can imagine, the client folder contains all files for React and the server folder contains all files for Node.js backend. The shared folder contains code you would like to share between client and server. This is a good place for e.g. utility functions, domain logic etc.

_NOTE: Be aware that the server files are not transpiled and thus don't support certain features like ES6 imports. This also the reason why all code in the shared folder must be executable with your current node.js version._

# Crana Modules
