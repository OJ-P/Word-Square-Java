# Word-Square-Java
# word square challenge for a coding interview in 2019


Coding Challenge
This challenge is to produce a word square. In a word square you are given a grid with letters
arranged that spell valid English language words when you read from left to right or from top to
bottom, with the requirement that the words you spell in each column and row of the same
number are the same word. For example, the first row and the first column spell the same
word, the second row and second column do, too, and so on. The challenge is that in arranging
those letters that you spell valid words that meet those requirements.
One variant is where you're given an n*n grid and asked to place a set of letters inside to meet
these rules, and that’s our challenge: given the grid dimensions and a list of letters, can you
produce a valid word square.

Input
You'll be given an integer telling you how many rows and columns (it's a square) to use and
then n 2 letters to populate the grid with. Example :

4 eeeeddoonnnsssrv

Output
Your program should emit a valid word square with the letters placed to form valid English
language words. Example :

rose
oven
send
Ends

Challenge
To write a program to solve the following word squares:
4 aaccdeeeemmnnnoo
5 aaaeeeefhhmoonssrrrrttttw
5 aabbeeeeeeeehmosrrrruttvv
7 aaaaaaaaabbeeeeeeedddddggmmlloooonnssssrrrruvvyyy

Challenge Solutions (Example)
moan
once
acme
need

feast
earth
armor
stone

threw
heart
ember
above

revue
trees
bravado
renamed

analogy
valuers
amoebas
degrade
odyssey

To ensure valid words, we suggest you may wish to use the following English-language
dictionary http://norvig.com/ngrams/enable1.txt

What we are looking for:
Using the Java API and other Java libraries or frameworks, we are looking for a program to solve
these challenges based on the inputs and outputs defined. Your program should run from the
command line and come with some form of documented instructions. As well as a working
algorithm, we are also looking for an elegance of solution, an Object Oriented design approach,
the development approach (TDD?) and use of the APIs and libraries. We also welcome proof
that it works and will ask more about the development approach at an interview. One big hint
is that we find the use of two dimensional arrays as unreadable, as well as unmaintainable. If
you think another technology is preferable, we don’t mind if you can explain why you made
your choice.
