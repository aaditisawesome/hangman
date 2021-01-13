# Installation
Install `AaditsHangman` with `pip install AaditsHangman`. 
This will install the module, and will also install other dependencies that this module needs.

# Opening up the game
Play the game by opening up some editor (or ig typing `python` in terminal also works)  
Then type this following code:
```py
from AaditsHangman import Hangman

hangman = Hangman()
hangman.new_game()
```
A tkinter window should open on your screen.

Have Fun playing!
# Tips on the game and how to play
1. The computer will choose the word, and you have to guess it

2. There is a timer on the top right corner of the window. When you get the word OR you run out of tries, that timer will end. See how fast you can get it!

3. Instead of pressing submit on your window, you can just press `Enter` on your keyboard!

4. The hangman is hung when you use up nine tries.

5. The `Submit` button automatically becomes `New Game` when the game is over. You can press `Enter` for that also.
