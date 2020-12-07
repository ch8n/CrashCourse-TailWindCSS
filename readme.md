# Tail-Wind-Css for rapid prototyping
No need for styles

## Vscode plugin
* tailwind intellisense for auto complete

## Enviorment setup
* Requires [nodejs](https://nodejs.org/en)
* npm package
  * [tailwindCSS](https://tailwindcss.com/docs/installation)

## Npm script setup
- CSS compile script 
```javascript
// add to package.json scripts
"build:css": "tailwindcss build ./src/styles.css -o ./dist/output.css",
// ./src/styles.css is you main css file
```



