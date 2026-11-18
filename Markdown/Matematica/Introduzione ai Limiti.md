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

Una funzione $f$ costante in $]a,b[$ è continua in $]a,b[$.

Si abbia $f(x)=k, \forall x \in ]a,b[, k \in \mathbb{R}$.

Preso $x_{0} \in ]a,b[$ si scelga:

$$
\delta = \min(x_{0}-a,b-x_{0})
$$
Dunque si consideri l'intorno:

$$
I_{\delta}(x_{0})=\ ]x_{0}-\delta;x_{0}+\delta[
$$

Allora se $x \in I_{\delta}(x_{0})$ si avrà anche che:

$$
a<x<b \implies f(x)=k
$$

Per definizione.

Si calcola che:

$$
|f(x)-f(x_{0})|=|k-k|=0, \forall x \in\ ]a,b[
$$

Quindi, per ogni $\varepsilon>0$ si ha che se $x \in I_{\delta}(x_{0})$:

$$
|f(x)-f(x_{0})|< \varepsilon
$$

In definitiva:

$$
\lim_{ x \to x_{0} } f(x)=f(x_{0})=k
$$

$\mathbf{Dimostrazione.}$

Una funzione polinomiale è continua nel suo dominio.

$\mathbf{Lemma\ 1.}$

Un monomio è una funzione continua.

Si abbia $f: D \to \mathbb{R}, f(x)=ax^{n}$, con $n>0, n \in \mathbb{N}, a \neq 0$.

Preso $x_{0} \in D$, si può scrivere:


$$
\lvert ax^{n}-ax_{0}^{n} \rvert=|a|\lvert x-x_{0} \rvert |x^{n-1}+x^{n-2}x_{0}+\dots+x_{0}^{n-2}x+x_{0}^{n-1}|
$$

Si scelgano $x$ tali che:

$$
|x-x_{0}|<r,\ r>0
$$

Si calcola che:

$$
\lvert x-x_{0} \rvert +\lvert x_{0} \rvert < r+ \lvert x_{0} \rvert 
$$

Definito $M=r+\lvert x_{0} \rvert$, si ottiene che:

$$
\lvert x_{0} \rvert < M=r+\lvert x_{0} \rvert 
$$

E con la disuguaglianza triangolare:

$$
\lvert x-x_{0}+x_{0} \rvert \leq |x-x_{0}|+ \lvert  x_{0} \rvert < M \implies \lvert x \rvert <M
$$


Ogni termine della somma di potenze  $x^{n-1-k}x_{0}^{k},\ 0 \leq k \leq n-1$ è certamente minore (o uguale) di $|x|^{n-1-k}|x_{0}|^{k}$, quindi si avrà che:

$$
\lvert  x\rvert^{n-1} +|x|^{n-2}|x_{0}|+\dots+|x_{0}|^{n-2}|x|+|x_{0}|^{n-1} < nM^{n-1}
$$
Quindi si trova che:

$$
|a|\lvert x-x_{0} \rvert |x^{n-1}+x^{n-2}x_{0}+\dots+x_{0}^{n-2}x+x_{0}^{n-1}| <  \lvert a \rvert \lvert x-x_{0} \rvert nM^{n-1}
$$

Si deve avere quindi che:

$$
\begin{cases}
|a| \lvert x-x_{0} \rvert nM^{n-1}<\varepsilon \\ \\\lvert x-x_{0} \rvert <r
\end{cases}
$$

$$
\begin{cases}
\lvert x-x_{0} \rvert < \frac{\varepsilon}{\lvert a \rvert nM^{n-1}} \\ \\ \lvert x-x_{0} \rvert <r
\end{cases}
$$

Si scelga quindi:

$$
\delta=\min\left( r, \frac{\varepsilon}{\lvert a \rvert nM^{n-1}} \right)
$$

Se accade che:

$$
x \in ]x_{0}-\delta, x_{0}+\delta[
$$

Si verificherà a prescindere che:

$$
\lvert x-x_{0} \rvert < \frac{\varepsilon}{\lvert a \rvert nM^{n-1}}
$$

Quindi:

$$
\lvert f(x)-f(x_{0}) \rvert \leq \lvert a \rvert \lvert x-x_{0} \rvert nM^{n-1}< \lvert a \rvert \cdot \frac{\varepsilon}{\lvert a \rvert\ nM^{n-1}}\cdot nM^{n-1}=\varepsilon
$$

In definitiva si avrà che:

$$
\lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$

Per $\delta$ opportunamente scelto.

> ***NOTA:*** nel caso in cui $an=0$, $f(x)$ è una funzione costante, la cui continuità è già stata dimostrata.

$\mathbf{Lemma\ 2.}$

Se $f(x)$ e $g(x)$ sono continue in $x_{0}$, anche $h(x)=f(x)+g(x)$ lo è.

Si abbia:

$$
\lvert f(x)-f(x_{0}) \rvert < \frac{\varepsilon}{2}; \qquad \lvert g(x)-g(x_{0})\rvert < \frac{\varepsilon}{2} 
$$
Perché per la continuità di $f$ e di $g$ in $x_{0}$ esistono $\delta_{1},\delta_{2}$ tali che:

$$
\lvert x-x_{0} \rvert < \delta_{1} \implies \lvert f(x)-f(x_{0}) \rvert < \frac{\varepsilon}{2};\qquad \lvert x-x_{0} \rvert <\delta_{2}\implies \lvert g(x)-g(x_{0}) \rvert < \frac{\varepsilon}{2}
$$

Basta scegliere:

$$
\delta=\min(\delta_{1},\delta_{2})
$$

Affinché le condizioni siano verificate contemporaneamente. 

Sommando membro a membro:

$$
\lvert f(x)-f(x_{0}) \rvert +\lvert g(x)-g(x_{0}) \rvert < \varepsilon
$$

Per la disuguaglianza triangolare:

$$
\lvert f(x)+g(x)-f(x_{0})-g(x_{0}) \rvert \leq \lvert f(x)-f(x_{0}) \rvert +\lvert g(x)-g(x_{0}) \rvert 
$$

Quindi:

$$
\lvert f(x)+g(x)-(f(x_{0})+g(x_{0})) \rvert \leq \lvert f(x)-f(x_{0}) \rvert +\lvert g(x)-g(x_{0}) \rvert < \varepsilon
$$

Cioè:

$$
\lvert h(x)-h(x_{0}) \rvert < \varepsilon
$$

A condizione che:

$$
\lvert x-x_{0} \rvert < \delta
$$


Un polinomio è una somma di monomi, che come si è dimostrato nel $\mathbf{Lemma\ 1.}$ sono funzioni continue. Il $\mathbf{Lemma\ 2.}$ dimostra che una somma di funzioni continue è una funzione continua, quindi un polinomio è una funzione continua.

Per una generalizzazione si introducono due nuovi lemmi.

$\mathbf{Lemma\ 3.}$

Una funzione $f: D \to \mathbb{R}, f(x)=ax^{k}, k \in \mathbb{Z}^-$ è continua nel suo dominio.

Si ricorda che:

$$
x^{a}=\frac{1}{x^{-a}}
$$

Quindi:

$$
ax^{k}= \frac{a}{x^{-k}}
$$

$k<0 \implies -k>0$, si pone $n=-k, n \in \mathbb{N}$ e si ottiene che:

$$
f(x)= \frac{a}{x^{n}}
$$

Posto:

$$
\lvert x-x_{0} \rvert < \frac{\lvert x_{0} \rvert }{2}
$$

Si calcola:

$$
\lvert x_{0} \rvert -\lvert x-x_{0} \rvert > \frac{\lvert x_{0} \rvert }{2}
$$

Per la disuguaglianza triangolare:

$$
\lvert x-x_{0}+x_{0} \rvert \geq \lvert x_{0} \rvert - \lvert x-x_{0} \rvert > \frac{\lvert x_{0} \rvert }{2}
$$

$$
\lvert x \rvert > \frac{\lvert x_{0} \rvert }{2}
$$

Si può ottenere anche che:

$$
\lvert x-x_{0} \rvert +\lvert x_{0} \rvert < \frac{3}{2} \lvert x_{0} \rvert 
$$

$$
\lvert x-x_{0}+x_{0} \rvert \leq \lvert x-x_{0} \rvert + \lvert x_{0} \rvert < \frac{3}{2} \lvert x_{0} \rvert 
$$

$$
\lvert x \rvert < \frac{3}{2} \lvert x_{0} \rvert 
$$


Si ottiene che:

$$
\frac{\lvert x_{0} \rvert }{2}< \lvert x \rvert < \frac{3}{2} \lvert x_{0} \rvert 
$$


Avendo:

$$
\lvert f(x)-f(x_{0}) \rvert= \left\lvert  \frac{a}{x^{n}}- \frac{a}{x_{0}^{n}}  \right\rvert = \lvert a \rvert \left\lvert  \frac{(x-x_{0})(x^{n-1}+x^{n-2}x_{0}+\dots+x_{0}^{n-2}x+x_{0}^{n-1})}{x^{n}x_{0}^{n}}  \right\rvert
$$

$$
\lvert f(x)-f(x_{0}) \rvert = \lvert a \rvert \lvert x-x_{0} \rvert \frac{\lvert x^{n-1}+x^{n-2}x_{0}+\dots+x_{0}^{n-2}x+x_{0}^{n-1} \rvert}{\lvert x \rvert^{n} \lvert x_{0} \rvert^{n} } 
$$

Per la disuguaglianza triangolare, si ha che:

$$
\lvert x^{n-1}+x^{n-2}x_{0}+\dots+x_{0}^{n-2}x+x_{0}^{n-1} \rvert \leq \lvert x \rvert ^{n-1}+\lvert x \rvert ^{n-2}\lvert x_{0} \rvert +\dots+\lvert x_{0} \rvert ^{n-2}\lvert x \rvert +\lvert x_{0} \rvert ^{n-1}
$$

Maggiorando il numeratore e minorando il denominatore, noto che $\frac{\lvert x_{0} \rvert}{2}< \lvert x \rvert< \frac{3}{2} \lvert x_{0} \rvert$, si ha che:

$$
\lvert f(x)-f(x_{0}) \rvert \leq \lvert a \rvert \lvert x-x_{0} \rvert \cdot \frac{n\left(  \frac{3}{2} \lvert x_{0} \rvert  \right)^{n-1}}{ \frac{\lvert x_{0} \rvert^{n} }{2^{n}} \cdot  \lvert x_{0} \rvert^{n} }  
$$

Dopo le dovute semplificazioni:

$$
\lvert f(x)-f(x_{0}) \rvert \leq \lvert a \rvert \lvert x-x_{0} \rvert \frac{2 \cdot 3^{n-1}n}{\lvert x_{0} \rvert ^{n+1}}
$$


$$
\lvert a \rvert \lvert x-x_{0} \rvert \frac{2 \cdot 3^{n-1}n}{\lvert x_{0} \rvert ^{n+1}} < \varepsilon 
$$

$$
\lvert x-x_{0} \rvert < \frac{\varepsilon \lvert x_{0} \rvert ^{n+1}}{n\lvert a \rvert 2\cdot 3^{n-1}}
$$

Si ricorda che dev'essere anche:

$$
\begin{cases}
\lvert x- x_{0} \rvert < \frac{\lvert x_{0} \rvert }{2} \\ \\ \lvert x-x_{0} \rvert < \frac{\varepsilon \lvert x_{0} \rvert ^{n+1}}{n\lvert a \rvert 2\cdot 3^{n-1}}
\end{cases}
$$

Affinché siano verificate entrambe le condizioni, basta scegliere:

$$
\delta= \min\left(  \frac{\lvert x_{0} \rvert }{2}, \frac{\varepsilon \lvert x_{0} \rvert ^{n+1}}{n\lvert a \rvert 2\cdot 3^{n-1}} \right)
$$

Quindi:

$$
\lvert x-x_{0} \rvert < \delta \implies \lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$

Così si è provato che:

$$
\lim_{ x \to x_{0} } f(x)=f(x_{0})
$$

Cioè che $f$ è continua in $x_{0}$.

$\mathbf{Lemma\ 4.}$

Sia $f: D \to \mathbb{R}, f(x)=ax^{\alpha}, \alpha \in \mathbb{R}$, $f$ è continua in ogni punto del suo dominio, tranne al più in $0$.

Se $\alpha=0$, $f$ è costante ma non definita in $x=0$, quindi è continua in ogni punto del suo dominio.

Se $\alpha \not\in \mathbb{Q}$, $f$ è definita solo per valori positivi di $x$, quindi:

$$
\lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$

$$
\lvert ax^{\alpha}-ax_{0}^{\alpha} \rvert< \varepsilon 
$$

$$
-\varepsilon< ax^{\alpha}-ax_{0}^{\alpha}<\varepsilon
$$

$$
ax_{0}^{\alpha}-\varepsilon<ax^{\alpha}<ax_{0}^{\alpha}+\varepsilon
$$

$$
x_{0}^{\alpha} \pm \frac{\varepsilon}{a} <x^{\alpha}<x_{0}^{\alpha}\mp \frac{\varepsilon}{a}
$$

La scelta dei segni $\pm, \mp$ non è arbitraria, ma dipende dal segno di $a$.

Nell'eventualità in cui $x_{0}^{\alpha} \pm \frac{\varepsilon}{a}<0$, basta scegliere un $\tilde{\varepsilon}<\varepsilon$ per cui invece questo numero è positivo. Ripercorrendo i passaggi a ritroso si otterrà che:

$$
\lvert f(x)-f(x_{0}) \rvert <\tilde{\varepsilon}<\varepsilon
$$
$$
\lvert f(x)-f(x_{0}) \rvert<\varepsilon
$$



$$
\left( x_{0}^{\alpha}\pm \frac{\varepsilon}{a} \right)^{1/\alpha}<x<\left( x_{0}^{\alpha}\mp \frac{\varepsilon}{a} \right)^{1/\alpha}\qquad (1)
$$

Scelto quindi:

$$
\delta=\min \left (\left\lvert  x_{0}-\left( x_{0}^{\alpha}\pm \frac{\varepsilon}{a} \right)^{1/\alpha}  \right\rvert,\left\lvert  \left(x_{0}^{\alpha}\mp \frac{\varepsilon}{a} \right)^{1/\alpha}-x_{0}  \right\rvert  \right)
$$

Poiché $\alpha >0$ $f$ è monotona crescente, questo implica che se:

$$
\lvert x-x_{0} \rvert < \delta
$$

$x$ appartiene anche all'intervallo asimmetrico precedentemente individuato, per cui si aveva:

$$
\lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$

Allora:

$$
\lvert x-x_{0} \rvert <\delta \implies \lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$

Cioè che:

$$
\lim_{ x \to x_{0} } f(x)=f(x_{0})
$$

Nel caso in cui $\alpha <0$ è sufficiente invertire i versi della $(1)$.

Nell'eventualità in cui $\alpha=\frac{p}{q}$, con $p,q \in \mathbb{Z}, q \neq 0$, la funzione è continua in ogni punto del suo dominio escluso al più $0$. Se $p=0$, la funzione è costante, e si ha:

$$
f(x)=a,\ x \neq 0
$$
Che si è già dimostrato essere continua nei punti del suo dominio.

Se $q=1$, l'esponente è intero, quindi $f$ è continua come si è mostrato nel $\mathbf{Lemma\ 3.}$

Altrimenti, si noti che se $\text{mcd}(p,q)=1$ e $q$ dispari:

$$
x^{p/q}= \begin{cases}
(-x)^{p/q} \text{ con $p$ pari, si ha $f$ pari } \\ \\ -(-x)^{p/q} \text{ con $p$ dispari, si ha $f$ dispari }
\end{cases} \qquad (2)
$$



$\mathbf{Lemma\ 4.1.}$

Se una funzione pari è continua in $x_{0}$, lo è anche in $-x_{0}$.

Se si ha che:

$$
\lim_{ x \to x_{0} } f(x)=f(x_{0})
$$

Allora per ogni $\varepsilon >0$ esiste un $\delta >0$ tale per cui:

$$
\lvert x-x_{0} \rvert <\delta \implies \lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$


$$
\lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$

Si consideri l'intorno:

$$
I_{\delta}(-x_{0})=]-x_{0}-\delta;-x_{0}+\delta[
$$


Per $x \in I_{\delta}(-x_{0})$ si ha che:

$$
-x_{0}-\delta<x<-x_{0}+\delta \iff x_{0}-\delta<-x<x_{0}+\delta
$$

Allora è facile calcolare che:

$$
\lvert f(x)-f(-x_{0}) \rvert = \lvert f(-x)-f(x_{0}) \rvert <\varepsilon
$$

Quindi:

$$
\lvert x+ x_{0}\lvert <\delta \implies \lvert f(x)-f(-x_{0}) \rvert <\varepsilon
$$

Cioè:

$$
\lim_{ x \to -x_{0} } f(x)=f(-x_{0})
$$

Una funzione dispari continua in $x_{0}$ è continua anche in $-x_{0}$.

Se si sa che:

$$
\lim_{ x \to x_{0} }f(x) =f(x_{0})
$$

Cioè che per ogni $\varepsilon>0$ esiste $\delta >0$ tale che:

$$
\lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$

Si consideri l'intorno:

$$
I_{\delta}(-x_{0})=]-x_{0}-\delta;-x_{0}+\delta[
$$

Per ogni $x \in I_{\delta}(-x_{0})$ si ha che:

$$
-x_{0}-\delta<x<-x_{0}+\delta \iff x_{0}-\delta<-x<x_{0}+\delta
$$

Si calcola allora che $\forall x \in I_{\delta}(-x_{0})$:

$$
|f(x)-f(-x_{0})|=\lvert -f(-x)-(-f(x_{0})) \rvert=\lvert f(-x)-f(x_{0}) \rvert<\varepsilon  
$$

$$
\lvert f(x)-f(-x_{0}) \rvert <\varepsilon
$$

Perciò si è scoperto che:

$$
\lvert x+x_{0} \rvert <\delta \implies \lvert f(x)-f(-x_{0}) \rvert <\varepsilon
$$

Il che significa:

$$
\lim_{ x \to -x_{0} } f(x)=f(-x_{0})
$$

Utilizzando il $\mathbf{Lemma\ 4.1.}$ nella $(2)$ si vede che basta dimostrare la continuità di $f$ nel ramo positivo per dimostrarla in tutto il dominio escluso al più $0$. Per fare ciò si può procedere analogamente al caso in cui $\alpha \not\in \mathbb{Q}$.

Si conclude così la dimostrazione.

$\mathbf{Dimostrazione.}$

Una funzione logaritmica è continua in tutto il suo dominio.

Si abbia $f: D \to \mathbb{R}, f(x)=\log_{a}(x),a>0,a \neq 1$.

Preso $x_{0} \in D$ e un qualsiasi $\varepsilon >0$:

$$
\lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$

$$
\lvert \log_{a}(x)-\log_{a}(x_{0}) \rvert <\varepsilon
$$

$$
\left\lvert  \log_{a}\left(  \frac{x}{x_{0}} \right)  \right\rvert <\varepsilon
$$

$$
-\varepsilon<\log_{a}\left(  \frac{x}{x_{0}} \right)<\varepsilon
$$

$$
a^{\pm \varepsilon}< \frac{x}{x_{0}}<a^{\mp\varepsilon}
$$

$$
x_{0}a^{\pm \varepsilon}< x<x_{0}a^{\mp\varepsilon}
$$

Il segno è da scegliere opportunamente a seconda dell'intervallo di appartenenza di $a$.

Si scelga:

$$
\delta= \min(\lvert x_{0}-x_{0}a^{\pm \varepsilon} \rvert, \lvert x_{0}-x_{0}a^{\mp\varepsilon} \rvert ) 
$$

E si consideri l'intorno:

$$
I_{\delta}(x_{0})=] x_{0}-\delta;x_{0}+\delta[
$$

e si noti che:

$$
x \in I_{\delta}(x_{0}) \implies x_{0}a^{\pm \varepsilon}< x<x_{0}a^{\mp\varepsilon} \implies \lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$

Quindi si è trovato che:

$$
\lvert x-x_{0} \rvert <\delta \implies \lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$

Cioè:

$$
\lim_{ x \to x_{0} } f(x)=f(x_{0})
$$

$\mathbf{Dimostrazione.}$

Una funzione esponenziale è una funzione continua in ogni punto del suo dominio.

Si abbia $f: D \to \mathbb{R}, f(x)=a^{x}$.

Se $a=0$ la funzione non è definita in $x \leq 0$, mentre è costante nel suo dominio, perciò è continua nel suo dominio. 

Se $a=1$ la funzione è costante in tutto il suo dominio, in particolare $f(x)=1, \forall x \in D$.

In generale, preso $x_{0} \in D$ e $\varepsilon>0$:

$$
\lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$

$$
\lvert a^{x}-a^{x_{0}} \rvert <\varepsilon
$$

$$
-\varepsilon<a^{x}-a^{x_{0}}<\varepsilon
$$

$$
a^{x_{0}}-\varepsilon<a^{x}<a^{x_{0}}+\varepsilon
$$

Nell'eventualità in cui $a^{x_{0}}-\varepsilon \leq 0$, è sufficiente scegliere $\tilde{\varepsilon}<\varepsilon$ per cui $a^{x_{0}}-\tilde{\varepsilon}>0$, si otterrà, ripercorrendo i passaggi a ritroso:

$$
\lvert f(x)-f(x_{0}) \rvert < \tilde{\varepsilon}<\varepsilon
$$

Cioè:

$$
\lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$


$$
\log_{a}(a^{x_{0}} \pm \varepsilon)< x< \log_{a}(a^{x_{0}}\mp \varepsilon)
$$

I segni $\pm,\mp$ non sono arbitrari ma sono da scegliere a seconda dell'intervallo di appartenenza di $a$.

Si sceglie:

$$
\delta = \min(|x_{0}-\log_{a}(a^{x_{0}} \pm \varepsilon)|, |x_{0}-\log_{a}(a^{x_{0}}\mp \varepsilon)|)
$$

E l'intorno:

$$
I_{\delta}(x_{0})=]x_{0}-\delta; x_{0}+\delta[
$$

Ma:

$$
x \in I_{\delta}(x_{0}) \implies \log_{a}(a^{x_{0}} \pm \varepsilon)< x< \log_{a}(a^{x_{0}}\mp \varepsilon) \implies \lvert  f(x)-f(x_{0}) \rvert <\varepsilon
$$

Si è trovato che:

$$
\lvert x-x_{0} \rvert <\delta \implies \lvert f(x)-f(x_{0}) \rvert <\varepsilon 
$$

Cioè:

$$
\lim_{ x \to x_{0} } f(x)=f(x_{0})
$$

Se $a<0$ la funzione non è definita su $\mathbb{R}$.

$\mathbf{Dimostrazione.}$

$\sin x$ è continua nel suo dominio.

Si abbia:

$$
\lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$



$$
\lvert \sin x-\sin x_{0} \rvert <\varepsilon
$$

Dalle formule di prostaferesi

$$
\sin x-\sin x_{0}=2\cos \left( \frac{x+x_{0}}{2} \right)\sin\left( \frac{x-x_{0}}{2} \right)
$$

$$
\left\lvert  2  \cos \left( \frac{x+x_{0}}{2} \right)\sin\left( \frac{x-x_{0}}{2} \right)  \right\rvert <\varepsilon
$$

Si sa che:

$$
\cos X \leq 1
$$

E che:

$$
\sin X \leq X
$$
Quindi:

$$
\left\lvert  2  \cos \left( \frac{x+x_{0}}{2} \right)\sin\left( \frac{x-x_{0}}{2} \right)  \right\rvert \leq \left\lvert  2\cdot 1 \cdot \frac{x-x_{0}}{2}  \right\rvert =\lvert x-x_{0} \rvert 
$$

Si scelga quindi l'intorno centrato in $x_{0}$ di raggio $\delta = \varepsilon$, e si otterrà:

$$
\lvert \sin x-\sin x_{0} \rvert \leq\lvert x-x_{0} \rvert <\delta=\varepsilon
$$

Da cui:

$$
\lvert \sin x -\sin x_{0} \rvert<\varepsilon 
$$

E quindi si è trovato che:

$$
\lvert x-x_{0} \rvert <\delta \implies \lvert f(x)-f(x_{0}) \rvert <\varepsilon
$$

Cioè:

$$
\lim_{ x \to x_{0} } f(x)=f(x_{0})
$$

$\cos x$ è una funzione continua perché è una traslazione di $\sin x$.

$\mathbf{Lemma\ 5.}$

Se $f$ è continua in $x_{0}$ e $f(x_{0}) \neq 0$, anche $g(x)=\frac{1}{f(x)}$ è continua in $x_{0}$.

...












































































