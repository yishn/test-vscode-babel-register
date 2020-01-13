## Reproduction Steps

- Install depedencies using `npm i`
- Open folder in VS Code
- Set a breakpoint on line 2 in `test.ts`
- Launch debugging by pressing <kbd>F5</kbd>

Notice that VS Code does not stop at breakpoint.

- Set an additional breakpoint on line 3 in `test.ts`
- Launch debugging by pressing <kbd>F5</kbd>

Notice that VS Code stops directly at line 3.

- Step over by pressing <kbd>F10</kbd>

Notice that VS Code doesn't stop at the next line, instead all code runs through.
