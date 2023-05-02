Download Link: https://assignmentchef.com/product/solved-comp248-assignment-3-producing-a-flowchart-given-code
<br>
<em>            </em>

Welcome to The Program

—————————————————–

Please enter the number of sequences

<strong>5 </strong>

The result is:

<h1>□,□,□,□,□</h1>

Do you want to repeat? (Yes/No)

<strong>Yes </strong>

Please enter the number of sequences

<strong>3 </strong>

The result is:

<h1>□,□,□</h1>

Do you want to repeat? (Yes/No)

<strong>No </strong>




Thank you for choosing our program, have a nice day!

Figure 2- Sample output for question 1







<strong>Question 2 – Cashier Calculator </strong>

For this question you are required to write a Cashier Calculator, which will compute the total price of some items including taxes (Tax1 &amp; Tax2).

The subtotal, taxes, and total price are calculated as follows:

SubTotal =   where n = number of items bought and P(i) = the price of item i.

Tax1 = SubTotal × tax1Rate

(e.g., tax1Rate =0.06 stands for 6%)

Tax2 = (SubTotal + Tax1) × tax2Rate

(e.g., tax2Rate=0.075 stands for 7.5%)




Total = SubTotal + Tax1 + Tax2




Your program will require the user to enter the following:

<ul>

 <li>The number of items</li>

 <li>The price of each item</li>

 <li>The Tax1 rate in percentage</li>

 <li>The Tax2 rate in percentage</li>

</ul>




The following constraints are given:

x The minimum number of items is 1 and the maximum number of items is 10.

x The minimum price of each item is $1 and the maximum price of each item is $1,000. The price may be a decimal number.

x The minimum tax rate for Tax1 and Tax2 is 0 and the maximum tax rate is 100.  Suppose the tax rate is 12.345%, the user will enter “12.345”. You will need to divide it by 100 to compute the tax rates. You can assume that the user will not enter the “%” symbol.

x All of the above minimum and maximum values are <strong>constants</strong>, i.e., they remain unchanged throughout the entire program. You should know how to define them.




The program must behave in the following manner:

x The program will require the user to enter the needed values one after another. If any of the entered values is invalid, then the program will detect that and go into a loop requiring the user to enter a valid value. The program must keep track of the total number of invalid values that the user has entered.

x Using SubTotal and tax1Rate, the program should compute Tax1. x Using Tax1 and tax2Rate, the program should compute Tax2.

x The program will calculate the SubTotal, Tax1, Tax2 and Total then display the following:

<ul>

 <li>How many times the user has entered invalid values for <em>all </em>the required inputs.</li>

</ul>

If the user did not enter any invalid value, then no message should be displayed. In other words, “You have entered 0 invalid inputs” should NOT be displayed if the user has entered all values correctly.

<ul>

 <li>The subtotal o The Tax1 o The Tax2 o The total <strong> </strong></li>

</ul>

x The displayed subtotal, Tax1, Tax2, and total <strong><u>must</u></strong> have 2 decimal places.




Here is a sample output to illustrate the expected behavior of your program. User input is in green.

<table width="565">

 <tbody>

  <tr>

   <td width="565">-$-$-$————————————-$-$-$-Welcome to Cashier Calculator Program-$-$-$————————————-$-$-$-Please enter the number of items bought [1…10]: <strong>0</strong> Please enter the number of items bought [1…10]: <strong>2</strong> Please enter the price of items 1 [1…1000]: <strong>0</strong>Please enter the price of items 1 [1…1000]: <strong>100.50</strong>Please enter the price of items 2 [1…1000]: <strong>500</strong>Please enter the tax rate of Tax1 [0…100]: <strong>11111</strong>Please enter the tax rate of Tax1 [0…100]: <strong>5</strong>Please enter the tax rate of Tax2 [0…100]: <strong>7.5</strong> Here are your results———————You have entered 3 invalid inputs.Subtotal: $ 600.50Tax 1: $ 30.03Tax 2: $ 47.29  TOTAL: $ 677.81 Hope you shopping trip was an enjoyable one!</td>

  </tr>

 </tbody>

</table>

Figure 3- Sample output for question 2

<strong> </strong>

<strong> </strong>

<strong><u>Question 3</u> – Producing a flowchart given code </strong>




Given the code below:

<ol>

 <li>What is the output of the program?</li>

 <li>Draw an appropriate flowchart for this program.</li>

</ol>




<table width="634">

 <tbody>

  <tr>

   <td width="634"><strong>import</strong> java.util.Scanner; <strong>class</strong> A3Q3{<strong>public</strong> <strong>static</strong> <strong>void</strong> main (String[] args){     //Variable declarationScanner scanner = <strong>new</strong> Scanner(System.<strong><em>in</em></strong>);<strong>int</strong> i = 0 ,value = 0, n;String string = “”;  System.<strong><em>out</em></strong>.println(“Enter the value of n:”);n = scanner.nextInt(); <strong>for</strong> (i = 1; i &lt;= n; i++){<strong>int</strong> counter=0;<strong>for</strong>(value = 1; value &lt;= i; value++){<strong>if</strong>(i%value==0){counter = counter + 1;}}<strong>if</strong> (counter == 2){string = string + i + ” “;}} System.<strong><em>out</em></strong>.println(“Output is :”);System.<strong><em>out</em></strong>.println(string); scanner.close();}} </td>

  </tr>

 </tbody>

</table>




How to submit the answers to this question?

<u>Option 1</u>: Draw your flowchart by hand and write up your answers to questions a) and b); and submit a photo of your answers which you zip together with your .java files for questions 1 and 2.

<u>Option 2</u>: Use one of the free s/w for flowchart drawing, or Word or even Power Point.  Don’t forget to include the answers to questions a) and b) of this questions.


