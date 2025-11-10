# Big-O and Big-Θ Proof Practice

For **big-O proof**, if there exist constants `c` and `n₀` such that  
`f(n) ≤ c * g(n)` for every `n ≥ n₀`, then  
`f(n) = O(g(n))`.

For **big-Θ proof**, if there exist constants `c₁`, `c₂`, and `n₀` such that  
`c₁ * g(n) ≤ f(n) ≤ c₂ * g(n)` for every `n ≥ n₀`, then  
`f(n) = Θ(g(n))`.

---

## 1. Use the formal proof of Big-O and Big-Θ to show the following

a) $n^2 + 5n - 2$ is $O(n^2)$

#### Step 1. Definition
By definition,  
\( f(n) = O(g(n)) \) ⇔  
∃ constants \( c > 0 \) and \( n_0 > 0 \) such that  
\( f(n) \le c \cdot g(n) \) for all \( n \ge n_0 \).

Here, \( g(n) = n^2 \).

---

#### Step 2. Find constants \( c \) and \( n_0 \)
For \( n \ge 1 \):
\[
n^2 + 5n - 2 \le n^2 + 5n + 2 \le n^2 + 7n \le n^2 + 7n^2 = 8n^2
\]

Thus, we can take \( c = 8 \) and \( n_0 = 1 \).

---

#### Step 3. Conclusion
Since for all \( n \ge 1 \),
\[
f(n) \le 8n^2
\]
the definition of Big-O is satisfied.

Therefore,
\[
\boxed{f(n) = O(n^2)}
\]

b) $\frac{n^2 - 1}{n + 1}$ is $O(n)$

c) $$\sqrt{5n^2 - 3n + 2} \in \Theta(n)$$

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
