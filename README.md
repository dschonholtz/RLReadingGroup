# RLReadingGroup

I am flying by the seat of my pants. I love all suggestions.

## Papers in consideration:

Evolving Neural Networks through Augmenting Topologies
- https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.28.5457&rep=rep1&type=pdf
- Abstract:
An important question in neuroevolution is how to gain an advantage from evolving neural network
topologies along with weights. We present a method, NeuroEvolution of Augmenting Topologies (NEAT)
that outperforms the best fixed-topology method on a challenging benchmark reinforcement learning task.
We claim that the increased efficiency is due to (1) employing a principled method of crossover of different
topologies, (2) protecting structural innovation using speciation, and (3) incrementally growing from minimal structure. We test this claim through a series of ablation studies that demonstrate that each component
is necessary to the system as a whole and to each other. What results is significantly faster learning. NEAT
is also an important contribution to GAs because it shows how it is possible for evolution to both optimize
and complexify solutions simultaneously, offering the possibility of evolving increasingly complex solutions
over generations, and strengthening the analogy with biological evolution.

An Introduction to Counterfactual Regret Minimization
- http://modelai.gettysburg.edu/2013/cfr/cfr.pdf
- Abstract:
In 2000, Hart and Mas-Colell introduced the important game-theoretic algorithm of regret matching.
Players reach equilibrium play by tracking regrets for past plays, making future plays proportional to
positive regrets. The technique is not only simple and intuitive; it has sparked a revolution in computer
game play of some of the most difficult bluffing games, including clear domination of annual computer
poker competitions.
Since the algorithm is relatively recent, there are few curricular materials available to introduce
regret-based algorithms to the next generation of researchers and practitioners in this area... [Continues but is long]

ReBeL
- https://arxiv.org/pdf/2007.13544.pdf
- Abstract:
The combination of deep reinforcement learning and search at both training and test
time is a powerful paradigm that has led to a number of successes in single-agent
settings and perfect-information games, best exemplified by AlphaZero. However,
prior algorithms of this form cannot cope with imperfect-information games. This
paper presents ReBeL, a general framework for self-play reinforcement learning
and search that provably converges to a Nash equilibrium in any two-player zerosum game. In the simpler setting of 
- perfect-information games, ReBeL reduces to
an algorithm similar to AlphaZero. Results in two different imperfect-information
games show ReBeL converges to an approximate Nash equilibrium. We also show
ReBeL achieves superhuman performance in heads-up no-limit Texas hold’em
poker, while using far less domain knowledge than any prior poker AI.

Pluribus
- https://www.cs.cmu.edu/~noamb/papers/19-Science-Superhuman.pdf
- Abstract
In recent years there have been great strides in artificial intelligence (AI), with games often
serving as challenge problems, benchmarks, and milestones for progress. Poker has served for
decades as such a challenge problem. Past successes in such benchmarks, including poker,
have been limited to two-player games. However, poker in particular is traditionally played
with more than two players. Multiplayer games present fundamental additional issues
beyond those in two-player games, and multiplayer poker is a recognized AI milestone. In
this paper we present Pluribus, an AI that we show is stronger than top human professionals
in six-player no-limit Texas hold’em poker, the most popular form of poker played by humans.


Mastering the game of Go with deep neural networks and tree search (AlphaGo)
- https://www.nature.com/articles/nature16961
- Abstract:
The game of Go has long been viewed as the most challenging of classic games for artificial intelligence owing to its 
enormous search space and the difficulty of evaluating board positions and moves. Here we introduce a new approach to 
computer Go that uses ‘value networks’ to evaluate board positions and ‘policy networks’ to select moves. These deep 
neural networks are trained by a novel combination of supervised learning from human expert games, and reinforcement 
learning from games of self-play. Without any lookahead search, the neural networks play Go at the level of 
state-of-the-art Monte Carlo tree search programs that simulate thousands of random games of self-play. 
We also introduce a new search algorithm that combines Monte Carlo simulation with value and policy networks. 
Using this search algorithm, our program AlphaGo achieved a 99.8% winning rate against other Go programs, 
and defeated the human European Go champion by 5 games to 0. This is the first time that a computer program has 
defeated a human professional player in the full-sized game of Go, a feat previously thought to be at least a decade away.


Mastering the game of Go without human knowledge (AlphaGo Zero)
- https://www.nature.com/articles/nature24270
- Abstract:
A long-standing goal of artificial intelligence is an algorithm that learns, tabula rasa, superhuman proficiency in
challenging domains. Recently, AlphaGo became the first program to defeat a world champion in the game of Go. 
The tree search in AlphaGo evaluated positions and selected moves using deep neural networks. These neural networks
were trained by supervised learning from human expert moves, and by reinforcement learning from self-play. Here we
introduce an algorithm based solely on reinforcement learning, without human data, guidance or domain knowledge
beyond game rules. AlphaGo becomes its own teacher: a neural network is trained to predict AlphaGo’s own move
selections and also the winner of AlphaGo’s games. This neural network improves the strength of the tree search,
resulting in higher quality move selection and stronger self-play in the next iteration. Starting tabula rasa,
our new program AlphaGo Zero achieved superhuman performance, winning 100–0 against the previously published, 
champion-defeating AlphaGo.


Mastering Atari, Go, Chess and Shogi by Planning with a Learned Model (MuZero)
- https://arxiv.org/abs/1911.08265
- Abstract:
Constructing agents with planning capabilities has long been one of the main challenges in the pursuit of 
artificial intelligence. Tree-based planning methods have enjoyed huge success in challenging domains, 
such as chess and Go, where a perfect simulator is available. However, in real-world problems the dynamics 
governing the environment are often complex and unknown. In this work we present the MuZero algorithm which, by 
combining a tree-based search with a learned model, achieves superhuman performance in a range of challenging and 
visually complex domains, without any knowledge of their underlying dynamics. MuZero learns a model that, when 
applied iteratively, predicts the quantities most directly relevant to planning: the reward, the action-selection
policy, and the value function. When evaluated on 57 different Atari games the canonical video game environment
for testing AI techniques, in which model-based planning approaches have historically struggled our new algorithm 
achieved a new state of the art. When evaluated on Go, chess and shogi, without any knowledge of the game rules,
MuZero matched the superhuman performance of the AlphaZero algorithm that was supplied with the game rules.


DeepStack: Expert-Level Artificial Intelligence in No-Limit Poker
- https://arxiv.org/abs/1701.01724
- Abstract:
Artificial intelligence has seen several breakthroughs in recent years, with games often serving as milestones.
A common feature of these games is that players have perfect information. Poker is the quintessential game of
imperfect information, and a longstanding challenge problem in artificial intelligence. We introduce DeepStack,
an algorithm for imperfect information settings. It combines recursive reasoning to handle information asymmetry,
decomposition to focus computation on the relevant decision, and a form of intuition that is automatically learned
from self-play using deep learning. In a study involving 44,000 hands of poker, DeepStack defeated with statistical
significance professional poker players in heads-up no-limit Texas hold'em. The approach is theoretically sound and is
shown to produce more difficult to exploit strategies than prior approaches.

