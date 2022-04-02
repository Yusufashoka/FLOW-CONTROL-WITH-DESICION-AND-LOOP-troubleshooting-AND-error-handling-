# FLOW-CONTROL-WITH-DESICION-AND-LOOP-troubleshooting-AND-error-handling-

# OUTLINE
<ul>
  <li>For and Else</li>

<li>While and Else</li>

<li>Break</li>

<li>Continue</li>

<li>Pass</li>

<li>List Comprehension</li>

<li>Syntax Error</li>

<li>Exception</li>

<li>Handling Exception</li>
  
# FOR
 <li> A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).</li>

 <li>Loop continues until we reach the last item in the sequence. The body of for loop is separated from the rest of the code using indentation.</li>

 #  for Loop with the range() Function
  <li> the range() Function</li>
  <li>to loop through a set of code a specified number of times, we can use the range() function,</li>
<li> the range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and ends at a specified number.
  
  # Nested For Loop
  
<li>A nested loop is a loop inside the body of the outer loop.

<li>For each iteration of an outer loop the inner loop re-start and    completes its execution before the outer loop can continue to its next iteration.

<li>The outer loop can contain more than one inner loop. There is no limitation on the chaining of loops.

  # Else After For

<li>the else function after for is a function that takes precedence over search loops - to provide a program exit when the search is not found
  
  # While
  <li> A while loop will run a piece of code while a condition is True. It will keep executing the desired set of code statements until that condition is no longer True
    
# Else after While
<li>In the while statement, the else statement block will always be executed when the while condition is false</li>

 #  Break
 <li> A break statement , when used inside the loop, will terminate the loop and exit. If used inside nested loops, it will break out from the current loop.

 # Continue
 <li> A continue statement, when used inside a loop, will stop the current execution, and the control will go back to the start of the loop.
   
# PASS
<li> pass is used if you want a statement or block of statements (statements), but do not continue anything-continue execution in order

# Syntax Error
<li> 1.Syntax errors </li>
usually the easiest to spot, syntax errors occur when you make a typo. Not ending an if statement with the colon is an example of an syntax error.
<li> 2.Logical errors </li >
  also called semantic errors, logical errors cause the program to behave incorrectly, but they do not usually crash the program
 
# Exception
<li> An exception is an event, which occurs during the execution of a program that disrupts the normal flow of the program's instructions. In general, when a Python script encounters a situation that it cannot cope with, it raises an exception. An exception is a Python object that represents an error.
  
# Handle Exception
<li> In Python, exceptions can be handled using a try statement. The critical operation which can raise an exception is placed inside the try clause. The code that handles the exceptions is written in the except clause. We can thus choose what operations to perform once we have caught the exception.
  
# File Not Found Error
<li> This Error happened when you want to open a file that you not assign/run before or the file is doesn't exist
  
# Key Error
<li> A python KeyError exception is what is raised when you try to access a key that isn't in a dictionary ( dict )
 
# Value Error
<li>A python valueerror exception is what is raised when you try to access a key that isn't in a dictionary ( dict )

#Type Error
<li> type error  is raised whenever an operation is performed on an incorrect/unsupported object type. For example, using the / (divide) operator on a string and an integer value will raise TypeError.
  
 # Handling Complex Error (Bonus Bonus)
 <li> then in more complex applications, exception handling can use a single except statement that handles more than one type of error concatenated in a tuple.
