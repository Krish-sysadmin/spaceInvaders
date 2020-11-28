The game was a challenge by me for me in C using the N-curses library, and it's played entirely within the shell with ASCII graphics.

Inspired by the [1978 arcade game](https://en.wikipedia.org/wiki/Space_Invaders) (long before my time) 

To use this repo:

```
cd Desktop (or other desired directory)
git clone https://github.com/Krish-sysadmin/spaceInvaders
cd spaceInvaders
gcc -o spacegame invaders.c -lncurses && ./spacegame (compiles and executes the executable)
```
To play use the keyboard arrows to navigate left and right and the spacebar to shoot!

Press M to open menu options. 

```
1. Change overall game speed
2. Change alien motion speed
3. Change tank shot speed
4. Change alien bomb speed
5. Change alien bomb dropping frequency
6. Return to the game
7. Exit the game

Enter your option:

```

Forgive sloppy coding!
