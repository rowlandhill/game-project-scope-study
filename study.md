# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.
    [Desktop Wireframe 1st draft](http://imgur.com/g933oFU)
    [Desktop Wireframe 2nd draft](http://imgur.com/UYcVpLd)
    [Mobile Wireframe 1st draft](http://imgur.com/H0Ct8vN)
-   The data structure you plan to use.
  <!-- -*- I plan on using JSON to store user credentials and records.  I'm going to use an array to store the winning parameters and I believe I'm going to use corresponding tables to set up the board, although I may use divs since you guys said we should stay away from tables :) -->
-   How you will take the markup of the game board and represent it in JS
  <!-- -*-  The class and id I give my board will be used in JavaScript to be tested against an array with all the winning combinations and an empty array to track the progress of the game.  I'll also be saving the winning arrays with the user credentials to keep track of their records. -->
-   How you plan to approach this project.
  <!-- -*- I am going to plan out the logic of the game, so after each step I take, I know where I will need to go - mirroring what we did with the books training at the end of last week.  -->
-   4-8 user stories for your game project.
<!--
  As a user, I want to be able to play tic tac toe.  I want to be able to create an account, so I can sign in and out with a password.

  I would like to be able to change my password if I want.

  I would like my record saved to my account, and I would like to see the rankings of the top 5-10 users shown on the app, like an arcade.

  I want to be able to click a button to start a new game without having to refresh the page.

  Eventually, I want the starting playing to be randomized, and I would also like to be able to play a user on another computer. -->

-   How you plan to keep your code modular.
  <!-- -*- I will keep my JavaScript, HTML and CSS files, along with my scripts, separate.  My callbacks will be organized by what they do and what they manipulate, and they'll be stored accordingly (API calls, events, user interface, etc...) -->
-   What creative spin will you add to your project?
  <!-- -*- I'd like to add some different events to signal the start and end of the game.  If there's time, I'd like to style it more, or give the user the ability to choose an avatar for their 'X' or 'O'.  I'd also like to have the rankings show, like an arcade, where you type in your initials and it shows your record vs everyone else. -->
-   How will you use version control to backup / track your project?
  <!-- -*- I will commit early and commit often.  Each time a line of code is written, it will be tested.  Each time a function is completed, the entire app will be tested and if it works, I will commit with thorough notes.  That way, if something goes horribly wrong, I will be able to go back to when the app last worked. -->
-   Do you plan to attempt any of the bonuses?
  <!-- -*- If I have time, yes.  I would like to be able to have two users on two different systems play each other. -->

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur](http://imgur.com/).
