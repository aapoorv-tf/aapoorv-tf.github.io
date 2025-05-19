---
layout: post
title:  "The Special Theory of Relativity"
excerpt: "Time is suspect"
date:   2025-04-30 11:00:00
mathjax: true
---

For over 200 years, Newton's laws were believed to be correct but in the early 20th Century, the error in these laws and their correction was discovered by Einstein. According to the Galilean relativity - laws of motion must be the same in all inertial frames of reference. This was used as the basis of Newtonian mechanics. Newton's laws were invariant to Galiliean transformation, for example imagine two frames of reference, one is at rest (Alice) and the other is moving with a constant velocity `v` (Bob)

To Bob the position of an event at point P is `(x, y)` and for Alice moving at velocity `v` the same event at time `t` is at position ``P`(x`, y`)``. Here $x', y', t'$ are the two coordinates and the time measured by Bob in the moving frame

<img src="/assets/imgs/galtransformation.png" style="max-width:70%; height:250px;">

If the origins of the frames concides at time t = 0, the galilean transformation for position is

- $x' = x - vt$ 
- $y' = y$
- $t' = t$ (Obviously, time is same for both the inertial frames)

To obtain the velocity transformation we can differentiate the position transformation w.r.t to time

- $dx'/dt' = dx/dt - v$ (since $t' = t$)
- $dy'/dt' = dy/dt$

In component form this would be $v' = u - v$ ($u$ is velocity observed by Bob of the object at point P in the rest frame). Now to obtain the acceleration we can differentiate again w.r.t to time

- $d^2x'/dt'^2 = d^2x/dt^2$  (since $t' = t$ and $v$ is constant)
- $d^2y'/dt'^2 = d^2y/dt^2$

In component form: $a' = a$. Multiply with the mass $m$ and we obtain the equation of forces, $ma' = ma$ or $F' = F$. Thus the laws of motion are the same in all inertial frames meaning that Newton's second law $F = ma$ is invariant to Galiliean tranformation and holds true for constant relative velocities. Remember these transformations assume that time is absolute and same for all observers.

In 1865, James Clerk Maxwell presented his electromagnetic theory which predicted a constant speed of light in vacuum, no matter the motion, regardless of the velocity, acceleration, etc. of the light source or the observer. How could it be? This did not obey the principle of relativity as the speed of electromagnetic waves derived from the Maxwell's equations is $c = $ $1 \over\sqrt(\mu_0 \epsilon_0)$, determined purely by $\mu_0$ (permeability) and $\epsilon_0$ (permittivity) in vacuum. This speed is fixed. There is no reference to any frame of motion. If we performed Galilean transformation to Maxwell's equations it won't preserve it's form as it did with Newton's laws of motion. This means Bob in his moving spaceship would observe different laws of electromagnetism as compared to Alice at rest, thus allowing Bob to detect absolute motion and breaking the principle of relativity

#### Events, Clocks and Observers