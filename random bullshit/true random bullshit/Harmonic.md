$\huge{\mathbf{TESI}}$

La serie armonica è una serie divergente.

$$
1+\frac{1}{2}+\frac{1}{3}+\frac{1}{4}+\frac{1}{5}+\frac{1}{6}+\frac{1}{7}+\dots =\sum_{k=1}^{\infty} \frac{1}{k}=\infty 
$$

---

Confrontiamo la serie armonica con un'altra seerie associando in questo modo i termini:

$$
$$
$$
1+\left( \frac{1}{2} + \frac{1}{3} \right)+\left( \frac{1}{4}+\frac{1}{5}+\frac{1}{6}+\frac{1}{7} \right)+\left( \frac{1}{8}+\dots+\frac{{1}}{15} \right)+\left( \frac{1}{16}+\dots+\frac{1}{31} \right)+\dots
$$
$$
\frac{1}{2}+\left( \frac{1}{4}+\frac{1}{4} \right)+\left( \frac{1}{8}+\frac{1}{8}+\frac{1}{8}+\frac{1}{8} \right)+\left( \frac{1}{16}+\dots+\frac{1}{16} \right)+\left( \frac{1}{32}+\dots+\frac{1}{32} \right)+\dots
$$

Osserviamo che è possibile associare i termini della serie armonica raggruppati ordinatamente secondo $n$-uple, con $n=2^k$, dei reciproci degli interi da $\frac{1}{2^k}$ a $\frac{1}{2^{k+1}-1}$ a delle $n$-uple di termini $\frac{1}{2^{k+1}}$.

La somma dei termini di ciascuna $n$-upla nella seconda serie è:

$$
\frac{1}{2^{k+1}}\cdot 2^k=\frac{1}{2}
$$

---

Confrontando una $n$-upla $Q$ della serie armonica con la corrispondente $n$-upla $q$ della nuova serie, otteniamo che:

$$
 Q>q
$$

perché il numero più piccolo di $Q$ è maggiore di ogni numero in $q$, allora lo sono anche gli altri elementi, e a parità di numero di elementi, se quelli di una $n$-upla sono maggiori, allora anche la somma è maggiore. Per il confronto tra $n$-uple, indicando con $H$ il risultato della serie armonica e con $h$ il risultato della serie ausiliaria, ricaviamo che:

$$
H>h
$$

Dato che ci sono infinite $n$-uple $q$, possiamo scrivere il risultato della seconda serie come una somma infinita di $\frac{1}{2}$, tuttavia:

$$
h=\lim_{ n \to \infty } \frac{1}{2}n=\infty
$$

Se $H>h$ dev'essere anche che:

$$
H=\infty
$$
Ciò dimostra la tesi.

$\mathbf{Q.E.D} \qquad\blacksquare$