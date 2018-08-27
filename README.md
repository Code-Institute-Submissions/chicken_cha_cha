# Chicken Cha Cha Cha

Interactive Frontend Development Project - Code Institute

This is a Javascript single page application game called chicken Cha Cha Cha. It is based on the [board game of the same name](https://boardgamegeek.com/boardgame/3570/chicken-cha-cha-cha)  
The game is intended for children, but can obviously be played by all ages!  
In the original game, 2-4 players play against each other by trying to take each others lives by moving around the game board.  
Players move around the game board by matching images around the board with hidden images in the middle of the game board.  
As well as recreating the rules from the original board game for multiple players, this version also includes a single player version.  


### A live version is hosted [here](https://mparkcode.github.io/chicken_cha_cha/)  

## UX

The game is originally intended for children, as such the design is intended to appeal to children.  
There are fun cartoon images as well as fonts that would be visually interesting to children.  
Text is kept minimal to keep the focus on the game.  
There is a score sheet to keep track of player's lives in a multiplayer game, and keep track of necessary information in a single player game.  
The score sheet also contains controls to play a new game, play and pause the music, mute the fx, and bring up a modal with instructions on how to play the game.  
Modals are employed at the start of the game for picking the type of game to play.  
Background images and sound effects are also used in the game to enhance the childlike feeling of the app.  

User requirements are met in the following ways:  
* Players can choose the type of game to play at the start of the game (single or multiple)
* In single player games the player can choose type of game and difficulty level
* In multiplayer games players can input their names through prompt boxes
* When a player wins in a multi player game a modal appears congratulating the player by name, the modal also contains a new game button
* When a player wins or loses a single player game a modal appears with an appropriate message and a new game button
* sound controls are available to mute/unmute music and effects
* A player can view the rules on how to play at any time
* a player can start a new game at any time
* Information partaining to lives is on screen during multiplayer games
* Information partaining to time left or clicks left during single player games is available on screen

### Wireframing

A wireframe was made using the pencil application and can be found in the wireframes folder

## Technologies Used
* HTML
* CSS
* Javascript
* Bootstrap


## Features

### Existing Features
* new game button
* mute/unmute buttons for audio
* modal for information on how to play
* information relevant to the game is available
* start of game modals to easily choose the type of game to play
* ability to enter players names in multiplayer games

### Features left to implement
* modals for entering players names as opposed to prompt boxes
* new game button to start new game without reloading page - presently the new game button simply reloads page
* I would like to design the game pieces as octagons for the hiddens pieces and eggs for the visible pieces - to match the original board game
* I would also like to incorporate more audio into the game, maybe ambient farm noises playing in the background.

## Testing
The site was tested on 21" monitors, 15" and 13" laptop screens and on an iPhone SE and iPhone 8 screen to test responsiveness.  
It was also tested using chrome, firefox and safari.
In the case of this game, due to the high amount of visuals and elements on screen, and due to the fact it can be played by multiple players, it is primarily intended to be played on desktop/laptop size screens and bigger.  
It is responsive down to mobile size, however the user would be required to put their device on its side to view landscape. It is not practical to play in portrait on a mobile device.  
The background image is changed when viewing on smaller devices. The original kids play area background gives a too cluttered feeling on smaller devices.  

My original intention was to have background music autoplay on load, however due to new [browser policies such as on chrome](https://developers.google.com/web/updates/2017/09/autoplay-policy-changes), this proved difficult.  
My solution was to give the player the choice to have music or not, they can turn the music on once the game starts if they choose.   

Manual testing was done to ensure:
* The game plays as intended
* Appropriate win/loose notifications show up
* appropriate information is displayed on the game information sheet
* modals work correctly
* the controls provided to the player (new game buttons, audio control buttons, how to play button) work correctly
* Many tests to ensure the game is fun to play!

## Deployment
The site is hosted on github pages.  
It is deployed from the master branch. 

### Run locally
To run this site locally, in your terminal enter: git clone https://github.com/mparkcode/chicken_cha_cha

## Credits

### Media
* Background images used were obtained from Pexels and google images
* images were obtained from google images and png tree
* sound effects were obtained from orangefreesounds.com and soundbible.com
* background music came from bensound.com
* Fonts used were obtained from Google Fonts

### Acknowledgements
Code for shuffling an array came from [stackoverflow](https://stackoverflow.com/questions/6274339/how-can-i-shuffle-an-array)  
understanding of how to implement modals came from [this tutorial by Traversy Media](https://www.youtube.com/watch?v=6ophW7Ask_0)  