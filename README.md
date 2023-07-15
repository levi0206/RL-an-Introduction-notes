# RL an Introduction notes
My earlier notes were written by hand with GoodNotes, so I might miss some information in those notes. Later I change to using LaTex which allows directly import the screen shots to illustrate examples more conveniently. Sometimes I will write down my understanding or add more information in the terms of *Remark*. 

## About the notes

Currently, my primary focus is on the idea and construction of reinforcement learning algorithms, leading me to skip Ch11 and some sections in Ch12.
Ch11 talks about the challenge of off-policy learning due to the instability of semi-gradient TD methods that involve bootstrapping. 
> The whole area of off-policy learning is relatively new and unsettled. Which methods are best or even adequate is not yet clear.

As for Ch12, the most popular and useful algorithms are TD($\lambda$), Truncated TD($\lambda$) and Sarsa($\lambda$), which are the purposes of the notes. Other sections are relatively not important for me. 
## My point of view
Reinforcement learning is a science of decision making, a very powerful tool to solve the problems that are unsolvable or difficult for classical mathematics. The core idea of RL is based on the interaction of the **agent** and the **environment**. The agent observes a **state**, and according to the state, the agent takes an **action** to the environment. As a reaction, the environment returns a corresponding **reward** and state. Then the agent select the next action according to the information it received, state and reward, and so on and so forth.

When you study the reinforment learning algorithms, you can always ask youself these questions:
- What is target, or return, that we want to approximate?
- What and why is this algorithm good or imperfect in terms of time complexity and memory cost?
- What is the improvement of this algorithm compared with other algorithms? For example, why is TD better than Monte Carlo?
  
Although you probably cannot answer these questions immediately (I cannot answer all as well), one day you will understand if you keep them in mind and keep studying related content. 

If you you don't have time to study the 13 chapters, you can focus on ch2,3,4,6,10,13 only. However, I recommend everyone who seriously aims to understand reinforcement learning to read all 13 chapters. This will help you approach to the essence of reinforcment learning.

The meeting record is available in the [study group](https://sites.google.com/view/sntung/study-group?authuser=0) held by Prof. Tung.

Any suggestion is welcome: levihsu2002@gmail.com
