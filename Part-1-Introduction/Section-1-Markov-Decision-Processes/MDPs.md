# Markov Decision Processes - MDPs

___

## Table of Contents
- [1. Components of an MDP](#1)
- [2. MDP notation](#2)
- [References](#ref)
___

<a name="1"></a>
### 1. Components of an MDP

> **MDPs** is the bedrock for our understanding of RL and **MDPs** give us a way to **formalize sequential decision making.**

\- **In an MDP**, we have : 

+ **agent** : a decision maker that interacts with the **environment** it's placed in. These interactions occur sequentially over time.

+ **state** : At each time step, **the agent** will get some **state** of environment.

+ **action** : After given ***above state***, **the agent** selects an **action** to take.

+ **reward** : **the environment** is then transitioned into ***a new state***, then the agent is given a **reward** as a consequence of *the previous action*.

> **The above process** happens sequentially over and over again. This process creates a **trajectory** that shows the sequence of **states**, **actions** and **rewards**.

> Throughout this process, **agent's goal** is to **maximize the cumulative rewards.**

<a name="2"></a>
### 2. MDP notation.

![](https://i.imgur.com/nIUdsIm.jpg)

![Formulation1]()

![Formulation2]()

## References

+ https://deeplizard.com/learn/video/my207WNoeyA