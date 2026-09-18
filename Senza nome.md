$\mathbf{Problema\ } 1.$

La risposta corretta è $\mathbf{C.}$

$q=3.2 \times 10^{-6} \text{C}$

$q+q_{1}=0 \implies q_{1}=-q$

$q_{1}=ne \implies n=\frac{-q}{e}= \frac{-3.2 \times 10^{-6}C}{-1.6 \times 10^{-19}C}=2.0 \times 10^{13}$

$\mathbf{Problema\ }2.$

$\mathbf{B.}$ 

Gli oggetti si attraggono.

$\mathbf{Problema\ }3.$

$$
F(R)=k \frac{Q \cdot 2Q}{R^2}=k \frac{2Q^2}{R^2}
$$

$$
F(2R)= k\frac{2Q^2}{(2R)^2}= k\frac{2Q^2}{4R^2}=\frac{F(R)}{4}
$$

La risposta corretta è $\mathbf{A.}$

$\mathbf{Problema\ }4.$

La risposta corretta è $\mathbf{D.}$

La particella $2$ è carica negativamente, pertanto si muove in senso opposto rispetto al vettore del campo elettrico $\vec{E}$, perciò se la particella va verso l'alto, il campo elettrico dev'essere orientato in basso.

$\mathbf{Problema\ }5.$

La risposta corretta è $\mathbf{C.}$

Secondo il teorema di Gauss:

$$
\phi_{s}(\vec{E})=\frac{Q}{\varepsilon_{0}}
$$
Dato che la carica interna $q$ è la stessa, il flusso è lo stesso.

$\mathbf{Q.E.D.} \qquad\blacksquare$

$\mathbf{Problema\ } 6.$

Consideriamo il cubo $\hat{C}$ di lato $L=2\ell$ e il cubo originale $C$ di lato $\ell$, e orientiamo $\hat{C}$ nello spazio in modo che il suo centro geometrico coincida con la posizione di $q$. Dal teorema di Gauss sappiamo che:

$$
\phi_{\hat{C}}(\vec{E})= \frac{q}{\varepsilon_{0}}
$$
Dato che $C$ è $\frac{1}{8}$ di $\hat{C}$, concludiamo che:

$$
\phi_{C}(\vec{E})= \frac{\phi_{\hat{C}}(\vec{E})}{8}= \frac{q}{8\varepsilon_{0}}
$$

$\mathbf{Problema\ } 7.$

La risposta corretta è $\mathbf{A.}$

$$
E_{A}(R)=\frac{Q}{4\pi \varepsilon_{0}R_{A}^3}R_{A}=\frac{Q}{4\pi\varepsilon_{0}R_{A}^2}=\frac{\sigma S_{A}}{S_{A} \varepsilon_{0}}=\frac{\sigma}{\varepsilon_{0}}
$$

$$
E_{B}(R)= \frac{Q}{4\pi \varepsilon_{0}R_{B}^3}R_{B}=\frac{Q}{4\pi R_{B}^2 \varepsilon_{0}}=\frac{\sigma S_{B}}{S_{B} \varepsilon_{0}}=\frac{\sigma}{\varepsilon_{0}}
$$

$$
\frac{E_{A}(R)}{E_{B}(R)}=\frac{\frac{\sigma}{\varepsilon_{0}}}{\frac{\sigma}{\varepsilon_{0}}}=1
$$
$$
\square
$$

$\mathbf{Problema\ }8.$

La risposta corretta è $\mathbf{E.}$

Sia $\vec{E}$ il campo elettrico localmente uniforme nei pressi di una particella di massa $m$ caricata positivamente $+q$.

Con eccellente approssimazione $\vec{G}_{i} = \vec{G}_{f}$ per piccoli spostamenti, allora resta che:

$$
\vec{P}_{f}=\vec{P}_{i}=m\vec{g}_{i}
$$
Per ipotesi, $\vec{E}$ è uniforme, quindi è banale che:

$$
\vec{E}_{i}=\vec{E}_{f}=\vec{E} \implies \vec{F}_{i}=\vec{F}_{f}
$$

dove $\vec{F}=q\vec{E}$ è la forza per effetto del campo elettrico.

Dunque, dire che:

$$
\vec{F}_{i}+\vec{P}_{i}=0
$$
è equivalente a dire che:

$$
\vec{F}_{f}+\vec{P}_{f}=0
$$

Da cui la tesi.

$\mathbf{Q.E.D.} \qquad\blacksquare$



$\mathbf{Problema\ }9.$

La risposta corretta è $\mathbf{C.}$

### Dimostrazione preliminare

Calcoliamo il campo elettrico di un guscio di raggio $R$ alla distanza $r$ dal centro del guscio.

Analizziamo il caso in cui $r > R$. 

Consideriamo una sfera $S$ di raggio $r$ concentrica al guscio, per i teorema di Gauss abbiamo che:

$$
\phi_{S}(\vec{E})= \frac{Q}{\varepsilon_{0}}
$$
$$
\phi_{S}(\vec{E})= 4\pi r^2 \cdot E
$$

$$
4\pi r^2 \cdot E= \frac{Q}{\varepsilon_{0}} \implies E =\frac{Q}{4\pi\varepsilon_{0}r^2}=k \frac{Q}{r^2}
$$
Analizziamo ora il caso in cui $r \leq R$.

Consideriamo di nuovo una superficie sferica di raggio $r$, ricaviamo dal teorema di Gauss che:

$$
\phi_{S}(\vec{E})= \frac{Q}{\varepsilon_{0}}
$$
ma $Q=0$ perché la carica del guscio è distribuita sulla superficie e non all'interno, quindi il flusso è nullo. Allora:

$$
S \cdot E = 0 \implies E = 0
$$
Abbiamo concluso che:

$$
E(r)= \begin{cases}
k \frac{Q}{r^2} \text{\ se\ } r > R \\ 0 \text{\ se\ } r \leq R
\end{cases}
$$
### Soluzione 

Per $r < b$ abbiamo che $E=0$, come abbiamo dimostrato. Per $b < r \leq 2b$ abbiamo che $E=E_{1}$, perché $E_{2}=0$ e al massimo $E=k \frac{Q}{b^2}$. Per $r\geq 2b$ abbiamo che $E= k \frac{2Q}{r^2}$, al massimo $E= k \frac{Q}{2b^2}$. Il massimo assoluto si ottiene quando $r=b$.

Tecnicamente i "massimi" sono degli estremi superiori non raggiungibili, ma con un abuso di notazione e di concetto li abbiamo definiti così. Tuttavia, nella pratica, il massimo di $E$ si ottiene quando $r \to b^+$, cioè appena fuori dal primo guscio.

$\mathbf{Q.E.D.} \qquad\blacksquare$

$\mathbf{Problema\ } 10.$

La risposta corretta è $\mathbf{E.}$

Affinché il campo elettrico totale $\vec{E}_{t}$ sia nullo, deve accadere che:

$$
\vec{E}_{1}+\vec{E}_{2}=0 \implies \vec{E}_{1}=-\vec{E}_{2}
$$

dove $(\vec{E}_{1}, \vec{E}_{2})$ sono i vettori dei campi elettrici generati da $(q_{1},q_{2})$ rispettivamente. 

I vettori campo elettrico devono dunque essere opposti, cioè devono avere stesso modulo e direzione ma verso opposto. L'unico modo affinché abbiano la stessa direzione è che siano giacenti sulla retta congiungente le due cariche. Vediamo su quale punto della retta si annulla $\vec{E}_{t}$.

Chiaramente, il punto cercato non può trovarsi tra le due cariche, perché queste formano un dipolo elettrico e la linea di campo appartenente alla retta è rivolta verso $q_{2}$, quindi $\vec{E}_{t}$ non è nullo. Il punto cercato non può nemmeno trovarsi sulla destra di $q_{2}$, dato che se così fosse avremmo che $||\vec{E}_{2}|| > ||\vec{E}_{1}||$ poiché $r_{2}<r_{1}$. Allora questo punto deve trovarsi a sinistra di $q_{1}$.

Perciò possiamo scrivere che:

$$
k \frac{q_{1}}{r_{1}}-k \frac{|q_{2}|}{(r_{1}+1)^2}=0
$$

$$
\frac{r_{1}^2}{q_{1}}=\frac{(r_{1}+1)^2}{|q_{2}|}
$$

$$
r_{1}^2 \left( 1- \frac{|q_{2}|}{q_{1}} \right)+2\text{m}r_{1}+1\text{m}^2=0
$$
Diciamo $a= 1-\frac{|q_{2}|}{q_{1}}=1-\frac{9\text{nC}}{4\text{nC}}=-\frac{5}{4}$, allora:

$$
r_{1}= \frac{-2 \text{m} \pm \sqrt{ 4 \text{m}^2-4a }}{2a}=\frac{-1 \pm \sqrt{ 1-a }}{a} \text{m}= \left(  1 \pm \frac{3}{2} \right) \frac{4}{5} \text{m}
$$
Naturalmente, per i motivi discussi in precedenza, cerchiamo $r_{1}>0$, pertanto concludiamo che dev'essere

$$
r_{1}=2\text{m}
$$
Si è conclusa la dimostrazione.

$\mathbf{Q.E.D.} \qquad\blacksquare$