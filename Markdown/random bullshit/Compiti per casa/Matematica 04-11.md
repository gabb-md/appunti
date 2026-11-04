# Pagina 1448

$\Huge{\mathbf{Esercizio\ }65.}$


$$
A=\{ x:x=\sqrt{ n }, n \in \mathbb{N} \}
$$


Dimostrare che $x_{n} \in A$ è un punto isolato di $A$ $\forall\ n \in \mathbb{N}$.

Scegliamo la terna di numeri $(x_{n-1},x_{n},x_{n+1})=(\sqrt{ n-1 }, \sqrt{ n }, \sqrt{ n+1 })$ con $n \geq 1$.

Dimostriamo che non esiste $m \in \mathbb{N}$ tale che:

$$
\sqrt{ n-1 } < \sqrt{ m } < \sqrt{n}\ \lor\ \sqrt{  n}< \sqrt{ m }<\sqrt{ n+1 }
$$

Si consideri l'intorno centrato in $x_{n}$ così definito:


$$
I(x_{n})=\ ]x_{n}-\delta_{1}; x_{n}+\delta_{2}[;\qquad \delta_{1}=\sqrt{ n }-\sqrt{ n-1 };\qquad \delta_{2}=\sqrt{ n-1 }-\sqrt{ n }
$$

Dimostriamo che non esiste alcun $\sqrt{ m } \in A$ appartenente a questo intorno.

Se abbiamo:


$$
\sqrt{ n -1}< \sqrt{ m }<\sqrt{ n }
$$

Possiamo elevare al quadrato:


$$
n-1<m<n \implies -1<m-n<0
$$

Dato che $m,n \in \mathbb{N}$, perlomeno $m-n \in \mathbb{Z}$, ma non esiste nessun intero in $(-1,0)$, perciò non può esistere l'$m$ cercato in $\mathbb{N}$. Esattamente allo stesso modo si può dimostrare che non esiste $m' \in \mathbb{N}$ tale che $\sqrt{ n }<\sqrt{ m' }<\sqrt{ n-1 }$.

Si consideri allora l'intorno centrato in $x_{n}$ così definito:

$$
I^*(x_{n})=\ ]x_{n}-\delta;x_{n}+\delta[;\qquad \delta=\frac{\delta_{2}+\delta_{1}}{4}
$$

Avendo appurato che non esistono $m,m'$ nell'intorno $I(x_{n})$, ed essendo $I^*(x_{n})$ un suo sottinsieme (dal momento che $\delta<\delta_{2}<\delta_{1}$), possiamo concludere che non esistano $m$ o $m'$ $\in \mathbb{N}$ che appartengono a $I^*(x_{n})$.

Abbiamo concluso.

$\mathbf{Q.E.D.}\qquad\blacksquare$

---

$\Huge{\mathbf{Esercizio\ }73.}$

$\mathbf{a.}$

**Vero**, perché il contrapposito è vero.

Dimostriamo questa affermazione prima nel caso in cui $x_{0} \in A$.

Se $A \neq \emptyset$ non fosse infinito, ma composto da $N \in \mathbb{N}$ elementi, si potrebbe ordinare, perciò si dica $x_{n}$ l'$n$-esimo elemento più piccolo di $A$, si scelga allora:

$$
\delta=\frac{\min(x_{n}-x_{n-1},x_{n+1}-x_{n})}{2}
$$

e si consideri l'intorno $I(x_{n})$ così definito:


$$
I(x_{n})=\ ]x_{n}-\delta;x_{n}+\delta[
$$

Tuttavia, $\forall\ X \in I(x_{n})$ avremmo che:


$$
X> x_{n}>x_{n-1}\ \lor X<x_{n}<x_{n+1}
$$

Se $X$ appartenesse ad $A$, per l'ordinamento che si è adoperato, dovrebbe al più essere che $X=x_{n-1}\ \lor\ X=x_{n+1}$, ma $X>x_{n-1}\ \lor\ X<x_{n+1}$, il che è una contraddizione, perciò non può essere che $X \in A$. Così si è visto che $x_{n}$ è un punto isolato.

> **NOTA:** nel caso in cui $n=1$, basta scegliere $\delta=\frac{x_{2}-x_{1}}{2}$, e fare lo stesso ragionamento. Analogamente, se $n=N$, basta scegliere $\delta=\frac{x_{N}-x_{N-1}}{2}$. Per i pedanti, se $N=1$, basta scegliere un qualsiasi $\delta >0$.

Nell'ipotesi in cui $x_{0} \not\in A$ invece dobbiamo operare diversamente.

Possiamo vedere subito che $x_{0}$ non può essere punto di accumulazione di $A$ se $x_{0} < m=\min A$ o $x_{0} > M=\max A$, perché basterebbe scegliere in questi casi rispettivamente:

$$
\delta= \frac{m-x_{0}}{2};\qquad \delta=\frac{x_{0}-M}{2};
$$

E considerare $I_{\delta}(x_{0})$, nessun $X \in A$ può appartenere al primo perché ciò implicherebbe che $X<\min A$, allo stesso modo nessun $X \in A$ può appartenere al secondo perché ciò implicherebbe che $X> \max A$ (assurdo in entrambi i casi).

Consideriamo ora il caso in cui $m<x_{0}<M$.

Prendiamo il più grande $X \in A$ tale che $X<x_{0}$ e il più piccolo $Y \in A$ tale che $Y>x_{0}$, se prendiamo:

$$
\delta=\frac{\min(x_{0}-X, Y-x_{0})}{2}
$$
Non troveremo alcun elemento in $I_{\delta}(x_{0})$, perché sarebbe contraddittorio ammettere l'esistenza di $(X',Y') \in A$ tali che:


$$
X<X'<x_{0},\ Y>Y'>x_{0}
$$
Così abbiamo concluso che:

$$
I_{\delta}(x_{0}) \cap A= \emptyset. 
$$

Abbiamo terminato la dimostrazione.


$\mathbf{Q.E.D.} \qquad\blacksquare$

$\mathbf{b.}$

**Vero**, un esempio è il seguente:


$$
A= \{ X: X=x^2,x \in \mathbb{R}, |x|\leq1 \}
$$

Come si vede, l'insieme corrisponde all'intervallo:


$$
[0,1]
$$

Che è limitato, ma infinito, e ad esempio $x_{0}=\frac{1}{2}$ è un punto di accumulazione di $A$.

$\mathbf{c.}$

**Falso**, per definizione di punto di accumulazione, un $x_{0}$ in $\mathbb{R}$ è punto di accumulazione di $A \subset \mathbb{R}$ se e solo se ogni intorno centrato in $x_{0}$ contiene almeno un elemento di $A$ diverso da $x_{0}$. In altre parole, l'appartenenza di $x_{0}$ ad $A$ non è neanche richiesta nella definizione.

$\mathbf{d.}$

**Falso**, perché per la definizione di punto di accumulazione:


$$
\forall\ I_{\delta}(x_{0}), \exists X \in (A \cap I_{\delta}(x_{0})): X\neq x_{0}.
$$

Non basta quindi che l'intorno contenga $X \in A$, ma deve anche essere $X\neq x_{0}$.

---

$\Huge{\mathbf{Esercizio\ }75.}$


$$
A=\left\{  x:x=\frac{1}{n+2}, n \in \mathbb{N}  \right\}, x_{0}=0.
$$

Dato l'insieme $A$, ci viene chiesto di dimostrare che $x_{0}$ sia punto di accumulazione per $A$.

Innanzitutto notiamo che $x_{n}>0, \forall n \in \mathbb{N}$:


$$
\frac{1}{n+2}>0 \iff 1>0
$$
Banalmente vero.

Cerchiamo $x_{n} \neq x_{0}$ in un intorno di $x_{0}$:


$$
I_{\delta}(x_{0})=\ ]x_{0}-\delta; x_{0}+\delta[;\qquad \delta >0.
$$

Se $x_{n}$ appartiene all'intorno avremo che:


$$
0-\delta<x_{n}<0+\delta
$$

Essendo ogni $x_{n}>0$, trascuriamo la prima disuguaglianza e concentriamoci sulla seconda:

$$
x_{n}<\delta
$$

Come step intermedio, dimostriamo che il massimo di $A$ è $M=\frac{1}{2}$:


$$
\frac{1}{n+2}\leq \frac{1}{2} \iff n+2 \geq 2 \iff n \geq 0
$$

Come si è stabilito nella definizione di $A$, quindi $\max A = \frac{1}{2}$.

Per $\delta > \frac{1}{2}$ la condizione è verificata per ogni $x_{n}$, altrimenti:

$$
\frac{1}{n+2} < \delta \implies n> \frac{1}{\delta}-2
$$

Si consideri allora $N= \left\lceil  \frac{1}{\delta} -1  \right\rceil> \frac{1}{\delta}-2$, allora è semplice scegliere il punto $x_{N} \in A$ che appartiene anche all'intorno $I_{\delta}(x_{0})$.

Abbiamo finito.

$\mathbf{Q.E.D.} \qquad\blacksquare$

---

















