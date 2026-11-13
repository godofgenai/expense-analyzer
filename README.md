What did you predict for Warmup.js, and what did it print? Explain the first line and the error from Part B.

Answer: I predicted undefined for var a as it old var format and is assigned undefined before initialization. 99 and 1 as we were using spread operator and it wont modify original datastructure. and 3 due to closure concept.
Part B error throws reference error because with let and const variables are just declared and not yet initialized which is the opposite of var.

Why did Loop finished print before Async read finished? Who did the reading while your loop was running?

Answer: Async read finished later because it was an asyncronous operation and synchronous operations are priotized first for the main thread execution. The reading was done by black box which is the event loop.

How does tracker remember spent after createBudgetTracker has returned?

Answer: The tracker remembers spent after createBudgetTracker was removed because of a concept called closure. In closure values of variables of that specific environement are cached which js thinks can be used later by other processes or functions.

What does the ^ in front of the lodash version in package.json mean, and why is package-lock.json created?

Answer: ^ specifies npm can install upto the latest minor or patch version ut cannot auto upgrade a major version. package-lock.json is created to maintain the graph between all the dependencies for maintaining the intigirty of the packaeges intalled within a project.
