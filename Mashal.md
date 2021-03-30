---
layout: math
studentname: Mashal
subject: Year 10 Math.
times: Tuesdays 6:30pm - 7:30pm
---

### Notes for 2nd of March
I am very impressed with your ability to pick up knowledge so quickly! Most of 
the things we went over were simply things that were not covered by the teacher,
so you are doing very well.

Things we covered:

- Long Division
- Synthetic Division
- Difference/Sum of Cubes

When I was learning these things, factorizing higher order polynomials was one 
of the most painful things to learn. There are quite a few strategies you have
to keep in mind for different cases.

To take the examples we did in class:

$$ (x^2 + x + 3)(x^2 + x + 4) - 12 $$

$$ x^4 + x^3 + 4x^2 + x^3 + x^2 + 4x + 3x^2 + 3x + 12 - 12 $$

$$ x^4 + 2x^3 + 8x^2 + 7x $$

$$ x(x^3 + 2x^2 + 8x + 7) $$

Now here's the part that no one really likes, we have to find _a_ solution for
the cubic on the right. We can only do this by guessing! But our guesses can be
informed by the [rational root theorem](https://en.wikipedia.org/wiki/Rational_root_theorem).

The definition on the wikipedia page of this is very precise. But basically, after
as much simplification has been done (like when we factored out the $$x$$) the
root must be $$\frac{p}{q}$$, where $$p$$ is a factor of the last coefficient (7) and
$$q$$ is a factor of the leading coefficient (1 in this case). Because the leading
coefficient is 1, which only really has the factor 1. Our case is, as I said, 
factors of the last term.

These factors can be positive or negative, so we must test $$-1$$, $$1$$, $$-7$$ and $$7$$.
Thankfully, on our second try, $$-1$$ seems to fit the bill.

$$ (-1)^3 + 2(-1)^2 + 8(-1) + 7 $$

$$ -1 + 2 - 8 + 7 $$

$$ 0 $$

This means that $$-1$$ is a _solution_ and $$(x + 1)$$ is a _factor_. So, we both did
full [polynomial division](https://www.khanacademy.org/math/algebra2/x2ec2f6f830c9fb89:poly-div/x2ec2f6f830c9fb89:quad-div-by-linear/v/polynomial-division) and [synthetic division](https://www.khanacademy.org/math/algebra-home/alg-polynomials/alg-synthetic-division-of-polynomials/v/synthetic-division) (Khan academy is amazing, should help you if you are confused)

If we divide them, we are left with $$x^2 + x + 7$$. So that means the factorized form is:

$$ x(x + 1)(x^2 + x + 7) $$

We did a couple more examples of this.

Finally, [difference and sum of perfect cubes](https://www.purplemath.com/modules/specfact2.htm) is very simply a matter of identification
and remembering the formulas. I despise remembering things in math! I prefer
everything to be 'intuitive'. You can pretty easily verify these, but it would
honestly be simpler to remember.

$$ a^3 - b^3 = (a - b)(a^2+ab+b^2) $$

$$ a^3 + b^3 = (a + b)(a^2-ab+b^2) $$

Keep an eye out for when this can be applied, you might not see a cube sign!

For instance, our example:

$$ x^6 - 8 $$

has no cube but $$x^2 = a$$ and $$2 = b$$ fit the bill.

Another one to watch out for is expressions, such as

$$ (x + 2)^3 - 27  $$

$$x + 2 = a$$ and $$3 = b$$ work, but mean you might have to simplify later down
the track.

If you have any questions throughout the week, feel free to email me! I don't
charge extra for that. 

### Notes for 9th of March
Looking into fractions! You're doing a very good job.

Remember, _we can never divide by 0_. If you want the working out for the problem
I showed you so that you can show it to your friends, here it is:

$$ x^2 - x^2 = x^2 - x^2 $$
$$ x(x-x) = (x+x)(x-x) $$
$$ x = (x + x) $$
$$ x = 2x $$
$$ 1 = 2 $$

This is why $$\frac{a}{0}$$ is always undefined, even if $$a$$ is also 0!

When $$a \neq 0$$, $$\frac{0}{a} = 0$$.

But in the end, working with fractions is just an extension of your algebreic
knowledge! Such as:

$$ \frac{a}{b} = c  $$

$$ a = bc $$

This method helps turn fractions into multiplications, which is very useful.

Simplifying fractions is a process of removing things that are on both the top
and the bottom, just like factorizing!

Nevertheless, I don't think you really need this, you are doing a fantastic job.

## Notes on Quadratics
I know that we wanted to talk about quadratics!

There are a couple of ways that one can solve a quadratic, and it is usually
a trade off between solving only a subset of quadratics in a difficult way or
a few quadratics in an easy way.

Let's take a look at the easiest variety:

$$ x^2 - 2x - 24 $$

We've seen this one! The technique for solving these works if the coefficient of
$$x^2$$ is $$1$$, and it has integer solutions.

To find a solution to this one, we have to determine what two numbers (we will call
them $$a$$ and $$b$$, _add_ together to make $$-2$$ and _multiply_ together to make
$$-24$$.

To work out what those numbers are, it's a good to recognize that $$-2$$ is negative,
so the _larger_ solution will be negative. Then we can run through the _factors_
of -24. That is, the only possible solutions are 1 and -24 (which don't add up),
2 and -12, which fails again, 3 and -8 which adds up to -5, then 4 and -6, which
finally does work!

We then just put those solutions into this form:

$$ (x + 4)(x - 6) $$

And we are done! This is the easiest way to solve a quadratic, if you can do it
that way.

If you run through all the factors and you can't find any, then that means that
it is either _unsolvable_ or it does not have integer solutions.

To determine whether a quadratic is unsolvable, we use the following formula:

$$ b^2 - 4ac $$

This is called the _discriminant_, and is part of the larger _quadratic formula_

$$ \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$

If the discriminant is lower than 0, the equation is unsolvable.

The next method of solving equations is when $$a$$ is not $$1$$, here's an example:

$$2x^2 - 7x - 15$$

Here, it's almost exactly the same process, but instead, we ask what two numbers
add together to make $$-7$$, but multiply together to make $$2\times -15$$ or $$-30$$.
We can do the same process, realizing that the larger number must be negative,
and going through the factors.

-30 and 1 doesn't work, 2 and -15 doesn't work, 3 and -10 however does!

We then split the middle term into those, and then factor the first two and the
later two, then factor them both.

$$2x^2 -10x + 3x - 15$$

$$2x(x - 5) + 3(x - 5)$$

$$(x - 5)(2x + 3)$$

And we are done!

The final method for solving these equations is by recognition. If we can recognize
that it is in the form of:

$$a^2 - b^2$$

Then we know the solution is

$$(a+b)(a-b)$$

It can be sometimes difficult to recognize whether it is in this form, for instance,
all of these are in that form:

$$x^2 - 9 = x^2 - (3)^2$$

$$36a^2 - 9b^2 = (6a)^2 - (3b)^2$$

$$x^2 - 2 = x^2 - (\sqrt{2})^2$$

Hope this helps!
