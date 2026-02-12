# Project-14-Long-Variables
Long variable project

Variables are set up for power being number1, number2, a, b, and the resultant power.
Serial data becomes available and inputs can be put in with buffers in between so nothing happens when data comes in.
number1,2 are 0 until values are put in via a and b. The two while loops are repeated for each input with a total of 4.
Lines 50 - 58 are your inputs printed out and calculated with the result printed out.

*****Questions******
unsure about what line11, lines22-26 do such as the serial read and available which is commanding the input and why do we multiply the number by 10.


*Answers from Matt*
Line 11 effectively matches the output clock speed to the speed expected by the serial register.

Line 22 moving the first digit that the user types into the tens digit place, line 28 then adds the second number to ten times the first number.  This is only if more than one number is pressed before pressing Enter.
Line 26 converts the input number from ASCII to an integer value.  ASCII numbers start at serial value 48 and go up from there.  E.g. 0=48, 1=49, 2=50, etc.  So subracting '0' will give the correct integer value that Arduino can use.

Great questions that show you are thinking critically about the code.  Good job.
