<h1 style="text-align:center;"> POLINOMI <h1>

Peak

<br/><br/>
<h1 style="text-align:center;"> STIME, SERIE E DENSITÀ<h1>

<br/><br/>
<details><summary>  </summary> </details>
## 1. Serie

Sia $a_{n}$ una successione di numeri reali, la *serie associata ad* $a_{n}$ è la somma di tutti gli elementi della successione. Il comportamento di una serie associata ad una successione di termini finiti è prevedibile: il risultato della serie è un numero reale che si ottiene sommando manualmente tutti i termini (oppure trovando una formula chiusa). Nel caso delle serie infinite invece si possono distinguere tre diversi comportamenti:

- Convergenza: si dice che una serie *converge* ad un particolare numero reale $r$ quando, asintoticamente, tende a quel numero, cioè se è possibile avvicinarsi ad $r$ in un intervallo di raggio arbitrariamente piccolo $\epsilon >0$. Più rigorosamente, sia $S(n)$ il valore di una serie infinita calcolato fino all'indice $n \in \mathbb{N}$, si dice che la serie converge ad $S$ se per ogni $\epsilon >0$ esiste un $N$ tale che per ogni $n > N$ accade che $\epsilon > |S(n)-S|$.
<br/>
-  Divergenza: Sia $S(n)$ il valore il valore di una serie infinita $S$ calcolato fino all'indice $n \in \mathbb{N}$, si dice che $S$ *diverge* se per ogni $M>0$ esiste un $m$ tale che $|S(m)|> M$ per ogni $n \geq m$. Una serie può divergere a $\pm \infty$.
<br/>
-  Comportamento indefinito: una serie infinita è *indefinita* quando non converge e non diverge. Praticamente ciò vuol dire che è indefinita quando il valore della serie non si può determinare univocamente.

## 2. Densità e densità naturale o asintotica 

La densità di un insieme di numeri naturali $A$ valutata in $n$ è concettualmente equivalente alla probabilità di estrarre uno qualsiasi degli elementi appartenente ad $A$ dal sottoinsieme di $\mathbb{N}$ contenente i numeri naturali compresi nell'intervallo0 $[1,n]$. Siano $\delta(A,n)$ la densità di $A$ valutata in $n$ e $N=\{a \in \mathbb{N}: 1 \leq a \leq n\}$ l'insieme di interi positivi da $1$ ad $n$, scriviamo che:

$$
\delta(A,n)=\frac{|A \cap N|}{n}
$$

La densità quindi si calcola dividendo la cardinalità dell'intersezione $A \cap N$ per il numero $n$ in cui si valuta.

La *densità naturale* o *densità asintotica* di un insieme $A$ è definita come:

$$
\delta(A)=\lim_{ n \to \infty } \frac{A \cap N}{n}
$$

dove $N$ è l'insieme così definito: $N=\{a \in \mathbb{N}: 1 \leq a \leq n\}$.

La densità dei numeri pari per un certo $n$ è $\delta(P,n)=\frac{\left\lfloor  \frac{n}{2}  \right\rfloor}{n}$, è semplice calcolare che $\delta(P)=\frac{1}{2}$ ($P$ denota l'insieme dei numeri pari).

È banale osservare che la densità naturale di un insieme finito di elementi è uguale a $0$. È più interessante studiare la densità naturale di insiemi infiniti, come ad esempio l'insieme dei numeri primi, la cui densità naturale è comunque uguale a $0$, perché (approssimativamente) $\lim_{ n \to \infty } \frac{\pi(n)}{n}=\lim_{ n \to \infty } \frac{n}{n\log n}=0$, dal teorema dei numeri primi.
<br/><br/>

## 3. Stime

Una *stima* è una valutazione approssimativa sul valore di un certo numero. Si può stimare ad esempio la cardinalità di un insieme costruito in modo particolare (ad es. la cardinalità delle coppie di numeri primi gemelli fino ad un certo $n$ naturale), oppure il valore di convergenza di una serie. Spesso non è necessario calcolare esattamente un valore particolare, potrebbe essere semplicemente necessario dimostrare che il valore cercato si trovi in un certo intervallo. Ad esempio consideriamo la famosa serie infinita $\zeta(2)$:
$$
\zeta(2)=\sum_{k=1}^{\infty} \frac{1}{k^2} 
$$

è ben noto che $\zeta(2)=\frac{\pi^{2}}{6}$, ma si può dimostrare più facilmente la sua convergenza provando che $1 < \zeta(2) < 2$ utilizzando la serie di Mengoli notando che $k^2 >k(k-1)$ (per i più audaci, si ricorda anche che $\frac{1}{k(k+1)}=\frac{1}{k}-\frac{1}{k+1}$.

<br/>

<h1 style="text-align:center;"> DISUGUAGLIANZE BANALI <h1>

<br/><br/>

## 1. Disuguaglianza tra medie

<br/>

### 1.1 Introduzione

Data una qualsiasi $n$-upla di numeri reali positivi, la media armonica $HM$, la media geometrica $GM$, la media aritmetica $AM$ e la media quadratica $QM$ di questi numeri si trovano in questa relazione:

$$
QM \geq AM \geq GM \geq HM
$$

Per esteso:

$$
\sqrt{\frac{x_{1}^2+x_{2}^2+\dots+x_{n}^2}{n} }  \geq \frac{x_{1}+x_{2}+\dots+x_{n}}{n} \geq \sqrt[n]{x_{1}x_{2}\dots x_{n}} \geq \frac{n}{\frac{1}{x_{1}}+\frac{1}{x_{2}}+\dots+\frac{1}{x_{n}}}
$$

<br/><br/>

### 1.2 Generalizzazione 

La disuguaglianza tra medie può essere generalizzata con la media delle potenze ($PM$). Siano $P$ e $p$ numeri reali diversi da $0$, allora vale la relazione:

$$
P > p \implies \sqrt[P]{\frac{x_{1}^{P}+x_{2}^{P}+\dots+x_{n}^{P}}{n}} >\sqrt[p]{\frac{x_{1}^{p}+x_{2}^{p}+\dots+x_{n}^{p}}{n}}
$$

Con $p=0$ si otterrebbe la media geometrica, con $p=1$ si ottiene la media aritmetica e con $p=-1$ si ottiene la media armonica.

In ogni caso ogni media rimane minore del massimo degli elementi e maggiore del minimo (che si ottengono con $p=+\infty$ e $p=-\infty$ rispettivamente. 

Siano $m=\min_{n}(x_{n})$ e $M=\max_{n}(x_{n})$, si ha che:

$$
M \geq PM \geq QM \geq AM \geq GM \geq HM \geq m
$$
 (con $p >2$).
 
<br/><br/>

### 1.3 Caso di uguaglianza

L'uguaglianza tra medie si ottiene se e solo se $x_{1}=x_{2}=\dots=x_{n}$, in quel caso tutte le medie sono uguali tra loro simultaneamente. Quindi:

$$
M=PM=QM=AM=GM=HM=m
$$
con $p>2$.

<br/><br/>

### 1.4 Disuguaglianza delle medie pesate

Si può associare a ciascun elemento $x_{i}$ della $n$-upla un peso reale positivo $a_i$, la $n$-upla di pesi $a_i$ è tale che $\displaystyle{\sum_{i=1}^na_{i}=1}$. Si generalizza finalmente la disuguaglianza tra medie:


$$
M \geq \sqrt[p]{\frac{a_{1}x_{1}^{p}+a_{2}x_{2}^{p}+\dots+a_{n}x_{n}^{p}}{a_{1}+a_{2}+\dots+a_{n}}} \geq \frac{a_{1}x_{1}+a_{2}x_{2}+\dots+a_{n}x_{n}}{a_{1}+a_{2}+\dots+a_{n}} \geq \sqrt[n]{x_{1}^{a_{1}}x_{2}^{a_{2}}\dots x_{n}^{a_{n}}} \geq \frac{a_{1}+a_{2}+\dots+a_{n}}{\frac{a_{1}}{x_{1}}+\frac{a_{2}}{x_{2}}+\dots+\frac{a_{n}}{x_{n}}} \geq m
$$

con $p>1$.

> ***NOTA***: sono accettabili anche valori di $p \in (0,1)$, la media $M_p$ associata è da collocarsi in $AM \geq M_p \geq GM$

<br/><br/>

## 2. Disuguaglianza di Cauchy-Schwarz

<br/><br/>

### 2.1 Introduzione

Per due $n$-uple qualunque di numeri reali sussiste l'uguaglianza di Cauchy-Schwarz:

$$
\left( \sum_{i=1}^{n} x_{i}y_{i} \right)^2 \leq \left( \sum_{i=1}^{n} x_{i}^2 \right) \left( \sum_{i=1}^{n} y_{i}^2 \right)
$$

<br/><br/>

### 2.2 Caso di uguaglianza

L'uguaglianza si ottiene se e solo se le due $n$-uple sono linearmente dipendenti, cioè che sono tali che ordinando opportunamente ciascun $x_{i}$ e $y_{i}$ accade che:

$$
\frac{x_{i}}{y_{i}}=\lambda
$$

con $\lambda \in \mathbb{R}$.

<h1 style="text-align:center;"> CONVESSITÀ<h1>

<br/><br/>

## 1. Definizione di convessità e di concavità

Una funzione $f$ si dice *convessa* se comunque si prendano due punti distinti $(x_{1},f(x_{1}))$ e $(x_{2},f(x_{2}))$ ogni punto del segmento che ha per estremi i due punti si trova sopra al grafico della funzione.

Una funzione $f$ si dice *concava* se, al contrario, comunque si prendano due punti distinti $(x_{1},f(x_{1}))$ e $(x_{2},f(x_{2}))$ ogni punto del segmento che ha per estremi i due punti si trova sotto al grafico della funzione.

<br/>

In altre parole, $f: D \to C$ è convessa se e solo se $\forall (x_{1},x_{2}) \in D, x_{1} \neq x_{2}$ accade che:
$$
t_{1}f(x_{1})+t_{2}f(x_{2}) \geq f(t_{1}x_{1}+t_{2}x_{2})
$$
con $t_{1}$ e $t_{2}$ reali positivi tali che $t_1+t_2=1$.

Mentre $f: D \to C$ è concava se e solo se $\forall (x_{1},x_{2}) \in D, x_{1} \neq x_{2}$ accade che:
$$
t_{1}f(x_{1})+t_{2}f(x_{2}) \leq f(t_{1}x_{1}+t_{2}x_{2})
$$
con $t_{1}$ e $t_{2}$ reali positivi tali che $t_1+t_2=1$.

<br/><br/>

### 1.1 Fatti sulla convessità

Elenchiamo alcuni fatti sulle funzioni convesse:

- $f$ è convessa se e solo se $-f$ è concava;

- $f: D \to C$ è  convessa in $I \subseteq D$ se $f$ è derivabile due volte in $I$ e $\forall x \in I$ risulta che $f''(x)>0$;
- Se $f$ e $g$ sono convesse $f+g$ è convessa;
- Se $f(x)$ è convessa, allora, per ogni $c \geq 0$, $cf(x)$ è convessa;
- Se $f(x)$ è convessa $g(x)=f(x-c)$ è convessa;
- Una combinazione lineare di funzioni convesse è una funzione convessa.

<br/><br/>

### 1.2 Trucco della tangente

<h1 style="text-align:center;"> ... <h1>
<br/><br/>

## 2. Disuguaglianza di Jensen

La disuguaglianza di Jensen generalizza la disuguaglianza precedentemente ricavata per una funzione convessa.

Se $f: D \to C$ è convessa, per ogni $(x_1, x_{2},\dots,x_{n}) \in D$ e per ogni $(t_{1},t_{2},\dots,t_{n}) \in \mathbb{R}^+$ tale che $\displaystyle{\sum_{i=1}^{n}}t_{i}=1$, si ha che:

$$
t_{1}f(x_{1})+t_{2}f(x_{2})+\dots+t_{n}f(x_{n}) \geq f(t_{1}x_{1}+t_{2}x_{2}+\dots+t_{n}x_{n})
$$

In forma compatta:

$$
\sum_{i=1}^{n} t_{i}f(x_{i}) \geq f\left(  \sum_{i=1}^{n} t_{i}x_{i} \right)
$$

<br/><br/>

> ***AGGIUNGERE TANGENT LINE TRICK 1.2 E IL CAPITOLO SUI POLINOMI***


