
<h1 align="center">Recipe Share</h1>

[View the live project here.](https://adam-sykes-recipe-project.herokuapp.com/)

The idea of this project was to create a site where users could come and share their recipes with one another.

The user has create, edit and delete functionality so they can store all their recipes in one place.

<img src="https://github.com/sykez12/Recipes/blob/a44337cc86ff13af7c0046188b2b11481670a218/Documentation/Recipe%20Share.png" alt="Amiresponsive">

## User Experience (UX)

-   ### User stories

    -   #### Experienced Cook Goals 

        1. As an experienced cook, I want a site where I can share my recipes with other people.
        2. As an experienced cook, I want a site that will enable me to store all my recipes in one place.

    -   #### Novice Cook Goals

        1. As a Novice Cook, I want to learn recipes from others.
        2. As a Novice Cook, I want to try my hand at creating my own recipes.

    -   #### Dietary Requirement Cook Goals

        1. As a cook with certain dietary requirements, I want a site where I can find recipes that meet my needs.
        2. As a cook with certain dietary requirements, I want to be able to store my niche selection in one place.

-   ### Design
    -   #### Colour Scheme
        -   The Main theme is a dark 'green pepper' green, that entices the user through association.
        -   A light blue is used throughout the site to indicate editorial options. While red is used for cancellation or deletion purposes.
        -   A dark blue and deep orange are also used to spice up the colour theme, while still matching with the main dark green.

*   ### Wireframes

    -   Wireframes for all devices - [View](https://github.com/sykez12/Recipes/blob/a44337cc86ff13af7c0046188b2b11481670a218/Documentation/Wireframes/Recipe%20Share.pdf)


*   ### Dbdiagram

    -   Dbdiagram showing database relations - [View](Documentation/RecipeSharedbdiagram.png)

## Features

-   Responsive on all device sizes.

-   Recipe Creation. Edit and Delete functionality are also present.

-   Category Creation. Edit and Delete functionality are also present. This functionality is for the admin only.

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
-   [Javascript](https://en.wikipedia.org/wiki/JavaScript)
-   [Python](https://en.wikipedia.org/wiki/Python_(programming_language))

### Frameworks, Libraries & Programs Used

1. [Materialize:](https://materializecss.com/)
    - Materialize was used to assist with the responsiveness and styling of the website.
1. [Font Awesome:](https://fontawesome.com/icons?d=gallery)
    - Font Awesome was used for their brilliant free icons.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/sykez12/Recipes/blob/a44337cc86ff13af7c0046188b2b11481670a218/Documentation/Wireframes/Recipe%20Share.pdf) during the design process.
1. [Jquery:](https://jquery.com/)
    - Jquery used for dynamic functionality.


## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results]()
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/sykez12/Recipes/blob/bf64f5b5c429ac4d2e2d265d124f8de0f201a076/Documentation/CSSValidationRecipeShare.png)

### Testing User Stories from User Experience (UX) Section

-   #### Experienced Cook Goals

    1. As an experienced cook, I want a site where I can share my recipes with other people.

        1. Upon entering the site, users are given the option to register and create an account.
        2. Once the account is made, they can create their own recipes for all site viewers to see.

    2. As an experienced cook, I want a site that will enable me to store all my recipes in one place.

        1. Each User has their own profile page that displays only the recipes that they have created themselves.
        2. Once created, the user has the option to edit them to their liking, as well as delete them if necessary.

-   #### Novice Cook Goals

    1. As a Novice Cook, I want to learn recipes from others.

        1. As soon as the user enters the site they are shown all the recipes for them to try out.
        2. The Novice user can follow others recipes without having to create their own account or make their own recipes.

    2. As a Novice Cook, I want to try my hand at creating my own recipes.

        1. Encouraged by other recipes on the site, a novice cook could try their own hand at creating recipes.

-   #### Dietary Requirement Cook Goals

    1. As a cook with certain dietary requirements, I want a site where I can find recipes that meet my needs.

        1. As a vegetarian, vegan, or somebody who is on a diet, the site is all inclusive.
        2. The user can use the search bar to search for the dishes that meet their requirements.

    2. As a cook with certain dietary requirements, I want to be able to store my niche selection in one place.

        1. The site gives the user a perfect storage to collate their favourite recipes.

### Further Testing

1. Testing the site
    * Click on all navigation links including the Logo to ensure they are working correctly.
    * Repeat this while logged in and while logged out to ensure consistency.
    * Search dishes in the search function to verify functionality.
    * Search something that is not on the site to ensure No results shows up as expected.
    * Use the reset button to certify it works as intended. 
    * Click "See Recipe" to verify the user is sent to the correct recipe page.
    * For the user created recipes, test the edit and delete button functionality.
    * Create a new recipe to guarantee all fields are required and that recipe is displayed properly.
    * Log in to admin to create new categories.
    * Test the admin edit and delete functionality of categories.
    * Log in to different users to verify functionality.
    * Repeat all these steps across all device sizes.


-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was tested on Laptop, Desktop, Ipad, GalaxyS5, OnePlus6.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

-   On smaller phones, some field placeholder text is not aligned correctly within the field.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/sykez12/braintrain)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://sykez12.github.io/braintrain/) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/sykez12/Recipes)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/sykez12/Recipes)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/sykez12/Recipes
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/sykez12/Recipes
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Code


-   [Materialize](https://materializecss.com/): Materialze used throughout the project mainly to make site responsive.


### Acknowledgements

-   My Mentor Aaron for his continuous, helpful input.

-   Code Institute tutorials.

-   Tutor support at Code Institute for their assistance.

