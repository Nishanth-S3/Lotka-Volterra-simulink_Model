# Lotka-Volterra-Model
Lotka-Volterra model is an example of Kolmogorov Model which is a more general framework that model the dynamics of ecological systems with prey-predator interactions, competition, disease, and mutualism.
Here, In this basic model one species is eating (or dependent on) the other. So, here one species is the resource for survival for the other species.
Assumptions - not all are realizable for the environment and evolution
of the predator and prey populations:

1. The prey population finds ample food at all times.
2. The food supply of the predator population depends entirely on the
size of the prey population.
3. The rate of change of population is proportional to its size.
4. During the process, the environment does not change in favour of
one species, and genetic adaptation is inconsequential.
5. Predators have limitless appetite.
Here, solution of ODE is deterministic & continuous It implies that the
generations of both predator and prey are continually overlapping.
System Equations:
i. dx/dt=αx-βxy
ii. dx/dt=δxy-γy
Prey are assumed to have an unlimited food supply, & reproduce exponentially, unless subject to predation; this exponential growth is represented by αx. The rate of predation upon the prey is assumed to be proportional to the rate at which the predators and the prey meet, this is represented above by βxy. If either x or y is zero, then no predation, both extincts. With these 2 terms the eqn. can be interpreted as follows: the rate of change of the prey's population is given by its own growth rate minus the rate at which it is preyed upon.
Here, δxy represents the growth of the predator population. Similarity is there to the predation rate; however, a different constant is used, as the rate at which the predator population grows is not necessarily equal to the rate at which it consumes the prey. γy represents the loss rate of the predators due to either natural death or emigration, it leads to an exponential decay in the absence of prey. Hence the equation expresses that the rate of change of the predator's population depends upon the rate at which it consumes prey, minus its intrinsic death rate.
the
parameters β/α and δ/γ are absorbable in the normalizations of y and x respectively.
γ is normalized function of t, only α/γ remains arbitrary. It is the only parameter affecting the nature of the solutions.
