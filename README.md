# odin-recipes
Odin Project Foundations Course 

# Instructions

1. Create a new repo for this project on GitHub.com and call it odin-recipes and choose the public option instead of the default private.

2. Clone that repository onto your local machine, inside the repos folder that you previously created in the Git Basics lesson. The command should look like git clone git@github.com:username/odin-recipes.git (use SSH).

3. Now cd into the odin-recipes project directory that is now on your local machine.

4. Set up your README.md file and write a brief introduction describing what the current project is and what skills you will have demonstrated once you have completed it. (You can also do this as a self-reflection at the end of the project, which is a good way to review what you have learned.)

# Assignment

Iteration 1: initial structure

    Within the odin-recipes directory, create an index.html file.
    Fill it out with the usual boilerplate HTML and add an h1 heading “Odin Recipes” to the body.

Iteration 2: recipe page

    Create a new directory within the odin-recipes directory and name it recipes.
    Create a new HTML file within the recipes directory and name it after the recipe it will contain. For example lasagna.html. You can use the name of your favorite dish or, if you need some inspiration, you can find a recipe to use at Allrecipes.
    For now, just include an h1 heading with the recipe’s name as its content.
    Back in the index.html file, add a link to the recipe page you just created. Example: Under the <h1>Odin Recipes</h1> heading, write out the link like so: <a href="recipes/recipename.html">Recipe Title</a>. The text of the link should again be the recipe name.

Iteration 3: recipe page content

    Your new recipe page should have the following content:

    An image of the finished dish under the h1 heading that you added earlier. You can find images of the dish on Google or Allrecipes.

    Under the image, it should have an appropriately sized “Description” heading followed by a paragraph or two describing the recipe.

    Under the description, add an “Ingredients” heading followed by an unordered list of the ingredients needed for the recipe.

    Finally, under the ingredients list, add a “Steps” heading followed by an ordered list of the steps needed for making the dish.

Iteration 4: add more recipes

    Add two more recipes with identical page structures to the recipe page you’ve already created.
    Don’t forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren’t all on one line.

    Example:
    
    <ul>
    <li><a href="recipes/yourrecipe.html">Recipe Title 1</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 2</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 3</a></li>
    </ul>

    