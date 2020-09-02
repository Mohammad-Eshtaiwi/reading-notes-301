# refactoring

restructuring means to restructer your code to make it more readable and easier to maintain. Also can make it reusable. for example if you create a logic to read a number from a console for a part of your code you can transform your logic into readFromConsole() and use the same function with other part which need to use that logic.

## Pure functions

-   It returns the same result if given the same arguments (it is also referred as deterministic)
-   It does not cause any observable side effects

how to not make side effects?

```
let counter = 1;

const increaseCounter = (value) => value + 1;

increaseCounter(counter); // 2
console.log(counter); // 1
```

## Pure functions benefits

-   The code’s definitely easier to test

-   Immutability : Unchanging over time or unable to be changed.

## Higher-order functions

-   takes one or more functions as arguments, or
    returns a function as its result
