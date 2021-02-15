# Project Name: SEIS-CrazyEight 

# Vision:

This card game is to learn to generate a number of different ideas within a short period of time. This 
basically keeps the mind engaged in panning strategies to discard all your cards. The goal is to push beyond your first idea, 
frequently the least innovative, and to generate a wide variety of solutions to the challenge.  



# Limitations

This application will be currently written in Java so after the product is finished, the game can only be played on devices
that support java.  This application originally will not support cloud-based
data storage.  This application will, at its first release, only be a Human and a computer player.


# CrazyEight Rules and Instructions: The basic game

1. The basic game of Crazy Eights uses a standard 52 card pack, or two such packs shuffled together if there are a lot of players. 
2. The dealer deals (singly) five cards to each player (seven each if there are only two players). 
3. The remainder of the pack is stacked face down on the table as a stock from which cards will be drawn. 
4. The top card of the stock is turned face up and placed beside the stock to start the discard pile.
5. Starting with the player to dealer's left, and continuing clockwise, each player in turn must either play a legal card face up on top of the discard pile, or draw a card from    the undealt stock. The following plays are legal.
6. If the top card of the discard pile is not an Eight, you may play any card which matches the rank or suit of the previous card (for example if the top card was the king of      hearts you could play any king or any heart).
7. An Eight may be played on any card, and the player of the Eight must nominate a suit.
8. If an Eight is on top of the pile, you must play either another Eight or any card of the suit nominated by the person who played the Eight.
9. If an Eight is turned up by the dealer as the first card of the play pile, it is treated as though the dealer had played it. The dealer looks at his or her hand and nominates    a suit, and the first player must play a card of that suit or another Eight.
10.A player who has only one card left in their hand must alert the other players by saying "last card". A player who fails to do this before the next player takes their turn      must draw two cards from the top of the stock as a penalty.
11.The first player who gets rid of all their cards wins, and the other players score penalty points according to the cards they have left in their hands - 50 for an eight, 10      for a picture, and spot cards at face value (one point for an ace, two for a two and so on).
12.If the stock pile is exhausted, the played cards, except for the last card, are shuffled and stacked face down to make a new stock and the game continues.



# Features of CrazyEight: (These are not ordered)
1.  Start Game
2.  Read Card for human 
3.  Computer automatically plays.
4.  Remove cards from the Hands.
5.  Check Legal Card
6.  Pick a suit.
7.  Create a Deck
8.  Shuffle a Deck.
9.  Deal Card
10. Discard Card
11. Calculate Total Points
12. Get Players
13. Nominate a suit.
13. End Game


# User Stories:
1. As a player, I would like a game to help me to take quick decisions and become efficient. 
2. As a player, I would like to choose how can I get rid of my cards by strategically planning the rules of the game.
3. As a player, I should be asked if I would like to start the game or not.
4. As a player, I would like the software to distribute each players seven cards face down.
5. As a player, I would like the remainder of the pack is stacked face down on the table as a stock from which cards will be drawn. (#3)
6. As a player, I would like the top card of the stock is turned face up and placed beside the stock to start the discard pile. (#4)
7. As a player, I would like to know the current suit being played all the time.( the suit frequently changes as the game progresses)
8. As a player, I would like to select one card and have the program displays them and then indicate if it matches the rank or suit of the previous card(#6)
9. As a player, if the cards in my hand don't match the suit on the board, the software allows me to pick the cards from the deck of cards untill I find the match.
10. As a player, If I play an Eight, the software allows me to nominate a suit and changes the suit display on the board to the chosen suit by the player who played an Eight.
11. As a player, I would like the software to keep track of how quickly I get rid of my cards in handso that I know I am thinking quickly and efficiently finishing the game, possibly winning the game everytime. 
12. As a player, I would like the software to tell me who wins the game at the end.
