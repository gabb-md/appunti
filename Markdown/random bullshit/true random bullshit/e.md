$\mathbf{Problem.}$

$\text{Prove that } e \text{ is irrational}.$


------

$\mathbf{Proof.}$


<br/>

Suppose that $e=\dfrac{a}{b}$ for some $a,b>0 \in \mathbb{N}$.

We know that the McLaurin's expansion for $e^x$ is the following:

$$
 e^{x}=\sum_{n=0}^{\infty} \frac{x^n}{n!}
$$


So, for $e^{1}=e$, we have that:

$$
e^{1}=\sum_{n=0}^{\infty} \frac{1}{n!}=e \qquad (1)
$$



---

Let us define $x$ as the quantity:

$$
x=b!\left( e-\sum_{n=0}^{b} \frac{1}{n!} \right) \qquad (2)
$$

Substitute $e=\dfrac{a}{b}$:

$$
x=b!\left( \frac{a}{b}-\sum_{n=0}^{b} \frac{1}{n!} \right)=a(b-1)!-\sum_{n=0}^{b} \frac{b!}{n!} \qquad (3)
$$
<br/>

Considering this new expression for $x$, it is trivial to see that $x$ is an integer. 
That is because $a(b-1)!$ is an integer, and $\displaystyle{\sum_{n=0}^{b} \frac{b!}{n!}}$ is also an integer because $b \geq N$ for all $N \in [0,b]  \cap \mathbb{N}$. 

Any difference of integers is an integer by the definition of $\mathbb{Z}$:

$$
\mathbb{Z}= \{a-b\ |\ a,b \in \mathbb{N}\}
$$
Therefore $x \in \mathbb{Z}$.

----

However, from $(1)$ and $(2)$ it also follows that:


$$
x= b! \left( \sum_{n=0}^{\infty} \frac{1}{n!}-\sum_{n=0}^{b} \frac{1}{n!}  \right) = \sum_{n=b+1}^{\infty} \frac{b!}{n!}
$$


Since the series is increasing and each term is positive, it follows that $x>0$.


Let us notice that:

$$
\frac{b!}{n!}=\frac{b \cdot (b-1) \cdot (b-2)\dots}{n \cdot (n-1) \cdot (n-2) \cdot ... \cdot (b+1)\cdot b \cdot (b-1) \cdot ...}= \frac{1}{n \cdot (n-1) \cdot (n-2) \cdot ... \cdot (b+1)}
$$

After the simplifications, the denominator has $n-b$ factors.


Since $n \geq b+1$ for all $n \in [b+1, \infty)$, the sum is bounded by:


$$
\sum_{n=b+1}^{\infty} \frac{b!}{n!} < \sum_{n=b+1}^{\infty} \frac{1}{(b+1)^{n-b}}= \sum_{n=1}^{\infty} \left(\frac{1}{b+1} \right)^n=\frac{\frac{1}{b+1}}{1-\frac{1}{b+1}}=\frac{1}{b} \leq 1 \qquad (4)
$$

since $b \in \mathbb{N}$.


This leads to conclude that

$$
0<x<1
$$

It has been established in $(3)$ that $x$ is an integer and it is possible to deduce from $(4)$ that $x \in (0,1)$. However, there are no integers in that interval. 

A contradiction has been reached.

$\mathbf{Q.E.D.}\qquad\blacksquare$
