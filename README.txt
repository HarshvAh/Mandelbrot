Author Name: Harshvardhan Ahirwar
Date: 19th Nov. 2021
Time: 11:42 pm :P
___________________________________________________________________

Hi !

This is the readme file for my CS293 project.
This project is made on Ubuntu Distro, Linux.
I have utilised SFML library for drawing the plot, and made use of escape time algorithm along with continuous colouring algorithm for making the plot.

I have included a bash file - "make.sh", please run this file on terminal to get the SFML plot.

Here's what the bash file will do,
    It will install the SFML library if not installed, uses sudo apt-get(might ask for authentication)
    It will compile main.cpp and link the SFML library along with it (calling make for the makefile present in this directory)
    It will run the executable present in bin/

Keys :
    W,A,S,D - for navigating throughout the image
    R - Resets the plot back to initial condition
    MouseWheelScrollUp - Zoom in at the cursor position
    MouseWheelScrollDown - Zoom out at the cursor position
    MouseButtonClick Left - Increase resolution
    MouseButtonClick Right - Decrease resolution

Here is the link to my demo video :-
    https://drive.google.com/file/d/1aRqgw-UGx1nRb5dAUJS2r3HumD8OqpA2/view?usp=sharing