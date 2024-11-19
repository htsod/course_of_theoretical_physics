# The Fundamental Principles of Statistical Mechanics

The presentation of the concepts in this introductory chapter is both fascinating and profound. It beats the numerous topics in statistical mechanics into its bare bond and connect those with a core spine.

## Statisticla Distribution

1. Difference between mechanics and statistical mechanics

The many-body particles problem follows the simple mechanical rules but due to the large degree of freedom makes the problem intractable.

As the complexity and intricacy of the interaction increases, a new statistical regularity appear.

__These statistical laws resulting from the very presence of a large number of particles forming the body cannot in any way be reduced to purely mechanical laws.__

2. Phase space and phase trajectory to describe the subsystem

__Phase space__ describe the states of the $i$th particles having momentun $p_{i}$ and position $q_{i}$. For a system that has $s$ particles, it will correspond to $6s$ degree of freedom $(q_{1}, q_{2},...,q_{s}, p_{1}, p_{2},...,p_{s})$.

We consider a subsytem that is still large enough to be a macroscopic part of the system. At sufficiently long time $T$, the subsystem would have explore every possible states many times. At a time interval $\triangle t << T$, the subsystem will occupy the phase space $\triangle q \triangle p$. At the limit $T\rightarrow \infty$, $w= lim_{T\rightarrow \infty}{\frac{\triangle t}{T}}$, is a constant value. 

This approach connects the time dependent macroscopic quantities and the phase space weighting or the ensemble average (averaging over the phase space volume for the subsystem), leading to a time-independent and probablistic picture of the system, where the initial condition no longer matters for any macroscopic quantities of the system. We could write the probability of the state of the subsystem as:

$$ dw = \rho (q_{1},q_{2},...,q_{s},p_{1},p_{2},...,p_{s}) dp dq$$

where $dpdq = dq_{1}dq_{2}...dq_{s}dp_{1}dp_{2}...dp_{s}$. $dw$ tells us the probability of the subsystem being in the infinitesimal phase volume $dpdq$ and $\rho$ is the weighting of of the phase space, or in other words the probability density distribution in the phase space.


3. Time average and ensemble average of the macroscopic quantities are the same

Any average of the observable $f(p,q)$ can be obtained by integrating over the phase space with the probability density distribution as follow:

$$ \bar{f} = \int{\rho f(p, q) dp dq}$$

By this formalism, the time average and the ensemble average of the observable $f$ equal and could be expressed as the following equality:

$$ \bar{f} = \frac{1}{T} \int{f(t)dt} = \int{\rho f(p, q) dpdq} $$

This is saying that the ensemble average of the value is invariant for a system. And all the macroscopic quantities in the subsystem is specify by the weighted average in the phase space. Since the initial time we choose is arbitrary, the average value is independent of the initial condition.

Then determining the probability distribution function $\rho$ is of special important in statisitical mechanics, since it gives a time-invariant measure to equilibrium system.



4. Equilibrium and relaxation time

Here we are considering the time taken to equilibrate the system $T$ is long enough for the system to reach __equilibrium__. Quoting from the book:

__If a closed microscopic system is in a state such that in any macroscopic subsystem the macroscopic physical quantities are to a high degree of accuracy equal to their mean values, the system is said to be in a state of _statistical equilibrium_.__

 In study of statistical mechanics, we limit our scope to equilibrium system, any thing that concern with the equilibration of the system, is in the study of _kinetics_. Any closed system this is yet to approach equilibrium will eventually equiliibrium to equilibrium state. The time taken to reach equilibrium state is known is the __relaxation time__.



### Statistical Independence

