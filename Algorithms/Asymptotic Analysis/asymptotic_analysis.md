# Asymptotic Analysis

### Runtime Overview
- Instead of raw time, compare how runtime grows as input size n grows
- Provides upper and lower bounds for a specific case (Worst case, Best Case)
- Other devices can make a program run slower or faster 
    - Does not change how fast it grows as n increases.

### Definitions
- Asymptotically
    - n -> ∞
- Big O 
    - O(g(n)) (upper bound)
    - The algorithm grows no faster than g(n) (Worst case ceiling)
- Big Omega
    -  Ω(g(n)) (lower bound)
    - The algorithm grows no slower than g(n) (Best case floor)
- Big Theta
    - 𝚹(g(n)) (Tight bound)
    - The algorithm grows exactly like g(n)