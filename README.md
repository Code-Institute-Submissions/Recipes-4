
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
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import Original Surfer font and the emboss effect
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
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results]()

### Testing User Stories from User Experience (UX) Section

-   #### Experienced Cook Goals

    1. As an experienced cook, I want a site where I can share my recipes with other people.

        1. Upon entering the site, users are immediately greeted with a colourful page and a colourful game.
        2. When the computer or the user selects a colour, the element will flash with a new, brighter colour.

    2. As an experienced cook, I want a site that will enable me to store all my recipes in one place.

        1. When the computer selects a colour, a sound will play that is allocated to that specific colour.
        2. When the user selects the right colour, the sound will play. It acts as a victory noise.

-   #### Novice Cook Goals

    1. As an Adult Visitor, I want access to a quick-start memory game to challenge myself.

        1. The site is a singular page that the user can return to and can be playing within a matter of seconds.

    2. As an Adult Visitor, I want to be able improve my memory capability and compete against my friends.

        1. The endless levels mean there is a challenge for even the most intelligent users.
        2. Experienced users can train their memory, and try to beat their friends' best scores.

-   #### Dietary Requirement Cook Goals

    1. As a cook with certain dietary requirements, I want a site where I can find recipes that meet my needs.

        1. The memory game is a fantastic way to keep the brain active, and the memory fresh.
        2. As an Elderly Visitor/Alzheimer Patient I can keep track of my progress via the levels I can get to.

    2. As a cook with certain dietary requirements, I want to be able to store my niche selection in one place.

        1. The rules are constantly on display for users to refer to.
        2. The basic colours used within the game help to keep it simple.
        3. The noises used in tandem with the colours help with remembering the sequences.
        4. The low amount of elements available (four) to interact also help to keep it simple.

### Further Testing

1. Playing the game
    * Click the start button and click the elements to ensure the user cannot interact while compTurn=true.
    * Repeat the computer sequence to see if nextTurn is working correctly.
    * Lose the game to see if the game resets as intended.
    * Keep clicking the start button to see if the game restarts correctly despite the interference.
    * Complete the level to see if the next level starts correctly.
    * Repeat the above steps for every level.
    * Complete these steps on every device size.


-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was tested on Laptop, Desktop, Ipad, GalaxyS5, OnePlus6.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

-   If the user clciks on the same colour in rapid succession, the element might not play sound due to the length of the sound used.
-   If the user spam clicks the colours very quickly before the game starts, the sequence might break, and the page may need to be refreshed.

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

