---
layout: post
title:  "The Special Theory of Relativity - Part 1"
excerpt: "Time is suspect"
date:   2025-04-30 11:00:00
mathjax: true
---

For over 200 years, Newton's laws were believed to be correct but in the early 20th Century, the error in these laws and their correction was discovered by Einstein. The physics you learnt in high school was slightly wrong or rather a good approximation of our physical reality. According to the Galilean relativity - laws of motion must be the same in all inertial frames of reference (frames that are at rest or moving with constant velocity, and not under any acceleration. *It is important to note that the Special Theory of relativity only applies to inertial frames of reference* and going forward, in this blog, by any frame of reference that I refer, will be inertial. For accelerated frames Einstein published a more general theory in 1915). Let's take two trains side by side, one at rest and the other is moving forward. Imagine yourself in the moving one and when you look outside the window it seems the other train is moving backward. Suddenly you are not sure is your train moving forward? Or is the other train moving backward? (Unless ofcourse you look at the ground, trees and all but let's ignore them). In your perspective (frame) you are not moving, you and your train are both at rest, try throwing a ball straight up and it would land back in your hand. The physics governing the motion of the ball is the same whether the train is moving or not. This is Galiliean relativity. From inside the train, there is no mechanical experiment (like dropping a ball or throwing it) you can perform that will tell you whaether your train is at rest or moving at constant velocity. Any experiment performed in a non-accelerating moving frame should yield the same result as when done in the rest frame thus showing laws of mechanics do not change between uniformly moving frames and that *you can't detect absolute motion - only relative motion*. This was used as the basis of Newtonian mechanics and the laws of motion were invariant to Galiliean transformation. For example, let's take two inertial reference frames, one is at rest (Alice) and the other is moving with a constant velocity $v$ (Bob)

To Alice the position of an event is at point $P(x, y)$ and for Bob moving at velocity $v$ the same event at time $t$ is at position $P'(x', y')$. This event could be anything like the motion of a ball of mass $m$ experiencing some force.

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
- **Speed of a wave remains unaffected for a moving source.** Let's consider a paddle device generating waves in water. If we start moving this paddle, the waves generated would only be closer to each other in the direction the device is moving and not increasing the wave speed. The actual molecules are not moving with the wave, they are just going up and down. It's the pattern that's moving. Therefore with a moving source the frequency increases. A real life example would be a train moving towards you at the station would have a higher pitch as the sound waves would compress (The speed of sound remains the same) and as it goes by, the sound waves will be more spaced out and the pitch becomes lower (Frequency decreases)
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

So finally, what was the result of this experiment? No time difference was found. The velocity of the Earth through the aether could not be detected! *The result was null*. This was very puzzling and disturbing so much so that it haunted Michelson for the rest of his life. An explanation was given that maybe somehow Earth dragged the aether along with it as it revolved around the Sun such that light at the surface will be unaffected. However, experiments like the Stellar Aberration argued against it. In the 1700s, the astronomer James Bradley observed that in order to observe a star using a telescope, it must be tilted at a slight angle to capture the light properly since the Earth is moving through space. If the aether is really being dragged along the surface, there would be no need for such tilt.

Physicists like Fitzgerald, Lorentz and Poincare tried coming up with explanations to the MM experiment's result while still involving aether. According to Lorentz, the length of the longitudinal arm (in the direction of the motion) contracts due to the properties of the aether and the factor by which it contracts compensates for the time light would take thus explaining the no time difference between both the directions. He derived a set of equations in a sophisticated manner, which came to be known as the Lorentz transformation equations. But this was very ad-hoc - the contraction of length came out of nowhere and was not satisfying. In 1905, Einstein, working as a patent clerk in the Swiss patent office, approached this from a completely different perspective. He did not involve aether and started with two assumptions-
- The laws of physics are the same in all inertial frames of reference, including that of electromagnetism
- THe speed of light is the constant $c$ for all moving observers, regardless of the motion of the source

The implications of these two simple postulates changed the way how we perceive the world and all it took was high-school level maths to realise-
> Time is Suspect

### The Dilation of Time
Let's take a light clock analogy, it consists of two mirrors and a light pulse, travelling at speed $c$, getting reflected between the two. Each cycle of the light starting from a mirror and returning back to it corresponds to one tick of a clock. Let's bring back Alice and Bob. Both of them have an identical light clock with the distance between the two mirros being $L$ and Bob starts moving with a constant velocity $v$ while Alice remains stationary and is observing Bob's clock. This situation is very similar to that of the transverse arm in the Michelson-Morley experiment.

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">

  <figure style="flex: 1; min-width: 200px; text-align: center;">
    <img src="/assets/imgs/lightclockbob.png" style="max-width:40%; height:auto;">
    <figcaption>Bob's Light Clock in his Frame</figcaption>
  </figure>

  <figure style="flex: 1; min-width: 200px; text-align: center;">
    <img src="/assets/imgs/lightclockalice.png" style="max-width:95%; height:auto;">
    <figcaption>Bob's Light Clock in Alice's Frame</figcaption>
  </figure>

</div>


In Alice's frame of reference, she would observe the light pulse on Bob's clock to take a diagonal path, at speed $c$. If the duration of one tick (One round trip of the light pulse) as observed by Alice on Bob's clock is $\Delta t_A$, the bottom mirror would have advanced by $v\Delta t_A$ and the light pulse would've travelled a distance $c\Delta t_A$. As evident from the diagram, 

$$\frac{c^{2}\Delta t_A^{2}}{4} = L^{2} + \frac{v^{2}\Delta t_A^{2}}{4}$$

$$ \implies \Delta t_A^{2} = \frac{4L^{2}}{c^2 - v^2} \quad \text{or} \quad \Delta t_A = \frac{2L}{\sqrt{c^2 - v^2}}$$

$$ \implies \Delta t_A = \frac{2L}{c\sqrt{1 - \frac{v^2}{c^2}}} $$

As far as Bob is concerned, his clock would seem to run normally. Remember the second postulate, speed of light is the same for all moving observers. So, the duration of one tick in his clock as observed by him would simply be $\Delta t_B = \frac{2L}{c}$ as he too, would observe the speed of the light pulse to be $c$. Therefore, the duration of one tick on Bob's clock as observed by Alice is $\Delta t_A$ and the duration of one tick on Bob's clock as observed by Bob is $\Delta t_B$, comparing both the durations, we get

$$ \frac{\Delta t_A}{\Delta t_B} = \frac{1}{\sqrt{1 - \frac{v^2}{c^2}}} \quad \text{or} \quad \Delta t_A = \frac{\Delta t_B}{\sqrt{1 - \frac{v^2}{c^2}}}$$

The factor $\frac{1}{\sqrt{1 - \frac{v^2}{c^2}}}$ is called the Lorentz factor and is denoted by $\gamma$

Thus, we can conclude that clocks run slower in a moving frame of reference as observed by a stationary observer, by a factor of $\gamma$. (To the observer in the moving frame, however, everything appears perfectly normal). As the duration of a tick on the moving clock increases, the time elapsed for a stationary observer would be greater. One might ask that in bob's frame of reference, it's Alice who is moving, so would her clock appear to move slowly to Bob? Yes, absolutely. It goes both ways since motion is relative. This can lead to paradoxes, which technically aren't since there is another implication due to the constancy of the speed of light which I will explain later.
Time dilation is not only true for light clocks but for normal analog/digital clocks, or any other clock operating on whatsoever principle at all. Suppose we have both light clock as well as a normal clock with wheels and gears and we synchronise them both -- when the light pulse in the light clock goes up and back, the normal clock has ticked as well. Then we take both these clocks on the spaceship with Bob. If time dilation only worked for our light clock and not for the normal one, Bob would immediately notice this discrepancy and be able to detect his absolute motion using the mismatch between the clocks! That goes against principle of relativity. Now if all moving clocks run slower, we have to say that time itself appears to be slower in moving frame of reference. All the phenomena - Bob's heart rate, his thought process, all biological processes in his body would slow down by the same proportion to an observer in the rest frame.
Why do we not see the effect of time dilation in day to day life? Everyday velocities are significantly slower than the speed of light and so the term $\frac{v}{c}$ is approximately $0$ (We're also squaring this value) due to which the Lorentz factor is almost equal to 1 and any effect is negligible.

### Length Contraction

<figure style="text-align: center;">
  <img src="/assets/imgs/lengthcont1.png" style="max-width:60%; height:auto;">
  <figcaption style="font-size: 0.9em; color: #555;">Spaceship's left end is aligned with Alice. Both their clocks read 0</figcaption>
</figure>
<figure style="text-align: center;">
  <img src="/assets/imgs/lengthcont2.png" style="max-width:60%; height:auto;">
  <figcaption style="font-size: 0.9em; color: #555;">Spaceship's right end is aligned with Alice</figcaption>
</figure>

Imagine Bob in a spaceship of length $L_B$ moving with velocity $v$ towards left. Alice, as usual, is a stationary observer along with her clock. Now, in Bob's frame of reference, he would notice Alice moving towards right with velocity $v$. In the beginning, the left end of Bob's spaceship was aligned with Alice and after time $t_{B} = \frac{L_B}{v}$, the right end of the spaceship has reached Alice. As far as Bob's concerned it's Alice who has travelled from the left end to the right end of the spaceship and the time elapsed on her clock as observed by Bob would be $t_{A} = \frac{t_{B}}{\gamma}$, therefore the distance Alice travelled is $vt_{A} = v\frac{t_{B}}{\gamma}$ or $L_{A} = \frac{L_{B}}{\gamma}$. Hence, the length observed by Alice for Bob's spaceship is $\frac{L_{B}}{\gamma}$. More generally, $L_{B}$ is the proper length, i.e, the distance measured by an observer in their own frame of reference, in this case, Bob would measure his spaceship's length, which is at rest in his frame, to be $L_{B}$, while to an outside observer, Alice, this length would appear to be contracted by a factor of $\gamma$. 

$$L_{moving} = \frac{L_{rest}}{\gamma}$$

#### Do other dimensions contract as well?
No, only the length in the direction of the motion contracts. Width and height remain unaffected otherwise we will end up with paradoxes for example- Imagine yourself in a moving train that is about to enter a tunnel having the same height as that of your train. If height were to get contracted, then in your frame, the tunnel would be appear to be shorter and you will start panicking that you're about cram right into it! However, for an outside observer at rest, it is your train that would appear to be shorter and should easily fit into the tunnel. Both these situations cannot be true at the same time and for this contradiction, we can conclude that dimensions in the perpendicular direction won't get contracted. By symmetry, this can be extended to the width as well, or you can take the same train example and this time, it's the railway tracks that are contracted for an observer inside the train, while to an outside the observer, the train's width contracts leading to the train going off rail.

#### The Invariant Interval
We have proved that the transverse dimensions are not suspects. They don't get contracted or expanded, the dimension in the direction of motion does. Let's setup the same situation as in the light clock analogy, but also bring in the third friend Kris travelling at 3 times the velocity of Bob. All of them are observing Bob's light clock and the height $h$ (distance between the mirrors) would be appear to be the same in all frames of reference. Using simple pythogorean theorem, we can get the relation between $h$, $t$ and $x$. This comes out to be, assuming $t_B$, $t_A$ and $t_K$ times have elapsed for Bob, Alice and Kris respectively.

$$4h^2 = c^{2}t_B^{2} - 0$$

$$4h^2 = c^{2}t_A^{2} - x_A^2$$

$$4h^2 = c^{2}t_K^{2} - x_K^2$$

Comparing these equations, we can see that the value $c^2t^2 - x^2$ remains constant in the all the frames of reference. It's invariant and is denoted as $\Delta s^2$. This can be extended to all the dimensions of the space, giving us a more general form

$$\Delta s^2 = c^2\Delta t^2 - (\Delta x^2 + \Delta y^2 + \Delta z^2)$$


### The Relativity of Simultaneity
In the 19th century when the railroads were expanding, a good time keeping system was required so that every city had more or less the same time and the clocks between various stations are synchronised. There were a lot of patents and inventions for this problem that people submitted at places like the Swiss patent office where Einstein was working. He was getting a lot of this and probably one of the reasons that led to his key insight in developing the special theory of relativity. So how do we synchronise the clocks? Consider two railway stations, one of them is on the left of the main station and the other is on the right of the main station. Assuming the tracks between them are straight and the ground is level. One way is to bring all the clocks together, set the exact same time and move them to their respective stations. But now we know that moving the clocks is out of the question as it would lead to time dilation. Instead, we can let the clocks be at their respective stations and from the main station emit a laser beam in both the directions. Once these beams hit the clocks at the outlying stations, they start ticking. Ofcourse there would be a lag due to the time taken by the light to reach the clocks, so to adjust for this delay we can set the clocks ahead by that time and as they start ticking, the clock at our main station would be reading the same time. Using this method we can synchronise multiple clocks in a straight line. For the purposes of our thought experiments, we will assume in a frame of reference there are infinite number of point clocks at each coordinate in three-dimensional space, together forming *a lattice or a grid of clocks*. As soon as an event occurs at a position, the clock at that coordinate will take a photograph (It's a very sophisticated clock), That photo will have a reading for when an event occurs and at what position. Basically using this set up, any event can be recorded using a set of 4 values $(x,y,z,t)$ - The 3 space coordinates and 1 time coordinate.

Now that we know how to sychronise our clocks, let's start with another thought experiment with Alice and Bob. As usual Bob will be in his spaceship moving at a constant velocity $v$ with Alice as a stationary observer. At both ends of his spaceship of length $L_{B}$ (Proper length) he has two synchronised clocks. The question is, will those clocks be synchronised in Alice's frame of reference as well? We will take two cases to understand this qualitatively.  
- **Case 1:** At the center of Bob's spaceship there is a gun which shoots paintball in both the directions at speed $u$. As far as Bob's concerned, both the paintballs will travel at the same speed and arrive at the either ends of his ship at the same time. When observed by Alice, the speed of the paintball moving towards left will be $v - u$, but the left end of Bob's ship is also moving towards the ball at speed $v$. Similarly, the rightward moving ball will travel at speed $v + u$ as the right end of the ship moves away from it at speed $v$. So effectively, both the balls arrive at the ends at the same time. 

<figure style="text-align: center;">
  <img src="/assets/imgs/paintballsimul.png" style="max-width:70%; height:auto;">
  <figcaption style="font-size: 0.9em; color: #555;">Case 1 with paintballs</figcaption>
</figure>
<figure style="text-align: center;">
  <img src="/assets/imgs/lightpulsesimul.png" style="max-width:70%; height:auto;">
  <figcaption style="font-size: 0.9em; color: #555;">Case 2 with light pulses</figcaption>
</figure>

- **Case 2:** Now let's replace the paintball with a light pulse. In Bob's frame, the speed of light is $c$, so both the pulses arrive at the clocks at the same time and when they do, a flash of light is emitted. In Alice's frame as well the speed of both the light pulses is $c$ (**Not** $c + v$ or $c - v$. Remember the second postulate). However, as the left end of the ship is approaching the left pulse, it arrives first and the right end is moving away from the right pulse, it arrives at a later time. Therefore, events that were synchronised in Bob's frame of reference are not in sync in Alice's frame of reference -- flashes of light would occur simulataneously for Bob, but not for Alice. We can conclude that clocks in a moving frame of reference are *not* synchronised from the perspective of a stationary observer OR events simultaneous in one frame are not simultaneous in another frame.

> Leading clocks lag

Having said that, let's calculate by how much does a leading clock lag by. Alice and Bob both have their lattice of synchronised clocks arranged. Synchronised ofcourse in their owns frames of reference. Initially, the leftmost clock in both Bob and Alice's frame are aligned and reading 0. Some amount of time $t_{A1}$ later for Alice, she observes the left pulse has reached the leftmost clock in the spaceship. The left end of the ship would have advanced by $vt_{A1}$ and the actual distance travelled by the pulse would be $L_{A} - vt_{A1}$ or $ct_{A1}$, where $L_{A}$ is the length of the ship measured by her. Therefore, $t_{A1} = \frac{L_{A}}{2(c + v)}$. Later at time $t_{A2}$ she observes the right pulse has arrived at the rightmost clock in the spaceship. This time can be calculated similarly by keeping in mind that the right end of the ship has moved away by $vt_{A2}$ and hence more distance required by this pulse to traverse. $t_{A2} = \frac{L_{A}}{2(c - v)}$. The difference in time or the time elapsed between both the events for Alice is 

$$\Delta t_A = t_{A2} - t_{A1}$$

$$\implies \Delta t_A = \frac{L_{A}}{2(c - v)} - \frac{L_{A}}{2(c + v)}$$

$$\implies \Delta t_A = \frac{2vL_{A}}{2(c^{2} - v^{2})}$$

$$\implies \Delta t_A = \frac{vL_{A}}{c^{2}(1 - \frac{v^{2}}{c^{2}})}$$

where $\frac{1}{(1 - \frac{v^{2}}{c^{2}})}$ is just $\gamma^{2}$

$$\implies \Delta t_A = \frac{vL_{A}\gamma^2}{c^{2}}$$

The time elapsed in Bob's lattice of clocks as measured by Alice is $\Delta t_{B} = \frac{\Delta t_{A}}{\gamma}$

$$\Delta t_{B} = \frac{vL_{A}\gamma}{c^{2}}$$

And we also know that the length measured by Alice is contracted, so $L_A = \frac{L_B}{\gamma}$. Therefore,

$$\Delta t_{B} = \frac{vL_{B}}{c^{2}}$$

This is the amount by which the front clock would lag by. In a more general sense, a clock at distance $D$ in the moving frame, in the direction of motion, would be behind by $\frac{vD}{c^2}$. Ofcourse if you are in the moving frame, all your clocks would tick at the same rate and show the same time. It is important to note that all this weirdness is from the perspective of an outside observer while everything looks normal to the observer in the moving frame of reference otherwise they would be able to detect absolute motion, their own velocity.
As for the amount calculated above, let's try to understand why should it be the lag value. When both the flashes of light occur, all of Bob's clock are reading the exact same time, say $t_B$ and he also has photographic evidences of those events which would have been recorded by the respective clocks at the position of the event. For Alice, the first flash of light occurs at $t_{A1}$, she too, has a photographic evidence for the same recorded by her clock at the position of that event, and it will have the readings for both her clock and Bob's clock at that position. Now, these pictures shouldn't contradict with each other. The photos that Bob has shows the time on his leftmost clock and the rightmost clock to be $t_B$. The photo Alice has, should also show the time on Bob's clock when the first flash occured, i.e, the leftmost clock, to be $t_B$ and her clock to read $t_{A1}$. This means, since the second flash has not yet occured for her, Bob's rightmost clock should be behind in time in her perspective! If the next flash occurs after $\Delta t_A$ time has elapsed for Alice (already calculated above), then as observed by her, Bob's rightmost clock should be reading $t_{B} - \frac{\Delta t_{A}}{\gamma}$. Dividing by $\gamma$ because of time dilation -- the rate at which Bob's clocks are ticking is slowed down. When the second flash finally occurs for her, $\frac{\Delta t_{A}}{\gamma}$ time would have elapsed on Bob's clocks and the rightmost clock would ultimately be reading $t_B$, which matches with the photo taken by that clock when the flash occured. It all fits together.

### Lorentz Transformation


### A Real Life Example
The muon is one of the fundamental subatomic particles and is similar to electrons but weighs 207 times more. They have a lifespan of about 2.2 microseconds and are created naturally when cosmic rays from outerspace hit atoms in the atmosphere at an altitude of 10 km, resulting into a spray of particles which include muons that travel with an average velocity of 0.998c. So according to the calculations, these muons should only be able to travel $0.998c \times 2.2 \times 10^{-6} \approx 660$ metres. However, at the surface of the earth we still observe a lot of these muons. The reason ofcourse is the effects due to time dilation and length contraction. From the perspective of an observer on earth, muon's internal clock would be running slowly by a factor of $\gamma = \frac{1}{\sqrt{1 - \frac{v^2}{c^2}}}$. Plug in the value of $v = 0.998c$, we get 15.81 and hence the muon will be able to travel a distance of $15.81 \times 660 \approx 10000$ metres. Now, from the perspective of the muon, the distance to the surface is contracted by that same factor, so it only has to travel a distance of $10000 / 15.81 \approx 630$ metres to reach the surface! This real life observation proves the correctness of the special theory of relativity.

In the next part I would like to cover some paradoxes, like the Twins paradox and Pole in the barn paradox. Also some of the implications of relativity and maybe even derive the famous equation which was an after-thought by Einstein to his theory.