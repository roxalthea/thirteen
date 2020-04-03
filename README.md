# thirteen
A personal project attempting to create a card game called: 'Thirteen', written in Java.

## Game Details
- This card game uses the standard 52 playing cards, except the Joker cards.
- It is a hierarchy style card game in that, Hearts > Diamonds > Clubs > Spades;
- 2 > A > K > Q > J > 10 ... 5 > 4 > 3
- The game supports 2 to 4 players.
- At the start of the game, each player rolls a dice to determine the starting player and the cycle. Then each player is shuffled and drawn 13 cards from the deck.
- The winning condition is the 1st player to empty their hand; granting them significantly more points than the other placements.
- The game includes a 'Passing' system by which if a player is unable to beat a certain combo, they will be required to pass. If all players 'Pass' then the last player to play the combo (the one being passed) is granted a free turn.

**Free Turn**
- in a 'Free Turn' the player granted this can play any combo they choose, regardless of the previous combo.

## Viable Combos
This card game implements a combo system, in conjunction with the hierarchy of cards (Note: list is not in order of strongest to weakest).

Note: '2' cannot be in a combo except of itself.

**Four-of-a-Kind:**
- e.g. A, A, A, A
- Note: has the ability to beat single '2' card play.

**Three-of-a-Kind:**
- e.g. 5, 5, 5

**Pair:**
- e.g. 2, 2

**Four-pair Flush:**
- e.g. J, J, Q, Q, K, K, A, A
- Note: has the ability to beat single '2' card play.

**Three-pair Flush:**
- e.g. 3, 3, 4, 4, 5, 5

**Flush:**
- e.g. 3, 4, 5, 6 ,7
- e.g. J, Q, K
- Note: can be any sequential combination of cards, as long as it's not less than 2 cards.

**Dragon/Exodia:**
- Have all cards in hand from 3 to 2
- Instally win the whole game, 
- Note: can be any combination of suits.

**Singles:**
- e.g. 1
- Note: just one card play, nothing much.

