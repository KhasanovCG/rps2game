# rps2game
RPS25 is an expanded version of the traditional Rock, Paper, Scissors game, adding more depth and strategy by introducing 25 unique symbols. Each symbol has its own set of defeats, creating an intricate web of relationships where certain symbols triumph over others.

How does it work?
Just like in the classic game, players select a symbol, and the winner is determined based on the relationships between symbols. However, with 25 symbols to choose from, the gameplay becomes more strategic and exciting.

The Game class manages the backbone of the RPS25 game, handling symbol initialization and determining winners.
In its constructor, it sets up a map to store symbols and their associated defeat relationships.
The initializeSymbols() method populates the map with symbols and their corresponding defeats.
determineWinner() method compares two symbols to find the winner or declare a tie.
