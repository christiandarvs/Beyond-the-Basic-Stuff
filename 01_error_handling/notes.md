## Examining Tracebacks
- The traceback shows the place where the exception occurred and the trail of function calls leading up to it.
- Frame objects hold local variables and other data associated with function calls.
- Frame objects are created when a function is called and destroyed when the function returns.
- The traceback displays a frame summary for each frame leading up to the crash.
- The final frame summary displays the line that triggered the unhandled exception, along with the exception's name and message.