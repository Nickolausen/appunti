---
{"dg-publish":true,"permalink":"/analisi-1/successioni/successioni-definizioni/","noteIcon":"","created":"2023-10-12T22:47:22.000+02:00","updated":"2023-10-13T11:22:28.957+02:00"}
---

Il concetto di successione è propedeutico alla comprensione del concetto di limite.

#Definizione: Sia $A \neq \emptyset$, chiamiamo **SUCCESSIONE in A** una qualsiasi funzione $$f:\mathbb{N}\longrightarrow A$$
La notazione utilizzata per indicare una successione è la seguente:$$a_{n}\coloneqq a(n)$$
**ES**: $a_{n}=k,\quad k\in{R}$ - successione costante, graficamente rappresentata come segue:![Pasted image 20231012113619.png](/img/user/media/Pasted%20image%2020231012113619.png)
- $a_{n}=n^{2}+1$
- $a_{n}=(-1)^{n}=-1,+1,-1,+1,\dots$
- $a_{n}=\frac{1}{n}\qquad a_{n}:\mathbb{N}\smallsetminus \{ 0 \} \longrightarrow\mathbb{R}$

---
**ES**: $a_{n}=\frac{1}{n}$
![Pasted image 20231012114132.png](/img/user/media/Pasted%20image%2020231012114132.png)
**ES**: $a_{n}=\frac{1}{2^{n}}$

Verifichiamo che:  $\displaylines{a_{n}\longrightarrow 0 \\ n\rightarrow+\infty}$

Infatti, sia $\epsilon > 0$
$$\mid a_{n}\mid = \frac{1}{2} \leq \epsilon \Longleftrightarrow 2^{n}\geq \frac{1}{\epsilon}\Longleftrightarrow n\geq \log_{2}\left( \frac{1}{\epsilon} \right)$$
Posso scegliere $m_{\epsilon}=\left[ \log_{2}\left( \frac{1}{\epsilon} \right) \right] + 1$

---

**ES**: $a_{n}=\frac{(-1)^{n}}{n}$

| $n$ | $a_{n}$        |
| --- | -------------- |
| 1   | -1             |
| 2   | $\frac{1}{2}$  |
| 3   | $-\frac{1}{3}$ |

Verifichiamo che: $\displaylines{\frac{(-1)^{n}}{n}\longrightarrow 0 \\ n \rightarrow +\infty}$

Dato $\epsi$
___
*Università di Bologna - facoltà di Ingegneria e Scienze Informatiche, Cesena
**Date**: 12-10-2023, 11:30
**Author**: Nicholas Magi
Inspired by: Ludovico Spitaleri - https://lspita.github.io/*