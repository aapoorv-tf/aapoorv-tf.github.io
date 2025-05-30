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
<img src="/assets/imgs/mmexp.png" style="max-width:60%; height:auto; display:block; margin:auto;">

This experiment was performed with an apparatus as shown above. It was mainly comprised of a light source $A$, two mirrors $C$ and $D$, and a half silvered mirror $B$, all mounted on a rigid base. The mirrors are placed at an equal distance $L$ from the silver plate. An oncoming beam of light would be split by the plate in two perpendicular directions to the mirrors, where they get reflected back to the plate and are finally recombined as a superposed beam. If the apparatus is at rest, the time taken by the two beams to go from the plate to their respective mirrors and back will be the same, but if it is moving at a constant velocity $v$, the times taken would differ. Let us see why.

#### From the Perspective of an Observer Moving with the Apparatus
This situation is similar to a boat moving upstream, downstream or perpendicular to the flow of the river. Replace the boat with a light beam, and the river with the aether wind moving with the relative velocity $v$. The light beam moving upstream (From $B$ to $D$) has its velocity reduced due to $c - v$, and when it bounces back from the mirror it moves downstream (From $D$ to $B$) with its velocity increased to $c + v$ (Moving medium affects the wave speed). The times taken would be $t_1 =$ $L \over{c - v}$ to arrive at the mirror $D$ and $t_2 =$ $L \over{c + v}$ to arrive back at the plate $B$. In the transverse direction, the light beam would be facing the wind in the perpendicular direction. To reach the mirror $C$ it needs to move at a certain angle such that due to the wind the effective velocity would be in the correct direction towards the mirror. Referring the below diagram it is easy to calculate this effective velocity using vector addition and the pythogoras theorem. $v_{actual} =$ $\sqrt{c^2 - v^2}$. The time taken to travel back and forth in the transverse direction would be $t_3 =$ $2L \over v_{actual}$

<img src="/assets/imgs/riveranal.png" style="max-width:40%; height:auto; display:block; margin:auto;">

#### From the Perspective of an Observer Resting in the Aether 
Let's say the time required by the light to go from $B$ to $D$ is $t_1$ and the time for the return is $t_2$. Now while the light is on its way to the mirror, the apparatus would have moved a distance $vt_1$, the mirror $D$ advances to $D'$. So the light has to traverse a distance of $L + vt_1$ at speed $c$. Therefore,

$$
ct_1 = L + vt_1 \quad \text{or} \quad t_1 = \frac{L}{c - v}
$$

Similarly, on it's way back to the plate, the apparatus would have moved a distance $vt_2$ and the plate advances to the position $B'$, so the return distance of the light is $L - vt_2$. Therefore,

$$
ct_2 = L - vt_2 \quad \text{or} \quad t_2 = \frac{L}{c + v}
$$

The total time from the plate to the mirror $D$ and back would be,

$$t_1 + t_2 = \frac{L}{c - v} + \frac{L}{c + v}$$

$$= \frac{2Lc}{c^2 - v^2}$$

$$= \frac{2L}{c(1 - \frac{v^2}{c^2})}$$

<img src="/assets/imgs/movedmmexp.png" style="max-width:60%; height:auto; display:block; margin:auto;">

Let's calculate for $t_3$ now. In this case light would be travelling along the hypotenuse of a triangle. From the diagram above it's evident the triangle is right angled. The mirror C would advance by $vt_3$ to the position $C'$, the distance travelled by light would be $ct_3$ along the hypotenuse and the distance between $B'$ and $C'$ would still be $L$. So, 

$$
c^{2}t_{3}^{2} = L^2 + v^{2}t_{3}^{2}
$$

$$
\implies t_{3}^{2} = \frac{L^2}{c^2 - v^2} \quad \text{or} \quad t_{3} = \frac{L}{\sqrt{c^2 - v^2}}
$$

$$
\implies t_{3} = \frac{L}{c\sqrt{1 - \frac{v^2}{c^2}}}
$$

From the symmetry of the diagram, we can conclude the time for the light to return to the plate would be exactly the same, $t_3$. Therefore in total, the time taken by light in the transverse direction is $2t_3 = \frac{2L}{c\sqrt{1 - \frac{v^2}{c^2}}}$ and in the longitudinal direction is $t_1 + t_2 = \frac{2L}{c(1 - \frac{v^2}{c^2})}$. Clearly, both these times are different, light would take longer to traverse the longitudinal direction. This time difference is exactly what Michelson and Morley were trying to detect in their experiment. However, the actual value of L was quite small around $11$ metres. Using the formula the difference ($t_1 + t_2 - 2t_3$) would be approximately $3.67 \times 10^{-16}$ seconds. There is no way back then one would be able to a measure a time difference this small. Michelson was a genius experimentalist, so instead of measuring the time difference he decided to measure the interference pattern of the superposed beam. Once both the beams arrive at the detector and there is no time difference then the beams would be in phase (the peaks and the troughs line up), resulting into a constructive interference. They used a sodium light which has a wavelength of $589$ nm and so the period ($wavelength\over c$) will be about $2 \times 10^{-15}$ s -- which is greater than the expected time difference. So if the lights are out of phase due to the time difference, we will observe an interference pattern. There is another minor technical issue, what if the lengths $BC$ and $BD$ are not exactly the same? For this, after the first measurement, they rotated the apparatus by $90^\circ$ and did the measurement again. This way if the lengths were not the same, we would anyway observe an interference pattern and upon rotating the apparatus ($BC$ is now $BD$ and $BD$ is now $BC$), if there was no time difference, the same interference pattern would be observed, otherwise the pattern would change. 

So finally, what was the result of this experiment? No time difference was found. The velocity of the Earth through the aether could not be detected. *The result was null*. This was very puzzling and disturbing so much so that it haunted Michelson for the rest of his life.
Physicists like Fitzgerald, Lorentz and Poincare tried coming up with explanations to this result while still involving aether. According to Lorentz, the length of the longitudinal arm (in the direction of the motion) contracts due to the properties of the aether and the factor by which it contracts compensates for the time light would take thus explaining the no time difference between both the directions. He derived a set of equations in a sophisticated manner, and came to be known as the Lorentz transformation equations. But this was very ad-hoc - the contraction of length came out of nowhere and was not satisfying. In 1905, Einstein, working as a patent clerk in the Swiss patent office, approached this from a completely different perspective. He did not involve aether and started with two assumptions-
- The laws of physics are the same in all inertial frames of reference, including that of electromagnetism
- THe speed of light is the constant $c$ for all moving observers, regardless of the motion of the source

The implications of these two simple postulates changed the way how we perceive the world and all it took was high-school level maths to realise-
> Time is Suspect

### The Dilation of Time
Let's take a light clock analogy, it consists of two mirrors and a light pulse, travelling at speed $c$, getting reflected between the two. Each cycle of the light starting from a mirror and returning back to it corresponds to one tick of a clock. Let's bring back Alice and Bob. Both of them have an identical light clock with the distance between the two mirros being $L$ and Bob starts moving with a constant velocity $v$ while Alice remains stationary and is observing Bob's clock. This situation is very similar to that of the transverse arm in the Michelson-Morley experiment.

In Alice's frame of reference, she would observe the light pulse on Bob's clock to take a diagonal path, at speed $c$. If the duration of one tick (One round trip of the light pulse) as observed by Alice on Bob's clock is $\Delta t_A$, the bottom mirror would have advanced by $v\Delta t_A$ and the light pulse would've travelled a distance $c\Delta t_A$. As evident from the diagram, 

$$\frac{c^{2}\Delta t_A^{2}}{4} = L^{2} + \frac{v^{2}\Delta t_A^{2}}{4}$$

$$ \implies \Delta t_A^{2} = \frac{4L^{2}}{c^2 - v^2} $$

$$ \implies \Delta t_A = \frac{2L}{\sqrt{c^2 - v^2}} $$

$$ \implies \Delta t_A = \frac{2L}{c\sqrt{1 - \frac{v^2}{c^2}}} $$

As far as Bob is concerned, his clock would seem to run normally. Remember the second postulate, speed of light is the same for all moving observers. So, the duration of one tick in his clock as observed by him would simply be $\Delta t_B = \frac{2L}{c}$ as he too, would observe the speed of the light pulse to be $c$. Therefore, the duration of one tick on Bob's clock as observed by Alice is $\Delta t_A$ and the duration of one tick on Bob's clock as observed by Bob is $\Delta t_B$, comparing both the durations, we get

$$ \frac{\Delta t_A}{\Delta t_B} = \frac{1}{\sqrt{1 - \frac{v^2}{c^2}}} \quad \text{or} \quad \Delta t_A = \frac{\Delta t_B}{\sqrt{1 - \frac{v^2}{c^2}}}$$

The factor $\frac{1}{\sqrt{1 - \frac{v^2}{c^2}}}$ is called the Lorentz factor and is denoted by $\gamma$

Thus, we can conclude that clocks run slower in a moving frame of reference as observed by a stationary observer, by a factor of $\gamma$. (To the observer in the moving frame, however, everything appears perfectly normal). As the duration of a tick on the moving clock increases, the time elapsed for a stationary observer would be greater.

