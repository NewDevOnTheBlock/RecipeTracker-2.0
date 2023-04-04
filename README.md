<br/>
<p align="center">
  <a href="https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/RecipeTracker-2.0">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Recipe Tracker 2.0</h3>

  <p align="center">
    A new full-stack version of my world famous recipe tracking app!
    <br/>
    <br/>
    <a href="https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/RecipeTracker-2.0"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/RecipeTracker-2.0">View Demo</a>
    .
    <a href="https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/RecipeTracker-2.0/issues">Report Bug</a>
    .
    <a href="https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/RecipeTracker-2.0/issues">Request Feature</a>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/RecipeTracker-2.0/total) ![Contributors](https://img.shields.io/github/contributors/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/RecipeTracker-2.0?color=dark-green) ![Issues](https://img.shields.io/github/issues/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/RecipeTracker-2.0) ![License](https://img.shields.io/github/license/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/RecipeTracker-2.0) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)

## About The Project

![Screen Shot](https://recipe-tracker-m-front.onrender.com)

You can view a deployed version of this app at: https://recipe-tracker-m-front.onrender.com

Note: Render can take a minute to show relevant information retrieved from the DB. This is a common issue with deployment on Render, but rest assured that the app is functioning and does indeed work properly. If all else fails, try either refreshing the page, or loading in from a new window.

This full-stack web based application allows a user to submit a recipe to a database, and every one that gets added to the DB is added to the home page. There are two separate pages, one for a list of all recipes, and one that picks five random recipes from your list for expedited meal planning.

It uses a relational database (PostgreSQL) with just simple CRUD methods. A user can submit a recipe with the name, cuisine origin, and a link to a website with the recipe ingredients and steps. The user is able to delete a recipe at any time.

## Built With

Front-End Technologies Used:
- HTML/CSS/JavaScript
- React.js
- React-Router-Dom
- Bootstrap (style)

Back-End Technologies Used:
- PostgreSQL (Relational Database)
- Express.js (RESTful API development)
- Knex.js (database querying)
- Cors
- dotenv
- nodemon (server used for development)

## Getting Started

To get started locally, you can fork the repo or download the .zip (be sure to extract it!) as normal, then after you use the command line to cd your way into the directory. After doing so, a simple "npm i" is more than enough to get the project up and running. 

To run the front-end, just enter "npm run start:react"
to run the back-end, just use "npm run start:dev"

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

* npm

```sh
npm install npm@latest -g
```

### Installation

1. Clone the repo

```sh
git clone https://github.com/your_username_/Project-Name.git
```

2. Install NPM packages

```sh
npm install
```

## Usage

During my time at Chegg/Thinkful's Engineering Immersion bootcamp, we had a small front-end project that utilized basic react, html, and css. I told my girlfriend about the project and she mentioned how she would like to have an app for herself to track recipes. After graduation, to refine my skills a little more, I revisited old projects to either build a front/back end for them, or add functionality. Originally it was just a front-end app with a static data set. I took it upon myself to build a simple PostgreSQL database and RESTful API, then added CRUD methods. Once I was done, I added a button to retrieve 5 recipes at random in order to make her meal planning a little easier. 

In short, this app allows you to save recipes you like to cook, and if you're about to grocery shop for the week and don't know what you want, then you can just generate 5 recipes at random and add those ingredients to your shopping list for maximum meal planning profit!

## Roadmap

See the [open issues](https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/RecipeTracker-2.0/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/RecipeTracker-2.0/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.
* Please also read through the [Code Of Conduct](https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/RecipeTracker-2.0/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [LICENSE](https://github.com/NewDevOnTheBlock/https://github.com/NewDevOnTheBlock/RecipeTracker-2.0/blob/main/LICENSE.md) for more information.

## Authors

* **Pierce DeAnda** - *Full-Stack Engineer* - [Pierce DeAnda](https://github.com/NewDevOnTheBlock/) - *Primary Contributor and Programmer*

## Acknowledgements

* [Pierce DeAnda](https://github.com/NewDevOnTheBlock/)
* [Express](https://expressjs.com)
* [MongoDB](https://mongodb.com)
* [React Docs](https://legacy.reactjs.org/docs/getting-started.html)
