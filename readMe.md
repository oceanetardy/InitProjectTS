#Initialiser un projet TypeScript
npm init

package name: porte le nom du projet (version : 0.0.1)

npm install express

npm i typescript —save-dev

npm i -D @types/express @types/node

tsc —init

npm i -D nodemon

npm i -D ts-node

mkdir src

cd src

mkdir handlers

mkdir models

Création de server.ts dans /src

Création de home.ts dans /handlers

//////

--- Dans package.json : -----

"scripts": {

"start": "nodemon",

"test": "echo \"Error: no test specified\" && exit 1",

"build": "tsc"

},

puis

"main": "src/server.ts",