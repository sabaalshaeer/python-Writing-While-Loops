# python-Writing-While-Loops
Write a while loop to keep the whole program running.

Position the insertion point in line 16 and press Enter.

Type while True: and press Enter.

Writing while True is essentially telling Python to execute the following code as long as True is True. Since this is always the case, the code will run indefinitely until it encounters a break statement.

Highlight all of the code under the while loop—from lines 19 through 39—and press Tab.

You want all of this code to run indefinitely, so indenting it places it under the control of the loop.

Verify that this entire block of code is positioned within the while loop.

Write a while loop to keep the second input question running until given an acceptable answer.

Position the insertion point in line 26 and press Enter.

Press Tab twice to align the insertion point with common_word

Type another while statement as shown.

Select the input and if statements in lines 28-32.

Press Tab to indent the selected block.

As long as the user doesn't answer the question correctly (with "y" or "n"), the question will keep prompting for new input.

Write a while loop to keep the third input question running until given an acceptable answer.

Place the insertion point on line 33 and press Enter to create a new line.

Press Tab twice to position the insertion point in line with user_output, and enter another while statement as shown.

Indent the rest of the code (lines 35-41) so that it is contained by this while loop as shown.

Like the previous while loop, as long as the user doesn't supply a "y" or "n" answer to the question, it will keep being asked, and the subsequent code will keep executing.

Add control statements where the loops need to do something different.

Position the insertion point at the end of line 24, and press Enter.

Type continue

If the program doesn't find the file requested by the user, the top-level while loop will restart the code under it. In this case, the loop will keep asking the file's path until it gets what it's looking for.

On line 33, change the pass placeholder to break.

You'll write the code to handle this option later, but for now, you'll break out of this if statement if the user provides an acceptable answer ("y" or "n").

Add break statements after the "Success!" and "Exiting…" print lines.

When your program has finished outputting the results to a file, or if the user doesn't want the results output to a file, this will terminate the while loop and the program will stop.

Add a break statement at the end of the source code, nested within the else branch above.

If the program enters the else branch (i.e., the user provides a valid file and path), the program can exit when all the code in the else branch is finished executing.

Define variables so the loops can execute properly.

Observe the highlighted variables on lines 28 and 35.

The PyCharm editor has identified a problem in the code.

Point at the highlighted variables on lines 28 and 35, and pause to view the warning message.

The way the code is currently written, during execution, it is possible that these variables may not be assigned a value because both are referenced in the while condition, but are only assigned a value after that point in the code. You can resolve this by assigning them an initial value before the while statement.

Position the insertion point at the end of line 26 and press Enter.

Type common_word = "", making sure that the statement is within the else branch.

This defines common_word and initializes it with an empty string, which will be filled during the program's execution. The variable can now be evaluated when the while condition is evaluated the first time.

Position the insertion point in line 35 and press Enter.

Press Tab twice to indent.

Type a statement to initialize user_output, followed by an empty line, as shown.

Observe that PyCharm has removed the highlighting from common_word and user_output.

Test out your input loops.

Run the program.

Enter any test input for the first prompt.

For the second question, enter any input other than "y" or "n".

Verify that, until you answer "y" or "n", the question repeats.

Do the same for question three, and verify that it acts the same way.
