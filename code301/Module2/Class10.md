# Module 2 Class 10 Reading Notes

## The Call Stack

### What is a ‘call’?

The call is the invocation of a function

### How many ‘calls’ can happen at once?

The calls happen one at a time, synchronously

### What does LIFO mean?

Last In, First Out

### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

The first function calls the second. The second calls the third. The third is then executed, followed by the second and lastly the first.

### What causes a Stack Overflow?

A stack overflow occurs when the browser reaches its maximum stack call - e.g in the case of a recursive function that does not have an exit point.

## JavaScript Error Messages

### What is a ‘reference error’?

When you try and use a variable that has not been declared

### What is a ‘syntax error’?

When the browser can't parse the code

### What is a ‘range error’?

When an invalid length is given e.g. an empty array length -1

### What is a ‘type error’?

This occurs when types you are trying to access are incompatible

### What is a breakpoint?

A breakpoint is a point where you stop the code when debugging. You can achieve this using a console.log statement. If the statement logs then you know the code is correct up to that point. You can also add a debugger statement into your code.

### What does the word ‘debugger’ do in your code?

Invokes debugging functionality e.g setting a breakpoint.
