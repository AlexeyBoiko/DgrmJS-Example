# DgrmJS Example
This is a minimalistic example of using the DgrmJS library.

DgrmJS is a JavaScript library for creating SVG diagram editors.   
[DgrmJS GitHub](https://github.com/AlexeyBoiko/DgrmJS).

## This example shows, how to

<img src="https://raw.githubusercontent.com/AlexeyBoiko/DgrmJS-Example/doc/img/dgrm-js-example.PNG" alt="diagram" width="600"/>

- Install DgrmJS library from npm.
- Create a shape with one In-Connector and one Out-Connector.
- Add shapes to diagram, update shape, delete shape from diagram.
- Connect shapes with code.
- Subscribe to diagram events.

## Run example
Clone repository.

Install dependencies:
```
npm i
```

Run:
```
npm run start
```

## How to create the same project yourself
Create directory for the project. Go to project directory.  
Init node project:
```
npm init
```

Install DgrmJs library from npm:
```
npm i dgrm
```

This exmaple uses [Live Server](https://www.npmjs.com/package/live-server) as development http server.  
Install 'Live Server':
```
npm install --save-dev live-server
```
Add 'start' script to the package.json:
```
"scripts": {
	"start": "live-server"
},
```

Add [index.html](https://github.com/AlexeyBoiko/DgrmJS-Example/blob/main/index.html) file to the project diractory.

Run:
```
npm run start
```
