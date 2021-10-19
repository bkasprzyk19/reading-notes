[<==Back](README.md)

# Read the following articles

## Solving Problems

- allocate time appropriately
- use a methodical process to break down any problem abd take the time to visualize the process.
- write out psuedo code or comments
- replace comments with real code
- optimize and refactor as needed

## Act like you make $1000/hr

- be focused not busy
- stress is the enemy
- as you think, so you are
- make time to do what is needed
- "living in a frenzy is a sign we've squandered too much"- niklas goke

## How to think like a programmer

- problem solving methods
- innovation, refactoring you mental methods
- opening your mindset to shift your internal programming and optimize your mind

-understand
-plan
-divide
-practice

## The 5 Whys

- assess a problem and get to its roots
- define you problem
- define your working environment
- establish your sandbox
- follow your "why?" all the way down the rabbit holes to find the roots of any issues
- address the cause

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

- he invented a tool that visualizes the js runtime at runtime, its called loop spelled loupe

- the forEach method on an array ran async vs sync

- this made me think of loading in video games played online and im not sure the comparison is accurate but i think so

## The Super Mario Effect

- I enjoyed this ted talk and very basic principles to coding your brain.
