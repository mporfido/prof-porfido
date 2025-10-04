---
draft: true
---


# Studio di funzione razionale fratta

$$
f(x)=\frac{-x^{3}}{x^{3}-1}
$$

---

### 1) Dominio

Poiché si tratta di una funzione razionale fratta, il denominatore deve essere diverso da zero.

$$
x^{3}-1\ne0\rightarrow x^{3}\ne1\rightarrow x\ne\sqrt[3]{1}=1
$$

Il dominio è $D=R \setminus \{1\}$, che può essere scritto come:

$$
D = (-\infty, 1) \cup (1, +\infty)
$$

---

### 2) Simmetrie

Si calcola $f(-x)$ per verificare la presenza di simmetrie (funzione pari o dispari).

$$
f(-x)=\frac{-(-x)^{3}}{(-x)^{3}-1}=\frac{+x^{3}}{-x^{3}-1}
$$

Poiché $f(-x) \ne f(x)$ e $f(-x) \ne -f(x)$, la funzione **non presenta simmetrie**.

---

### 3) Intersezioni con gli assi

**Asse x (y=0):**

$$
\frac{-x^{3}}{x^{3}-1} = 0 \rightarrow -x^3 = 0 \rightarrow x=0
$$

**Asse y (x=0):**

$$
y = \frac{-0^{3}}{0^{3}-1} = 0
$$

L'unica intersezione con gli assi è l'origine **(0, 0)**.

---

### 4) Segno della funzione

Si studia la positività della funzione, risolvendo $f(x)>0$.

$$
\frac{-x^{3}}{x^{3}-1}>0
$$

**Numeratore (N):**

$$
-x^{3}>0 \rightarrow x^{3}<0 \rightarrow x<0
$$

**Denominatore (D):**

$$
x^{3}-1>0 \rightarrow x^{3}>1 \rightarrow x>1
$$

Studiando il grafico dei segni, si ottiene:
- **Funzione positiva ($f(x)>0$):** per $0 < x < 1$
- **Funzione negativa ($f(x)<0$):** per $x < 0 \lor x > 1$

---

### 5) Comportamento agli estremi del dominio (Asintoti)

**Asintoto Orizzontale:**
Si calcolano i limiti per $x \rightarrow \pm\infty$.

$$
\lim_{x\rightarrow\pm\infty}\frac{-x^{3}}{x^{3}-1} = \lim_{x\rightarrow\pm\infty}\frac{-x^{3}}{x^{3}(1-\frac{1}{x^{3}})} = -1
$$

La retta $y=-1$ è un **asintoto orizzontale**.

**Asintoto Verticale:**
Si calcolano i limiti destro e sinistro per $x \rightarrow 1$.

$$
\lim_{x\rightarrow1^{-}}\frac{-x^{3}}{x^{3}-1}= \frac{-1}{0^{-}} = +\infty
$$

$$
\lim_{x\rightarrow1^{+}}\frac{-x^{3}}{x^{3}-1}= \frac{-1}{0^{+}} = -\infty
$$

La retta $x=1$ è un **asintoto verticale**.

---

### 6) Studio della derivata prima

Si calcola la derivata prima per studiare la monotonia della funzione.

$$
f'(x)=\frac{-3x^{2}(x^{3}-1)-(-x^{3})(3x^{2})}{(x^{3}-1)^{2}} = \frac{-3x^{5}+3x^{2}+3x^{5}}{(x^{3}-1)^{2}}
$$

$$
f'(x)=\frac{3x^{2}}{(x^{3}-1)^{2}}
$$

**Punti stazionari:**
Si cercano i punti in cui si annulla la derivata prima ($f'(x)=0$).

$$
\frac{3x^{2}}{(x^{3}-1)^{2}} = 0 \rightarrow 3x^2 = 0 \rightarrow x=0
$$

Il punto $x=0$ è un punto stazionario a tangente orizzontale.

**Segno della derivata prima:**
Si studia $f'(x)\ge0$.
- **Numeratore (N):** $3x^{2}\ge0 \rightarrow \forall x\in D$
- **Denominatore (D):** $(x^{3}-1)^{2}>0 \rightarrow \forall x\in D$

Poiché $f'(x) \ge 0$ per ogni $x$ nel dominio, la funzione è **sempre crescente**.
Il punto stazionario $x=0$ non è un massimo o un minimo, ma un **flesso a tangente orizzontale**.

---

### 7) Studio della derivata seconda

Si calcola la derivata seconda per studiare la concavità e trovare i flessi.

$$
f''(x) = \frac{6x(x^{3}-1)^{2}-3x^{2} \cdot 2(x^{3}-1) \cdot 3x^{2}}{(x^{3}-1)^{4}}
$$

Semplificando un fattore $(x^3-1)$:

$$
f''(x) = \frac{6x(x^{3}-1)-18x^{4}}{(x^{3}-1)^{3}} = \frac{6x^{4}-6x-18x^{4}}{(x^{3}-1)^{3}} = \frac{-12x^{4}-6x}{(x^{3}-1)^{3}}
$$

$$
f''(x) = \frac{-6x(2x^{3}+1)}{(x^{3}-1)^{3}}
$$

**Segno della derivata seconda:**
Si studia $f''(x)>0$.
- **Fattore 1:** $-6x > 0 \rightarrow x < 0$
- **Fattore 2:** $2x^{3}+1 > 0 \rightarrow x^{3} > -\frac{1}{2} \rightarrow x > -\frac{1}{\sqrt[3]{2}}$
- **Denominatore:** $(x^{3}-1)^{3}>0 \rightarrow x^{3}-1>0 \rightarrow x > 1$

Studiando il grafico dei segni si trovano i seguenti intervalli di concavità:
- **Concavità verso l'alto (convessa):** $x < -\frac{1}{\sqrt[3]{2}} \lor 0 < x < 1$
- **Concavità verso il basso (concava):** $-\frac{1}{\sqrt[3]{2}} < x < 0 \lor x > 1$

La funzione ha due **punti di flesso**:
1.  Il primo in $x=0$, che corrisponde al punto **(0, 0)**.
2.  Il secondo in $x = -\frac{1}{\sqrt[3]{2}}$. Calcoliamo l'ordinata:

$$
f(-\frac{1}{\sqrt[3]{2}})=\frac{-(-\frac{1}{2})}{-\frac{1}{2}-1}=\frac{\frac{1}{2}}{-\frac{3}{2}}=-\frac{1}{3}
$$
Il secondo punto di flesso è **$(-\frac{1}{\sqrt[3]{2}}, -\frac{1}{3})$**.
