# Blackjack Game

This is a simple command-line Blackjack game implemented in Python. The game allows you to play multiple rounds of Blackjack against a dealer.

## How to Play

1. Run the `main.py` script.
2. Enter the number of games you want to play.
3. Follow the prompts to either "Hit" or "Stand" during your turn.
4. The game will automatically handle the dealer's actions and determine the winner.

## Classes

### `Card`

Represents a single playing card.

- `__init__(self, suit, rank)`: Initializes a card with a suit and rank.
- `__str__(self)`: Returns a string representation of the card.

### `Deck`

Represents a deck of playing cards.

- `__init__(self)`: Initializes a deck with 52 cards.
- `shuffle(self)`: Shuffles the deck.
- `deal(self, number)`: Deals a specified number of cards from the deck.

### `Hand`

Represents a player's or dealer's hand.

- `__init__(self, dealer=False)`: Initializes a hand. If `dealer` is `True`, the hand belongs to the dealer.
- `add_card(self, card_list)`: Adds cards to the hand.
- `calculate_value(self)`: Calculates the total value of the hand.
- `get_value(self)`: Returns the total value of the hand.
- `is_blackjack(self)`: Checks if the hand is a Blackjack.
- `display(self, show_all_dealer_cards=False)`: Displays the hand. If `show_all_dealer_cards` is `False`, the dealer's first card is hidden.

### `Game`

Manages the game logic.

- `play(self)`: Starts the game and handles the game loop.
- `check_winner(self, player_hand, dealer_hand, game_over=False)`: Checks and announces the winner.

## Running the Game

To run the game, execute the following command in your terminal:

```sh
python main.py

Sure! Here's an updated `README.md` file that includes a section about using the project to learn Python:

```markdown
# Blackjack Game

This is a simple command-line Blackjack game implemented in Python. The game allows you to play multiple rounds of Blackjack against a dealer.

## How to Play

1. Run the `main.py` script.
2. Enter the number of games you want to play.
3. Follow the prompts to either "Hit" or "Stand" during your turn.
4. The game will automatically handle the dealer's actions and determine the winner.

## Classes

### `Card`

Represents a single playing card.

- `__init__(self, suit, rank)`: Initializes a card with a suit and rank.
- `__str__(self)`: Returns a string representation of the card.

### `Deck`

Represents a deck of playing cards.

- `__init__(self)`: Initializes a deck with 52 cards.
- `shuffle(self)`: Shuffles the deck.
- `deal(self, number)`: Deals a specified number of cards from the deck.

### `Hand`

Represents a player's or dealer's hand.

- `__init__(self, dealer=False)`: Initializes a hand. If `dealer` is `True`, the hand belongs to the dealer.
- `add_card(self, card_list)`: Adds cards to the hand.
- `calculate_value(self)`: Calculates the total value of the hand.
- `get_value(self)`: Returns the total value of the hand.
- `is_blackjack(self)`: Checks if the hand is a Blackjack.
- `display(self, show_all_dealer_cards=False)`: Displays the hand. If `show_all_dealer_cards` is `False`, the dealer's first card is hidden.

### `Game`

Manages the game logic.

- `play(self)`: Starts the game and handles the game loop.
- `check_winner(self, player_hand, dealer_hand, game_over=False)`: Checks and announces the winner.

## Running the Game

To run the game, execute the following command in your terminal:

```sh
python main.py
```

## Requirements

- Python 3.x

## Learning Python

This project is a great way to learn Python programming. By exploring and modifying the code, you can learn about:

- Object-Oriented Programming (OOP) concepts such as classes, objects, inheritance, and methods.
- Basic Python syntax and data structures like lists and dictionaries.
- Control flow statements like loops and conditionals.
- Handling user input and displaying output.

Feel free to experiment with the code, add new features, or improve the existing functionality. This hands-on approach will help you understand Python programming better.

## License

This project is licensed under the MIT License.
```

This `README.md` file now includes a section on how the project can be used to learn Python, highlighting key concepts and encouraging experimentation.