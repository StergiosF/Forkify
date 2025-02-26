# 🍴 Forkify

A recipe search application made with JavaScript.

## Deployment

Deployed Website: https://forkify-stergios.netlify.app

## About The Project

[![forkify.png](/src/img/forkify.PNG)](https://forkify-stergios.netlify.app/)

Forkify is a vanilla JavaScript application that interacts with the Forkify API to fetch and display recipe food data. This app uses modern JavaScript tools, such as Parcel to bundle the modules, and Babel to convert ES6, ES7 and ES8 back to ES5. 
The user can search for a specific recipe, and save it to a favorites list via local storage. The user can easily increase or decrease servings as per his needs and can view detailed directions.

## Built With

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [SCSS](https://sass-lang.com/)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/javascript)
- [Parcel](https://parceljs.org/)
- [NPM](https://www.npmjs.com/)

## Getting Started

To get started with the project simply fork this repo or download it locally on your System.

To get a local copy up and running follow these simple example steps.

### Installation

1. Get a free API Key at [Forkify API_KEY](https://forkify-api.herokuapp.com/v2)

2. Clone the repo

```sh
git clone https://github.com/StergiosFotoglou/Forkify.git
```

3. Install NPM packages

```sh
npm install npm@latest -g
```

4. Enter your API key in `config.js`

```JS
const KEY = 'ENTER YOUR API KEY';
```

5. Start a local server for the project
```sh
npm start
```

## Usage

1. The Forkify Recipe App allows users to search for recipes.

2. Users can view the recipe along with the cooking time and also
   increase or decrease the amount of servings they need.

3. Bookmarked recipes are stored in local storage so no database was
   required for this application.
