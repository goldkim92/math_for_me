# math_for_me


### Eigenvectors of real symmetric matrices are orthogonal
----
For any real matrix $$A$$ and any vectors $$x$$ and $$x$$, we have

$\left<Ax,y\right>=\left<x,A^Ty\right>$

Now assume that $$A$$ is symmetric, and $$x$$ and $$y$$ are eigenvectors of $$A$$ corresponding to distinct eigenvalues $$\mu$$ and $$\lambda$$. Then

$$\lambda\left<x,y\right> = \left<\lambda x,y\right> = \left<Ax,y\right> = \left<x,A^Ty\right> =\left<x,Ay\right> = \left<x,\mu y\right>=\mu \left<x,y\right>$$

Therefore, $$\left(\lambda-\mu\right) \left<x,y\right>=0.$$ Since $$\lambda-\mu\neq0$$, then $$\left<x,y\right>=0$$, i.e., $$x\bot y$$.


### Real symmetric matrices have real eigenvalues
----
Let $$v$$ be a vector whose entries are allowed to be complex. It is no longer true that $$v \cdot v \geq 0$$ with equality only when $$v = 0$$.
 
However, if $$v$$ is the complex conjugate of $$v$$, it is true that $$v \cdot v \geq 0$$ with equality only when $$v = 0$$.

With this in mind, suppose that $$\lambda$$ is a (possibly complex) eigenvalue of the real symmetric matrix $$A$$. Thus there is a nonzero vector $$v$$, also with complex entries, such that $$Av = \lambda v$$.
By taking the complex conjugate of both sides, and noting that $$\bar{A} = A$$ since $$A$$ has real
entries, we get $$\overline{Av} = \overline{\lambda v} \Rightarrow A\bar{v} = \bar{\lambda} \bar{v}$$. Then, using that $$A^T = A$$,

$$
\bar{v}^TAv = \left<\bar{v},Av\right> = \left<\bar{v},\lambda v\right> = \lambda \left<\bar{v}\cdot v\right>, \\
\bar{v}^TAv = \left<A^T\bar{v},v\right> = \left<A\bar{v},v\right> = \left<\bar{\lambda}\bar{v},v\right> = \bar{\lambda}\left<\bar{v},v\right>
$$

Since $$v\neq 0$$, we have $$\bar{v}\cdot v \neq 0$$. Thus $$\bar{\lambda} = \lambda$$, which means $$λ \in \R$$.



