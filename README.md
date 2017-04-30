# Reinforcement learning workshop

[![Join the chat at https://gitter.im/RL_workshop/Lobby](https://badges.gitter.im/RL_workshop/Lobby.svg)](https://gitter.im/RL_workshop/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

![Atari](pics/atari.jpg)

Materials and organization for the RL workshop.

This workshop is part of series of lectures / workshops listed at http://lectures.ai

**UPDATE** 7/12/2016

Workshop is now over.

Thanks to all the participants!

The winner of the competition is Khanh Chuong Le (aka Milan) and he received a price (5TB external hard drive).

The winning solution:
https://gym.openai.com/evaluations/eval_LYKxica8TwyO4z79y6xOQ

## Why reinfocement learning?

> Reinforcement learning is hot! You may have noticed that computers can now automatically learn to play ATARI games (from raw game pixels!), they are beating world champions at Go, simulated quadrupeds are learning to run and leap, and robots are learning how to perform complex manipulation tasks that defy explicit programming. It turns out that all of these advances fall under the umbrella of RL research.
> https://karpathy.github.io/2016/05/31/rl/

## Date & place

November 19th 2016, FIT ČVUT, room 350

## Program

Main organizer: MS, assisting: JZ

Saturday workshop is all about reinforcement learning (RL).
 
There will be competition amongst the participants to create the best algorithm for a given task, with a small award :-)

![Trophy](pics/trophy.jpg)

### What is reinforcement learning?

Reinforcement learning is an area of machine learning inspired by behaviorist psychology, concerned with how software agents ought to take actions in an environment to maximize some notion of a cumulative reward.

Take a look at this two-minute-paper which nicely summarizes recent publications:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=Ih8EfvOzBOY
" target="_blank"><img src="http://img.youtube.com/vi/Ih8EfvOzBOY/0.jpg"
alt="two-minute-paper RL video" width="240" height="180" border="10" /></a>

Usually the agent doesn't have any prior knowledge about the environment and through exploration of the environment and exploitation of his knowledge about it he finds a policy to take the most cumulatively rewarding actions.

In machine learning, the environment is typically modeled as a Markov decision process (MDP) as many reinforcement learning algorithms utilize dynamic programming techniques.
 
Q-learning is a model-free reinforcement learning technique. Q-learning can be used to find an optimal action-selection policy for any given (finite) Markov decision process (MDP)

A recent application of Q-learning to deep learning, by Google DeepMind, titled "deep reinforcement learning" or "deep Q-networks", has been successful at playing some Atari 2600 games at expert human levels. They are games such as [Space Invaders](https://www.youtube.com/watch?v=437Ld_rKM2s), [Pong](https://www.youtube.com/watch?v=moqeZusEMcA), [Breakout](https://www.youtube.com/watch?v=QIs3UOTdsJM) and others.

Deep reinforcement learning has very interesting real-world applications besides game playing. In July, 2016, [DeepMind announced](https://deepmind.com/blog) they reduced google data center electricity cooling bill by 40%, which is a huge saving on costs and the environment.

You can look forward to learn about basics of RL, recent papers and get hand-on experience with RL by training algorithms on GPUs.

### Workshop details
We will go through necessary theory and basics in the morning. In the afternoon we will focus on solving problems from OpenAI Gym and train RL models on GPUs.

### Timetable (subject to change):

| Time            | Delta | Activity                                | Who   |
|-----------------|-------|-----------------------------------------|-------|
| 08:30 - 08:40   |  10m  | Workshop introduction                   | MS,JZ |
| 08:40 - 09:10   |  30m  | Theory for convnets                     | JZ    |
| 09:10 - 10:00   |  50m  | Basics with TensorFlow                  | JZ    |
| *10:00 - 10:30* |  30m  | *Coffee break*                          |       |
| 10:30 - 11:00   |  30m  | Basics from game theory                 | MS    |
|                 |       | - minimax                               |       |
|                 |       | - alfa-beta pruning                     |       |
|                 |       | - Samuel checkers                       |       |
|                 |       | - MCTS, intro to bandits                |       |
|                 |       | - UCT (MCTS)                            |       |
|                 |       | - Markov chains, MDPs                   |       |
| 11:00 - 12:00   |  1h   | Theory for RL                           | MS    |
|                 |       | - Temporal-difference learning          |       |
|                 |       | - Q-learning                            |       |
|                 |       | - DQN                                   |       |
| *12:00 - 13:00* |  1h   | *Lunch break*                           |       |
| 13:00 - 14:30   |  1.5h | Case studies                            | MS    |
|                 |       | - TD-Gammon                             |       |
|                 |       | - Atari games                           |       |
|                 |       | - Go playing                            |       |
| 14:30 - 16:30   |  2h   | Tutorials                               | MS    |
|                 |       | - Atari games                           |       |
|                 |       | - Gym environment                       |       |
| *16:30 - 17:00* |  30m  | *Coffee break*                          |       |
| 17:00 - 19:30   |  2.5h | Free session coding                     | MS,JZ |
| 19:30 - 20:00   |  30m  | Finalizing the day                      | MS,JZ |
|-----------------|-------|-----------------------------------------|-------|
| midnight on     |  8d   | Running models until deadline           |       |
| Sunday 27th     |       | Submit results.                         |       |

### Competition
Details about the competition are to be be specified.

## Sponsor

We'd like to thank our sponsor, Blindspot solutions, for providing us pizzas and prizes.

[![Michal Šustr](pics/blindspot.png)](http://blindspot-solutions.com/)

## Necessary prerequisites for participants

For the workshop to run effectively, participants should:

- be proficient at programing in Python
- have taken courses on probability & statistics, linear algebra and mathematical analysis

It is a plus if you had taken a courwse in Optimization/Biologically inspired algorithms/Planning
  
If you don't know python, please learn some basics - there's a lot materials available online and it is quite a simple language.

## Main organizer

![Michal Šustr](pics/michal.sustr.png)

Michal Šustr (MS)

- [homepage](http://michal.sustr.sk/) 
- [twitter](https://twitter.com/michal_sustr)

### Lecturer

![Jan Zikeš](pics/jan.zikes.png)

Jan Zikeš (JZ)
    
- [twitter](https://twitter.com/ziky90)
- [github](https://github.com/ziky90)

### Co-organizers:

- https://www.fit.cvut.cz/
- http://datalab.fit.cvut.cz/


