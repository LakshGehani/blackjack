# Blackjack Game in Python

Welcome to this simple text-based Blackjack game written in Python. In this game, you will play against the computer dealer, trying to get as close to 21 points as possible without going over.

## How to Play

1. The game begins with both you and the dealer receiving two cards.
2. You can choose to "Hit" (get another card) or "Stand" (keep your current hand).
3. Your goal is to get a hand value as close to 21 as possible without going over.
4. Face cards (Jack, Queen, King) are worth 10 points, and Aces can be worth either 1 or 11 points, depending on which value benefits you more.
5. If your hand exceeds 21 points, you lose the game (bust).
6. After you make your move, the dealer will reveal their facedown card and draw cards until their hand value is 17 or higher.
7. If the dealer busts or has a lower hand value than you, you win. If the dealer has a higher hand value, you lose.
8. A tie occurs if both you and the dealer have the same hand value.

## Instructions for Running the Game

To play the game, follow these steps:

1. Ensure you have Python installed on your computer.
2. Open a terminal/command prompt.
3. Navigate to the directory where the Python script is saved.
4. Run the script using the following command:

   ```
   python blackjack.py
   ```

5. Enjoy the game!

## Game Interface

The game provides a simple text-based interface where you'll see the cards and scores for both you and the dealer. Follow the on-screen instructions to make your choices (Hit or Stand).

## Additional Information

- This game uses a standard 52-card deck.
- Aces are automatically counted as 11 unless this would cause you to bust, in which case they are counted as 1.
- The game will continue until you choose to quit.

Have fun playing Blackjack!
