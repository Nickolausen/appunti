---
{"dg-publish":true,"permalink":"/analisi-1/insiemi/","noteIcon":"","created":"2023-10-04T21:54:59.085+02:00","updated":"2023-10-13T00:39:25.591+02:00"}
---

#Definizione: Un insieme è una collezione di oggetti dei quali si può dire in modo non equivoco che ne fanno parte.

- Un insieme si indica con una lettera MAIUSCOLA.
- Gli oggetti interni ad un insieme si dicono **ELEMENTI**.
	- Per indicare che un elemento appartiene ad un insieme si usa la seguente notazione: **$a \in A$**

Posso identificare un insieme tramite tre modi diversi:
1. Per **ELENCAZIONE**: indico direttamente gli elementi che fanno parte dell'insieme;

ES: $$A=\{1,2,3,4\}$$
2. Per **PROPRIETÀ CARATTERISTICA**: indico la proprietà che accomuna tutti gli elementi dell'insieme (utile per identificare insiemi di infiniti elementi)

ES: $$A = \{n \in \mathbb{N}\mid 1 \leq\ n \leq 4\}$$
#### > Relazione di INCLUSIONE
#Definizione: Dati due insiemi A e B, si dice che $A \subseteq B$ se tutti gli elementi di A sono elementi di B
ES: $$A = \{ 2,3,4 \} \qquad B = \{ n \in \mathbb{N} \mid n \geq 2 \}$$ $A \subseteq B$ - A è **sottoinsieme** di B - non escludo che A e B possano essere uguali

In linguaggio matematico, definisco la relazione di inclusione come segue:
$$A \subseteq B = \{ \forall a \in A \mid a \in B \}$$
> **N.B**: Se B contiene anche altri elementi oltre a quelli di A, allora per precisare posso scrivere $A \nsubseteq B$

#### > DIFFERENZA tra insiemi
#Definizione: $A \setminus B$ contiene tutti gli elementi di A che con appartengono a B.
$$A \smallsetminus B = \{ a \in A \mid a \notin B \}$$
ES: $$A = \{ 2,3,4 \} \qquad B = \{ n \in \mathbb{N} \mid n \geq 2 \}$$$$A \smallsetminus B = \emptyset \qquad B \smallsetminus A = \{ n \in \mathbb{N} \mid n \geq 2 \}$$
>**N.B.**: L'operazione non gode della proprietà commutativa - non è simmetrica.

![IMG_5547F53A852B-1.jpeg](/img/user/media/IMG_5547F53A852B-1.jpeg)
#### > Relazione di UNIONE
#Definizione: $$A \cup B = \{ c \in A \vee c \in B  \}$$
>**N.B.**: Si tratta di un OR NON ESCLUSIVO, l'insieme risultato è composto dagli elementi o di A, o di B, o entrambi.

#### > Relazione di INTERSEZIONE
#Definizione:$$A\cap B = \{ c\in A \wedge c\in B \}$$
#### > DIFFERENZA SIMMETRICA
#Definizione: $$A \triangle B = (A \smallsetminus B ) \cup (B \smallsetminus A )$$
Esiste anche un altro modo equivalente di fare la sottrazione simmetrica, ossia: $$A \triangle B =(A \cup B)\smallsetminus(B \cup A)$$
#### > PRODOTTO tra INSIEMI
#Definizione: $$A \times B = \{ (a,b) \mid a \in A \wedge b \in B  \}$$
Il prodotto cartesiano tra due insiemi è un insieme di coppie di valori ordinate.
> **Ricorda**: l'ordine è importante!

ES:
$$A = \{ 1,2,7 \} \qquad B=\{  3,5 \} $$
$$A \times B = \{ (1,3), (1,5), (2,3), (2,5), (7,3), (7,5) \}$$
$$B \times A = \{ (3,1), (3,2), (3,7), (5,1), (5,2), (5,7) \}$$
$$\therefore A \times B \neq B \times A$$

#### INSIEMI NUMERICI FONDAMENTALI
1. Numeri naturali: $\mathbb{N} = \{ 1,2,3,\dots \}$
2. Numeri interi: $\mathbb{Z} = \{ \dots,-2,-1,0,1,2,\dots \}$
3. Numeri razionali: $\mathbb{Q} = \left\{  \frac{m}{p} \mid m,p\in\mathbb{Z},p\neq 0   \right\}$
4. Numeri reali: $\mathbb{R} \to$ posso rappresentarlo come una retta

___
*Università di Bologna - facoltà di Ingegneria e Scienze Informatiche, Cesena
**Date**: 04-10-2023, 13:42
**Author**: Nicholas Magi
Inspired by: Ludovico Spitaleri - https://lspita.github.io/