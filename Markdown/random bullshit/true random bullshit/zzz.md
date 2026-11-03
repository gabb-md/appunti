$\mathbf{Esercizio}$:

Si sa che $p(x)$ è un polinomio tale che $\forall\ a,b,c \in \mathbb{Z}$, si ha che:


$$
a+b+c=2022 \implies p(a)+p(b)+p(c)=p(674)
$$

Inoltre si sa che $p(0)=-2696$. Quanto vale $p(2022)$?

$\mathbf{Bonus}$:

Trova $p(x)$.

---

$\mathbf{Soluzione}$:

Notiamo che:


$$
674+674+674=2022 
$$
Allora:


$$
p(674)+p(674)+p(674)=p(674) \implies p(674)=0
$$

Notiamo anche che:


$$
2022+0+0=2022
$$

Quindi:


$$
p(2022)+p(0)+p(0)=p(674)=0
$$


$$
p(2022)-2696-2696=0 \implies p(2022)=5392
$$
---

Passiamo al **bonus**.

Prendiamo $a,b \in \mathbb{Z}$ e $c=2022-a-b$. Ovviamente $a+b+c=a+b+2022-a-b=2022$, quindi:


$$
p(a)+p(b)+p(2022-a-b)=p(674)=0
$$

Scegliamo $k=674$, quindi:


$$
a+b+c=2022=3k
$$

Scriviamo così le nostre variabili:

$$
\begin{cases}
a=k+u \\ b=k+v \\ c=k+w
\end{cases}
$$

Allora:


$$
(k+u)+(k+v)+(k+w)=3k \implies u+v+w=0
$$


Allora possiamo concludere che:


$$
p(k+u)+p(k+v)+p(k+w)=0\ \forall\ u,v,w(u+v+w=0)
$$

Consideriamo il polinomio:

$$
q(x)=p(x+k)
$$

Cioè:


$$
\begin{cases}
p(k+u)=q(u) \\ p(k+v)=q(v) \\ p(k+w)=q(w) \\ p(k+u)+p(k+v)+p(k+w)=0
\end{cases}
$$

Da cui:

$$
q(u)+q(v)+q(w)=0
$$

Scrivendo $w=0-u-v=-(u+v)$:


$$
q(u)+q(v)+q(-(u+v)) \implies q(u)+q(v)=-q(-(u+v))
$$

Questa relazione vale per ogni $(u,v)$, quindi sostituiamo $(u,v) \mapsto (0,0)$:


$$
q(0)+q(0)=-q(-0) \implies q(0)=0
$$

Ora prendiamo $(u,v) \to (u,0)$:


$$
q(u)+q(0)=-q(-u) \implies q(u)=-q(-u)
$$

Allora $q(x)$ è dispari, perciò:

$$
q(u)+q(v)=q(u+v)
$$

$q(x)$ è una soluzione all'equazione funzionale di Cauchy:


$$
f(x+y)=f(x)+f(y)
$$

Sappiamo anche che $q(x)=p(x+k)$ è un polinomio (perché $p(x)$ è un polinomio), quindi è una funzione continua. Come ha dimostrato Darboux, l'unica soluzione continua all'equazione di Cauchy sui reali è propri quella trovata dallo stesso Cauchy su $\mathbb{Q}$:


$$
f(x)=mx
$$

Quindi:


$$
p(x+k)=q(x)=mx \implies q(x-k)=p(x)=m(x-k)
$$

$$
p(0)=-2696 \implies m(0-674)=-2696 \implies m=4
$$

Abbiamo trovato che:


$$
p(x)=4x-2696
$$

Il problema di Cauchy garantisce che questa sia l'unica soluzione polinomiale.

>***NOTA:*** Se non imponiamo che $p(x)$ sia un polinomio, basta scegliere $p(x)=A(x-674) +g(x)$, con $A(x)$ una qualsiasi fuzione *additiva* che risolve Cauchy su $\mathbb{R}$ e $g(\mathbb{Z})=0$ (come ad esempio $g(x)=\sin(2\pi x)$), e ovviamente un'infinità di funzioni definite a tratti ad hoc per soddisfare le ipotesi del problema.

---

$\mathbf{Bonus\ }2$:

Risolviamo l'equazione di Cauchy su $\mathbb{Q}$, cioè vogliamo trovare tutte le funzioni $f: \mathbb{Q} \to \mathbb{Q}$ tali che:


$$
f(x+y)=f(x)+f(y)
$$

Si consideri $f: \mathbb{N} \to \mathbb{N}$ con la stessa proprietà, proviamo a sostituire $(x,y) \to (0,0)$:


$$
f(0+0)=f(0)+f(0) \implies f(0)=0
$$

Mentre notiamo che $f(1)$:

$$
f(1)=f(1+0)=f(1)+f(0)
$$

Scegliamo $f(1)=c$ e calcoliamo $f(n)$ per $n \in \mathbb{N}$:

$$
f(n)=f(1 \cdot n)=f(1+1+\dots+1)=f(1+1)+f(1+1+\dots+1)
$$


$$
=f(1)+f(1)+f(1+1)+f(1+1+\dots+1)=nf(1)=cn
$$

(sommiamo $1$ $n$ volte, poi scomponiamo la somma sommando $f(1+1)$ e $f(1 \cdot(n-2))$ volte,  ecc.)

Estendendo $f$ a $f: \mathbb{Z} \to \mathbb{Z}$, proviamo a calcolare $f(z)$ con $z \in \mathbb{Z}$:


$$
f(z-z)=f(z)+f(-z)=f(0)=0 \implies f(z)=f(-z)
$$

Allora $f$ è dispari. Detto $\overline{z}=-z$, per $z > 0$, abbiamo che:

$$
f(\overline{z})=-f(z)=-cz=c\overline{z}
$$

Così abbiamo finito sugli interi.

Ragioniamo similmente sui razionali, calcolando direttamente $f\left( \frac{m}{n} \right)$ con $m,n \in \mathbb{Z}$:


$$
nf\left( \frac{m}{n} \right)=f\left( \frac{m}{n} \right)+f\left( \frac{m}{n} \right)+ (n-2)f\left( \frac{m}{n} \right)=f\left( 2\frac{m}{n} \right)+(n-2)f\left( \frac{m}{n} \right)=f(m)
$$


$$
nf\left( \frac{m}{n} \right)=f(m) \implies f\left( \frac{m}{n} \right)=\frac{f(m)}{n}=\frac{cm}{n}=c \frac{m}{n}
$$


$$
f\left( \frac{m}{n} \right)=c \frac{m}{n}
$$

Abbiamo concluso che la soluzione all'equazione di Cauchy sui razionali è:

$$
f(x)=mx
$$




































