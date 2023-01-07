# ∞ Omnifood

## About The Project

[![Project screenshot]](/src/img/forkify.PNG)

Forkify is a vanilla JavaScript application that interacts with the Forkify API to fetch and display recipe food data. This app uses modern JavaScript tools, such as Webpack to bundle the modules, and Babel to convert ES6, ES7 and ES8 back to ES5. The user can search for a specific recipe, and save to a favorites list via local storage. The user can easily increase or decrease
servings as per his need and can view detailed directions.

## Build With

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [SCSS](https://sass-lang.com/)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/javascript)
- [Webpack](https://webpack.js.org/)
- [NPM](https://www.npmjs.com/)

## Getting Started

To get started with project just simply fork this repo or download locally on your System.

To get a local copy up and running follow these simple example steps.

### Prerequisites

Start with the latest version of NPM to avoid any errors:

```sh
npm install npm@latest -g
```

### Installation

1. Get a free API Key at [Forkify API_KEY](https://forkify-api.herokuapp.com/v2)

2. Clone the repo

```sh
git clone https://github.com/StergiosFotoglou/Forkify.git
```

3. Install NPM packages

```sh
npm install
```

4. Enter your API key in `config.js`

```JS
const KEY = 'ENTER YOUR API KEY';
```

## Usage

1. The Forkify Recipe App allows users to search for recipes.

2. Users can view the recipe along with the cook time and also
   increase or decrease the amount of servings they need.

3. Bookmarked recipes are stored in local storage so no database was
   required for this application.
