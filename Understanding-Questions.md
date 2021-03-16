# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- The user presses the 1 button.
- Within App, the onClick attribute (handleAddOne) is triggered
- Said attribute references the imported data from actions (index.js within actions)
- The ADD_ONE from actions is given Function from reducers (index.js within reducers)
- Reducers sets the logic to something like "Running total = runningTotal + 1" (Not actually a string)
- This is all returned back to the display very quickly
- TotalDisplay shows the total plus 1.
