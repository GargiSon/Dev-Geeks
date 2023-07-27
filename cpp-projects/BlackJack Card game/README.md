 # Blackjack Card Game
This is a C++ implementation of the Blackjack card game. The game is played between the player and the dealer. The objective is to have a hand value as close to 21 as possible without exceeding it.
If the player's hand value is higher than the dealer's but does not exceed 21, the player wins the round.

## How to Play
1. Compile and run the code in a C++ environment.
2. The game uses a standard deck of 52 cards. Each player is dealt two cards face up, and the dealer also receives two cards (one face up and one face down).
3. The player can choose to "hit" (draw another card) or "stand" (keep their current hand). To hit, type 'h'. To stand, type 's'.
4. The player can continue hitting until they decide to stand or their hand value exceeds 21 (busting), in which case they lose the round immediately.
5. After the player's turn, the dealer reveals their face-down card and plays according to specific rules (usually hits until their hand value is 17 or higher).
6. The dealer continues hitting until their hand value is 17 or higher.
7. The player with a hand value closer to 21 without exceeding it wins the round. If the dealer busts (exceeds 21), all remaining players win.
8. The game then asks if the player wants to play again.

## Card Values
- Numbered cards (2 to 10) have their face value.
- Face cards (Jack, Queen, King) have a value of 10.
- The Ace can be worth either 1 or 11, depending on which value benefits the hand more.

## How to Run
1. Copy the code into a single `.cpp` file or keep the code files in the same directory.
2. Compile the code using your C++ compiler.
3. Run the executable generated by the compiler.
