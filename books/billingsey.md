<link href="../whirlwind.css" rel="stylesheet">

<whirlheader>
    <p>megafluffykoala</p>
    <p>Lecture 1</p>
    <p>2025</p>
</whirlheader>

# Probability

## Borel's Normal Number Theorem


<details>
<summary>Motivation</summary>

- Discrete probability theory is sufficient for many topics in probability.
- It is inadequate for two types of problems:
  1. Infinitely repeated operations (e.g., infinite coin tosses).
  2. Infinitely fine operations (e.g., random drawing a point from a segment).
- A complete probability theory based on measure theory addresses both types of problems equally.
- The goal of this section is to demonstrate why measure-theoretic probability unifies these issues.

</details>

### The Unit Interval

<details>
<summary>The Unit Interval</summary>

The unit interval $(0, 1]$ is the sample space $\Omega$, with a random point denoted as $\omega$.

</details>

<details>
<summary>Length of an Interval</summary>

The length of an interval $I=(a,b]$ is given by
$$
  |I|=b-a.
$$

</details>

<details>
<summary>Probability of Finite Disjoint Union of Intervals</summary>

For a set $A$ represented as a finite disjoint union of intervals:
$$
  P(A) = \sum_{i=1}^n |I_i|
$$

</details>

<details>
<summary>Additivity of probability for disjoint sets</summary>

If $A$ and $B$ are disjoint,
$$
  P(A \cup B) = P(A) + P(B)
$$

</details>

<details>
<summary>Model for Fine Operations</summary>

- The time interval during which a radioactive substance emits a single $\alpha$-particle, occurring within the subinterval $(a, b]$, is given by $b - a$.
- The probability that a telephone call arrives within a time interval $(a,b]$, where the arrival time is random, is given by $b-a$.

</details>

<details>
<summary>Model for Repeated Operations (Coin Toss) via Dyadics</summary>

- For each $\omega\in (0,1]$ has a dyadic expansion:
  $$
  \omega = \sum_{n=1}^\infty \frac{d_n(\omega)}{2^n}, \quad d_n(\omega) \in \{0,1\}
  $$
- The sequence $(d_1(\omega), d_2(\omega), \ldots)$ acts like an infinite sequence of coin tosses.
- The interval is defined by 
  $$
  [\omega: d_i(\omega) = u_i, \quad i=1,...,n] = \left(\sum_{i=1}^n \frac{u_i}{2^i}, \sum_{i=1}^n \frac{u_i}{2^i} + \frac{1}{2^n} \right]
  $$
- The **dyadic intervals** have endpoints $\frac{k}{2^n}$ and $\frac{k+1}{2^n}$, where $n$ is the **rank** of the interval.
- From the binomial formula, 
  $$
    P\left[\omega: \sum_{i=1}^n d_i(\omega) = k\right] = \binom{n}{k} \frac{1}{2^n}, \quad 0\le k \le n.
  $$

</details>

### The Weak Law of Large Numbers 

<details>
<summary>The Weak Law of Large Numbers</summary>

<theorem>
<src>The Weak Law of Large Numbers</src>

For each $\epsilon$, 
$$
\lim_{n\to \infty} P\left[ \omega: \left| \frac{1}{n} \sum_{i=1}^n d_i(\omega) - \frac{1}{2} \right| \ge \epsilon \right]=0
$$

</theorem>

- This says that if $n$ is large, then there is a small probability that the fraction of heads in $n$ tosses deviates from $\frac{1}{2}$.

</details>


<details>
<summary>Rademacher Function</summary>
<definition>

The **Rademacher** function is defined by 
$$
r_n(\omega)=2d_n(\omega)-1 = \begin{cases}
+1 & \text{ if }d_n(\omega)=1, \\ 
-1 & \text{ if }d_n(\omega)=0, \\ 
\end{cases}
$$

</definition>

- Define $s_n(\omega) := \sum_{i=1}^n r_i(\omega)$.
- Flip a coin successfully. If a particle (starting from the origin) performs a random walk on $\mathbb{Z}$ by successively moving one unit in the +/- direction if the coin is H/T, then $r_i(\omega)$ represents the distance it moves on the ith step and $s_n(\omega)$ represents its position after $n$ steps.

</details>

<details>
<summary>The Weak Law of Large Numbers, Restated</summary>

<theorem>
<src>The Weak Law of Large Numbers, Restated</src>

For each $\epsilon$, 
$$
\lim_{n\to \infty} P\left[ \omega: \left| \frac{1}{n} s_n(\omega) \right| \ge \epsilon \right]=0
$$

</theorem>

</details>

<details>
<summary>Proof</summary>

**Step 1**: Each dyadic interval of rank $i-1$ splits into two dyadic intervals of rank $i$: $r_i(\omega)=-1$ on a set of intervals of total length $\frac{1}{2}$ on one and $r_i(\omega)=1$ on a set of length $\frac{1}{2}$.

**Step 2**: Conclude that
  $$
  \int_0^1 r_i(\omega) \,d\omega =0 \implies \int_0^1 s_n(\omega)\,d\omega =0.
  $$

**Step 3**: Suppose that $i<j$. On a dyadic interval of rank $j-1$, $r_i(\omega)$ is constant and $r_j(\omega)=-1$ on the left half and $r_j(\omega)=+1$ on the right half. So 
  $$
  \int_0^1 r_i(\omega) r_j(\omega) \,d\omega =0, \quad i\neq j.
  $$ 

**Step 4**: Since $r_i^2(\omega)=1$, $\int_0^1 s_n^2(\omega)\,d\omega =n$.

**Step 5**: State and prove the lemma:

<lemma>

Let $f$ be a step function such that $f(\omega)=c_j$ for $\omega \in (x_{j-1}, x_j]$, where $0=x_0< ... < x_k=1$. If $f$ is a nonegative step function, then $[\omega: f(\omega) \ge \alpha]$ is for $\alpha >0$ a finite union of intervals and 
$$
P[\omega: f(\omega)\ge \alpha] \le \frac{1}{\alpha}\int_0^1 f(\omega)\,d\omega.
$$

</lemma>

**Step 6**: Apply the lemma with $\alpha=n^2\epsilon^2$ and $f(\omega)=s_n^2(\omega)$:
$$
P\left[ \omega: |s_n(\omega)| \ge n\epsilon \right] \le \frac{1}{n^2\epsilon^2} \int_0^1 s_n^2(\omega)\,d\omega = \frac{1}{n\epsilon^2}
$$

</details>

### The Strong Law of Large Numbers

<details>
<summary>Normal Numbers</summary>

<definition>

Points in the set 
$$
N=\left[ \omega: \lim_{n\to \infty} \frac{1}{n} \sum_{i=1}^n d_i(\omega) = \frac{1}{2} \right]
$$
are called **normal numbers**.

</definition>

This is the set of $\omega$ for which the asymptotic relative frequency of $1$ in the sequence $(d_1(\omega), d_2(\omega), ...)$ is $\frac{1}{2}$

- This says that if $n$ is large, then there is a small probability that the fraction of heads in $n$ tosses deviates from $\frac{1}{2}$.

  
</details>

<details>
<summary>Negligible</summary>

<definition>

A subset $A$ of $\Omega$ is **negligible** if for each $\epsilon$, there exists a finite or countable collection $I_1, I_2, ...$ of intervals satisfying
$$
A\subset \bigcup_k I_k
$$
and 
$$
\sum_k |I_j|<\epsilon>
$$

</definition>

A negligible set can be covered by intervals whose lengths can be made arbitrarily small.

</details>

<details>
<summary>Finite/countable unions of negligible sets if negligible</summary>

<proposition>

A finite or countable union of negligible sets is negligible.

</proposition>

TO DO 

</details>

<details>
<summary>Every countable set is negligible</summary>

<proposition>

Every countable set is negligible

</proposition>

TO DO 

</details>

<details>
<summary>Borel's Normal Number Theorem</summary>

<theorem>

The set of normal numbers has negligible complement.

</theorem>

Proof: TO DO

</details>

<details>
<summary>Strong vs Weak</summary>

TO DO

</details>

### Length 

<theorem>

1. If $\bigcup_k I_k \subset I$ and the $I_k$ are disjoint, then $\sum_k |I_k| \le |I|$ 
2. If $I\subset \bigcup_k I_k$ (the $I_k$ need not be disjoint), then $|I|\le \sum_k |I_k|$.
3. If $I=\bigcup_k I_k$ and the $I_k$ are disjoint, then $|I|=\sum_k |I_k|$.

</theorem>

### The Measure Theory of Diophantine Approximation


<theorem>

If $x$ is irrational, there are infinitely many irreducible fractions $\frac{p}{q}$ such that
$$
\left| x-\frac{p}{q}\right| < \frac{1}{q^2}
$$

</theorem>


<theorem>

Suppose that $\varphi$ is positive and nondecreasing. If 
$$
\sum_q \frac{1}{q\varphi(q)}=\infty
$$
then $A_\varphi$ has negligible complement.

</theorem>

<theorem>

Suppose that $\varphi$ is positive. If 
$$
\sum_q \frac{1}{q\varphi(q)} <\infty
$$
then $A_{\varphi}$ is negligible.

</theorem>

# Probability Measures 