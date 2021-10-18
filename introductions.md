# Read the following articles

- Solving Problems

- Act like you make $1000/hr

- How to think like a programmer

- The 5 Whys

# Watch these videos

## what the heck is the event loop anyway

This video was a breakdown of javascript. Phil said his question was what is javascript?

- as a professional dev he couldn't answer this question.

18 months later Phil thinks he figured it out

- the JS runtime is a heap with a call stack
- although when you clone the v8 codebase this is not in there.

-to start from the beginning, this is a single threaded programming language

- it has a single call stack, can do one thing at a time.

- blowing the stack was interesting.

- visualizing the call stack

- synchronous request block the stack.

- setTimeout (function ())

setTimeout - API provided by tge browser. It kicks off a timer. It handles the countdown for you. the set Timeout Call itself is complete so it can come off the stack. The timer in the webAPI completes, this is when the callback que comes in, or the task que

- now the event loop. the simple piece. its looks at the stack and the task que. if the stack is clear, it moves the que'd callback and gets run.

## The Super Mario Effect

- I enjoyed this ted talk and very basic principles to coding your brain.
