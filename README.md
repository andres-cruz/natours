# Natours

This project uses the library node-sass to compile .scss files to css.
```json
"devDependencies": {
    "node-sass": "^4.12.0"
  }
```  
### Commands

To compile sass run this command:
```sh
$ npm run compile:sass
```

To run live-server run this command:
```sh
$ live-server
```
### Scripts

This script in the package.json file is the responsible for compiling sass:
```json
"compile:sass": "node-sass sass/main.scss css/style.css"
```  

You can add the "-w" flag to the script to make the compiler to watch for changes:
```json
"compile:sass": "node-sass sass/main.scss css/style.css -w"
```  