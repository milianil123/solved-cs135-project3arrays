Download Link: https://assignmentchef.com/product/solved-cs135-project3arrays
<br>









<h1>Project Goals</h1>




The goals of this project are to explore the use of one dimensional and two dimensional arrays.




<h1>Project Description</h1>




This project consists of two programs:




<h2>Program 1 (Scramble a sentence):​</h2>




Write a program that scrambles a sentence by: 1) reversing the order of words in a sentence and 2) shifting all the letters in each word by two positions to the right. When shifting to the right, the letters wrap around to the beginning. This program should:




❏ prompt a user to enter a sentence ending with either a period, a question mark or an exclamation mark

❏ output the same sentence with all of the words, with letters shifted to the right by two positions and printed in reverse order.




Here is an example of how the program should behave:




Enter a sentence ended by a ‘.’, a ‘?’ or a ‘!’: <u>​</u><u>you can cage a</u> <u>swallow can’t you?</u>




Reversed sentence: ouy ‘tcan owswall a geca anc ouy?




Code for this program should be in a file named ​<em>scramble_sentence.c</em>




<strong>Program 2 (Magic square): </strong>




Write a program that prints an 9×9 magic square (a square arrangement of the numbers 1, 2, …, n​<sup>2 </sup>​in which the sums of the rows, columns and diagonals are all the same).  Strategy: store the magic square in a two-dimensional array. Start by placing the number 1 in the middle of row 0. Place each of the remaining numbers 2, 3, …, n​<sup>2</sup>​ by moving up one row and over one column. Any attempt to go outside the bounds of the array should “wrap around” to the opposite side of the array. For example, instead of storing the next number in row-1, we would store it in row n-1 (the last row). Instead of storing the next number in column n, we would store it in column 0. If a particular array element is already occupied, put the number directly below the previously stored number.




For example, for a magic square of size 5, your program should print:




<table width="255">

 <tbody>

  <tr>

   <td width="48">17</td>

   <td width="48">24</td>

   <td width="48"> 1</td>

   <td width="48"> 8</td>

   <td width="63">15</td>

  </tr>

  <tr>

   <td width="48">23</td>

   <td width="48"> 5</td>

   <td width="48"> 7</td>

   <td width="48">14</td>

   <td width="63">16</td>

  </tr>

  <tr>

   <td width="48"> 4</td>

   <td width="48"> 6</td>

   <td width="48">13</td>

   <td width="48">20</td>

   <td width="63">22</td>

  </tr>

  <tr>

   <td width="48">10</td>

   <td width="48">12</td>

   <td width="48">19</td>

   <td width="48">21</td>

   <td width="63"> 3</td>

  </tr>

  <tr>

   <td width="48">11</td>

   <td width="48">18</td>

   <td width="48">25</td>

   <td width="48"> 2</td>

   <td width="63"> 9</td>

  </tr>

 </tbody>

</table>




<h2>Constraints ❏ You must use a 2-dimensional array​     .​</h2>

❏ Make sure that your program outputs the numbers aligned on the right on the columns, similar to the example above




Code for this program should be in a file named ​<em>magic_square.c </em>







<h2>Program 3 – Challenge (Hexadecimal addition)</h2>

<strong> </strong>

Write a program to perform addition of two hexadecimal numerals, each with up to 10 digits. If the result of the addition is more than 10 digits long, the program should output the message “Addition overflow” and not the result of the addition.




This program should:




❏ prompt a user to enter the two numbers to be added

❏ output sum of the two numbers or the message “Addition overflow”.




Here is an example on how the algorithm should behave:




Please enter the first hexadecimal number (10 digits maximum): 13A570

Please enter the second hexadecimal number (10 digits maximum): 3CA21 The sum of the two numbers is: 176F91




<strong>Note:</strong> the numbers can have any number of digits between 1 and 10.​




<h2>Constraints</h2>

❏ You must use <strong>arrays</strong>​ to store hexadecimal numerals as arrays of characters.​




Code for this program should be in a file named ​<em><sub>add_hex.c</sub></em>


