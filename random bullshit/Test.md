$\huge{{\mathbf{TESI}}}$

$\text{La serie armonica generalizzata con esponente } 2 \text{ (alternativamente } \zeta(2) \text{) converge ad un numero reale } x \in (1,2).$
$$
1<\zeta(2)<2
$$
-----
$\text{Partiamo dalla definizione}$:
$$
\zeta(2)=\sum_{k=1}^{\infty} \frac{1}{k^2}
$$

$\text{Ai fini della dimostrazione, si prova vincente la seguente osservazione}$
$$k^2> k(k-1) \implies \frac{1}{k^2}< \frac{1}{k(k-1)}
$$
$\text{Quindi}$
$$\sum_{k=1}^{\infty} \frac{1}{k^2} < 1+\sum_{k=2}^{\infty} \frac{1}{k(k-1)}=1+\sum_{k=1}^{\infty} \frac{1}{k(k+1)} 
$$
$\text{dato che ogni termine della seconda serie risulta essere maggiore di un altro termine nella prima serie.}$


$\text{Quella a destra, nota come la serie di Mengoli, converge a } 1\text{. Dimostriamo la convergenza della serie di Mengoli:}$

$$
\frac{1}{k(k-1)}=\frac{1}{k-1}-\frac{1}{k}
$$
$\text{Allora si scopre ovvio che la serie sia telescopica. Lo si nota riscrivendola come:}$
$$
\sum_{k=2}^{\infty} \frac{1}{k-1}-\frac{1}{k}=\frac{1}{1}-\cancel{\frac{1}{2}}+\cancel{\frac{1}{2}}-\cancel{\frac{1}{3}}+\cancel{\frac{1}{3}}+\dots+\cancel{\frac{1}{k}}-\cancel{\frac{1}{k-1}}+\cancel{\frac{1}{k-1}}-\cancel{\frac{1}{k}}=1 
$$

$\text{Si scrive che}$

$$
\zeta(2)< 1+1=2
$$


$\text{Ma chiaramente}$
$$
\zeta(2)=1+\sum_{k=2}^{\infty} \frac{1}{k^2} >1
$$
$\text{In definitiva:}$

$$
1< \zeta(2)<2
$$
$\mathbf{Q.E.D.}$
$\qquad\square$