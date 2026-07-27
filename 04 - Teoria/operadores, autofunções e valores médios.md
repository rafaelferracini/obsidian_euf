---
date: 21-07-2026 09:33
tags:
  - mecanica_quantica
  - funcoes_de_onda
cssclasses: center-images
---

# Operadores
---
O EUF costuma cobrar, no contexto de função de ondas, apenas os operadores básicos em sua representação no espaço das posições e sempre no caso unidimensional. Todos constam no [[Formulário fornecido pelo EUF.pdf]]
1. Operador de posição $x = x$
2. Operador de momento $p_{x} = -i\hbar \partial_{x} \implies p_{x}^{2} = -\hbar^{2}\partial_{x}^{2}$
3. Operador momento angular $L_{z} = -i\hbar \partial_{\phi}$
4. Operador hamiltoniano $H = i \hbar \partial_{t}$

# Autofunções
---
Dado um operador $T$ uma função de onda $\psi(x)$.  Os autovalores $\lambda$ de $T\psi(x) = \lambda \psi(x)$ correspondem as possíveis medidas físicas associadas ao observável $T$ e $\psi(x)$ é nesse caso autofunção de $T$

**Ex.:** Autovalores de $H$ para a função de onda $\psi(x, t) = \cos(kx) e^{ -iat }$ 
$$
H\psi(x, t) = i \hbar \cos(kx) \frac{\partial}{\partial t} (e^{ -iat }) = \hbar a \cos(kx) e^{ -iat } = (\hbar a )\psi(x, t)
$$
Como a atuação de $\psi(x,t)$ é de fato uma autofunção de $H$ com autovalor $\hbar a$, dizemos que $\psi(x,t)$ tem energia bem definida (pois toda medida feita de $H$ retornará essa energia)

**Ex.:** Autovalores de $p_{x}$ para a função de onda $\psi(x, t) = \cos(kx) e^{ -iat }$ 
$$
p_{x}\psi(x,t) = -i\hbar e^{ -iat } \frac{\partial}{\partial x}\cos(kx) = i\hbar k \sin(kx)e^{ -iat } \neq \lambda \psi(x,t)
$$
então $\psi(x,t)$ não é uma autofunção do momento, isto é, a medição de momento não é bem definida

# Valores médios
---
**Def.:** Dada uma função de onda $\psi(x)$ e um observável $\hat{A}$, o valor médio (ou esperado) de $\hat{A}$ é dado por
$$
\langle \hat{A} \rangle = \int_{-\infty}^{\infty} \psi^{*}(x) \hat{A} \psi(x) dx
$$

**Ex.:** Calcule os valores médios de $x$, $x^{2}$, $p$ e $p^{2}$ para a solução $\psi(x) = \sqrt{ \frac{2}{L} } \cos\left( \frac{\pi}{L} x \right)$ de um poço infinito restrito a $-\frac{L}{2} < x < \frac{L}{2}$

1. $\langle x \rangle \sim \int x \cos ^{2}$
2. $\langle x^{2} \rangle \sim \int x^{2}\cos ^{2}$
3. $\langle p \rangle \sim \int \sin \cos$
4. $\langle p^{2} \rangle \sim \cos ^{2}$

Note que essas integrais vão estar em intervalos simétricos e possuem paridades. 

# vídeo aula
---
![[1.2 Operadores básicos e autofunções.mp4]]
![[1.3 Operadores básicos e valores médios.mp4]]