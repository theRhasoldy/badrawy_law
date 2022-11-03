# HTML SCSS JS Project Template

My current folder structure used for basic html scss and js web project (subject to change).

## Folder Structure

### Main Structure

```
.
|-- app
|   |-- assets
|   |   |-- jpeg
|   |   |-- svg
|   |-- js
|   |-- pages
|   |   |-- 404.html
|   |       ...
|   |-- scss
|-- dist
|   |-- styles.css
|   |-- styles.css.map
|-- index.html
```

### SCSS Structure

Following the 7-1 sass architecture, more [here](https://www.learnhowtoprogram.com/user-interfaces/building-layouts-preprocessors/7-1-sass-architecture).

```
|-- scss
|   |-- base
|   |   |-- _typography.scss
|   |       ...
|   |-- components
|   |   |-- _buttons.scss
|   |       ...
|   |-- layout
|   |   |-- _nav.scss
|   |   |-- _header.scss
|   |   |-- _grid.scss
|   |   |-- _footer.scss
|   |       ...
|   |-- pages
|   |   |-- _home.scss
|   |       ...
|   |--	utilities
|   |   |-- _mixins.scss
|   |   |-- _variables.scss
|   |       ...
|   |-- main.scss
```

## Test NPM Function

```
"scripts": {
	"test": "sass app/scss/main.scss dist/styles.css -w & live-server --browser=firefox-developer-edition"
},
```

And as always, happy coding 😁!
