# Choosing a Linter + Styleguide/Formatter for a Vue+Typescript Project

## Project overview
Linter is a tool that analyzes your code for syntax and programming errors. ESLint and TSLint are the 2 famous ones. TSLint is now deprecated since recently. And the migration to ESLint does not come easy. Specially if you are adding a style guide (airbnb, google, standard) and a code formatter (prettier, beautify) on top and you want to configure that to work with ESlint in an IDE (Visual Studio Code, Webstorm) with it's own extensions. Vue project with Typescript comes with it's own challenges. Vetur is the official extension for Vue on VS Code. That introduces it's own formatting rules. 

This project help transition from TSLint to ESLint for a Vue + Typescript project with the most seamless configuration of ESLint + Prettier +  Vetur + VS Code. But it can also be used for angular, react projects.

## Web of Problems & Confustions (Too many choices)

- What npm packages to install? (eslint, typescript-eslint/eslint-plugin, parser, eslint-plugin-prettier, etc..)
- How to install? (eslint --init, vue init eslint, vue add eslint)
- Which style guide to choose? (Airbnb, Google, Standard)
- what extensions to install in VS code? (Vetur, ESLint, Prettier)
- Which config script to use .vscode/settings.json .eslintrc.js, .prettierrc, .editorConfig) 
- What plugins and parsers and rules? 
- Recommended or Essential configuration?

## Project setup
Follow the commits from the start. First we create a legacy Vue + Typescript project with vue init. Then we replace TSLint by ESLint. Then we choose the most effective formatter and configure with ESLint using VS Code extensions and config files.
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
