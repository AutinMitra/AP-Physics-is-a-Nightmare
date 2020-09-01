# Chapter 2: Motion Along a Straight Line

*Oh boy real math, at least it's easy enough. insert speed pun*

## 2.1: Position, Displacement, and Average Velocity
### Motion
- **kinematics**: The classification and comparison of motions
- Three general properties of motion restrictions
	- Motion must be on a straight line
		- Vertical, horizontal, or slanted, as long as it's straight
	- Forces cause motion
		- We won't talk about this right now, but we'll see more about this in chapter 5
	- Moving objects moves like a **particle**, or moves like one
		- **Particle**: Point-like objects (like electron), moves in same direction at the same rate
### Position and Displacement
- Objects location depends on a reference points
	- Usually the **origin**
- **Positive direction** of an axis is the direction where numbers increase
	- **Negative direction** is the opposite (duh)
- A change from positions is **displacement**
	
	- Displacement from two x positions: <a href="https://www.codecogs.com/eqnedit.php?latex=\Delta&space;x&space;=&space;x_{2}&space;-&space;x_{1}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\Delta&space;x&space;=&space;x_{2}&space;-&space;x_{1}" title="\Delta x = x_{2} - x_{1}" /></a>
- Displacement is a **vector quantity**
	- A quantity which has both direction and magnitude

### Average Velocity and Average Speed
- Multiple quantities can refer to "how fast" something is in a direction (vector quantity)
- **Average Velocity <a href="https://www.codecogs.com/eqnedit.php?latex=v_{avg}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?v_{avg}" title="v_{avg}" /></a>**
	- <a href="https://www.codecogs.com/eqnedit.php?latex=v_{avg}&space;=&space;\frac{\Delta&space;x}{\Delta&space;t}&space;=&space;\frac{x_{2}-x_{1}}{t_{2}&space;-&space;t_{1}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?v_{avg}&space;=&space;\frac{\Delta&space;x}{\Delta&space;t}&space;=&space;\frac{x_{2}-x_{1}}{t_{2}&space;-&space;t_{1}}" title="v_{avg} = \frac{\Delta x}{\Delta t} = \frac{x_{2}-x_{1}}{t_{2} - t_{1}}" /></a>
	- Ratio of displacement of *Δx* over an interval of time *Δt*
	- Common unit is meters per second
	- On a graph,  v_avg is the slope of the line connecting two points (duh)
	- v_avg will always have the same sign as Δx because Δt is always positive
- **Average Speed** <a href="https://www.codecogs.com/eqnedit.php?latex=s_{avg}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?s_{avg}" title="s_{avg}" /></a>
	- Includes total distance covered independent of direction (scalar quantity)
	- <a href="https://www.codecogs.com/eqnedit.php?latex=s_{avg}&space;=&space;\frac{total&space;distance}{\Delta&space;t}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?s_{avg}&space;=&space;\frac{total&space;distance}{\Delta&space;t}" title="s_{avg} = \frac{total distance}{\Delta t}" /></a>

## 2.2: Instantaneous Velocity and Speed
### Instantaneous Velocity and Speed
- We've seen how **average speed** and **average velocity** refer to "how fast"
- However, "how fast" most of the time refers to **instantaneous velocity**
	- The velocity at a given points at time
	- We can obtain this by shrinking the time interval (Δt) to 0, and as a result the average velocity will approach the limit: the velocity at that instant
	- <a href="https://www.codecogs.com/eqnedit.php?latex=v&space;=&space;\lim_{t&space;\to&space;0}&space;\frac{\Delta&space;x}{\Delta&space;t}&space;=&space;\frac{dx}{dt}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?v&space;=&space;\lim_{t&space;\to&space;0}&space;\frac{\Delta&space;x}{\Delta&space;t}&space;=&space;\frac{dx}{dt}" title="v = \lim_{t \to 0} \frac{\Delta x}{\Delta t} = \frac{dx}{dt}" /></a>
- **Speed** is the magnitude of velocity
	- Basically velocity stripped of direction
	- +5 m/s and  -5 m\s in velocity are both 5 m/s in speed
## 2.3: Acceleration
### Acceleration
- When a velocity of a particle changes, the particle **accelerates**
- Average Acceleration (<a href="https://www.codecogs.com/eqnedit.php?latex=a_{avg}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?a_{avg}" title="a_{avg}" /></a>)
	- <a href="https://www.codecogs.com/eqnedit.php?latex=a_{avg}&space;=&space;\frac{v_{2}-v_{1}}{t_{2}&space;-&space;t_{1}}&space;=&space;\frac{\Delta&space;v}{\Delta&space;t}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?a_{avg}&space;=&space;\frac{v_{2}-v_{1}}{t_{2}&space;-&space;t_{1}}&space;=&space;\frac{\Delta&space;v}{\Delta&space;t}" title="a_{avg} = \frac{v_{2}-v_{1}}{t_{2} - t_{1}} = \frac{\Delta v}{\Delta t}" /></a>
	- In layman term, it's the change of velocity in a certain time period
- Instantaneous Acceleration
	- <a href="https://www.codecogs.com/eqnedit.php?latex=a&space;=&space;\frac{dv}{dt}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?a&space;=&space;\frac{dv}{dt}" title="a = \frac{dv}{dt}" /></a>
	- Graphically, acceleration is the slope of any point on v(t) (velocity vs time) 
		- <a href="https://www.codecogs.com/eqnedit.php?latex=a&space;=&space;\frac{dv}{dt}&space;=&space;\frac{d}{dt}(\frac{dx}{dt})=\frac{d^2x}{dt^2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?a&space;=&space;\frac{dv}{dt}&space;=&space;\frac{d}{dt}(\frac{dx}{dt})=\frac{d^2x}{dt^2}" title="a = \frac{dv}{dt} = \frac{d}{dt}(\frac{dx}{dt})=\frac{d^2x}{dt^2}" /></a>
		- Second derivative of position x(t) in respect to time
- Acceleration is usually described in terms of m\s²
- Large accelerations are expressed in terms of *g* units, or 9.8 m/s²
	- *g* being the magnitude of the acceleration of something falling newar earth's surface
- **Signs** of acceleration
	- Positive means the object's speed is increasing, negative is the opposite

## 2.4: Constant Acceleration
### Constant Acceleration: A special case
- Acceleration can be constant (or approximately so) in many cases
	- Such as accelerating a car at a constant rate
- There's a couple of equations to deal with constant acceleration
- **First basic equation**
	- Our **first basic equation** is <a href="https://www.codecogs.com/eqnedit.php?latex=v&space;=&space;v_{0}&space;&plus;&space;at" target="_blank"><img src="https://latex.codecogs.com/gif.latex?v&space;=&space;v_{0}&space;&plus;&space;at" title="v = v_{0} + at" /></a>
	- Taken from <a href="https://www.codecogs.com/eqnedit.php?latex=a&space;=&space;a_{avg}&space;=&space;\frac{v-v_{0}}{t-0}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?a&space;=&space;a_{avg}&space;=&space;\frac{v-v_{0}}{t-0}" title="a = a_{avg} = \frac{v-v_{0}}{t-0}" /></a>, solved in terms of v (since average acceleration and instantaneous acceleration are the same when acceleration is constant)
- **Second basic equation**
	- Taking <a href="https://www.codecogs.com/eqnedit.php?latex=v_{avg}&space;=&space;\frac{x-x_{0}}{t-0}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?v_{avg}&space;=&space;\frac{x-x_{0}}{t-0}" title="v_{avg} = \frac{x-x_{0}}{t-0}" /></a>, and distributing it to: <a href="https://www.codecogs.com/eqnedit.php?latex=x&space;=&space;x_{0}&space;&plus;&space;v_{avg}t" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x&space;=&space;x_{0}&space;&plus;&space;v_{avg}t" title="x = x_{0} + v_{avg}t" /></a>
	- The average velocity from time 0 to time t, will be <a href="https://www.codecogs.com/eqnedit.php?latex=v_{avg}&space;=&space;\frac{1}{2}(v_{0}&space;&plus;&space;v)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?v_{avg}&space;=&space;\frac{1}{2}(v_{0}&space;&plus;&space;v)" title="v_{avg} = \frac{1}{2}(v_{0} + v)" /></a>
	- Substituting this equation's *v* with the first basic equation's *v* will result in <a href="https://www.codecogs.com/eqnedit.php?latex=v_{avg}&space;=&space;v_{0}&space;&plus;&space;\frac{1}{2}at^2" target="_blank"><img src="https://latex.codecogs.com/gif.latex?v_{avg}&space;=&space;v_{0}&space;&plus;&space;\frac{1}{2}at^2" title="v_{avg} = v_{0} + \frac{1}{2}at^2" /></a>
	- Substituting that into <a href="https://www.codecogs.com/eqnedit.php?latex=x&space;=&space;x_{0}&space;&plus;&space;v_{avg}t" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x&space;=&space;x_{0}&space;&plus;&space;v_{avg}t" title="x = x_{0} + v_{avg}t" /></a> will result in our **second basic equation**: <a href="https://www.codecogs.com/eqnedit.php?latex=x&space;-&space;x_{0}&space;=&space;v_{0}t&space;&plus;&space;\frac{1}{2}at^2" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x&space;-&space;x_{0}&space;=&space;v_{0}t&space;&plus;&space;\frac{1}{2}at^2" title="x - x_{0} = v_{0}t + \frac{1}{2}at^2" /></a>
- **Three Other Equations**
	- The first and second basic equations can be used to derive more equations that may be helpful in certain situations
	- Five quantities can be involved in constant acceleration problems (x - x_0, v, t, a, v_0)
	- Each of the basic equations only include four of these five (second missing *v*, first missing *x - x_0*
	- We can combine the equations in three ways to yield three equations, each having a different variable
	- <a href="https://www.codecogs.com/eqnedit.php?latex=v^2&space;=&space;v_{0}^2&space;&plus;&space;2a(x-x_{0})" target="_blank"><img src="https://latex.codecogs.com/gif.latex?v^2&space;=&space;v_{0}^2&space;&plus;&space;2a(x-x_{0})" title="v^2 = v_{0}^2 + 2a(x-x_{0})" /></a>
		- Useful if we don't know *t* and are not required to find *t*
	- <a href="https://www.codecogs.com/eqnedit.php?latex=x&space;-&space;x_{0}&space;=&space;\frac{1}{2}(v_{0}&space;&plus;&space;v)t" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x&space;-&space;x_{0}&space;=&space;\frac{1}{2}(v_{0}&space;&plus;&space;v)t" title="x - x_{0} = \frac{1}{2}(v_{0} + v)t" /></a>
		- Eliminates acceleration
	- <a href="https://www.codecogs.com/eqnedit.php?latex=x&space;-&space;x_{0}&space;=&space;vt&space;-&space;\frac{1}{2}at^2" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x&space;-&space;x_{0}&space;=&space;vt&space;-&space;\frac{1}{2}at^2" title="x - x_{0} = vt - \frac{1}{2}at^2" /></a>
		- Eliminates v_0
		- Difference between the second basic equation and this is that this involves the initial velocity, the other involves velocity at time t

## 2.5: Free-Fall Acceleration
### Free-Fall Acceleration
- If the effect of air is removed from a falling objects, an objects would accelerate down at a constant rate
	- This rate is called the **free-fall acceleration**
	- Usually represented by *g*
- In free-fall, motion direction is applied to the *y* axis, and is always negative since the motion is towards the earth's center
- Free-fall acceleration near Earth's surface is a = -g = -9.8 m/s², while the magnitude of the acceleration is 9.8 m/s²
## 2.6: Graphical Integration in Motion Analysis
-  On a graph of acceleration *a* versus time *t*, the change in velocity is given from the integral of of the acceleration curve from t_0 to t_1
- On a graph of velocity *v* versus time *t*, the change in positions is given from the integral of the velocity curve from t_0 to t_1

