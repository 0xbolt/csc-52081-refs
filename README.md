# csc-52081-refs
References and suggested readings for CSC-52081. Generated partially by ChatGPT.

> Please note that these are unofficial course notes. They may contains mistakes.

## Schedule
<div style="overflow-x: auto;">
<table>
  <thead>
    <tr>
      <th>Course Session</th>
      <th style="width: 280px;">Topics Covered</th>
      <th style="width: 280px;">Sutton &amp; Barto (Primary Text)</th>
      <th style="width: 280px;">Additional References</th>
      <th style="width: 280px;">Suggested Readings</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Session 1 – Probabilistic Reasoning and Decision Making</td>
      <td style="width: 280px;">• Autonomous / rational agents <br> • Observation → state → action → reward pipeline <br> • Decision theory &amp; expected reward <br> • Bayesian Networks (DAGs, factorization) <br> • Conditional independence &amp; explaining away <br> • Stochastic processes <br> • Markov property &amp; Markov processes <br> • HMM intuition <br> • POMDP intuition <br> • Planning vs decision making <br> • Imitation &amp; model learning (conceptual)</td>
      <td style="width: 280px;">Ch. 1.1–1.3 – RL problem &amp; agents <br> Ch. 3.1–3.3 – Agent–Environment Interface, Rewards <br> Ch. 3.5–3.6 – Markov Property, MDPs <br> Ch. 4 (conceptual) – Planning as optimization</td>
      <td style="width: 280px;">• Koller &amp; Friedman (2009), Probabilistic Graphical Models <br> • Murphy (2012), ML: A Probabilistic Perspective <br> • Rabiner (1989), HMM tutorial <br> • Kaelbling et al. (1998), POMDP survey</td>
      <td style="width: 280px;">• Sutton (2019), “The Bitter Lesson” — why general methods (search + learning) matter more than handcrafted knowledge <br> • Murphy Ch. 10 (Bayesian inference) <br> • Rabiner HMM tutorial (intuition only)</td>
    </tr>
    <tr>
      <td>Session 2 – Bandit Machines (and MCTS)</td>
      <td style="width: 280px;">• Multi-armed bandits <br> • Regret &amp; sequential decisions <br> • Exploration vs exploitation <br> • ε-greedy <br> • UCB (Upper Confidence Bounds) <br> • Regret guarantees (high-level) <br> • Thompson Sampling (Bayesian bandits) <br> • EXP3 (adversarial bandits, importance sampling) <br> • Contextual bandits <br> • Monte Carlo Tree Search (MCTS) <br> • UCT (UCB for Trees)</td>
      <td style="width: 280px;">Ch. 2.1–2.3 – Bandits, ε-greedy <br> Ch. 2.6 – UCB <br> Ch. 2.8 – Contextual bandits <br> Ch. 8.7–8.8 – Planning &amp; MCTS intuition</td>
      <td style="width: 280px;">• Auer et al. (2002) – UCB &amp; EXP3 <br> • Lattimore &amp; Szepesvári (2020), Bandit Algorithms <br> • Russo et al. (2018), Thompson Sampling tutorial <br> • Kocsis &amp; Szepesvári (2006), UCT</td>
      <td style="width: 280px;">• Lattimore &amp; Szepesvári Ch. 1–3 (regret &amp; exploration theory) <br> • Auer et al. (2002) for regret bounds <br> • Kocsis &amp; Szepesvári (2006) for UCT</td>
    </tr>
  </tbody>
</table>
</div>
