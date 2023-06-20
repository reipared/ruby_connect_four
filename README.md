# Connect Four Ruby Game

 The Connect Four Ruby game is a text-based implementation of the popular Connect Four board game. The game allows two players to take turns placing colored discs on a vertical grid with the objective of getting four of their own colored discs in a row, either horizontally, vertically, or diagonally.

The game is built using the provided `Game` class, which handles the game logic. The `main` method serves as the entry point for the game. It starts a loop where a new `Game` instance is created and the `play` method is called to start a new round of Connect Four. After each round, the `another_game?` method prompts the players if they want to play another round. If they choose to continue, the loop repeats, creating a new game instance.

The `another_game?`  method displays a prompt to the players, allowing them to choose between playing another round or exiting the game. It takes the user input and returns `true` if they choose to play another round or `false` if they choose to exit.

This Connect Four Ruby game provides an enjoyable experience for two players, allowing them to compete against each other in a classic strategy game. Players can enjoy the challenge of outsmarting their opponent and strategically placing their discs to achieve victory.
