# COMP9001_FINAL_PROJECT
## A simple Pokemon Game

### 1. `Pokemon` Class
The class Pokemon is the base class.
### 2. Pokémon Species Classes
- **Charmander, Squirtle, Bulbasaur, Pikachu** are implemented as a subclass of the base `Pokemon` class.

![Pikachu](https://s1.52poke.com/wiki/thumb/0/0d/025Pikachu.png/600px-025Pikachu.png?20230614102824)

### 3. `PokemonGame` Class

The `PokemonGame` class manages the overall game flow and player interactions.

It Includsfunctions such as viewing status, training, resting, fighting, switching, capturing, etc.

### 4. Running the Game

- Click below to enter the game
  ```python
  if __name__ == "__main__":
      game = PokemonGame()
      game.start()
