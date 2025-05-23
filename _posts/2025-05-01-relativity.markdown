---
layout: post
title:  "The Special Theory of Relativity"
excerpt: "Time is suspect"
date:   2025-04-30 11:00:00
mathjax: true
---

For over 200 years, Newton's laws were believed to be correct but in the early 20th Century, the error in these laws and their correction was discovered by Einstein. The physics you learnt in high school was slightly wrong or rather a good approximation of our physical reality. According to the Galilean relativity - laws of motion must be the same in all inertial frames of reference (frames that are at rest or moving with constant velocity, and not under any acceleration). Let's take two trains side by side, one at rest and the other is moving forward. Imagine yourself in the moving one and when you look outside the window it seems the other train is moving backward. Suddenly you are not sure is your train moving forward? Or is the other train moving backward? (Unless ofcourse you look at the ground, trees and all but let's ignore them). In your perspective (frame) you are not moving, you and your train are both at rest, try throwing a ball straight up and it would land back in your hand. The physics governing the motion of the ball is the same whaether the train is moving or not. This is Galiliean relativity. From inside the train, there is no mechanical experiment (like dropping a ball or throwing it) you can perform that will tell you whaether your train is at rest or moving at constant velocity. Any experiment performed in a non-accelerating moving frame should yield the same result as when done in the rest frame thus showing laws of mechanics do not change between uniformly moving frames and that *you can't detect absolute motion - only relative motion*. This was used as the basis of Newtonian mechanics and the laws of motion were invariant to Galiliean transformation. For example, let's take two inertial reference frames, one is at rest (Alice) and the other is moving with a constant velocity $v$ (Bob)

To Alice the position of an event at point P is $(x, y)$ and for Bob moving at velocity $v$ the same event at time $t$ is at position $P'(x', y')$. 

<img src="/assets/imgs/galtransformation.png" style="max-width:100%; height:auto; display:block; margin:auto;">


If the origins of the frames concides at time t = 0, the galilean transformation for position is (Here $x', y', t'$ are the two coordinates and the time measured by Bob in the moving frame)

- $x' = x - vt$ 
- $y' = y$
- $t' = t$ (Time is same for both the inertial frames)

To obtain the velocity transformation we can differentiate the position transformation w.r.t to time

- $dx'/dt' = dx/dt - v$ (since $t' = t$)
- $dy'/dt' = dy/dt$

In component form this would be $v' = u - v$ ($u$ is the velocity observed by Alice of the object at point P in the rest frame). Now to obtain the acceleration we can differentiate again w.r.t to time

- $d^2x'/dt'^2 = d^2x/dt^2$  (since $t' = t$ and $v$ is constant)
- $d^2y'/dt'^2 = d^2y/dt^2$

In component form: $a' = a$. Multiply with the mass $m$ and we obtain the equation of forces, $ma' = ma$ or $F' = F$. Thus the laws of motion are the same in all inertial frames meaning that Newton's second law $F = ma$ is invariant to Galiliean tranformation and holds true for constant relative velocities. Remember these transformations assume that time is absolute and same for all observers.

In 1865, James Clerk Maxwell presented his electromagnetic theory which predicted a constant speed of light in vacuum, no matter the motion, regardless of the velocity, acceleration, etc. of the light source or the observer. This did not seem to obey the velocity transformation rule as we derived above for Galilean relativity as the speed of electromagnetic waves derived from the Maxwell's equations is $c = $ $1 \over\sqrt(\mu_0 \epsilon_0)$, determined purely by $\mu_0$ (permeability) and $\epsilon_0$ (permittivity) in vacuum. This speed is fixed. There is no reference to any frame of motion and it created a contradiction - If Galilean transformation was universally true then in a frame moving at a relative velocity $v$, an observer should measure the speed of light to be $c \pm v$ (depending on the direction of motion) and if Maxwell's equations held true for all intertial frames, then the speed of light should be measured as the same constant $c$ in all inertial frames. By the early 19th century, light was well understood as a wave (not a particle, yet). And all known waves (sound waves, water waves, etc.) required a medium to propagate through, so physicists proposed a luminoferous aether which was thought to be an invisible substance filling all space and it carried light waves. It was assumed that the Maxwell's theory is incomplete and worked only for a preferred absolute rest frame which was the aether and light moved at speed $c$ relative only to it and for an inertially moving observer we can apply galilean transformation to get the speed of light in that frame. You might think that introducing this absolute aether frame for electromagnetism still goes against the notion of galiliean relativity that all inertial frames are equivalent- yes you're right about that, this had become a rather uncomfortable situation for physicists in the late 19th century. There was a major theoretical inconsistency. Physics was fractured, until Einstein came in clutch. Before we get into it, let's look at some key facts about waves in a medium.
- **Speed of a wave depends on the properties of the medium.** (A sound wave would travel faster in a denser medium)
- **Speed of a wave remains unaffected for a moving source.** Let's consider a paddle device generating waves in water. If we start moving this paddle, the waves generated would only be closer to each other in the direction the device is moving and not increasing the wave speed. The actual molecules are not moving with the wave, they are just going up and down. It's the pattern that's moving. Therefore with a moving source the frequency increases. A real life example would be a train moving towards you at the station would have a higher pitch (The speed of sound remains the same) and as it goes by the pitch becomes lower (Frequency decreases)
- **Speed of a wave changes with a moving medium.** If the molecules themselves are moving, it adds to the speed at which the disturbance is propogating (Speed of the medium $\pm$ Speed of wave)

Given that for a moving medium we observe a change in the speed of the wave, then the same must be true for light waves. For a moving observer, the aether medium would be in relative motion and observe a change in the speed of light. Multiple attempts were made to detect Earth's motion through this hypothetical aether. The most famous was the one proposed by Michelson and Morley in 1887.

### The Michelson-Morley Experiment
This experiment was performed with an apparatus as shown above. It was mainly comprised of a light source, two mirrors and a half silvered mirror, all mounted on a rigid base. The mirrors are placed at an equal distance from the silver plate. An oncoming beam of light would be split by the plate in two perpendicular directions to the mirrors, where they get reflected back to the plate and are finally recombined as a superposed beam. If the apparatus is at rest, the time taken by the two beams to go from the plate to their respective mirrors and back will be the same, but if it is moving at a constant velocity $v$, the times taken would differ. Let us see why --

#### From the Perspective of an Observer Moving with the Apparatus
This situation is similar to a boat moving upstream, downstream or perpendicular to the flow of the river. Replace the boat with a light beam, and the river with the aether wind. The light beam moving upstream has its velocity reduced due to $c - v$, and when it bounces back from the mirror it moves downstream with its velocity increased to $c + v$ (Moving medium affects the wave speed). The times taken would be $T_1 =$ $L \over (c - v)$ to arrive at the mirror and $T_2 =$ $L \over (c + v)$ to arrive back at the plate. In the transverse direction, the light beam would be facing the wind in the perpendicular direction. To reach the mirror it needs to move at a certain angle such that due to the wind the effective velocity would be in the correct direction towards the mirror. Referring the below diagram it is easy to calculate this effective velocity using vector addition and the pythogaras theorem. $v_a =$ $\sqrt(c^2 - v)$. The time taken to travel back and forth in the transverse direction would be $T_3 =$ $2L \over v_a$

#### From the Perspective of an Observer Resting in the Aether 


