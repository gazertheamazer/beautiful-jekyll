---
layout: post
title: How to Compute the Length of a Wiggly Rope (or Area of a Wiggly Surface)
subtitle: Arc Length Made Simple!
categories: Math
---

If you were shown a wiggly rope like this:

{: .center}
![Simple Square](/img/Square.png) 

How could you compute the total LENGTH $L$ of the wiggly rope?
If you had the rope in front of you now, you could straighten the rope and lay it beside a meter/yard stick.
But how could we do this _without_ straightening it?

**To figure out the length of a wiggly rope, we compute the _arc length_ of the rope.**

The wiggly rope makes _some_ particular shape that, when laid on the Cartesian plane, can be described by a function $f(x)$.
The total length of the rope (or function $f(x)$) can be viewed as a simple sum of all the small little lengths of rope $\Delta$$L$ along the way.
Then, the total length $L$ is "the sum of all $\Delta L$ pieces from the beginning to the end of the rope".

The key to the arc length formula is the Pythagorean Theorem. 
Clearly, building a wiggly rope out of small, straight segments produces some error, for the rope is definitely _not_ actually built of straight segments, it is a curve!
As long as we treat each of these pieces as _very, very small_, we can use some introductory calculus to compute the _exact_ arc length of the rope, with no error. 
Here is a zoomed-in image of a small, straight line segment approximating our rope.





Mathematically speaking, in the limit of $\Delta x$ -> 0 the Taylor Expansion of $f(x)$ collapses to the linear term. 


You have 

This question has two answers, depending on what we mean by the phrase _how far_.

Let's take a look at the trajectory of the ball. 
(insert image!)
Do we want to compute how far the ball is _from us when it lands_ (the **displacement**) or how far the ball travelled _along its total flight path_ (the **distance**). 
The (horizontal) displacement of the ball is referred to as the _range_ (like the range of an artillery shell) and can be computed quite easily using any of the projectile-motion equations.

The total distance of the flight path is (slightly) less trivial.
The distance is how many meters did travelled along its entire path: ie. the number of steps on the ball's FitBit, or the number of meters shown on its odometer.

{: .box-note} 
The total distance travelled along the parabola is called the **arc length** of $y = f(x)$.

If you'd like to find the arc length of a function, simply get a tape measure, bend it along the entire function, and take a reading. Voila! This is the arc length. In practice, simply knowing the function $f(x)$ itself is sufficient!




For a function simple function of one variable $y=f(x)$






In high school we commonly learn the F.O.I.L technique (First - Outside - Inside - Last) to expand a binomial like this: <br />

$$(a+b)^{2}=(a+b)(a+b)=a^{2}+2ab+b^{2}$$

Great, but why this rule? Notice that above we are **squaring** the quantity $(a+b)$. 
**The square of any number yields the area of the square, whose sidelengths are that number!** 
For example, squaring the number 10 will yield 100 which is the area of a square with side length 10: <br />

{: .center}
![Simple Square](/img/Square.png)

Given two positive numbers $a$ and $b$ (eg. 2 and 6, or 19 and 88), what is the area of a square whose sidelength is $a+b$? It seems the area should be exactly $(a+b)^{2}$. When we really _compute_ this value, we FOIL it, yielding:
<p align='center'>
Area = $(a+b)^{2}=(a+b)(a+b)=a^{2}+2ab+b^{2}$
  </p>

To imagine the right-hand-side, let's re-draw our square explicitly showing the lengths $a$ and $b$: <br />

{: .center}
![ABSquare](/img/absquare.png)

Cool! **The total area of the square is just the sum of the smaller inner areas**: a red square of area $a^{2}$, a green square of area $b^{2}$, and two identical blue rectangles of area $ab$. 
Since we've confirmed these areas are identical, we learn that the FOIL rule is rooted in simple area geometry. <br /> 

{: .box-note} 
**Apply the Result:** Can you explain FOIL-ing $(a+b+c)^{2}$ or $(a+b+c+d+.....+z)^{2}$?






