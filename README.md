Download Link: https://assignmentchef.com/product/solved-computer-architecture-homework-3
<br>
a) Assemble the following code snippet into MIPS binary, represented as hexadecimal numbers, one line for each instruction. You must show the HOW part, i,e, how did you come up with the opcode and other parts of the instruction for each instruction to get full credit.

addi $s0, $zero, 77 addi $s1, $zero, 31234 1w $tO, 12($s1)

domore: addi $tO, $tO, 100 sw $tO, 8($s1)

addi $s0, $s0, 1

slti $t7, $s0, 150

addi $s1, $s1, 1

bne $t7, $zero, domore sub $s0, $s0, 100

b) What are the MIPS assembly language statements that are represented in memory as the following hexadecimal numbers, one statement per line; You must show how did you come up with the answers to get full credit.

0x20117a02  0x8e28000c  0x21180064  Oxae8f0008  0x22100003  Ox2a0f0042

Hint: You can use MARS to verify your work.

2. Write a MIPS assembly language program that does the followings:

a) Prompt the user for an integer in the range of 0 to 100. If the user inputs 0 the program stops.

b) Otherwise, the program stores the numbers from 0 up to the input value into an array of words in memory. i.e. initializes the array with values from 0 up to N where N is the value that user has given.

c) The program then adds the value of all even numbers of the array together (up to N) by loading them from the main memory then add them up, then prints out the sum with the message “The sum of even integers from 0 to N is:”. For example, if the user gave 6 as the input the program prints out “The sum of even integers from 0 to 6 is 12”.