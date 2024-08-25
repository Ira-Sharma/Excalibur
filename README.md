# Excalibur
Excalibur is a custom pseudorandom number generator (PRNG) made by combining different known PRNGs- Linear congruential generator, Blum Blum Shub, Inversive Congruential Generator, Discrete Exponential Generator, and Multiplicative Congruential Generator or Lehmer RNG in a dynamic, semi-random order. 

1. The seed is initialized using the current time in seconds. This is a common method to get a dynamic seed value for PRNGs.
2. The selection of which PRNG to use is based on the current time's millisecond component. 
3. The order of the PRNG methods can be shuffled based on a condition. This approach adds layers of randomness to the generation process, aiming to produce less predictable random numbers.
4. Latitude and longitude values are used as seeds or parameters in the PRNG methods.

