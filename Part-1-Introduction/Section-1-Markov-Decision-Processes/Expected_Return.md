# Expected Return - What drives a Reinforcement Learning Agent in an MDP

___

## Table of Contents

___

### 1. Expected Return 

> **The agent's goal** in an *MDP* is to ***maximize*** `the expected return of rewards` which will drive the agent to make the decisions it makes.


> `Episodes` are subsequences ({state-action}) and to end in a terminal state at time **T**.

> `Continuing tasks` : **expected return** could be infinite (T = infinite)

### 2. Discounted Return

\- Rather than the agent's goal being to maximize the expected return of rewards, it will instead be to maximize **the expected discounted return of rewards**. 

+ Specifically, , the agent will be choosing action **At** at each time **t** to maximize the expected discounted return.

> **The discounted return** will care more about the ***immediate reward*** over ***future rewards***