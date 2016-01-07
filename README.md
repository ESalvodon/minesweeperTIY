# Minesweeper Clone

Minesweeper is a logic game where mines are hidden in a grid of squares. The object is to reveal all the safe squares without stepping on a mine. The game became famous when Microsoft included it with Windows 3.1 but its origins go even further back.

This weekend's lab is to build a front end interface to Minesweeper against a backend API. The API will handle all of the game logic for you.

The API documentation is available at https://minesweeper-api.herokuapp.com

The API endpoints will be at that domain as well, i.e., `https://minesweeper-api.herokuapp.com/game`. I will have that live for you later tonight!

### Deliverables

- A publicly visible website on `gh-pages`, etc.
- A repository on GitHub with your app's source code

### Explorer Mode

- Have at least two screens:
  - The player chooses the difficulty to start a new game
  - A game board, consisting of a grid of squares.
- Players should be able to click to reveal a given cell (this will map the `check` action of the Game API).
- Players should be able to right click to flag a given cell (this will map the `flag` action of the Game API). hint: [https://developer.mozilla.org/en-US/docs/Web/Events/contextmenu](contextmenu) + `preventDefault()`
- The board should re-render it self based on the array of data the API actions respond with.
  - The numbers of mines remaining should be included in this update.
- Include a timer that counts up from 0 while the player is playing.
- Players should not be able to "check" a flagged cell.
- Your game should look great!

### Adventure Mode

"Offline" play. Implement the game's logic yourself rather than use the external API.

### Additional Resources

- [https://github.com/jashkenas/backbone/wiki/Backbone,-The-Primer](Backbone, The Primer)
- [http://addyosmani.github.io/backbone-fundamentals/](Backbone Fundamentals eBook)
- [https://en.wikipedia.org/wiki/Minesweeper_(video_game)](Minesweeper on Wikipedia)
