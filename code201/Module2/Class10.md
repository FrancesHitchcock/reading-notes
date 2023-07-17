# Module 2 Class 10 Reading Notes

## Debugging

### The main differences between syntax errors and logic errors

With a syntax error you have usually spelt something incorrectly, or written a statement that the JS doesn't understand. These errors are usually immediately obvious because the code won't run at all. There may also be an error message in the console which tells you what the error is and where the program encountered it.

Logic errors occur where the code has been written in a way that produces a different outcome to what was intended. These can be harder to identify because the code simply follows the instructions and thinks it's got everything correct and doesn't flag up any anomolies.

### Errors I have encountered and how I corrected them

Firstly, I try and avoid errors by making console.log statements frequently when building my code. If they don't print then I know I have an error.

In the recent cookie-stand lab one of the objectives was to render a list of totals. I wanted to check that the program had added up the totals correctly and that I had not made a logic error in the program, so I checked by manually adding up the numbers for one of the totals, using a calculator. Fortunately there was not error on this occasion.

I have made a few sytax errors, for example with the control flow and getting things in the wrong order. In this case, I have been able to look at the error messages that tell me that certain variables are not recognised.

Assignment to const variable is a frequent one.

### How this topic can influence my long-term goals

I will debug frequently when building code, as it can be hard to identify where the errors are if you write a huge chunk of code and then debug it when it's complete.

## The JavaScript Debugger

### The JavaScript debugger tool and how it works

The JS debugger is part of the browser dev tools suite. It allows you to set breakpoints that pause execution and find problems by seeing the value of the variables.

### A breakpoint

A breakpoint is a point at which you want to pause the execution of the code.

### A call stack

A call stack is a representation of a stack of functions. When a function calls another function the called function is placed on top of the stack and so on to build the stack. The functions in the stack are then executed top down.

Debugging HTML: [mdn](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML)

Debugging CSS: [mdn](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Debugging_CSS)
