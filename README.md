# Sequential Circuits: Latches

In this lab, you’ve learned about edge-sensitive circuits and explored some of the power therein.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Summary

We learned about flip-flops and their functionality when paired with a clock input that allows for a toggle system and setting of data.

## Lab Questions

### What is different between edge and level sensitive circuits?

Edge triggered circuits will only change state when the clock signal is changing from a 0 to a 1 or vice versa. A level sensetive circuit will update the state as long as the clock is either 1 or 0, which means it will update as fast as it can.

### Why is it important to declare initial state?

At the beginning of a simulation or power-up, the inputs will be floating for a brief moment, and the output will not know what it needs to be. Setting the initial state fixes that issue and also allows other modules that are dependent on that value to function properly.

### What do edge-sensitive circuits let us build?
These types of circuits allow us to build predictable, synchronized systems that change state only on clock edges that are rising or falling.
