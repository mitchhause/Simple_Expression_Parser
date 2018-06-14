Simple_Expression_Parser

This project is a simple math expression parser and verifier built using HTML, CSS, and JavaScript for Compiler Construction. The project 
takes input from a text box and parses it using JavaScript functions. 

Returns an ACCEPT or REJECT message based on rules given below:

exp → term addop exp | term
addop → + | -
term → factor mulop term | factor
mulop → * | /
factor → ( exp ) | number
number → -integer | integer
integer → [0-9]integer | [0-9]

