# The Sipek Conjecture

Let $s: \mathbb{N} \rightarrow \mathbb{N}$ denote the function mapping a positive integer to the sum of its decimal digits. For any distinct positive integers $A_0, B_0 \in \mathbb{N}$, define the sequences $(A_k)\_{k=0}^{\infty}$ and $(B_k)\_{k=0}^{\infty}$ recursively by the relations:

$$
A_{k+1} = A_k + s(B_k), \quad B_{k+1} = B_k + s(A_k) \quad \text{for all } k \geq 0.
$$

Then, there exists a positive integer $k$ such that $A_k = B_k$.
