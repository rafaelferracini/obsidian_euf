---
date: 20-07-2026 20:41
tags:
  - mecanica_quantica
  - funcoes_de_onda
cssclasses: center-images
---

# Solução do Poço Infinito
---
Considere um sistema quântico submetido a um potencial da forma
$$
V(x) = 
\begin{cases}
0 ,\quad &0 < x < a \\
\infty, \quad &x < 0 \text{ ou } x> a
\end{cases} 
$$
A equação de Schrodinger independente do tempo é
$$
- \frac{\hbar^{2}}{2m} \frac{d^{2}\psi}{dx^{2}} + V(x) \psi = E \psi
$$
Para $0 < x < a$ temos
$$
\frac{ d^2 \psi }{ d x^2 }  = -\frac{2mE}{\hbar^{2}} \psi
$$
de forma que a solução é
$$
\psi(x) = A \cos \left( \sqrt{ \frac{2mE}{\hbar^{2}} } x \right)  + B \sin \left( \sqrt{ \frac{2mE}{\hbar^{2}}} x \right)
$$
Como a função tem que ser contínua, então $\psi(0) = 0 = \psi(a)$
$$
\psi(0) = A = 0 \implies \psi(x) = B \sin \left( \sqrt{ \frac{2mE}{\hbar^{2}} } x \right)
$$
$$
\psi(a) = B \sin \left( \sqrt{ \frac{2mE}{\hbar^{2}} } a \right) = 0 \implies \sin\left( \sqrt{ \frac{2mE}{\hbar^{2}} } a \right) = 0
$$
assim
$$
\sqrt{ \frac{2mE}{\hbar^{2}} } a= n\pi, \, n=1, 2, 3 
$$
portanto as soluções de energia são
$$
E = n^{2} \frac{\hbar^{2}\pi^{2}}{2ma^{2}}
$$
e as soluções da função de onda é
$$
\psi(x) = B \sin \left( \frac{n\pi}{a} x \right)
$$
sendo que $B$ é obtida normalizando a função de onda


![[1.5 Poço infinito.mp4]]