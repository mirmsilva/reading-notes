# Day 1 Reading Notes

## Debugging
- Clarify the problem by asking yourself the right questions
  - what did you expect your code to do vs what it did
- Examine your assumptions
  - Are you using the API correctly?
  - Are there any typos?
  - Did you make a change elsewhere in your code?
  - Do you understand the intent of the code?
- Step throug your code in debugging mode.
  - in VS you can enter debugging by pressing F5
- Start small. Add and test as you build.

## Try/Catch
- Place code that my cause exception in a try block & place anything that will handle exceptions in a catch block.
  - there can be multiple catches to handle and execute different types of exceptions
- CLR exceptions are not handled by catch blocks

## Statement Keywords
- Statements are program instructions & are executed in sequence
  - Selection Statements ( if / else / switch )
  - Iteration Statements ( do / for / foreach / while )
  - Jump Statements ( break / default / goto / return )
  - Exception Handling Statements( throw / try-catch )
  - Check & Unchecked Statements
  - Fixed Statement
  - Lock Statement

## Therac-25
- Computer Controlled radiation therapy machine produced by Atomic Energy of Canada Limited. It caused 6 incidents in which patients were given massive amounts of radiation. This was due to multiple programming errors.  Which led to patients being blasted with radition 100x's + the normal amounts & resulted in death or serious injury.

## Ariane 5
- Ariane 5 is a heavy lift space launch vehicle in Europe. It has had 82 consecutive launches. It was originally designed and as expendable launch system but since its intial launch it has been redesigned into updated safer iterations and is now rated for human for human space launches.

### Things I Want To Know More About:

### My Sources:
- https://docs.microsoft.com/en-us/visualstudio/debugger/debugging-absolute-beginners?view=vs-2019&tabs=csharp
- https://docs.microsoft.com/en-us/dotnet/standard/exceptions/how-to-use-the-try-catch-block-to-catch-exceptions
- https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/statement-keywords
- https://en.wikipedia.org/wiki/Therac-25
- https://en.wikipedia.org/wiki/Ariane_5
[Back to Main](README.md)