# Jewelry-Website

https://medium.freecodecamp.org/part-1-react-app-from-scratch-using-webpack-4-562b1d231e75

To create a inital directory with webpack4 and react
npm init
npm i webpack webpack-cli -D

create src folder with file index.ini and type
console.log("hello");

In package.json add the following script  
"scripts": {
"start": "webpack --mode development",
"build": "webpack --mode production"
},

npm run start
//add a .gitignore and add the following files: dist, node_modules
npm i react react-dom -S

npm i babel-core babel-loader babel-preset-env babel-preset-react -D
