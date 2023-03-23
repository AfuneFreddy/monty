0. push, pall
The opcode pint prints the value at the top of the stack, followed by a new line.
The opcode pop removes the top element of the stack
The opcode swap swaps the top two elements of the stack.
The opcode add adds the top two elements of the stack.
The opcode nop doesn’t do anything.
The opcode sub subtracts the top element of the stack from the second top element of the stack.
The opcode div divides the second top element of the stack by the top element of the stack.
The opcode mul multiplies the second top element of the stack with the top element of the stack.
The opcode mod computes the rest of the division of the second top element of the stack by the top element of the stack.
Every good language comes with the capability of commenting. When the first non-space character of a line is #, treat this line as a comment (don’t do anything).
The opcode pchar prints the char at the top of the stack, followed by a new line.
The opcode pstr prints the string starting at the top of the stack, followed by a new line.
The opcode rotl rotates the stack to the top.
The opcode rotr rotates the stack to the bottom.
The opcode stack sets the format of the data to a stack (LIFO). This is the default behavior of the program.

Usage: stack
The queue opcode

The opcode queue sets the format of the data to a queue (FIFO).
Write a Brainf*ck script that prints School, followed by a new line.
Read the two digits from stdin, add them, and print the result
Read the two digits from stdin, multiply them, and print the result
Read the two digits from stdin, multiply them, and print the result, followed by a new line
