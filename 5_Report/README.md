You have probably played the Tic-Tac-Toe game to pass time during school hours. It’s fun when you play with paper and pencil. Here, we have developed a mini project in C Tic Tac Toe game – a simple console application without graphics.

It is the same noughts and crosses or the Xs and Os, the other names for Tic-Tac-Toe, you’ve played with paper and pencil. This mini game project is written in C language in a very simple manner; it is complete and totally error-free.

While making a Tic Tac Toe game using C language, it is important to make use of arrays. The Xs and Os are kept in different arrays, and they are passed between several functions in the code to keep track of how the game goes. With the code here you can play the game choosing either X or O against the computer.

This Tic Tac Toe C game is such that you will have to input a numerical character, from 1 to 9, to select a position for X or O into the space you want. For example: if you are playing with O and you input 2, the O will go to first row – second column. If you want to place O in third row – first column, you have to enter 7. And, it is similar for the other positions.

This has been done this way because it is just a console application without graphics designed in C language. The gotoxy function has been used to print text in any part of the screen.

In Tic Tac Toe game, there are 765 states of space complexities or over 25,000 possible games on those different positions.

# Function Used:
I have divided this project into many functions, and below is a list of those functions. I have only described the gotoxy function in detail. Just go through the source code once, and other functions used are simple and easy to understand.
void menu() – In this mini project, this function displays the menu or welcome screen of this project. Scroll down to view the photo of the menu. With this function, you can select whether you wish to play the game with X or with O.

void go(int n)
void start_game()
void check_draw()
void draw_board()
void player_first()

void put_X_O(char ch, int pos) – This function puts one of the numerical character you input into the respective position in Tic-Tac-Toe. For example: if you are playing with X and you input 2, the X will go to first row – second column. If you want to place X in third row – first column, you have to enter 7. And, it is similar for the other positions.

void gotoxy (int x, int y) – You need to understand this function as it is one of the most important one used in Tic Tac Toe in C. This function allows you to print text in any place of the screen. 
