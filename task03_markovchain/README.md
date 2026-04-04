 # Questão 4 — Cadeias de Markov (Mercado de Sabão em Pó)
---
O mercado de sabão em pó numa região é dividido entre três marcas: **O, M e Q**. No início as porcentagens de vendas são: **O: 35%**, **M: 25%** e **Q: 40%**. Durante o primeiro mês, **65%** dos fregueses de **O** ficam fiéis ao produto, **25%** mudam para **M** e **10%** para **Q**. Neste mesmo período, **15%** dos de **M** mudam para **O**, **70%** permanecem e **15%** mudam para **Q**. Dos fregueses de **Q**, ficam fiéis ao produto **55%**, **20%** mudam para **O** e **25%** para **M**. Suponha que os hábitos de compra não se alterem nos próximos períodos (as tendências se mantêm) e que o mercado não se expanda nem se contraia.

**(a)** Como estará o mercado ao fim do **1º mês**? e do **2º**?

**(b)** Mostre que depois de dois meses, considerando só os fregueses originariamente de **Q**, teremos uma nova distribuição entre as marcas, que pode ser obtida pela matriz de transição.

**(c)** Discuta a afirmação (use o programa computacional).

---

## Dados do problema

A matriz de transição é:

$$
A =
\begin{bmatrix}
0.65 & 0.15 & 0.20 \\
0.25 & 0.70 & 0.25 \\
0.10 & 0.15 & 0.55
\end{bmatrix}
$$

O vetor inicial do mercado é:

$$
x_0 =
\begin{bmatrix}
0.35 \\
0.25 \\
0.40
\end{bmatrix}
$$
