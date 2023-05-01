Download Link: https://assignmentchef.com/product/solved-ch-230-a-assignment-6-c-preprocessor-bitwise-operators-linked-lists
<br>
<h1><strong>Problem 6.1 </strong>Swapping two variables                                                                          (</h1>

Write a macro and a program for swapping the contents of two variables. The macro should have three parameters: the two variables and the corresponding data type.

Your program should read two integers and two doubles from the standard input. Then you should print on the standard output the contents of the four variables after swapping (doubles with a floating point precision of 6).

<em>You can assume that the input will be valid. Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<table width="431">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 6.1: input</strong>123.455.677</td>

   <td width="141"><strong>Testcase 6.1: output</strong>After swapping:215.677000</td>

  </tr>

 </tbody>

</table>

3.450000

<h1><strong>Problem 6.2 </strong>Determine the least significant bit</h1>

Write a macro and a program for determining the least significant bit (the first bit from the right in the binary representation) of an unsigned char read from the standard input.

Your program should read an unsigned char from the standard input and print the decimal representation of the unsigned char as well as its least significant bit (which is either 1 or 0) on the standard output using only bitwise operators and without explicitly converting to binary representation.

<em>You can assume that the input will be valid. To pass the testcases your output has to be identical with the provided ones.</em>

<table width="553">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 6.2: input</strong>F</td>

   <td width="263"><strong>Testcase 6.2: output</strong>The decimal representation is: 70</td>

  </tr>

 </tbody>

</table>

The least significant bit is: 0

<h1><strong>Problem 6.3 </strong>Determine the mid-range of three values</h1>

Write multiple macros and a program for determining the mid-range of three values. The midrange of three variables a, b, and c is calculated as

<em>.</em>

For example if 3, 10, 1 is the input, the mid-range of these values is

<em>.</em>

Your program should read three integers from the standard input. For calculating the mid-range of these values only macros should be used. The mid-range should be printed on the standard output with a floating point precision of 6.

<em>You can assume that the input will be valid. Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<table width="497">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 6.3: input</strong>3</td>

   <td width="207"><strong>Testcase 6.3: output</strong>The mid-range is: 5.500000</td>

  </tr>

 </tbody>

</table>

10

1

<h1><strong>Problem 6.4 </strong>Conditional compilation for showing intermediate results</h1>

Write a program which computes the scalar product of two <em>n</em>-dimensional integer vectors and uses conditional compilation for showing/not showing intermediate results (products of the corresponding components). The scalar product of two <em>n</em>-dimensional vectors <em>x </em>= (<em>x</em><sub>1</sub><em>,x</em><sub>2</sub><em>,…,x<sub>n</sub></em>) and <em>y </em>= (<em>y</em><sub>1</sub><em>,y</em><sub>2</sub><em>,…,y<sub>n</sub></em>) is calculated as

<em>.</em>

For example the scalar product of the vector <em>x </em>= (1<em>,</em>2<em>,</em>3) with the vector <em>y </em>= (3<em>,</em>5<em>,</em>1) is

<em>&lt; x,y &gt;</em>= 1 · 3 + 2 · 5 + 3 · 1 = 3 + 10 + 3 = 16<em>.</em>

The intermediate results which are to be shown or not are 3, 10 and 3.

Your program should read from the standard input the dimension of the vector (in the previous example 3) along with the components of two integer vectors. The output consists of the intermediate results and the value of the scalar product of the two vector if the directive INTERMEDIATE is defined. If INTERMEDIATE is not defined then only the scalar product of the two vectors should be printed on the standard output.

<em>You can assume that the input will be valid. To pass the testcases your output has to be identical with the provided ones.</em>

<table width="577">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 6.4: input</strong>31233</td>

   <td width="287"><strong>Testcase 6.4: output</strong>The intermediate product values are:3103The scalar product is: 16</td>

  </tr>

 </tbody>

</table>

5

1

<h1><strong>Problem 6.5 </strong>Binary representation backwards</h1>

Write a program using bit masks and bitwise operators for printing the binary representation of an unsigned char backwards. For example the character ’2’ is encoded as 50 in decimal representation which is in binary representation 110010. Therefore, the backwards binary representation is 010011.

Your program should read an unsigned char from the standard input and print on the standard output the backwards binary representation of the read character without explicitly converting the decimal value to binary or using an array to store the bits.

<em>You can assume that the input will be valid. Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<table width="657">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 6.5: input</strong>2</td>

   <td width="367"><strong>Testcase 6.5: output</strong>The decimal representation is: 50The backwards binary representation is: 010011</td>

  </tr>

  <tr>

   <td width="290"><strong>Problem 6.6 </strong><em>Binary representation</em></td>

   <td width="367"> </td>

  </tr>

  <tr>

   <td width="290"> </td>

   <td width="367"> </td>

  </tr>

 </tbody>

</table>

<h2>Language: C</h2>

Write a program using bit masks and bitwise operators for printing the binary representation of an unsigned char without storing the bits in an array or explicitly converting to binary. For example the character ’2’ is encoded as 50 in decimal representation which is in binary representation on 8 bits 00110010.

Your program should read an unsigned char from the standard input and print on the standard output the binary representation of the read character.

<em>You can assume that the input will be valid. To pass the testcases your output has to be identical with the provided ones.</em>

<table width="593">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 6.6: input</strong>2</td>

   <td width="303"><strong>Testcase 6.6: output</strong>The decimal representation is: 50The binary representation is: 00110010</td>

  </tr>

  <tr>

   <td width="290"><strong>Problem 6.7 </strong><em>set3bits()</em></td>

   <td width="303"> </td>

  </tr>

 </tbody>

</table>

Write a program for setting three bits of an unsigned char to 1. The function set3bits should have four parameters: the unsigned char to be changed and the three bits which are to be set to 1. For example the character ’2’ is encoded as 50 in decimal representation which is in binary representation on 8 bits 00110010. If set3bits() with bits 7, 6 and 1 to be set to 1 is called then the output on the standard output should be 11110010. Print the result on the standard output from the main() function.

<em>You can assume that the input will be valid. Your solution has to satisfy the requirements from the problem description and has to pass the following testcase and potentially other testcases which are uploaded. All characters are relevant for passing testcases including newlines and spaces.</em>

<table width="593">

 <tbody>

  <tr>

   <td width="264"><strong>Testcase 6.7: input</strong>2761</td>

   <td width="329"><strong>Testcase 6.7: output</strong>The decimal representation is: 50The binary representation is: 00110010After setting the bits: 11110010</td>

  </tr>

  <tr>

   <td width="264"><strong>Problem 6.8 </strong><em>A linked list</em></td>

   <td width="329"> </td>

  </tr>

 </tbody>

</table>

Using the example from the slides (Tutorial 6, pages 28 − 35), write a program that uses a linked list. Your program should wait for input from the keyboard. Entering from the keyboard an ’a’ will just add the following number (read as next from the keyboard) to the end of the list, while a ’b’ inserts at the beginning of the list. The character ’r’ will remove the first element from the list, a ’p’ will print the list while a ’q’ will free the memory used by the list and quit the execution of the program.

Use a switch-case statement to decide which action to take.

<em>You can assume that the input will be valid regarding the structure. To pass the testcases your output has to be identical with the provided ones.</em>

<h1><strong>Testcase 6.8: inputTestcase 6.8: output</strong></h1>

b3 2 4

22 4 b 3 a 4 p r p q

<h2>Problem 6.9 <em>An enhanced linked list                                                                           </em>(</h2>

Extend your program for <strong>Problem 6.8 </strong>by writing a function for inserting a new element into the list at a given position and a function for reversing the order of the elements in the list. Your program should wait for input from the keyboard. An ’i’ followed by two numbers (the position and the number to be inserted) should insert the second the number at position of the first number (the first element in the list has position 0). You can assume that the input does not contain any logical errors (e.g., ’i’ is always followed by two numbers, and ’b’ and ’a’ are followed by one number). However, if the position for inserting is negative or is greater than the number of elements in the list then print on the standard output “Invalid position!”. An ’R’ should reverse the order of the elements in the list without allocating new nodes or using a doubly linked list (i.e., only with the use of pointers). Use a switch-case statement to decide which action to take.

<em>You can assume that the input will be valid regarding the structure. To pass the testcases your output has to be identical with the provided ones.</em>

<table width="431">

 <tbody>

  <tr>

   <td width="290"><strong>Testcase 6.9: input</strong>b 2 b 3 a</td>

   <td width="141"><strong>Testcase 6.9: output</strong>3 2 42 42 5 4Invalid position!4 5 2</td>

  </tr>

 </tbody>

</table>

4 p r p i 1 5 p i 4

11 R p q