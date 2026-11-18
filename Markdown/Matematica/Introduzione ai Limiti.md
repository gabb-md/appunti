$\mathbf{Definizione.}$

Un ***intorno completo*** è un intervallo limitato definito da un punto $x_{0} \in \mathbb{R}$ e due ***raggi*** $\delta_{1}, \delta_{2} >0$ in questa maniera:

$$
I_{\delta_{1},\delta_{2}}(x_{0})=\ ]x_{0}-\delta_{1};x_{0}+\delta_{2}[
$$
Nel caso in cui $\delta_{1}=\delta_{2}=\delta$ si parla di ***intorno circolare di*** $x_{0}$, così definito:

$$
I_{\delta}(x_{0})=\ ] x_{0}-\delta; x_{0}+\delta[
$$

Si dice anche che $x_{0}$ è il ***centro*** del suddetto intorno (alternativamente, che l'intorno è *centrato* in $x_{0}$).

In ogni caso, l'***ampiezza*** dell'intorno è definita come la somma dei raggi:

$$
\Delta=\delta_{1}+\delta_{2}
$$
Si introducono i concetti di ***intorno sinistro*** e ***intorno destro***. L'intorno sinistro è definito come questo intervallo:

$$
I^-_{\delta}(x_{0})=\ [x_{0}-\delta; x_{0}]
$$
Mentre l'intorno destro:

$$
I^+_{\delta}(x_{0})=\ ]x_{0}; x_{0}+\delta[
$$

Si possono anche considerare gli intorni di *meno infinito* o di *più infinito*. Un intorno di meno infinito è un intorno di questa forma:

$$
I_{-\infty}(x_{0})=\ ]-\infty; x_{0}[,\ x_{0} \in \mathbb{R}
$$
Analogamente, un intorno di più infinito è definito così:

$$
I_{+\infty}(x_{0})=\ ]x_{0}; +\infty[,\ x_{0} \in \mathbb{R}
$$

$\mathbf{Definizione.}$

Un insieme numerico infinito (cioè composto da un numero infinito di elementi) può dirsi *superiormente limitato*, *inferiormente limitato*, *limitato*.

Un insieme numerico $A$ è *superiormente illimitato* se e solo se:

$$
\exists \alpha \in \mathbb{R}: \forall x \in A(x \leq \alpha)
$$
Si dice che $A$ è *inferiormente limitato* se e solo se:

$$
\exists \beta \in \mathbb{R}: \forall x \in A(x\geq \beta)
$$
Mentre $A$ è *limitato* se e solo se è sia superiormente limitato che inferiormente illimitato. Equivalentemente:

$$
\exists k > 0, \forall x \in A(|x| \leq k)
$$

Gli insiemi, se non sono limitati, sono detti *illimitati*. Gli insiemi illimitati possono essere *illimitati superiormente*, *illimitati inferiormente* o semplicemente *illimitati*.

Un insieme numerico $A$ è *illimitato superiormente* se e solo se:

$$
\forall m \in \mathbb{R}, \exists x \in A(x > m)
$$

$A$ è *illimitato inferiormente* se e solo se:

$$
\forall m \in \mathbb{R}, \exists x \in A(x < m)
$$

Mentre è *illimitato* se e solo se è illimitato sia inferiormente che superiormente.

$\mathbf{Definizione.}$

Un *maggiorante in* $M$ di un insieme numerico $A \subseteq M$ è un $m \in M$ tale che:

$$
\forall x \in A,\ m \geq x
$$
Un *minorante in* $M$ di un insieme numerico $A \subseteq M$ è un $m \in M$ tale che:

$$
\forall x \in A,\ m \leq x
$$
$\mathbf{Definizione.}$

Dato che $A \subseteq M$.

Si definisce *estremo inferiore di* $A$ il più grande minorante di $A$.

Si definisce *estremo superiore di* $A$ il più piccolo maggiorante di $A$.

Si dice che $m \in A$ è un *minimo di* $A$ se e solo se:

$$
\forall x \in A,\ x \geq m
$$
Si dice che $m \in A$ è un *massimo di* $A$ se e solo se:

$$
\forall x \in A,\ x \leq m
$$








$\mathbf{Definizione.}$

Dato un insieme numerico $A \subseteq \mathbb{R}$, $x_{0} \in A$ è *punto isolato di* $A$ se e solo se:

$$
\exists \delta >0,\ I_{\delta}(x_{0}) \cap A = \{ x_{0} \}
$$

Cioè, se esiste almeno un intorno di $x_{0}$ che non contiene alcun elemeno di $A$ diverso da $x_{0}$, si dice che $x_{0}$ è un punto isolato di $A$.

$\mathbf{Definizione.}$

Dato un insieme numerico $A \subseteq \mathbb{R}$, $x_{0} \in \mathbb{R}$ è *punto di accumulazione* di $A$ se e solo se:

$$
\forall \delta > 0,\ \exists X \in (I_{\delta}(x_{0}) \cap A): X \neq x_{0}
$$

Cioè, se per ogni intorno di $x_{0}$ esiste almeno un $X \in A \cap I_{\delta}(x_{0})$ diverso da $x_{0}$.

---

$\mathbf{Definizione.}$

Si abbia $f: D \to \mathbb{R}$ e $x_{0}$ punto di accumulazione di $D$, si dice che $L$ è il *limite della funzione per $x$ che tende a $x_{0}$* se e solo se:

$$
\forall \varepsilon > 0, \exists \delta >0(|x-x_{0}| < \delta\implies |f(x)-L|<\varepsilon), x \neq x_0
$$

E si scrive:

$$
L= \lim_{ x \to x_{0} } f(x)
$$
$\mathbf{Definizione.}$

Una fuzione $f: D \to \mathbb{R}$ si dice *continua in* $x_{0} \in D$ se accade che:

$$
\lim_{ x \to x_{0} } f(x)=f(x_{0})
$$

Cioè quando esiste il limite della funzione in $x_{0}$ e il limite è uguale al valore assunto dalla funzione in $x_{0}$. Quando la funzione gode di questa proprietà in ogni punto del suo dominio si dice che è ***continua nel suo dominio***.

$\mathbf{Dimostrazione.}$

Una funzione $f$ costante in $]a,b[$ è continua in ogni $x_{0} \in ]a,b[$.

Si abbia $f(x)=k, k \in \mathbb{R}, \forall x \in ]a,b[$.

Preso $x_{0} \in ]a,b[$, abbiamo che:

$$
f(x_{0})=k
$$
Allo stesso modo:

$$
|f(x_{0})-k|<\varepsilon, \varepsilon > 0
$$

$$
|k-k|< \varepsilon
$$

$$
\varepsilon > 0
$$

Che è vero per ipotesi.

$\mathbf{Dimostrazione.}$

Una funzione polinomiale è continua in tutti i punti del suo dominio.

$\mathbf{Lemma\ 1.}$

Un monomio è una funzione continua nel suo dominio.

Si abbia $f: D \to \mathbb{R}, f(x)=ax^{n}$

Se $a = 0\ \lor\ n=0$, la funzione è costante nel suo dominio, quindi è continua nel suo dominio.

Supponiamo che $a,n \neq 0$.

Si verifica che:

$$
\lvert f(x)-f(x_{0}) \rvert < \varepsilon
$$

$$
|a(x^{n}-x_{0}^{n})| < \varepsilon
$$

$$
-\varepsilon< a(x^{n}-x_{0}^{n})< \varepsilon
$$

$$
ax_{0}^{n}-\varepsilon< ax^{n}< ax_{0}^{n}+\varepsilon
$$

$$
x_{0}^{n} \pm \frac{\varepsilon}{a}< x^{n}< x_{0}^{n} \mp \frac{\varepsilon}{a}
$$

In base al segno di $a$.

Se $n$ è dispari, si estra semplicemente la radice $n$-esima, quindi:

$$
\sqrt[n]{x_{0} \pm \frac{\varepsilon}{a}  } < x< \sqrt[n]{x_{0} \mp \frac{\varepsilon}{a}  }
$$

Che è un intorno di $x_{0}$.

In generale, se $n \in \mathbb{R} \setminus \{ 0 \}$:

$$
|x|< \frac{\sqrt[n]{x_{0}^{n} \mp \frac{\varepsilon}{a}  }- \sqrt[n]{x_{0} \pm \frac{\varepsilon}{a}  }}{2}
$$

$\mathbf{Lemma\ 2.}$

Se $f(x)$ e $g(x)$ sono continue in $x_{0}$, anche $h(x)=f(x)+ g(x)$ lo è.

Si abbia che:

$$
\lvert f(x)-f(x_{0}) \rvert < \varepsilon; \qquad \lvert g(x)-g(x_{0}) \rvert < \varepsilon.
$$


$$
\lvert f(x)-f(x_{0})\rvert + \lvert g(x)-g(x_{0}) \rvert < 2\varepsilon
$$

Per la disuguaglianza triangolare, si ha che:

$$
|f(x)-f(x_{0}) + g(x)-g(x_{0})| \leq \lvert f(x)-f(x_{0})\rvert + \lvert g(x)-g(x_{0}) \rvert< 2\varepsilon
$$

$$
\lvert h(x)-h(x_{0}) \rvert <2 \varepsilon
$$

Così è conclusa la dimostrazione.

Un polinomo è una somma di monomi, che sono funzioni continue, quindi un polinomio è continuo.

$\mathbf{Dimostrazione.}$

Una funzione esponenziale è continua nel suo dominio.

Sia $f(x)=a^{x}$, con $a >0, a \neq 1$.



$$
|f(x)-f(x_{0})|<\varepsilon
$$

$$
\lvert a^{x}-a^{x_{0}} \rvert < \varepsilon
$$

$$
-\varepsilon< a^{x}-a^{x_{0}}<\varepsilon
$$

$$
a^{x_{0}}-\varepsilon< a^{x}< a^{x_{0}}+ \varepsilon
$$

Supponendo $a^{x_{0}}-\varepsilon >0$.

$$
\log_{a}(a^{x_{0}} \pm \varepsilon)< x< \log_{a}(a^{x_{0}}\mp\varepsilon)
$$

Nel caso in cui $a \in ]0,1[,$ oppure $a>1$.

$\mathbf{Dimostrazione.}$

Una funzione logaritmica è continua nel suo dominio.

Sia $f(x)=\log_{a}x$, con $a>0, a \neq 1$.


$$
|f(x)-f(x_{0})<\varepsilon
$$

$$
\lvert \log_{a}x-\log_{a}x_{0} \rvert < \varepsilon 
$$

$$
\left\lvert   \log_{a} \left( \frac{x}{x_{0}} \right)  \right\rvert < \varepsilon
$$

$$
-\varepsilon< \log_{a}\left(  \frac{x}{x_{0}} \right)< \varepsilon
$$

$$
a^{\pm \varepsilon}< \frac{x}{x_{0}}< a^{\mp \varepsilon}
$$

$$
x_{0}a^{\pm \varepsilon}< x<x_{0}a^{\mp\varepsilon}
$$


Si scelga:

$$
\delta = x_{0}a^{\pm\varepsilon}-x_{0}
$$
Si nota che:

$$
-x_{0}<0 \iff x_{0}a^{\pm\varepsilon}-x_{0}<x_{0}a^{\mp\varepsilon}
$$

Allora vale che:

$$
|f(x)-f(x_{0})|< \varepsilon \implies x_{0}-\delta<x< x_{0}+\delta
$$

Perciò si è trovato che:

$$
\lim_{ x \to x_{0} } f(x)=f(x_{0})
$$

$\mathbf{Q.E.D.} \qquad\blacksquare$





































