# Textual-Draw-

An assembly code program which does the following:
```
Draw on textual screen by reading the commands from standard input. Type a command (or
more commands) to standard input and press enter to execute them. Implement the following
commands.
● h : displays help on stdout
● w, a, s, d : up, left, down, right
● f : changes drawing symbol to next typed character
● c : clears the screen and returns to center
● p : fills the screen with drawing symbol
● q : halt
```
## How to run 
>Download SicTools from terminal in the working directory by entering the following commands:
```
git clone https://github.com/jurem/SicTools.git
cd SicTools
make jar
```
>Run the assembly code using the below command:
```
java -cp out/make/sictools.jar sic.Asm TextDraw.asm
```
## Examples to run
```
● 'aaaa wwww dddd ssss' -> draws a 4x4 square
● 'f.' -> changes drawing symbol to '.'
● 'f-dddf df-dddf df-ddd' -> draws a dashed line '--- --- ---'
```
