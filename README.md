Download Link: https://assignmentchef.com/product/solved-cs1301-lab-02-computing-taxes-and-pay
<br>
Good programmers think before they begin coding. Part I of this assignment involves brainstorming with a group of peers with no computers to talk about a strategy for solving this week’s lab. Breakup into groups based on your seating (3-4 people per group) and brainstorm about how to solve the problems below. Make sure everyone understands the problem and sketch out potential ways to move toward a solution.  You may find it helpful to look over the required readings for this week.

<strong>Note: Brainstorms are to help you get started with the lab and get you in the habit of designing before you code.  You won’t submit them to eLC. </strong>

<h1>Exercise I – Computing Taxes and Pay</h1>

Create a class called <strong>NetPay</strong> to compute a person’s gross and net pay based on their hourly wage, hours worked, and several withholdings. All statements should be defined in the <strong>main</strong> method of the class (except for declarations of constants).

The output of the program should look similar to this:

<table width="0">

 <tbody>

  <tr>

   <td width="192">Hours per Week:</td>

   <td width="70">40</td>

  </tr>

  <tr>

   <td width="192">Gross Pay:</td>

   <td width="70">290.0</td>

  </tr>

  <tr>

   <td width="192">Net Pay: Deductions</td>

   <td width="70">225.765</td>

  </tr>

  <tr>

   <td width="192">Federal:</td>

   <td width="70">29.0</td>

  </tr>

  <tr>

   <td width="192">State:</td>

   <td width="70">13.05</td>

  </tr>

  <tr>

   <td width="192">Social Security:</td>

   <td width="70">17.98</td>

  </tr>

  <tr>

   <td width="192">Medicare:</td>

   <td width="70">4.205</td>

  </tr>

 </tbody>

</table>

Implementation Details:

<ul>

 <li>To make the outputs line up on the right-hand side, you will need to use the tab character ‘t’ in your print statements. You may need one or more ‘t’ characters in each line.  Play around with it until the output lines up.</li>

 <li>You will use the number of hours per week to compute the gross pay, net pay, and the deductions. You will need to create a variable for each value above.  Brainstorm the proper data types.</li>

 <li>Hours per week is your input to the program. For exercise 1, you will type it into the program.  For exercise 2 (below), it will come from the keyboard.</li>

 <li>You will also need to declare named constants and initialize them to the values shown. o <strong>FEDERAL_TAX_PERCENT</strong>:  00. o <strong>STATE_TAX_PERCENT</strong>: 4.5. o <strong>SS_PERCENT</strong>:   6.2. o <strong>MEDICARE_PERCENT</strong><strong>  </strong>1.45.</li>

</ul>

o <strong>PAY_PER_HOUR</strong>                       7.25.




<u>Questions to consider:</u>

<ul>

 <li>How do we compute gross pay? Store the result in the variable created for gross pay.</li>

 <li>How do we compute federal tax? Think about using gross pay and federal tax percent.</li>

 <li>Compute state tax, social security contribution, and medicare using similar methods as federal tax.</li>

 <li>How do we compute net pay?</li>

 <li>Display the values on the screen in the order listed above.</li>

</ul>

Once your program is implemented, compile and run your program. Afterwards, edit your program by changing the value assigned to the variable for hours per week. Do this in the code for now.  We will do user input in part 2<strong>.</strong>  Additional sample executions are shown below.  Your program may have more digits after the decimal point shown than the examples below, and that is okay as long as your program’s output is within 0.01 of the answer shown.

<table width="0">

 <tbody>

  <tr>

   <td width="86">Hours per Week:</td>

   <td colspan="2" width="69">30</td>

   <td width="411"> </td>

  </tr>

  <tr>

   <td width="86">Gross Pay:</td>

   <td colspan="2" width="69">217.5</td>

   <td width="411"> </td>

  </tr>

  <tr>

   <td width="86">Net Pay: Deductions</td>

   <td colspan="2" width="69">169.32375</td>

   <td width="411"> </td>

  </tr>

  <tr>

   <td width="86">Federal:</td>

   <td colspan="2" width="69">21.75</td>

   <td width="411"> </td>

  </tr>

  <tr>

   <td width="86">State:</td>

   <td colspan="2" width="69">9.7875</td>

   <td width="411"> </td>

  </tr>

  <tr>

   <td width="86">Social Security:</td>

   <td colspan="2" width="69">13.485</td>

   <td width="411"> </td>

  </tr>

  <tr>

   <td width="86">Medicare:</td>

   <td colspan="2" width="69">3.15375</td>

   <td width="411"> </td>

  </tr>

  <tr>

   <td colspan="2" width="88">Hours per Week:</td>

   <td colspan="2" width="129">35</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Gross Pay:</td>

   <td colspan="2" width="129">253.75</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Net Pay: </td>

   <td colspan="2" width="129">197.544375</td>

  </tr>

  <tr>

   <td colspan="2" width="88">DeductionsFederal:</td>

   <td colspan="2" width="129">25.375</td>

  </tr>

  <tr>

   <td colspan="2" width="88">State:</td>

   <td colspan="2" width="129">11.41875</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Social Security:</td>

   <td colspan="2" width="129">15.7325</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Medicare:</td>

   <td colspan="2" width="129">3.679375</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Hours per Week:</td>

   <td colspan="2" width="129">40</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Gross Pay:</td>

   <td colspan="2" width="129">290.0</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Net Pay: </td>

   <td colspan="2" width="129">225.765</td>

  </tr>

  <tr>

   <td colspan="2" width="88">DeductionsFederal:</td>

   <td colspan="2" width="129">29.0</td>

  </tr>

  <tr>

   <td colspan="2" width="88">State:</td>

   <td colspan="2" width="129">13.05</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Social Security:</td>

   <td colspan="2" width="129">17.98</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Medicare:</td>

   <td colspan="2" width="129">4.205</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Hours per Week:</td>

   <td colspan="2" width="129">45</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Gross Pay:</td>

   <td colspan="2" width="129">326.25</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Net Pay:</td>

   <td colspan="2" width="129">253.985625</td>

  </tr>

  <tr>

   <td colspan="2" width="88"> DeductionsFederal:</td>

   <td colspan="2" width="129">32.625</td>

  </tr>

  <tr>

   <td colspan="2" width="88">State:</td>

   <td colspan="2" width="129">14.68125</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Social Security:</td>

   <td colspan="2" width="129">20.2275</td>

  </tr>

  <tr>

   <td colspan="2" width="88">Medicare:</td>

   <td colspan="2" width="129">4.730625</td>

  </tr>

  <tr>

   <td width="86"></td>

   <td width="2"></td>

   <td width="67"></td>

   <td width="62"></td>

  </tr>

 </tbody>

</table>

<strong>   </strong>

<strong>Exercise 2: </strong>

Modify <strong>NetPay.java</strong> to <strong>ask the user for the number of hours worked</strong> (it is no longer typed into the program).  Note: you do not need to submit exercise 1 – only submit a single java file after completing both exercises.

<ul>

 <li>Which preexisting Java class did we use to read in keyboard input? Reference the textbook or class slides and borrow the necessary code from there (you don’t have to memorize this code).</li>

 <li>Don’t forget to prompt the user to enter the number of hours per week.</li>

</ul>




Compile and run your program. A run of your program should look like the example below (<strong>the blue (bold) is the user’s input – it is not being output by the program</strong>).  Your program may have more digits after the decimal point shown than the examples below, and that is okay as long as your program’s output is within 0.01 of the answer shown.

<table width="0">

 <tbody>

  <tr>

   <td width="192">Hours per Week:</td>

   <td width="79"><strong>100</strong></td>

  </tr>

  <tr>

   <td width="192">Gross Pay:</td>

   <td width="79">725.0</td>

  </tr>

  <tr>

   <td width="192">Net Pay: Deductions</td>

   <td width="79">564.4125</td>

  </tr>

  <tr>

   <td width="192">Federal:</td>

   <td width="79">72.5</td>

  </tr>

  <tr>

   <td width="192">State:</td>

   <td width="79">32.625</td>

  </tr>

  <tr>

   <td width="192">Social Security:</td>

   <td width="79">44.95</td>

  </tr>

  <tr>

   <td width="192">Medicare:</td>

   <td width="79">10.5125</td>

  </tr>

 </tbody>

</table>




You should run your program with various inputs, and test that your program is producing correct outputs.  For every programming lab and project this semester, you are responsible for ensuring that your program doesn’t contain any syntax, runtime, or logical errors.  Always test, test, and retest the programs you create.

<h1>Statement of Academic Honesty Requirement</h1>

You must include the Statement of Academic Honesty comment at the top of the program’s source file. Copy and agree to the entirety of the text contained in the file

<strong>StatementOfAcademicHonesty.txt</strong> on the Labs and Projects webpage, and fill in the class name of your <strong>.java</strong> file, your name, submission date, and the program’s purpose.  In the future, every Java source file of every lab and project you submit <strong><u>must</u></strong> have a comment such as this at the top of every source file.  Otherwise, points will be deducted from your assignment.

<h1>Additional Requirements</h1>

These are things that make the graders lives easier, and ultimately, you will see in the real world as well. Remember the teaching staff does not want to touch your code after they gave you requirements; they want to see the perfect results they asked for! Here is a checklist of things you can<strong> lose points</strong> for:




<ul>

 <li>(10 points) If the source file(s)/class(es) are named incorrectly (case matters!)</li>

 <li>(10 points) If your source file(s) have a package declaration at the top</li>

 <li>(10 points) If any source file you submit is missing your Statement of Academic Honesty at the top of the source file. All submitted source code files must contain your Statement of Academic Honesty at the top of each file.</li>

 <li>(10 points) If you have more than one instance of Scanner in your program. Your program should only have one instance of Scanner.</li>

 <li>(15 points) Inconsistent I/O (input/output) that does not match our instructions or examples exactly (unless otherwise stated in an assignment’s instructions). Your program’s I/O (order, wording, formatting, etc.) must match our examples and instructions.</li>

 <li>(100 points) If the source file(s) are not submitted before the specified deadline’s late period ends (48 hours after the deadline) or if they do not compile.</li>

 <li>(25 points) Late penalties will be deducted as per the course syllabus.</li>

 <li>If your (10 points) comments or (10 points) variables are “lacking” o Here, “lacking” means that you or a TA can find <strong>any</strong> lines of code or variables that take more than 10 seconds to understand, and there is no comment, or the variable name does not make sense (variable names like <strong>b</strong>, <strong>bb</strong>, <strong>bbb</strong>, etc. <strong>will</strong> <strong>almost never be acceptable) </strong></li>

 <li>(10 points) Indentation is not consistent throughout your source code o Refresh your memory of indentation patterns in chapter 2 in the course textbook o Be careful of a combination of tabs and spaces in your files (use one or the other)!</li>

</ul>




If any of the above do not make sense to you, talk to a TA, or ask on Piazza!