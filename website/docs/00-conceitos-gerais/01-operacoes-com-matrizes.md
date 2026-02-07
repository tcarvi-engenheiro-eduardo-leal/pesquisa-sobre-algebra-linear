# Operações com Matrizes

## Soma de Matrizes
C = A + B

## Subtração de Matrizes
C = A - B

## Multiplicação de Matrizes por escalar
C = k * A

## Divisão de Matrizes por escalar
C = A / k

# Propriedades das Operações com Matrizes
:::note[operações]
I) A + B = B + A  
II) A + (B + C) = (A + B) + C  
III) A + 0 = 0 + A = A, sendo 0 a matriz nula.  
IV) A - A = 0, sendo 0 a matriz nula.  
V) (K1 . K2) . A = K1 . (K2 . A); sendo K1 e K2 escalares.  
VI) (K1 + K2) . A = K1 . A + K2 . A; (propriedade distributiva da multipliação de matriz por soma de escalares)  
VII) K . (A + B) = K . A + K . B; (propriedade distributiva da multipliação de escalar por soma de matrizes)  
VIII) 1 . A = A  
:::  

## Multiplicação de Matrizes
- Exemplo:  
$$
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6
\end{pmatrix}
\times
\begin{pmatrix}
7 & 8 \\
9 & 10 \\
11 & 12
\end{pmatrix}
=
\begin{pmatrix}
(1\cdot7 + 2\cdot9 + 3\cdot11) & (1\cdot8 + 2\cdot10 + 3\cdot12) \\
(4\cdot7 + 5\cdot9 + 6\cdot11) & (4\cdot8 + 5\cdot10 + 6\cdot12)
\end{pmatrix}
$$
- Dada uma matriz A de ordem m $\times$ n e uma matriz B de ordem n $\times$ p, o produto de A por B é uma matriz C de ordem m $\times$ p.
- Cada elemento da matriz produto é calculada por:
$$
c_{ij} = \sum_{k=1}^{n} a_{ik} b_{kj}
$$
    - Em resumo: considerando o índice da matriz resultado, multiplica-se a linha (indice i) da primeira matriz pela  coluna (índice j) da segunda matriz. Depois soma-se os valores encontrados. O valor $ c_{ij} $ da nova matriz é igual a esta soma. Executa-se mesma operação para demais elementos da matriz produto.


