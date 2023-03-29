# welcome dlang oh

When only two variables are involved, the solutions to systems of lin-
ear equations can be described geometrically because the graph of a lin-
ear equation ax + by = c is a straight line if a and b are not both zero.
Moreover, a point P(s, t) with coordinates s and t lies on the line if and
only if as + bt = c—that is when x = s, y = t is a solution to the equa-
tion. Hence the solutions to a system of linear equations correspond to the
points P(s, t) that lie on all the lines in question.
In particular, if the system consists of just one equation, there must
be infinitely many solutions because there are infinitely many points on a
line. If the system has two equations, there are three possibilities for the
corresponding straight lines:
y
1. The lines intersect at a single point. Then the system has a unique
solution corresponding to that point.
x+y = 4
2. The lines are parallel (and distinct) and so do not intersect. Then
the system has no solution.
x+y = 2
x
(b) No Solution
y
−6x + 2y = −8
3x − y = 4
x
(c) Infinitely many solutions
(x = t, y = 3t − 4)
Figure 1.1.1
3. The lines are identical. Then the system has infinitely many
solutions—one for each point on the (common) line.
These three situations are illustrated in Figure 1.1.1. In each case the
graphs of two specific lines are plotted and the corresponding equations are
indicated. In the last case, the equations are 3x−y = 4 and −6x+2y = −8,
which have identical graphs.
With three variables, the graph of an equation ax + by + cz = d can be
shown to be a plane (see Section 4.2) and so again provides a “picture”
of the set of solutions. However, this graphical method has its limitations:
When more than three variables are involved, no physical image of the
graphs (called hyperplanes) is possible. It is necessary to turn to a more
“algebraic” method of solution.
Before describing the method, we introduce a concept that simplifies
the computations involved. Consider the following system
