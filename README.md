# csc-52081-refs
My own set of references and suggested readings for CSC-52081 (Reinforcement Learning) at École Polytechnique. Generated partially by ChatGPT.

> Please note that these are unofficial course notes. They may contain mistakes.

## Schedule
| Session & Topics | Readings & References |
| --- | --- |
| Session 1 – Probabilistic Reasoning and Decision Making <br><br> Topics: <br> • Autonomous / rational agents <br> • Observation → state → action → reward pipeline <br> • Decision theory &amp; expected reward <br> • Bayesian Networks (DAGs, factorization) <br> • Conditional independence &amp; explaining away <br> • Stochastic processes <br> • Markov property &amp; Markov processes <br> • HMM <br> • POMDP <br> • Planning vs decision making <br> • Imitation &amp; model learning (conceptual) | Sutton &amp; Barto: <br> • Ch. 1.1–1.3 – RL problem &amp; agents <br> • Ch. 3.1–3.3 – Agent–Environment Interface, Rewards <br> • Ch. 3.5–3.6 – Markov Property, MDPs <br> • Ch. 4 (conceptual) – Planning as optimization <br><br> Additional references: <br> • Koller &amp; Friedman (2009), Probabilistic Graphical Models <br> • Murphy (2012), ML: A Probabilistic Perspective <br> • [Rabiner (1989), HMM tutorial](https://www.cs.ubc.ca/~murphyk/Bayes/rabiner.pdf) <br> • [Kaelbling et al. (1998), POMDP](https://people.csail.mit.edu/lpk/papers/aij98-pomdp.pdf) <br><br> Suggested readings: <br> • Sutton (2019), [“The Bitter Lesson”](http://www.incompleteideas.net/IncIdeas/BitterLesson.html) — why general methods (search + learning) matter more than handcrafted knowledge <br>
| Session 2 – Bandit Machines (and MCTS) <br><br> Topics: <br> • Multi-armed bandits <br> • Regret &amp; sequential decisions <br> • Exploration vs exploitation <br> • ε-greedy <br> • UCB (Upper Confidence Bounds) <br> • Regret guarantees (high-level) <br> • Thompson Sampling (Bayesian bandits) <br> • EXP3 (adversarial bandits, importance sampling) <br> • Contextual bandits <br> • Monte Carlo Tree Search (MCTS) <br> • UCT (UCB for Trees) | Sutton &amp; Barto: <br> • Ch. 2.1–2.3 – Bandits, ε-greedy <br> • Ch. 2.6 – UCB <br> • Ch. 2.8 – Contextual bandits <br> • Ch. 8.7–8.8 – Planning &amp; MCTS intuition <br><br> Additional references: <br> • [Auer et al. (2002) – UCB &amp; EXP3](https://homes.di.unimi.it/~cesabian/Pubblicazioni/ml-02.pdf) <br> • Lattimore &amp; Szepesvári (2020), Bandit Algorithms <br> • [Russo et al. (2018), Thompson Sampling tutorial](https://arxiv.org/pdf/1707.02038) <br><br> Suggested readings: <br> • Lattimore &amp; Szepesvári Ch. 1–3 (regret &amp; exploration theory) <br> •  [Kocsis &amp; Szepesvári (2006), UCT](http://ggp.stanford.edu/readings/uct.pdf) |

## Books
- [Sutton & Barto — Reinforcement Learning](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf)
- [Lattimore & Szepesvári — Bandit Algorithms](https://tor-lattimore.com/downloads/book/book.pdf)
- Murphy — Probabilistic ML
- [Koller & Friedman — PGMs](http://mcb111.org/w06/KollerFriedman.pdf)
- [Russell & Norvig — AI: A Modern Approach](https://people.engr.tamu.edu/guni/csce625/slides/AI.pdf)

## Other Courses
> Only the Stanford one is open, but it's interesting to see what their content is.
- https://web.stanford.edu/class/cs234/
- https://davidstarsilver.wordpress.com/teaching/
- https://erachelson.github.io/RLclass_MVA/index.html
- https://www.master-mva.com/cours/reinforcement-learning-2/
- https://edu.epfl.ch/coursebook/fr/reinforcement-learning-EE-568
- https://rail.eecs.berkeley.edu/deeprlcourse/

## Seminal Papers
- Bellman (1957) — Dynamic Programming
- Watkins & Dayan (1992) — Q-learning
- Williams (1992) — REINFORCE
- Mnih et al. (2015) — DQN (Nature)
- Schulman et al. (2017) — PPO
- Lillicrap et al. (2016) — DDPG
- Silver et al. (2016) — AlphaGo
- Silver et al. (2017) — AlphaZero
- Osband et al. (2016) — Bootstrapped DQN
- Sutton (1988) — TD(λ)

## Miscellaneous
- https://spinningup.openai.com/en/latest/
- https://lilianweng.github.io/posts/2018-01-23-multi-armed-bandit/
- https://lilianweng.github.io/posts/2018-02-19-rl-overview/
- https://lilianweng.github.io/posts/2024-11-28-reward-hacking/
- https://lilianweng.github.io/posts/2018-04-08-policy-gradient/
- https://lilianweng.github.io/posts/2018-05-05-drl-implementation/
- https://lilianweng.github.io/posts/2019-06-23-meta-rl/
- https://lilianweng.github.io/posts/2019-09-05-evolution-strategies/
- https://lilianweng.github.io/posts/2020-01-29-curriculum-rl/
- https://lilianweng.github.io/posts/2020-06-07-exploration-drl/
- https://lilianweng.github.io/posts/2019-11-10-self-supervised/
- https://karpathy.github.io/2016/05/31/rl/
- https://karpathy.medium.com/alphago-in-context-c47718cb95a5
- https://gymnasium.farama.org
- https://www.jasonwei.net/blog/life-lessons-from-reinforcement-learning
- https://stable-baselines3.readthedocs.io/en/master/
- https://docs.ray.io/en/latest/rllib/index.html
- https://d2l.ai/chapter_reinforcement-learning/index.html
- https://distill.pub/2020/understanding-rl-vision/
- https://spinningup.openai.com/en/latest/spinningup/keypapers.html
- https://www.youtube.com/playlist?list=PLqYmG7hTraZDVH599EItlEWsUOsJbAodm