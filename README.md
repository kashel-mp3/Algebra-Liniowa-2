# Algebra Liniowa 2

## 1 Macierz przekształcenia liniowego

###  Zadanie 1.1
Wyznaczyć współrzędne wektora:
(a) $v = (1, −2, 0)$,
(b) $v = (0, 1, 2)$
w bazie $B = ((1, 3, 4), (0, 1, 2), (0, 0, −1))$ przestrzeni $\mathbb{R}^3$.

###  Zadanie 1.2
Niech $\phi : \mathbb{R}^3 \to \mathbb{R}^2$, $\psi : \mathbb{R}^2 \to \mathbb{R}^3$ będą przekształceniami liniowymi danymi wzorami:
$$\phi ((x_1, x_2, x_3)) = (4x_1 + 3x_2 + x_3, 5x_1 + 4x_2 + 2x_3)$$
$$\psi ((x_1, x_2)) = (3x_1 − x_2, 5x_1 − 3x_2, 7x_1 − 5x_2)$$

Wyznaczyć macierz przekształcenia liniowego $\phi$, $\psi$, $\phi \circ \psi$, $\psi \circ \phi$.

###  Zadanie 1.3 (zad. 262, 263, 296, JR)
Niech $\phi$ będzie przekształceniem liniowym. Wyznaczyć macierz $M_B^C (\phi)$ przekształcenia $\phi$ w bazach $B$ i $C$, gdzie:

(a) $\phi : \mathbb{R}^2 \to \mathbb{R}^2$, $\phi((x_1, x_2)) = (4x_1 − x_2, 7x_1 − 3x_2)$, $B = ((2, 1), (4, 7))$, $C = ((1, 1), (0, 1))$,

(b) $\phi : \mathbb{R}^3 \to \mathbb{R}^2$, $\phi((x_1, x_2, x_3)) = (x_1 + x_2, x_1 + 2x_2 - x_3)$, $B = ((1, 0, 1), (0, 1, 1), (1, 1, 0))$, $C = ((1, 4), (1, 5))$,

(c) $\phi : \mathbb{R}^3 \to \mathbb{R}^3$, $\phi((x_1, x_2, x_3)) = (x_1 - x_2 + x_3, x_1 + x_2 - x_3, -x_1 + x_2 + x_3)$, $B = ((1, 0, -1), (0, 1, -1), (1, 1, 0))$, $C = ((0, -1, 0), (1, 2, 0), (0, 0, 2))$,

(d) $\phi : \mathbb{R}^2 \to \mathbb{R}^3$, $\phi((x_1, x_2)) = (4x_1 + x_2, 7x_1 + 2x_2, x_1 - x_2)$, $B = ((1, 4), (2, 7))$, $C = ((-1, 9, 0), (2, 0, 5), (0, 7, 2))$.

### Zadanie 1.4
Wyznaczyć współrzędne $\phi(v)$ w bazie $C$, wykorzystując macierze otrzymane w odpowiednich podpunktach zadania 1.3, gdzie:

(a) $v = (6, 8)$;
(b) $v = (0, 0, 2)$;
(c) $v = (2, 1, -1)$;
(d) $v = (1, 3)$.

### Zadanie 1.5
Znaleźć macierz przekształcenia liniowego $\phi : V \to W$ w bazach $B$ i $C$, gdzie:

(a) $V = (\mathbb{Z}/7)^3$, $W = (\mathbb{Z}/7)^2$, 

$$\phi \begin{pmatrix} x_1 \\\ x_2 \\\ x_3 \end{pmatrix} = \begin{pmatrix} x_1 + 2x_3 \\\ x_1 + x_2 + 5x_3 \end{pmatrix}$$

$B = \left(\begin{pmatrix} 1 \\\ 2 \\\ 0 \end{pmatrix}, \begin{pmatrix} 0 \\\ 1 \\\ 4 \end{pmatrix}, \begin{pmatrix} 3 \\\ 2 \\\ 6 \end{pmatrix}\right)$

$C = \left(\begin{pmatrix} 3 \\\ 5 \end{pmatrix}, \begin{pmatrix} 2 \\\ 4 \end{pmatrix}\right)$

(b) $V = \mathbb{R}^3$, $W = \mathbb{R}[x]_4$, 

$$\phi \begin{pmatrix} a_1 \\\ a_2 \\\ a_3 \end{pmatrix} = (a_1 + a_2)x^4 + (-a_2 + 2a_3)x^3 + (-a_1 + 2a_2 - a_3)x^2 + a_1x + (a_1 + a_2 - a_3)$$

$B = \left(\begin{pmatrix} -1 \\\ 2 \\\ 1 \end{pmatrix}, \begin{pmatrix} 2 \\\ -2 \\\ -1 \end{pmatrix}, \begin{pmatrix} 1 \\\ 1 \\\ 0 \end{pmatrix}\right)$

$C = (1, x^3, x^4, x^2, x)$

(c) $V = \mathbb{R}[x]_4$, $W = \mathbb{R}[x]_4$, $\phi (f (x)) = f'(x)$, $B = (x, 1, x^3, x^2, x^4)$, $C = (x^4, x^3, x^2, x, 1)$

(d) $V = \mathbb{R}[x]_3$, $W = \mathbb{R}[x]_2$, $\phi (a_3x^3 + a_2x^2 + a_1x + a_0) = a_0x^2 + (a_1 + a_2)x + a_3$, $B = (x^3, x^2, x, 1)$, $C = (x^2, x, 1)$

### Zadanie 1.6 (zad. 264, 265, JR)
Niech $\phi$ będzie przekształceniem liniowym danym przez macierz $M_B^C (\phi)$. Znaleźć wzór:

(a) $\phi((x_1, x_2))$, gdzie $\phi : \mathbb{R}^2 \to \mathbb{R}^2$, 

$$M_B^C (\phi) = \begin{pmatrix} 1 & -3 \\\ 8 & -5 \end{pmatrix}$$

$B = C = ((1, 0), (0, 1))$

(b) $\phi((x_1, x_2))$, gdzie $\phi : \mathbb{R}^2 \to \mathbb{R}^2$, 

$$M_B^C (\phi) = \begin{pmatrix} -7 & -8 \\\ 3 & 5 \end{pmatrix}$$

$B = ((5, 1), (11, 2))$, $C = ((1, 1), (4, 3))$

(c) $\phi((x_1, x_2, x_3))$, gdzie $\phi : \mathbb{R}^3 \to \mathbb{R}^2$,

$$M_B^C (\phi) = \begin{pmatrix} 2 & -3 & 0 \\\ 5 & 7 & 3 \end{pmatrix}$$

$B = ((5, 4, 2), (1, 1, 0), (2, 2, 1))$, $C = ((3, 1), (2, 1))$.

### Zadanie 1.7 (zad. 268, 269, JR)

Niech $\phi : \mathbb{R}^2 \to \mathbb{R}^2$ będzie przekształceniem liniowym. Znaleźć bazę:

(a) $C$, gdy mamy dane: wzór przekształcenia $\phi((x_1, x_2)) = (3x_1 + x_2, x_1 + 3x_2)$, macierz 

$$M_B^C (\phi) = \begin{pmatrix} 9 & 1 \\\ 2 & 2 \end{pmatrix}$$

oraz bazę $B = ((5, 4), (3, 2))$,

(b) $B$, gdy mamy dane: wzór przekształcenia $\phi((x_1, x_2)) = (x_1 - x_2, 4x_1 + x_2)$, macierz 

$$M_B^C (\phi) = \begin{pmatrix} 4 & 3 \\\ -1 & -1 \end{pmatrix}$$

oraz bazę $C = ((-1, 6), (0, 5))$.

### Zadanie 1.8 (zad. 292, JR)

Przekształcenie liniowe $\phi : \mathbb{R}^3 \to \mathbb{R}^2$ dane jest przez macierz

$$M_B^C (\phi) = \begin{pmatrix} 4 & 3 & 5 \\\ 1 & 1 & -1 \end{pmatrix}$$

Znaleźć macierz $M_{B'}^{C'} (\phi)$, gdy:

(a) $B = ((4, 5, 1), (1, 1, 1), (3, 0, 5))$, $C = ((4, 4), (-4, -5))$,
$B' = ((6, 4, 5), (4, 1, 6), (5, 2, 7))$, $C' = ((0, 1), (4, 3))$.

(b) $B = ((4, 4, 1), (3, 0, 1), (4, 3, 1))$, $C = ((1, 2), (2, -1))$,
$B' = ((4, 4, 1), (5, 8, 1), (3, 1, 1))$, $C' = ((3, 1), (-5, 0))$.

### Zadanie 1.9 (zad. 293, JR)

Endomorfizm $\phi$ przestrzeni wektorowej $\mathbb{R}^2$ ma w bazie kanonicznej macierz

$$M (\phi) = \begin{pmatrix} 5 & 7 \\\ 3 & 4 \end{pmatrix}$$

Znaleźć macierz tego endomorfizmu w bazie $B$, gdzie:

(a) $B = ((1, 0), (-1, 1))$;

(b) $B = ((7, 5), (6, 3))$.

## 2 Jądro i obraz przekształcenia liniowego; przestrzeń ilorazowa

### Zadanie 2.1 (zad. 245, JR)

Sprawdzić, że jądro przekształcenia liniowego $\phi : V \to W$ jest podprzestrzenią przestrzeni $V$.

### Zadanie 2.2 (zad. 247, JR)

Sprawdzić, że obraz przekształcenia liniowego $\phi : V \to W$ jest podprzestrzenią przestrzeni $W$.

### Zadanie 2.3 (zad. 246, JR)

Wykazać, że przekształcenie liniowe $\phi : V \to W$ jest monomorfizmem wtedy i tylko wtedy, gdy $\text{Ker } \phi = \{\theta_V\}$.

### Zadanie 2.4 (zad. 248, JR)

Sprawdzić, że jeśli funkcja $\phi : V \to W$ jest przekształceniem liniowym i $V = L(v_1, \ldots, v_n)$, to $\text{Im } \phi = L(\phi(v_1), \ldots, \phi(v_n))$.

### Zadanie 2.5 (zad. 252, JR)

Znaleźć po jednej bazie jądra i obrazu przekształcenia liniowego $\phi : \mathbb{R}^3 \to \mathbb{R}^4$, którego wartość w dowolnym punkcie $(x_1, x_2, x_3) \in \mathbb{R}^3$ jest równa:

(a) $(x_1 - 3x_2 - 5x_3, x_1 - 3x_2 - 5x_3, x_1 - 3x_2 - 5x_3, x_1 - 3x_2 - 5x_3)$,

(b) $(x_1 + 2x_2 + 4x_3, 3x_1 + x_2 + 7x_3, 2x_1 + 5x_2 + 9x_3, 6x_2 + 6x_3)$,

(c) $(x_1 - x_2 + x_3, 2x_1 - x_2 + 2x_3, 3x_1 - x_2 + 4x_3, 4x_1 - 2x_2)$.

### Zadanie 2.6 (zad. 254, JR)

Wypisać wszystkie elementy podanej przestrzeni ilorazowej, znaleźć bazę podanej przestrzeni ilorazowej oraz zbudować tabelki działań w podanej przestrzeni ilorazowej:

(a) $(\mathbb{Z}/2)^3/W$, gdzie $W = \{(0, 0, 0), (1, 0, 0)\}$;

(b) $(\mathbb{Z}/3)^2/W$, $W = L((1, 2))$.

### Zadanie 2.7 (zad. 255, 256, JR)

Opisać warstwy przestrzeni wektorowej $V$ względem jej podprzestrzeni $W$. Korzystając z I twierdzenia o izomorfizmie, pokazać, że $V/W \cong V'$, gdzie:

(a) $V = \mathbb{R}^\infty$, $W = \{(a_n)^\infty_{n=1} \in V : a_2 = 0\}$, $V' = \mathbb{R}$;

(b) $V = \mathbb{R}^\infty$, $W = \{(a_n)^\infty_{n=1} \in V : a_1 = 4a_2 = 5a_3\}$, $V' = \mathbb{R}^2$;

(c) $V = M_2(\mathbb{R})$, $W = \{[a_{ij}] \in V : a_{12} = a_{21} = 0\}$, $V' = \mathbb{R}^2$;

(d) $V = C[0;1]$, $W = \{f \in V : f(0) = f(1) = 0\}$, $V' = \mathbb{R}^2$.

## Wektory własne, wartości własne i przestrzenie własne

### Zadanie 3.1
Wyznacz wektory i wartości własne endomorfizmu $f : V \to V$, jeśli

(a) $V = \mathbb{R}^3$ oraz $f ((x, y, z)) = (x − y − z, 2y − z, 3z)$;

(b) $V = \mathbb{R}^3$ oraz $f ((x, y, z)) = (−3x − 2y − 4z, 2x + 7y + 10z, x − 2y − 2z)$;

(c) $V = \mathbb{Q}^3$ oraz $f ((x, y, z)) = (3x − y + z, 2x + z, 2x − 2y + 3z)$;

(d) $V = \mathbb{C}^2$ oraz $f ((x, y)) = (x − y, x + y)$;

(e) $V = (\mathbb{Z}/5)^2$ oraz $f ((x, y)) = (2x + 4y, x + 4y)$;

(f) $V = \mathbb{R}[X]_4$ oraz $f (\phi(x)) = \phi'(x)$.

### Zadanie 3.2
Niech $n \geq 2$ i $a_0, a_1, \ldots, a_{n-1} \in K$. Wyznacz wielomian charakterystyczny dla macierzy

$$\begin{pmatrix} 
0 & 0 & \ldots & 0 & -a_0 \\\ 
1 & 0 & \ldots & 0 & -a_1 \\\ 
0 & 1 & \ldots & 0 & -a_2 \\\ 
\vdots & \vdots & \ddots & \vdots & \vdots \\\ 
0 & 0 & \ldots & 1 & -a_{n-1} 
\end{pmatrix}$$

Wywnioskuj, że dowolny unormowany wielomian $f \in K[X]$ stopnia $n$ jest wielomianem charakterystycznym pewnej macierzy $A \in M_n(K)$.

### Zadanie 3.3
Podaj przykład takiej macierzy $A \in M_n(K)$, że

(a) $A \in M_4(\mathbb{R})$ i $A$ nie ma wartości własnych.

(b) $A \in M_4(\mathbb{R})$ ma tylko jedną wartość własną i nie jest macierzą jednostkową pomnożoną przez skalar.

(c) $A \in M_3(\mathbb{Q})$ i $A$ nie ma wartości własnych.

(d) $A \in M_5(\mathbb{R})$ ma dokładnie dwie różne wartości własne.

### Zadanie 3.4
Dla wartości własnych podanych macierzy (nad $\mathbb{R}$) wyznacz krotność algebraiczną oraz krotność geometryczną

$$A = \begin{pmatrix} 
8 & -6 & 0 \\\ 
9 & -7 & 0 \\\ 
6 & -4 & 0 
\end{pmatrix}$$ 
\ [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/4_4_a_b.jpg)

$$B = \begin{pmatrix} 
2 & -1 & 1 \\\ 
6 & -3 & 4 \\\ 
1 & -1 & 2 
\end{pmatrix}$$
\ [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/4_4_a_b.jpg)

$$C = \begin{pmatrix} 2 & -1 & 1 \\\ 1 & 1 & 1 \\\ 0 & 1 & 1  \end{pmatrix}$$ 
\ 
[rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/4_4_c.jpg)

### Zadanie 3.5
Niech $\lambda \in K$ oraz

$$A = \begin{pmatrix} 
\lambda & 1 & 0 & \ldots & 0 & 0 & 0 \\\ 
0 & \lambda & 1 & \ldots & 0 & 0 & 0 \\\ 
0 & 0 & \lambda & \ldots & 0 & 0 & 0 \\\ 
\vdots & \vdots & \vdots & \ddots & \vdots & \vdots & \vdots \\\ 
0 & 0 & 0 & \ldots & \lambda & 1 & 0 \\\ 
0 & 0 & 0 & \ldots & 0 & \lambda & 1 \\\ 
0 & 0 & 0 & \ldots & 0 & 0 & \lambda 
\end{pmatrix} \in M_n(K)$$

Wykaż, że $\lambda$ jest wartością własną macierzy $A$ oraz oblicz jej krotność algebraiczną i geometryczną. \
[rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/4_5.jpg)

### Zadanie 3.6
Wyznaczyć wartości własne i wektory własne endomorfizmu
$\phi : \mathbb{R}[x]_2 \to \mathbb{R}[x]_2$,
danego wzorem:
$\phi(a_2x^2 + a_1x + a_0) = 2a_2x^2 + (a_2 + 5a_1 − 3a_0)x − 3a_1 + 5a_0$.

Czy macierz tego przekształcenia jest diagonalizowalna (czy da się sprowadzić do postaci diagonalnej)? \
[rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/4_6.jpg)

### Zadanie 3.7 (zad. 321, JR). 
Zbadać, czy macierz $A = \begin{bmatrix} 2 & 4 \\\ 1 & 4 \end{bmatrix} \in M_2(K)$ jest diagonalizowalna, jeśli ciało $K$ jest następujące:
(a) $\mathbb{Q}$;
(b) $\mathbb{R}$;
(c) $\mathbb{C}$;
(d) $\mathbb{Z}/5$;
(e) $\mathbb{Z}/7$;
(f) $\mathbb{Z}/11$. \
[rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/4_7.jpg)

### Zadanie 3.8 (zad. 322, JR). 
Znaleźć macierz diagonalną $D$ podobną do danej macierzy $A \in M_3(\mathbb{R})$, jeśli taka macierz $D$ istnieje. Znaleźć też wtedy macierz odwracalną $S$ taką, że $D = S^{-1}AS$, gdzie macierz $A$ jest postaci:

(a) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/4_8_a.jpg)

$$\begin{bmatrix} 4 & -2 & 1 \\\ 3 & -1 & 1 \\\ 6 & -6 & 4 \end{bmatrix}$$

(b) [rozwiązanie pt1](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/4_8_b.jpg)
[ pt2](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/4_8_b_2.jpg)

$$\begin{bmatrix} 4 & -4 & 8 \\\ 4 & -4 & 8 \\\ 1 & -1 & 2 \end{bmatrix}$$

(c) 

$$\begin{bmatrix} 1 & -4 & 1 \\\ 0 & -3 & 1 \\\ 0 & -6 & 2 \end{bmatrix}$$

(d) 

$$\begin{bmatrix} -5 & 1 & 4 \\\ -5 & 1 & 4 \\\ -4 & 1 & 3 \end{bmatrix}$$

(e) 

$$\begin{bmatrix} 6 & -4 & 1 \\\ 5 & -3 & 1 \\\ -4 & 4 & 0 \end{bmatrix}$$

(f) 

$$\begin{bmatrix} -7 & 2 & 6 \\\ -4 & 2 & 3 \\\ -8 & 2 & 7 \end{bmatrix}$$

(g) 

$$\begin{bmatrix} 3 & -2 & 1 \\\ 6 & -6 & 4 \\\ 6 & -5 & 3 \end{bmatrix}$$

(h) 

$$\begin{bmatrix} 8 & -7 & 1 \\\ 8 & -7 & 1 \\\ 8 & -8 & 1 \end{bmatrix}$$

(i) 

$$\begin{bmatrix} -11 & 5 & 5 \\\ -12 & 5 & 6 \\\ -12 & 6 & 5 \end{bmatrix}$$


### Zadanie 3.9. 
Niech $n \in \mathbb{N}$. Obliczyć:
$\begin{bmatrix} 4 & 3 \\\ 8 & 1 \end{bmatrix}^n$,
$\begin{bmatrix} 3 & 2 \\\ -1 & 6 \end{bmatrix}^n$,
$\begin{bmatrix} 1 & 1 & 1 \\\ -1 & 1 & 1 \\\ 1 & 1 & 1 \end{bmatrix}^n$,
$\begin{bmatrix} 3 & 2 & 4 \\\ 2 & 0 & 2 \\\ 4 & 2 & 3 \end{bmatrix}^n$,
$\begin{bmatrix} -7 & 2 & 6 \\\ -4 & 2 & 3 \\\ -8 & 2 & 7 \end{bmatrix}^n$

### Zadanie 3.10. 
Udowodnij, że przestrzeń $W = L(w_1, \ldots, w_n)$ jest $T$-niezmiennicza wtedy i tylko wtedy, gdy $T(w_j) \in W$ dla każdego $j = 1, 2, \ldots, n$.

### Zadanie 3.11. 
Sprawdzić, czy $W$ jest $T$-niezmienniczą podprzestrzenią w $V$:

(a) $V = \mathbb{R}^3$, $W = \{(t, -t, t) : t \in \mathbb{R}\}$, $T(x, y, z) = (x + 3y + 3z, -3x - 5y - 3z, 3x + 3y + z)$; \
[rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/4_11_a.jpg)

(b) $V = \mathbb{R}^3$, $W = L((1, 0, -1), (1, -1, 1))$, $T(x, y, z) = (x - y - z, 2x - y, 3z)$;

(c) $V = \mathbb{R}^3$, $W = L((1, -1, 1), (1, 1, -1))$, $T(x, y, z) = (-3x - 2y - 4z, 2x + 7y + 10z, x - 2y - 2z)$;

(d) $V = M_2(\mathbb{R})$, $W = \{A \in V : A^T = A\}$, $T(A) = \begin{bmatrix} 0 & 1 \\\ 1 & 0 \end{bmatrix} A$;

### Zadanie 3.12. 
Znaleźć wszystkie jednowymiarowe podprzestrzenie $T$-niezmiennicze w $\mathbb{R}^3$ dla operatora:
$T(x, y, z) = (x - 4y + z, -4x + y + z, 4x + 4y + 4z)$.

## 4 Formy dwuliniowe, radykał lewostronny i prawostronny

### Zadanie 4.1 
Które z następujących przekształceń są formami dwuliniowymi?

(a) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/5_1_a.jpg)

(b) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/5_1_b.jpg)

(c) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/5_1_c.jpg)

(d) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/5_1_d.jpg)

### Zadanie 4.2 
Znaleźć macierze następujących form dwuliniowych:

(a) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/5_2_a_b.jpg)

(b) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/5_2_a_b.jpg)


### Zadanie 4.3 
Metodami poznanymi na wykładzie (tj. z definicji oraz korzystając z macierzy przejścia od bazy do bazy), znaleźć macierz formy dwuliniowej β : R² × R² → R, danej wzorem:
w bazie B, gdzie:
(a)
(b) 
(c) 
(d) 

### Zadanie 4.4

(a) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/5_4_a_b.jpg)

(b) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/5_4_a_b.jpg)

(c) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/5_4_c.jpg)

### Zadanie 4.5
### Zadanie 4.6
### Zadanie 4.7
[rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/5_7.jpg)

## 5 Iloczyn skalarny, algorytm Grama-Schmidta
### Zadanie 5.1

(a) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_1.jpg)

(b) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_1.jpg)

(c) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_1_c.jpg)

### Zadanie 5.2
[rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_2.jpg)

### Zadanie 5.3

### Zadanie 5.4

(a) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_4_a.jpg)

(b) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_4_b.jpg)

### Zadanie 5.5
[rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_5.jpg)

### Zadanie 5.6
(a) rozwiązanie: [pt.1](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_6_1.jpg) [pt.2](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_6_2.jpg)

### Zadanie 5.7
[rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_7.jpg)

### Zadanie 5.8
[rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_8.jpg)

### Zadanie 5.9

(a) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_9_a.jpg)

(b) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_9_b.jpg)

### Zadanie 5.10
(a) [rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_10_a.jpg)

### Zadanie 5.11

### Zadanie 5.12
[rozwiązanie](https://github.com/kashel-mp3/Algebra-Liniowa-2/blob/main/rozwi%C4%85zania/6_12.jpg)

## 6 Formy kwadratowe

### Zadanie 6.1

### Zadanie 6.2

### Zadanie 6.3

### Zadanie 6.4

### Zadanie 6.5

### Zadanie 6.6

## 7 Postać kanoniczna Jordana

### Zadanie 7.1

### Zadanie 7.2

### Zadanie 7.3
