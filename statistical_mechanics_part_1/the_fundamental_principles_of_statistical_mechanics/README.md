## The Fundamental Principles of Statistical Mechanics

The presentation of the concepts in this introductory chapter is both fascinating and profound. It beats the numerous topics in statistical mechanics into its bare bond and connect those with a core spine.

### Statisticla distribution

1. Difference between mechanics and statistical mechanics

The many-body particles problem though follow the simple mechanical rules but due to the large degree of freedom makes the problem intractable. 
As the complexity and intricacy of the interaction increases, a new regularity appear.

2. Phase space and phase trajectory to describe the subsystem

Phase space describe the states of the \\(i\\)th particles having momentun \\(p_{i}\\) and position \\(q_{i}\\). For a system that has \\(s\\) particles, it will correspond to \\(6s\\) degree of freedom \\( (q_{1}, q_{2},...,q_{s}, p_{1}, p_{2},...,p_{s}) \\).

We consider a subsytem that is still large enough to be a macroscopic part of the system. At sufficiently long time \\(T\\), the subsystem would have explore every possible states many times. At a time interval \\(\triangle t << T\\), the subsystem will occupy the phase space \\(\triangle q \triangle p\\). Taking the limit \\(T\rightarrow \infty\\), the ratio between the time interval that the subsystem spent \\(\triangle t\\) in the phase volume \\(\triangle p \triangle q\\), \\(w= lim_{T\rightarrow \infty}{\frac{\triangle t}{T}}\\), is a constant value. 

This comparison between the time average and the ensemble average (averaging over the phase space volume for the subsystem) gives rise to a time-independent and probablistic picture of the system, where the initial condition no longer matters for any measurable of the system.

$$ dw = \rho (q_{1},q_{2},...,q_{s},p_{1},p_{2},...,p_{s}) dp dq$$

where \\(dpdq = dq_{1}dq_{2}...dq_{s}dp_{1}dp_{2}...dp_{s}\\). \\(dw\\) tells us the probability of the subsystem being in the infinitesimal phase volume \\(dpdq\\) and \\(\rho\\) is the probability density distribution in the phase space.


3. Time average and ensemble average

Any average of the observable \\(f(p,q)\\) can be obtained by integrating over the phase space with the probability density distribution as follow:

$$ \bar{f} = \int{\rho f(p, q) dp dq}$$

By this formalism, the time average and the ensemble average of the observable \\(f\\) equal and could be expressed as the following equality:

$$ \bar{f} = \frac{1}{T} \int{f(t)dt} = \int{\rho f(p, q) dpdq} $$

This is saying that the ensemble average of the value is invariant in a long time. Since the initial time we choose is arbitrary, the average value is independent of the initial condition.

Then determining the probability distribution function \\(\rho\\) is of special important in statisitical mechanics, since it gives a time-invariant measure to equilibrium system.

> "The determination of the __statistical distribution__ for any subsystem is in fact the fundamental problem of statistical physics"


4. Different deterministic nature from mechanics

The statsitical description is different from the mechanical description, which involving solving differential equation and the input of initial configurations. In here, we are merely dividing the large system into smaller consitituent and study distribution in the phase space. Though probablistic in nature, this approach gives rise to an accurate prediction of macroscopic measurable with small fluctuation that scales inversely to the square root of the size of system. Thus, in some sense, it is another kind of deterministic measure as oppose to classical mechanics.


5. Relaxation time

Here we are considering the time taken to equilibrate the system \\(T\\) is long enough for the system to reach equilibrium. In study of statistical mechanics, we limit our scope to equilibrium system, any thing that concern with the equilibration of the system, is in the study of _kinetics_, the relaxation process, of the system.


### Statistical independence

