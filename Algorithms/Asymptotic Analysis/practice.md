# Big-O and Big-Θ Proof Practice

For **big-O proof**, if there exist constants `c` and `n₀` such that  
`f(n) ≤ c * g(n)` for every `n ≥ n₀`, then  
`f(n) = O(g(n))`.

For **big-Θ proof**, if there exist constants `c₁`, `c₂`, and `n₀` such that  
`c₁ * g(n) ≤ f(n) ≤ c₂ * g(n)` for every `n ≥ n₀`, then  
`f(n) = Θ(g(n))`.

---

## 1. Use the formal proof of Big-O and Big-Θ to show the following

a)  
\( n^2 + 5n - 2 \) is \( O(n^2) \)

b)  
\( \frac{n^2 - 1}{n + 1} \) is \( O(n) \)

c)  
\( \sqrt{5n^2 - 3n + 2} \) is \( Θ(n) \)

---

## 2. State **True** or **False** and explain why

a)  
\( 8n^2(\sqrt{n}) \) is \( O(n^3) \)

b)  
\( 8n^2(\sqrt{n}) \) is \( Θ(n^3) \)

---

```bash
def func(lst):
for i in range(len(lst)):
if (len(lst) % 2 == 0):
return
```
