I want to create a code generator.
But first, I must create something that understands basic logic.

It starts with a program that generates 0s and 1s.
I create a random string generator of 0s and 1s.

Let's say it creates a 0.
I store this in a pattern database.

It creates a 1.
I store this.

I generate all patterns of length 1.
It doesn't have to be all.

I run this algorithm until I run into 100% cache hits for (# of patterns in solution length) / 3 times
length:	   cache hits required
	1	2
	2	4
	3	8

Then, I generate a random string of 0s and 1s, and I want to create this pattern
using my pattern database.

Encrypt any program as 0s and 1s.

For search problems, consider a sort to solve it.