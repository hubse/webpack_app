# Webpack App

## Description
This is a simple Webpack application that demonstrates basic functionality module bundler for JavaScript applications.

## What is webpack?
Webpack is a module bundler for JavaScript applications — basically, it takes your code (and all its dependencies like JS, CSS, images, etc.) and bundles it into one or more optimized files for the browser.

Here's a quick breakdown

## Steps to create App
mkdir my-webpack-demo
cd my-webpack-demo
npm init -y
npm install webpack webpack-cli style-loader css-loader --save-dev

1. created dist/index.html
2. created src/index.js
3. created src/style.css
4. created webpack.config.js
5. npx webpack, which creates dist/main.js.

## Project Structure
```
my-webpack-demo/
├── dist/
│   └── index.html
├── src/
│   ├── index.js
│   └── style.css
└── webpack.config.js
```

## What Webpack Did Behind the Scenes
Read your index.js
Saw you imported style.css
Loaded both into memory
Packed them into a single file (main.js)
You linked just that one file in index.html

## Here’s what Webpack helps with as your app grows:
Automatically compiles SCSS or TypeScript
Optimizes files for production
Code splitting: load only what's needed
Hot reload during development
Tree shaking: removes unused code

## Installation
1. Clone the repository.
2. Run `npm install` to install the necessary dependencies.

## Usage
1. Run `npm run build` to build the project.
2. Open `dist/index.html` in your browser to see the app in action.

## Advancement Steps
- Add more interactive features.
- Implement additional styling.
- Explore using other Webpack plugins for optimization.
