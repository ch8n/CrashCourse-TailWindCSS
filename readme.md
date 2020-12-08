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

## CSS tips
* Button
  * left and right padding needs to be bigger than top|bottom example : `75px 150px;`

* Positioning 
  * block :
    *  try to add new content into view
    *  always have width match_parent & height wrap_content, height is modifyiable
    *  ex: `<P>` tag
  * inline :
    * always try to adjust into the space 
    * always wrap_content, 
    * **cannot** update its height|width|margin|padding through styles. 
    * ex: `<a>` tag
  * inline-block :
    * situation where we need inline to be modifiable and and doesnt have strict width
    * 



