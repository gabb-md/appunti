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

