Interaction 2.0
---------------

From version 2.0 on this program does real user interaction by also allowing the user to enter data which is processed. (Even if the processing is just to store it in a variable and show it again on the screen after this).

The program can be invoked in a usual shell.

Go into the directory where it is located and just invoke it by its name, for example

  ./interact
  
Then the program asks for a number.

Unfortunately there was no code space left to implement also some prompt, so the "asking" for the number ist not visible so well. You can recognize it by a cursor being one line down after presing the ENTER- key at the invocation.

Enter a number and see the given number arising on the screen (in the shell window).

The program terminates after showing the given number, using a debugger to examine the answer as it was usual in the past is not necessary this time.



Version history:
----------------

Version 2.0

The code was written completely new.
With this version the program not just outputs a message, but also asks a value from the user.
Thus this time the program does the first real user interaction because also input of data is processed.


Version 1.4

Code redesign to make it readable and maintainable more clearly.
The function is the same as in version 1.3


Version 1.3

Added the line break in the output on the terminal.
So now the "C" won't hide before the prompt anymore and will be visible more clearly.
This will improve the user interaction a lot.


Version 1.2

Code redesign to make it more comfortable to read and maintain.
The function is the same as in version 1.0


Version 1.1

Code redesign to make it more comfortable to read and maintain.
The function is the same as in version 1.0


Version 1.0

Initial version.

