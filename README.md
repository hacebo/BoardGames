# BoardGames
Prototype application using angular.js, jasmine.js , bootstrap ,web api, ninject and mvc. 

Application structure

BoardGames
  -Is the main web solution where the main view, and the web api controllers are stored(It was stored here for simplicity), but it could be done on a saparate project.
  -Includes the angular logic under Scripts - app - appGame.js
  -Data is stored on a XML file(BoardGamesData.xml) under App_Data 
  
BoardGames.DataAccess
  -Is the data layer, here is stored the repository to access the XML file
  
BoardGames.Models
  -Should be the models of the application in this case just the Game model
  
BoardGames.Tests
  -Includes unit testing methods to test the web api GamesController.
  -Includes an index.html file in which is the logic to run the test cases for the gamesController.
  -File with the front-end tests is under tests folder



