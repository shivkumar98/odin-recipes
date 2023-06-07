# odin-recipes

## 📜 Assignment 📜

* Create a new repo for this project on GitHub called `odin-recipes`

### 🔴 Iteration 1 - Initial structure

1) Create a directory called `odin-recipes`, and create a `index.html` file
2) Create a `h1` heading "Odin Recipes"

### 🔴 Iteration 2 - Recipe Page

1) Within this directory, create a directory named `recipes`
2) Create a HTML file in the recipes directory, e.g. `lasagna.html`
3) Create a `h1` heading with the recipes name
4) Within the `index.html` page, add a link to the recipe page. E.g write out `<a href="recipes/recipename.html">Recipe Title</a>` below the heading

### 🔴 Iteration 3 - Recipe Page Content

1) An image of finished dish under h1 heading. You can find images of the dish from this [recipe site](https://www.allrecipes.com/)

2) Under the image, there should be an appreopiate sized "Description" heading followed by a paragraph describing the recipe

3) Under the Description, add an "Ingredients" heading followed by an **unordered list** of the ingredients

4) Add a "Steps" heading followed by an **ordered list** of the steps needed for the recipe.

### 🔴 Iteration 4 - Add More Recipes

1) Add two more recipes with identical page structures
2) Remember to add a link to the new recipes on the index page

<hr>

## 👨‍💻 Assignment Notes 👨‍💻

* I create a new repo on github

* I copy the SSH link: git@github.com:shivkumar98/odin-recipes.git

```sh
$ git clone git@github.com:shivkumar98/odin-recipes.git
```

* I create the `index.html` file in the `odin-recipes` directory:

```sh
$ touch index.html
```

* I open this file in VS Code and create the boilerplate and heading:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>My Recipe Page</title>
    </head>
    <body>
        <h1>Odin Recipes</h1>
    </body>
</html>
```