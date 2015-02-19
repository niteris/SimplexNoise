# SimplexNoise
Portable SimplexNoise Implementation

I made this implementation because I was tired of not being able to find any implementations on the internet.
I found this implementation from the repositor at https://github.com/FastLED/FastLED and eliminated most
microcontroller specific optimizations so that the solution was portable.

I removed the optimizations so that the barrier of entry for users to get up and running with SimpleNoise was
reduced.

I personally use this function for 1-dimensional simplex noise to program LED ropes, but your use case may vary.
