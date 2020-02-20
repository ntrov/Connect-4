# connect 4
Connect 4 game usign SFML C++.


To install the SFML Library run the following command in the terminal.

`sudo apt install libsfml-dev`

Now to play the game run the following commands in the terminal after opening the terminal in the project folder.

```
g++ -c connectFour.cpp main.cpp connectFour.h
g++ *.o -o ConnectFour -lsfml-graphics -lsfml-window -lsfml-system
./ConnectFour
```
