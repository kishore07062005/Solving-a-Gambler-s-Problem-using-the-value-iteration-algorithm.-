# Solving Gambler’s Problem using Value Iteration

## Aim
To implement the Value Iteration Algorithm for solving the Gambler’s Problem in Reinforcement Learning and determine the optimal policy that maximizes the probability of reaching the goal.

## Algorithm

1. Initialize the environment:
   - Define goal amount.
   - Define probability of winning.
   - Initialize value function and policy.

2. Initialize state values:
   - Set value of goal state to 1.
   - Set all other state values to 0.

3. Perform Value Iteration:
   - For each state:
     - Evaluate all possible stakes.
     - Compute expected returns for each action.
     - Update the value function with the maximum expected return.

4. Repeat the iteration until the value function converges.

5. Derive the optimal policy:
   - Select the action with the highest value for each state.

6. Display the optimal value function and policy.

---

## Program

```

        
```

---

## Output

```
```

---

## Result

The Value Iteration Algorithm was successfully implemented for the Gambler’s Problem. The optimal value function and policy were obtained, maximizing the probability of reaching the goal state through optimal betting decisions.
