# Mean Field Games With Congestion Effects

The theory of mean field games (MFGs in short), has been introduced in the pioneering works of J-M. Lasry and P-L. Lions, and aims at studying deterministic or stochastic differential games (Nash equilibria) as the number of players tends to infinity. 
It supposes that the rational players are indistinguishable and individually have a negligible influence on the game, and that each individual strategy is influenced by some averages of quantities depending on the states (or the controls) of the other players. 
The applications of MFGs are numerous, from economics and finance to the study of crowd motion. On the other hand, very few MFG problems have explicit or semi-explicit solutions. Therefore, numerical simulations of MFGs play a crucial role in obtaining quantitative information from this class of models.


We begin by introducing the objective and the controlled diffusion process governing the system. The goal is to determine an optimal control $u$ and a corresponding flow of probability densities $m$ that jointly satisfy a coupled system of Hamilton-Jacobi-Bellman (HJB) and Kolmogorov-Fokker-Planck (KFP) equations.  
The HJB equation, which characterizes the optimal control, is supplemented with a terminal condition, while the KFP equation, which describes the evolution of the probability densities, is equipped with an initial condition. A key challenge in this problem arises from the forward-backward structure of this coupled system.  
To solve this system, we employ a Picard fixed-point iteration scheme, which iteratively updates the control and density until convergence is achieved.  
