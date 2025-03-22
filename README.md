<p align=center>
 <img src="../master/gameplay.gif" width=700 height = 450/>
</p>

# Typing-Tutor  🎮 







A Typing-Tutor is a visually appealing and interactive typing game developed using C++. The project is designed to help users improve their typing speed and accuracy in an engaging and fun way. The game presents a series of random words or sentences that the player needs to type correctly within a given time limit. It provides real-time feedback on typing performance, showing errors and giving the player a score at the end of each round.

# Key Features

Real-time typing feedback (accuracy and speed).

Visually appealing user interface with dynamic animations.

Adjustable difficulty levels for players of all skill levels

Timed challenges to improve typing speed

A simple and intuitive interface for a smooth user experience



## How to Run

There's a file named "Typing Tutor.exe". Just run it and the game will start.

If "Typing Tutor.exe" isn't working then the game can be compiled using any of the two ways:

1) The project is compiled using Code Blocks. So, there is a file named "Typing Tutor.cbp". Open it in Code Blocks and the whole project will load up with all files. Then just click "Build and Run" and the game will start. {Add the libgdi32 library in Code Blocks using project->build options->linker settings-> add button (find libgdi32 for your compiler)} 

2) To have the best experience it is HIGHLY RECOMMENDED to compile the main.cpp file of the game using G++
using the command:
 ```g++ -o main.exe mygraphics.cpp myconsole.cpp main.cpp - lgdi32```

## Screenshot
![Game Play Screenshot](../master/interface.png)

Instructions to Play the Game                      
-----------------------------
The rules of my game "Typing Tutor" are :

--  You are provided with a Typing Box . A Box is shown moving vertically on the screen with a
    word in it.There are five still boxes containing words.
 
--  If you type the word shown in the moving box , correctly, then the moving box will
    start to move leftwards otherwise if you have entered an incorrect word in the Typing
    Box then you will lose one life .
 
--  When the moving Box collides with a still box (after the moving box has completely
    moved leftwards) , then if the words in both boxes are same , then your score
    will increase by one , otherwise you will lose one life. 

--  When the word you entered in the Typing Box do no match with that of the word in the Moving Box
    then your no. of lives will reduce by one .    

--  In order to win the game , you need to attain a score of 10 i.e by matching
    Ten times correctly .

--  You have a total of 5 lives in the beginning and if you lose all your lives i.e when you have
    0 lives , then you will lose the game and the game will end.

--  Once you have typed a character in the typing box , it cannot be removed by using
    BACKSPACE or DELETE key . So be careful while playing ;)

--  There are a total of four levels . Choose which ever level you want to play. Each one is more difficult than previous one.

Enjoy !!!!!!!


<hr>


## Technologies Used 

C++ for core game logic

Basic console-based UI for simplicity and portability

This project is a great way to practice and enhance your typing skills while having fun!






