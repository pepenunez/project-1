# Project 1
Blackjack with Python

Source: https://bicyclecards.com/how-to-play/blackjack/

# THE GAME
## OBJECT OF THE GAME
Each participant attempts to beat the dealer by getting a count as close to 21 as possible, without going over 21.

## CARD VALUES/SCORING
Face cards are 10 and any other card is its pip value. In this game "Ace" = 11.

## BASIC STRATEGY
Winning tactics in Blackjack require that the player play each hand in the optimum way, and such strategy always takes into account what the dealer's upcard is. When the dealer's upcard is a good one, a 7, 8, 9, 10-card, or ace for example, the player should not stop drawing until a total of 17 or more is reached. When the dealer's upcard is a poor one, 4, 5, or 6, the player should stop drawing as soon as he gets a total of 12 or higher. The strategy here is never to take a card if there is any chance of going bust. The desire with this poor holding is to let the dealer hit and hopefully go over 21. Finally, when the dealer's up card is a fair one, 2 or 3, the player should stop with a total of 13 or higher.

# THE CODE
## PLAYERS
There is a minimun of 1 player and a maximum of 5.

## THE PACK
The standard 52-card pack is used, but in most casinos several decks of cards are shuffled together. The six-deck game (312 cards) is the most popular. There is a variable to select how many packs we would like to play with. 

## BETTING
Before the deal begins, each player places a bet, in chips, in the designated placeholder. Minimum and maximum limits are established on the betting, and the general limits are from $2 to $500.

## THE DEAL
When all the players have placed their bets, the dealer gives one card face up to each player in rotation clockwise, and then one card face up to themselves. Another round of cards is then dealt face up to each player but the dealers card will be faced down.

## THE PLAY
The player to the left (Player1) goes first and must decide whether to "Stand" (not ask for another card) or "Hit" (ask for another card in an attempt to get closer to a count of 21, or even hit 21 exactly). Thus, a player may stand on the two cards originally dealt to them, or they may ask the dealer for additional cards, one at a time, until deciding to stand on the total (if it is 21 or under), or goes "bust" (if it is over 21). In the latter case, the player loses and the dealer collects the bet wagered. The dealer then turns to the next player to their left and serves them in the same manner.

## THE DEALER'S PLAY
When the dealer has served every player. If the total is 17 or more, it must stand. If the total is 16 or under, they must take a card. The dealer must continue to take cards until the total is 17 or more, at which point the dealer must stand. If the dealer has an ace, and counting it as 11 would bring the total to 17 or more (but not over 21), the dealer must count the ace as 11 and stand. The dealer's decisions, then, are automatic on all plays, whereas the player always has the option of taking one or more cards.

## CHECK RESULTS AND COLLECT MONEY OR PAY REWARDS
All of those players having a score of 21 (Blackjack) and if the dealer doesn't have a 21 score will multiply their bet per 2.5. All of those players having a score higher than the dealer but lower or equal to 21 will collect 2 times their bet. All of those players that have a score higher than 21 or that have a lower score than the dealer will loose all their money. Only in the case that the dealer scores more than 21 the players with a lower score than the dealer and than 21 (included) would win and collect 2 times their bet. 
