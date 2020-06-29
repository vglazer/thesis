# Thesis
A common way to produce [signature schemes](https://en.wikipedia.org/wiki/Digital_signature) 
is to apply the [Fiat-Shamir transform](https://en.wikipedia.org/wiki/Fiat%E2%80%93Shamir_heuristic) 
to an [identification scheme](http://www-math.ucdenver.edu/~wcherowi/courses/m5410/identschemes.pdf), 
which preserves security in the [Random Oracle Model](https://en.wikipedia.org/wiki/Random_oracle) (ROM).
In this [thesis](https://github.com/vglazer/thesis/blob/master/body/ut-thesis.pdf),
we present two results concerning security in the ROM. 

First, we show that for every canonical identification scheme, the corresponding 
Fiat-Shamir signature scheme is secure in the ROM. Previously, only 
“non-trivial” canonical identification schemes were known to yield 
Fiat-Shamir signature schemes which are secure in the ROM. 

Second, we 
show how to modify a certain 
[discrete logarithm](https://en.wikipedia.org/wiki/Discrete_logarithm)-based public-key 
encryption scheme so that it becomes 
[CCA2-secure](https://en.wikipedia.org/wiki/Adaptive_chosen-ciphertext_attack) 
in the ROM. 

This work was supervised by 
[Charlie Rackoff](http://www.cs.toronto.edu/dcs/people-faculty-rackoff.html).
