
# Foodaholic Project
Repository to upload the Foodaholic project.

## About
Website for food lovers to find their favorite recipes.

* Initial idea
    * Search for recipes retrieving data from Forkify API.
    * Use of modern JavaScript feautures (ES6, ES7, ES8), webpack (bundle together JavaScript modules) and babel (ES2015+ -> ES5).
    * Use of the MVC pattern.

* Improvements
	* Characters from recipes title were limited.
    * Added/removed spinner before/after showing data.
    * Added search results pagination feature.
    * Added time and servings features within a recipe.
    * Ingredients can be added to a shopping list.
    * Recipes can be added to a liked list.
    * Added persistent data using localStorage.

## Screenshot
![](https://github.com/jemtca/Foodaholic-v1/blob/master/screenshots/foodaholic-v1.gif)

## Technologies Used
* HTML, CSS, JavaScript.
* npm (packages used): [webpack](https://www.npmjs.com/package/webpack), [webpack-cli](https://www.npmjs.com/package/webpack-cli), [webpack-dev-server](https://www.npmjs.com/package/webpack-dev-server), [html-webpack-plugin](https://www.npmjs.com/package/html-webpack-plugin), [babel-core](https://www.npmjs.com/package/babel-core), [babel-loader](https://www.npmjs.com/package/babel-loader), [babel-preset-env](https://www.npmjs.com/package/babel-preset-env), [babel-polyfill](https://www.npmjs.com/package/babel-polyfill), [axios](https://www.npmjs.com/package/axios), [fractional](https://www.npmjs.com/package/fractional), [uniqid](https://www.npmjs.com/package/uniqid).
* APIs: [Food2Fork](https://www.food2fork.com/) -> [Forkify](https://forkify-api.herokuapp.com/).
* Cloud service: [GitHub Pages](https://pages.github.com/).

## How to run the project
* Open the console/terminal.
* Clone the repository: **`git clone https://github.com/jemtca/Foodaholic-v1.git`**
* Go to the project folder: **`cd Foodaholic-v1`**
* Install dependencies/packages: **`npm install`**
* Run the app: **`npm start`**
