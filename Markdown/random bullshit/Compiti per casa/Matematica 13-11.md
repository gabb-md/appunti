$\Huge{\mathbf{Esercizio\ 66.}}$


$$
A=\left\{  x:x=\frac{n+1}{n}, n \in \mathbb{N}-\{ 0 \}  \right\}
$$

Dimostrare che ogni $x_{n} \in A$ è un punto isolato di $A$.

Consideriamo la terna $(x_{n-1},x_{n},x_{n+1})$ con $n \geq 2$. Dato che la successione di $x_{n}$ è decrescente, abbiamo che:

$$
x_{n-1}>x_{n}>x_{n+1} \implies \frac{(n-1)+1}{n-1} > \frac{n+1}{n} > \frac{(n+1)+1}{n+1}
$$

$$
\frac{n}{n-1} > \frac{n+1}{n} > \frac{n+2}{n+1}
$$

Si considerino:

$$
\delta_{1}= \frac{x_{n-1}-x_{n}}{2};\qquad \delta_{2}=\frac{x_{n}-x_{n+1}}{2};\qquad \delta = \frac{\min(\delta_{1},\delta_{2})}{2 }
$$

E l'intorno circolare centrato in $x_{n}$:

$$
I_{\delta}(x_{n})=\ ] x_{n}-\delta; x_{n}+\delta[
$$

Supponiamo che esista $x_{m} \in I_{\delta}(x_{n}) \cap A-\{ x_{n} \}:\ x_{n+1}<x_{m}<x_{n-1}$:

$$
\frac{n+2}{n+1}< \frac{m+1}{m} < \frac{n}{n-1}
$$

$$
\frac{(n+1)+1}{n+1}< \frac{m+1}{m} < \frac{(n-1)+1}{n-1}
$$


$$
1 +\frac{1}{n+1}< 1+ \frac{1}{m} < 1+ \frac{1}{n-1}
$$

$$
\frac{1}{n+1} < \frac{1}{m} < \frac{1}{n-1}
$$

$$
n-1<m<n+1
$$

Dato che $m \in \mathbb{N}$ dev'essere intero, ma l'unico intero tra $n-1$ e $n+1$ è:

$$
\frac{(n-1)+(n+1)}{2}=n
$$

Quindi avremmo $m=n$, che contraddice l'ipotesi $x_{m} \neq x_{n}$. 
Avendo raggiunto un assurdo, possiamo concludere che non esista un $m \neq n$ che soddisfi le condizioni necessarie.

$x_{n}$ è un punto isolato per $n \geq 2$.

È immediato dimostrare che anche $x_{1}$ sia un punto isolato.

Dimostriamo che non esiste $x_{2}<x_{N} \in A<x_{1}$:


$$
\frac{2+1}{2}< \frac{N+1}{N}< \frac{1+1}{1}
$$


$$
\frac{3}{2}< 1+\frac{1}{N}< 2
$$


$$
\frac{1}{2}< \frac{1}{N}< 1
$$

$$
1<N<2
$$

Impossibile, perché non esiste alcun intero in $(1,2)$, concludiamo che non può neanche esistere $N \in \mathbb{N}-\{ 0 \}$ che rispetta le condizioni imposte.

$\mathbf{Q.E.D.} \qquad\blacksquare$

---

$\Huge{\mathbf{Esercizio\ 67.}}$


$$
A= \left\{  x: x=\frac{2}{n^{2}}, n \in \mathbb{N}-\{ 0 \}  \right\}
$$

Dimostrare che ogni $x_{n} \in A$ è un punto isolato di $A$.

Si noti che la successione di $x_{n}$ è decrescente, si consideri ora la terna $(x_{n-1},x_{n},x_{n+1})$ per $n \geq 2$, che per il motivo appena enunciato può essere ordinata così:

$$
x_{n+1}<x_{n}<x_{n-1} \implies \frac{2}{(n-1)^{2}}< \frac{2}{n^{2}}< \frac{2}{(n+1)^{2}}
$$

Si considerino i raggi:

$$
\delta_{1}= \frac{x_{n}-x_{n+1}}{2};\qquad \delta_{2}=\frac{x_{n-1}-x_{n}}{2};\qquad \delta = \frac{\min (\delta_{1},\delta_{2})}{2}
$$

E l'intorno:

$$
I_{\delta}(x_{n})=\ ]x_{n}-\delta; x_{n}+\delta[
$$

Dimostriamo che è impossibile trovare $x_{m} \neq x_{n}$ in $A \cap I_{\delta}(x_{n})$.

$$
 \frac{2}{(n-1)^{2}}< \frac{2}{m^{2}}< \frac{2}{(n+1)^{2}}
$$

$$
(n-1)^{2}<m^{2}<(n+1)^{2}
$$

$$
n-1<m<n+1
$$

Tuttavia, l'unico intero compreso tra $n-1$ e $n+1$ è:

$$
\frac{(n-1)+(n+1)}{2}=n
$$

Allora si deve avere che $m=n$, ma questo contraddice l'ipotesi per cui $x_{m} \neq x_{n}$, allora non si può trovare un altro $x_{m} \in A$ nell'intorno.

Dimostriamo che $x_{1}$ è un punto isolato.

Consideriamo il raggio:

$$
r= \frac{x_{1}-x_{2}}{2}
$$
Dunque l'intorno:

$$
I_{r}(x_{1})=\ ] x_{1}-r; x_{1}+r[
$$

Dimostriamo che non può esistere $x_{N} \in A: x_{2}<x_{N}<x_{1}$:

$$
\frac{2}{2^{2}}< \frac{2}{N^{2}}< \frac{2}{1^{2}}
$$

$$
1<N<2
$$

Assurdo poiché $N \in \mathbb{N}$, quindi non può esistere $x_N \in A$ nell'intorno $I_{r}(x_{1})$.

$\mathbf{Q.E.D.} \qquad\blacksquare$

---

$\huge{\mathbf{Esercizio\ 72.}}$

$\mathbf{a.}$

**Vero**, perché se $I \subset \mathbb{N}$ è un insieme finito, allora è composto solo da punti isolati, come si è visto nell'esercizio $\mathbf{73.}$, quindi vediamo la dimostrazione nel caso in cui $I$ è infinito.

Si considerino:


$$
f: A \subseteq \mathbb{N} \to \mathbb{N}
$$

$$
I=I_m(f) \text{ essendo $I_{m}(f)$ l'insieme immagine di $f$ }
$$

Allora:

$$
I_{m}(f) \subseteq \mathbb{N}
$$

Quindi $I$ si può ordinare. Indichiamo con $y_{n}$ l'$n$-esimo elemento più grande di $I_{m}(f)$, quindi:

$$
y_{1}<y_{2}<y_{3}<\dots<y_{n-1}<y_{n}<y_{n+1}<\dots
$$

Si scelga:

$$
\delta= \frac{\min(y_{n+1}-y_{n}, y_{n}-y_{n-1})}{2}
$$

E quindi l'intorno:

$$
I_{\delta}(y_{n})=\ ]y_{n}-\delta; y_{n}+\delta[
$$

$y_{m} \neq y_{n}: y_{m} \in I_{\delta}(y_{n})$ implica che:

$$
y_{n-1}<y_{m}<y_{n+1}
$$

Poiché $I_{\delta}(y_{n})$ è un sottinsieme dell'intorno:

$$
]y_{n-1}; y_{n+1}[
$$

Tuttavia, se questo elemento $y_{m} \in I$ esiste, dev'essere $y_{m}=y_{n}$ proprio perché $I$ è ordinabile. Questo prova che non esistono punti in $I_{\delta}(y_{n}) \cap I-\{ y_{n} \}$, cioè che $y_{n}$ è un punto isolato.

Anche $y_{1}$ è un punto isolato, perché basta scegliere:

$$
\delta^* = \frac{y_{2}-y_{1}}{2}
$$

Non vi saranno elementi di $I$ nell'intorno $I_{\delta^*}(y_{1})$, dato che $y_{1}$ è il minimo di $I$ per definizione, e nemmeno nell'intorno destro, perché quest'ultimo è un sottinsieme di:

$$
]y_{1}; y_{2}[
$$

che non contiene elementi di $I$ perché questi sono stati ordinati.

Alternativamente, sia $I \subseteq \mathbb{N}$; $\forall x \in I$ avremmo che:

$$
\left ]x-\frac{1}{2}; x+ \frac{1}{2}  \right[ \cap I = \{ x \}
$$

Perché se ci fosse $y \in I: y \neq x$ tale che:

$$
x-\frac{1}{2}<y< x +\frac{1}{2} 
$$

$$
2x-1 < 2y<2x+1 \\ \\ -1<2(y-x)<1 \implies 2(y-x)=0 
$$

Quindi otterremo che $y=x$, assurdo.



$\mathbf{b.}$

**Falso**, un controesempio è $\mathbb{N}$, per il quale ogni elemento è un punto isolato.

$\mathbf{c.}$

**Falso**, infatti:

$$
I= \{ x \in \mathbb{Z}: -2 \leq x \leq 2 \} = \{ -2,-1,0,1,2 \}
$$

Quindi $I$ è un insieme finito e, come si è già dimostrato, ogni suo elemento è un punto isolato.

$\mathbf{d.}$

**Vero**, questo è il contrapposito usato nella dimostrazione $\mathbf{a.}$ del $\mathbf{73.}$


$\Huge{\mathbf{Esercizio\ 76.}}$


$$
A= \left\{  x: x= 2+ \frac{1}{n}, n \in \mathbb{N}-\{ 0 \}  \right\},\ x_{0}=2.
$$

Dimostrare che $x_{0}$ è un punto di accumulazione per $A$.

L'asserto è vero poiché $2$ è l'estremo inferiore di $A$, ma non il suo minimo ($A$ non ammette minimi).

Dimostriamo intanto che $2$ non è il minimo di $A$. Se $x_{0}=2$ fosse il minimo di $A$, dovrebbe come minimo appartenere ad $A$, ma vediamo che non è così:

$$
x_{n}=x_{0}
$$

$$
2+\frac{1}{n}=2 \iff \frac{1}{n}= 0 \iff 1= 0
$$

Ovviamente falso.

Tuttavia, $2$ è l'estremo superiore di $A$.

Si vuole dimostrare che:

$$
\forall \varepsilon >0,\ \exists x_{n} \in A(x_{n}< 2+\varepsilon)
$$

$$
2+ \frac{1}{n}< 2+\varepsilon
$$

$$
\frac{1}{n}< \varepsilon \implies n > \frac{1}{\varepsilon}>0
$$

Dato che:
$$
\left\lceil  \frac{1}{\varepsilon}  \right\rceil \geq \frac{1}{\varepsilon} >0 \implies \left\lceil  \frac{1}{\varepsilon}  \right\rceil +1 >0
$$

Basta scegliere $N$ così:

$$
N= \left\lceil  \frac{1}{\varepsilon}  \right\rceil +1
$$

per trovare $N \in \mathbb{N}-\{ 0 \}$ tale che:

$$
x_{N}< 2+\varepsilon
$$

La dimostrazione è conclusa.

$\mathbf{Q.E.D.} \qquad\blacksquare$




































