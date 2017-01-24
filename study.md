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
	http://imgur.com/a/o0fNt

-   The data structure you plan to use.
	I’ll build the page with HTML and CSS, and use javascript to write the game logic.  I’ll use AJAX to do web requests to get, delete, post, and patch data in JSON format to the API.  The data that will be stored on the API is the state of the game and user accounts, including game history.

-   How you will take the markup of the game board and represent it in JS
	I imagine I could build the game board by using a 9 box grid and making some borders hidden so that it looks like a tic tac toe board.  I know that after a player makes a move, it is the other players turn, and I could implement that by using a for loop.  ‘i’ can increment 1 for each turn, and even numbers can represent player1’s turn while odd numbers mean it’s player2’s turn.

-   How you plan to approach this project.
	First I’ll build a page with a basic HTML and CSS layout.  Then I’ll focus on the javascript game logic and actually getting the game to play correctly.  When that’s done or almost done, I’ll work on connecting to the API and making sure the AJAX works.  After it’s all connected ill finish off the HTML and CSS by styling the page.

-   4-8 user stories for your game project.
	As a player, I want the game to feel quick and responsive.
	If I win the game, I’d like the game to declare my victory with fanfare.
	As a player, I want to be able to see my game history and be able to access my account from different computers.
	I want the page style to be colorful, but not aesthetically chaotic.
	I want the app the feel responsive and alive, like having animations for when buttons are pressed or moves are made.

-   How you plan to keep your code modular.
	I’ll try to keep my code organized by having different files linked together.  Each file should have a theme and only contain code relevant to it, such as a colors.css or typography.css.

-   What creative spin will you add to your project?
	I’m pretty interested in style and design, so I’d like to experiment with CSS and SASS to make a cool design and maybe even add in some animations or sounds.

-   How will you use version control to backup / track your project?
	I will make comments in my code frequently, and try to commit often.  Making frequent commits will help me track the changes and make it easier to debug if something goes wrong.

-   Do you plan to attempt any of the bonuses?
	I’d like to do some cool styling, with animations and nice color schemes.  I also think it would be cool to style the X’s and O’s with animations.

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur]
(http://imgur.com/).
