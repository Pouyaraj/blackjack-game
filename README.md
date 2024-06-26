# blackjack-game

## Description

This is a simple console-based Blackjack game implemented in Python. The game allows a user to play against a computer dealer. The user can draw additional cards to try to get as close to 21 as possible without going over.

1. The deck is unlimited in size. 
2. There are no jokers. 
3. The Jack/Queen/King all count as 10.
4. The the Ace can count as 11 or 1.
5. Use the following list as the deck of cards:
6. cards = [11, 2, 3, 4, 5, 6, 7, 8, 9, 10, 10, 10, 10]
7. The cards in the list have equal probability of being drawn.
8. Cards are not removed from the deck as they are drawn.
9. The computer is the dealer.

## Functions

### deal_cards()

Description: Deals a random card from the deck.
Returns: An integer representing the card value.

### calculate_score(cards)

Description: Calculates the score of a given list of cards. Adjusts for the ace (11 or 1) if the total score exceeds 21.
Parameters:
cards (list): A list of integers representing the cards in hand.
Returns: An integer representing the total score.

### compare(user_score, computer_score)

Description: Compares the scores of the user and the computer to determine the outcome of the game.
Parameters:
user_score (int): The user's total score.
computer_score (int): The computer's total score.
Returns: A string message indicating the result (win, lose, or draw).

### play_game()

Description: The main function to play the game. Handles the game logic, user interactions, and displays the result.
Returns: None