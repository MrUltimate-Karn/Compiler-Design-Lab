This repo contains lex program file.


#ASSIGNMENT 1:


Q1. Write a LEX program to count the number of vowels and consonants in a given string.


Q2. Write a LEX program to count the number of lines, spaces and tabs.


Q3. Write a LEX program to convert an octal number to decimal number.


#ASSIGNMENT 2:


Q1. Given an input sentence, write a Lex Program to count the number of words whose length is greater than 2.


Q2.Given a paragraph in English, write a lex program which count the number of words, number of special characters, number of lines, spaces and tabs in the paragraph.


Q3. Write a Lex program to check weather given number is odd or even and if it is odd also check whether it is prime or not.


Q4. Given  an  input  sentence,  write  a  Lex  Program  to find  the  maximum number of characters present in the longest word. 


#ASSIGNMENT 3:


Q1.A story writer wishesto recheck his story. In ordertorecheck he needs to find all those words which are followed by ‘?’and ‘!’. Write a lex program that can solve his problem.



Q2.Write a lex program to design a DFA over input {0,1}, which accept odd no. of 0s or even no. of 1s but not both together.


Q3.Write  a  lex  program to  design  a  DFA  over input {a,b}, which  accepts  all  thewords containing odd number of ‘b’.


Q4.Given a text file, write a lex program to search aninput word in the file. If the word is present then count the total number of its occurrences, and replace every odd occurrenceof the word with your roll number.

#ASSIGNMENT 4:


Q1.Write a Lex program to accept your Roll Number.


Q2.A story has been written and saved in file, later you have given a task to search given word in the story. Write a Lex program to accomplish this task.


Q3.Write a Lex program that accept a string start with 'b’ and end with 'a' over input alphabet a, b.


Q4.Write a Lex program accept 'baba' as a substring over input alphabet a, b.


#ASSIGNMENT 5:


Q1.Write a YACC program to implement following arithmetic operations Addition, Subtraction, Multiplication, and Division. Also print whether a arithmetic expression is valid or not.


Q2. Write a YACC program to recognize string over alphabet {a,b} having equal no. of ‘a, and equal no of ‘b’ and length of string is greater than equal to zero.


Q3.Write and YACC program which accept string that starts and end with 0 or 1.


Q4.Write an YACC program to convert base 2 digit to base 10 digit.


#ASSIGNMENT 6:


Q1.A student needs to check whether the given number is palindrome or not? He  had  the  problem  of  reversing  the  number.  Write  a YACC program  that can solve his problem.



Q2.A grammar is given: a^nb^nc^md^m, where n, m>=0. Check the validity of the following strings “abcd” and “aabbcd” using the given grammar with the help of a YACC program.


Q3.A C program file is given to a student and he was asked to recognize valid identifiers,  operators  and  keywords  in  the  given  program.  Write  a  YACC program that can solve his task.



Q4.Let's  say  we  have  a  thermostat  that  we  want  to  control  using  a  simple language. 


A session with the thermostat may look like this:


heat on


  Heater on!
  
  
heat off


   Heater off!
   
   
target temperature 22


    New temperature set!
    
    
Write a YACC program that can control the thermostat.



#ASSIGNMENT 7:



Q1.a)write C program to eliminate left recursion of following grammar.


E -> E + T / T


T -> T * F/ F


F -> id


Q1.b)write C program to find First and Follow sets of following grammar .


E -> E + T / T


T -> T * F/ F


F -> id


#ASSIGNMENT 8:


Q1.Every compiler has intermediate code representation phase. Given the set of expression:a+b+c*d/e+f.


Write a C program that can find the quadruples ofthe given expressionfor intermediate code representation.


Q2.Write  a  program in  C to  find  three  address  codeusing  triples for  the following set of input expression: a = b * –c + b * –c.


#ASSIGNMENT 9:


Q.1)Write a program to generate the three-address code for the following code of ‘if-else’.


if-else code:


A = 1;


B = 2;


if (A<B)


  return 1;
  
  
else


  return 0;
  


Q.2)Write a program to generate the three-address code for the following code of ‘for-loop’.


for-loop code:


a=3;


b=4;


n=6;


for(i=0;i<n;i++){


a=b+1;


a=a*a;


}


c=a;



Q.3)Write a program to generate the three-address code for the following code of ‘while-loop’.


while-loop code:


c = 0;


a = 1;


b = 2;


while(a < b){


 c = 1;
 
 
}


c = 0;


#ASSIGNMENT 10:


Q.1)In  the  syntax  analyzer  phase  of  the  compiler,  the  parser generates  the abstract syntax tree (condensed form of the parsetree). This abstract syntax tree needs to be converted into machine understandable format using the intermediate  code  generator. 


Write  a  program  in  C  to convert  the  given abstract syntaxes into their equivalent machine codes. The following specific machine instruction sets may be considered:



Following argument types may be used:


R →specifies a register in the form R0, R1, R2,etc.


L →specifies a numerical label.


V →specifies a `variable location'pointed to by a register.


A →specifies a constant value.


The instruction set may bedefined as follows:


LOAD A,R→loads the integer value specified by A into register R


STORE R,V→stores the value in register R to variable V.


OUT R→outputs the value in register R.


ADD A,R→adds the value specified by A to register R.


SUB A,R→subtracts the value specified by A from register R.


MUL A,R→multiplies the value specified by A by register R.


DIV A,R→divides register R by the value specified by A.


STOP→stops execution of the machine.


Example:


Input:= t3 99


Output:  STORE t3, 99


Input may be considered as:= 


= t1 2
[]= a 0 1
[]= a 1 2
[]= a 2 3
* t1 6 t2
+ a[2] t2 t3
- a[2] t1 t2
/ t3 t2 t2
print t2
