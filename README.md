# Course of Theoretical Physics by L.D. Landau and E.M. Lifshitz
Study notes on the book series of Course of Theoretical Physics.

# Table of Contents

1. [Mechanics](#mechanics)

2. [The Classical Theory of Fields](#the-classical-theory-of-fields)

3. [Quantum Mechanics](#quantum-mechanics-non-relativistic-theory)

4. [Quantum Electrodynamics](#quantum-electrodynamics)

5. [Statistical Mechanics Part I](#statistical-mechanics-part-i)

6. [Fluid Mechanics](#fluid-mechanics)

7. [Theory of Elasticity](#theory-of-elasticity)

8. [Electrodynamics of Continuous Media](#electrodynamics-of-continuous-media)

9. [Statistical Mechanics Part II](#statistical-mechanics-part-ii)

10. [Physical Kinetics](#physical-kinetics)


<!-- ## Mechanics


## The Classical Theory of Fields


## Quantum Mechanics (Non-relativistic Theory)

## Quantum Electrodynamics -->

## Statistical Mechanics Part I

### The Fundamental Principles of Statistical Mechanics

The presentation of the concepts in this introductory chapter is both fascinating and profound. It beats the numerous topics in statistical mechanics into its bare bond and connect those with a core spine.

#### Statisticla Distribution

1. _Difference between mechanics and statistical mechanics_

The many-body particles problem follows the simple mechanical rules but due to the large degree of freedom makes the problem intractable.

As the complexity and intricacy of the interaction increases, a new statistical regularity appear.

__These statistical laws resulting from the very presence of a large number of particles forming the body cannot in any way be reduced to purely mechanical laws, which draws the difference between mechanics and statsitical mechanics__

2. _Phase space and phase trajectory to describe the subsystem_

__Phase space__ describe the states of the $i$ th particles having momentun $p_{i}$ and position $q_{i}$. For a system that has $s$ particles, it will correspond to $6s$ degree of freedom $(q_{1}, q_{2},...,q_{s}, p_{1}, p_{2},...,p_{s})$.

We consider a subsytem that is still large enough to be a macroscopic part of the system. At sufficiently long time $T$, the subsystem would have explore every possible states many times. At a time interval $\triangle t << T$, the subsystem will occupy the phase space $\triangle q \triangle p$. At the limit $T\rightarrow \infty$, $w= lim_{T\rightarrow \infty}{\frac{\triangle t}{T}}$, is a constant value. 

This approach connects the time dependent macroscopic quantities and the phase space weighting or the ensemble average (averaging over the phase space volume for the subsystem), leading to a time-independent and probablistic description of the subsystem, where the initial condition no longer matters for any macroscopic quantities of the system. We could write the probability of the state of the subsystem as:

$$ dw = \rho (q_{1},q_{2},...,q_{s},p_{1},p_{2},...,p_{s}) dp dq$$

where $dpdq = dq_{1}dq_{2}...dq_{s}dp_{1}dp_{2}...dp_{s}$. $dw$ tells us the probability of the subsystem being in the infinitesimal phase volume $dpdq$ and $\rho$ is the weighting of the phase space, also known as the probability density distribution in the phase space.


3. _Time average and ensemble average of the macroscopic quantities are the same_

Any average of the observable $f(p,q)$ can be obtained by integrating over the phase space with the probability density distribution as follow:

$$ \bar{f} = \int{\rho f(p, q) dp dq}$$

By this formalism, the time average and the ensemble average of the observable $f$ equal:

$$ \bar{f} = \frac{1}{T} \int{f(t)dt} = \int{\rho f(p, q) dpdq} $$

This is saying that the ensemble average of the value is time invariant. And all the macroscopic quantities in the subsystem is specify by the weighted average in the phase space. Since the initial time we choose is arbitrary, the average value is independent of the initial condition.

Then determining the probability distribution function $\rho$ is of special important in statisitical mechanics, since it gives a time-invariant measure to equilibrium system.



4. _Equilibrium and relaxation time_

Here we are considering the time taken to equilibrate the system $T$ is long enough for the system to reach __equilibrium__. Quoting from the book:

__If a closed microscopic system is in a state such that in any macroscopic subsystem the macroscopic physical quantities are to a high degree of accuracy equal to their mean values, the system is said to be in a state of _statistical equilibrium_.__

For any closed system is yet to approach equilibrium will eventually reach a equilibrium state. The time taken to reach equilibrium state is known is the __relaxation time__. In the study of statistical mechanics, we limit our scope to equilibrium system, any thing that concern with the equilibration of the system, is in the study of _kinetics_.



#### Statistical Independence

1. _Weakly interacting subsystem are mutually statistical independent_

A subsystem which we defined to be large enough to be macroscopic has a much larger internal energy than its interacting energy. Hence, in a short enough time, the interaction between subsystem remains weak and does not contribute changes to the distribution.

Consider a composite system with probability density $\rho_{12}$ that composes of two subsystems $\rho_{1}$ and $\rho_{2}$. A statistical independent between the subsystem would imply that:

$$ \rho_{12}dp_{12}dq_{12} = \rho_{1}dp_{1}dq_{1}\rho_{2}dp_{2}dq_{2} $$

$$ \rho_{12} = \rho_{1}\rho_{2} $$

Let the macroscopic quantities in subsystems to be $f_{1}$ and $f_{2}$. Statistical independent would then suggests that the mean of the product between $f_{1}$ and $f_{2}$ will be the same as the product of the means. As shown in the following:

$$ \bar{f_{1}f_{2}} = \int{\rho_{12}dp_{12}dq_{12} f_{1}f_{2}} = \int{\rho_{1}dp_{1}dq_{2}f_{1}} \int{\rho_{2}dp_{2}dq_{2}f_{2}} =  \bar{f_{1}} \bar{f_{2}} $$


2. _The relative fluctuation of the system scales as $\frac{1}{\sqrt{N}}$_

The relative fluctuation of the system is defined to the ratio between the __root mean square__ fluctuation of the quantity $f$ and the mean of $f$.

$$ \frac{\left< (\triangle f)^{2} \right>^{1/2}}{\bar{f}} $$

where $\triangle f = f - \bar{f}$ is the difference to the mean. This ratio is strictly positive, it reduces to zero only when the difference to the mean becomes zero.

To show that this ratio is inversely proportional to the size of the system, we first note that most macroscopic quantity $f_{i}$ in the susbsystem $i$ is an additive value, meaning if we sum all the $f_{i}$ to get the macroscopic quantity for the entire system. This is due to the fact that the subsystems are _quasi-closed_.

$$ \bar{f} = \sum_{i}{\bar{f_{i}}} $$

So, the nominator of the relative fluctuation could be written as:

$$ \left< (\triangle f)^{2} \right>^{1/2} = \left< (\triangle \sum_{i}{f_{i}})^{2} \right>^{1/2} $$

<!-- 
Rewriting the square of the range of the fluctuation $(\triangle f)^{2} = \bar{f}^{2} + f^{2} -2 f \bar{f} = \bar{f}^{2} + f^{2}$, where in the second equality the last term vanishes because $f$ fluctuates in all directions.  -->

Making use of the fact that the subsystem is weakly interacting, leading us with $\triangle f_{i} \triangle f_{j} = \delta_{ij} (\triangle f_{i})^{2}$, where $\delta_{ij}$ is the dirac delta.

Then, we could express the relative fluctuation with the summation outside the average:

$$ \frac{\left< (\triangle f)^{2} \right>^{1/2}}{\bar{f}} = \frac{\left<(\sum_{i}{ \triangle f_{i}})^{2}\right>^{1/2}}{\sum_{i}{\bar{f_{i}}}} =  \frac{\sum_{i}{\left< (\triangle f_{i})^{2} \right>^{1/2}}}{\sum_{i}{\bar{f_{i}}}} \propto \frac{1}{\sqrt{N}} $$

That suggests that the deviation from the mean descreases with the size of the system increases. For typical molecular system with $N \approx 10^{23}$, the deviation is vanishingly small.



#### Liouville's Theorem

1. Long enough to be equilibrium not long enough to equilibrate

Like mention earlier, typical system has particles number of order $~10^{23}$ which renders an impossibility of a complete mechanical description of the system. Consider decomposing the entire system into macroscopic subsystem that only weakly interacting with other consitituents. We require a time duration that long enough for the subsystem to reach equilibrium, but not too long for the interaction that takes effect to equilibrate further. In this particular framework, we can allocate each subsystem a points in the phase space. The distribution of these phase points, of course, will follow the probability distribution function of the phase space $\rho(q, p)$.


2. Flow in the phase space

A probabilty distribution will follow the continuity equation which presume locality of the subsystem, restricting the possible form of the probability distribution.

$$ \frac{\partial\rho}{\partial t}  + \nabla \cdot (\rho v) = 0$$

where $v$ is the velocity of the generalized coordinates $p$ and $q$.

3. Invariant probability distribution

Suppose for a steady flow in a system with $s$ particles, by steady flow we suggest that the probability density function has no explict dependence on time, which is a reasonable assumption to make for a equilibrium system.


$$ \nabla \cdot (\rho v) = \sum_{i=1}^{22s}{\rho} = \sum_{i=1}^{s}{\left[ \frac{\partial}{\partial q_{i}} (\rho \dot{q_{i}}) + \frac{\partial}{ \partial p_{i}} (\rho \dot{p_{i}}) \right]} = 0 $$

Expanding yields:

$$ \sum_{i=1}^{s}{\left[ \dot{q_{i}} \frac{\partial \rho}{\partial q_{i}} + \dot{p_{i}}\frac{\partial \rho}{\partial p_{i}}  \right]} + \rho \sum_{i=1}^{s}{\left[ \frac{\partial \dot{q_{i}}}{\partial q_{i}} + \frac{\partial \dot{p_{i}}}{\partial p_{i}} \right]}  $$

For a Hamiltonian system, $\frac{\partial H}{\partial p_{i}} = \dot{q_{i}}$ and $-\frac{\partial H}{\partial p_{i}} = \dot{p_{i}}$. Substitute these in the second summation:

$$  \sum_{i=1}^{s}{\left[ \dot{q_{i}} \frac{\partial \rho}{\partial q_{i}} + \dot{p_{i}}\frac{\partial \rho}{\partial p_{i}}  \right]} = \frac{d\rho}{dt} $$

That suggests that the flow in phase space only depends on the momentum and position, which are the time-invariant quantities. The result is only valid for not too lon intervals of time, during which the subsystem behaves as if closed, to a sufficient approximation.


#### The Significant of Energy

1. $\rho$ is a integral of motion


From Liouville theorem, under qusi-closed subsystem condition, we have restricted the probability distribution function of the phase space to be only dependent on the momentum and position, which are the mechanical invariants of the subsystem. The probability distribution function then, being a function of the mechanical invariants, is itself an integral of the motion.

2. The logarithm of $\rho$ is additive

From the statistical independent of the susbsytems, the distribution $\rho_{12}$ for a combination of two subsystems is equal to the product of the distribution $\rho_{1}$ and $\rho_{2}$, hence:

$$ \log{\rho_{12}} = \log{\rho_{1}} + \log{\rho_{2}} $$

3. The values of the additive integrals of the motion completely defined the statistica properties of a closed system

Since $\rho$ is both an integral of the motion and additive, that restrict the form of $\rho_{a}$ for the $a$ th subsystem to be linear combinations of the seven independent additive integrals of the motion: the energy, the three components of the momentum vector and the three components of the angular momentum vector.

$$ \log{\rho_{a}} = \alpha_{a} + \beta E_{a}(p,q) + \gamma \cdot P_{a}(p,q) + \delta \cdot M_{\alpha}(p, q)$$

with constant coefficients $alpha_{a}, \beta, \gamma, \delta$ which  $\beta, \gamma, \delta$ must be the same for all subsystems in a given closed system by construction and $\alpha_{a}$ is the normalization constant.

Hence, the statistical properties could be completely specified by the values of the additive integral of the motion, which replace the unimaginable multiplicity of the data which would be required in the approach from mechanics.

One specific form of the distribution function is $\rho = constant$ for all points in phase space which corresponds to given constant values of the energy, momentum and angular momentum and $\rho = 0$ at all other points.

$$ \rho = constnat \times \delta (E-E_{0}) \delta (P-P_{0}) \delta (M-M_{0}) $$

Also known as the _microcanonical ensemble_.

We could further make the assumption that the subsystem follows both translational and rotational invariant. So that the points in the phase space has no preference over the value of the momentum and angular momentum.

$$ \log_{\rho_{a}} = \alpha_{a} + \beta E_{a}(p, q)  $$

The microcanonical distribution for the whole system is

$$ \rho = constant \times \delta (E-E_{0}) $$

4. Partial equilibrium within the system and its parts

The above derivation is valid for the time duration long compared with the relaxation time. In some instances taking time shorter than the relaxation time is in practice needed. The above consideration would still valid under such consideration as long as the system size is large, owing to the existence of what called partial equilibria. Such equilibria occur because the relaxation time increaes with the szie of the system, and so the subsystem reaches the equilibrium state considerably more quickly than equilibrium is established between these small parts.

This means the distribution function follows the form we just derived, with different values of the parameters $\beta, \gamma, \delta$ for each subsystems. In such a case the system is said to be in _partial equilibrium_. In the course of tim , the partial equilibrium gradually becomes complete, and the parameters for each subsystem slowly vary and finally become equal throughout the closed system.

5. Partial equilibrium between different processes

Partial equilibrium also happens when different processes have different rate of occurance and relaxation time.

One example is the partial equilibrium in a mixture of several substances involved in a chemical reaction where the equilibration of the molecues will be reached faster than the equilibration of the chemical reaction.

Partial equilibrium of systems lead to the concept of _macroscopic states_ of a system, which defined by the mean value of quantities describing sufficiently small but macroscopic parts of the system.


#### The statistical matrix







<!-- 
## Fluid Mechanics

## Theory of Elasticity

## Electrodynamics of Continuous Media

## Statistical Mechanics Part II

## Physical Kinetics -->

