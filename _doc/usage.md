# Usage

## Main Commands


:star: Create a new crana project

```bash
crana init <projectName> [projectFolderName]
```

:dizzy: Concurrently starts the frontend and the backend in development mode

```bash
crana dev 
```

:satellite: Starts the webpack development server for the frontend

```bash
crana dev:client
```

:bar_chart: Starts the node.js backend in development mode with live-reload

```bash
crana dev:server
```

:blue_car: Creates a production build for the frontend application

```bash
crana build:client
```

## Util Commands

:mag:  Executes eslint and styleling in autofix mode for your client files (src/client + src/shared)

```bash
crana lint:client
```

:mag: Executes eslint in autofix mode for your server files (src/server + src/shared)

```bash
crana lint:server 
```

:books: See how many LOC you've already written

```bash
crana count-lines 
```