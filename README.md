# Excalibur
Excalibur is a custom pseudorandom number generator (PRNG) made by combining different known PRNGs- Linear congruential generator, Blum Blum Shub, Inversive Congruential Generator, Discrete Exponential Generator, and Multiplicative Congruential Generator or Lehmer RNG in a dynamic, semi-random order. 
The selection of which PRNG to use is based on the current time's millisecond component, and the order of the PRNG methods can be shuffled based on a condition. This approach adds layers of randomness to the generation process, aiming to produce less predictable random numbers.
