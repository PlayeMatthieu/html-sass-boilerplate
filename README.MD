# Create HTML/Sass Boilerplate

Generate html/sass boilerplate in matter of seconds! 🕒

## How to
```sh
npx create-html-sass-boilerplate my-app
cd my-app
```

## Creating an app
**You will need to have Node 8.16.0 or Node 10.16.0 or later version on your local development machine**

#### npx
```sh
npx create-html-sass-boilerplate my-app
cd my-app
```
#### Npm
```sh
npm create-html-sass-boilerplate -g
create-html-sass-boilerplate my-app
```

once the boilerplate is created, cd into it:
```sh
cd my-app
```

### Folder structure
Generate a basic folder structure for you're next project
```
my-app
├── index.html
├── css
│   ├── style.css => has to be genereted with "sass --watch scss/main.scss css/style.css"
├── scss
│   ├── base
│       ├── _colors.scss
│       ├── _default.scss
│       ├── _fonts.scss
│   ├── layout
│       ├── _Header_.scss
│       ├── _Hero.scss
├── js
│   ├── main.js
├── assets
│   ├── icons
│   ├── images
├── pages
```