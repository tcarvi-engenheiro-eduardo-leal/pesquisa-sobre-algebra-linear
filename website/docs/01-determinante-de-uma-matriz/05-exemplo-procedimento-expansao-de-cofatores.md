# Exemplo do Procedimento do Método Expansão de Cofatores

$$
A_{m,n} = \begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{pmatrix}
$$

## Etapa 1
- Escolher se vai considerar linha ou coluna, para o método de expansão de cofatores. Escolho linha.

## Etapa 2
- Escrever fórmula final, para a escolha de se considerar linha:
$$
\det(A) = \sum_{j=1}^{n} a_{ij} C_{ij} \quad \text{(expansão pela i-ésima linha)}
$$

$$
\det(A) = \sum_{j=1}^{n} a_{ij} C_{ij} \quad \text{(expansão pela i-ésima linha)}
$$
  
## Etapa 3
- Escolher qual linha será expandida. Escolho linha 1.

## Etapa 4
- Listar todos os elementos que serão somados (i foi fixado como 1):
$$
a_{11} C_{11}
$$  
$$
a_{12} C_{12}
$$ 
$$
a_{13} C_{13}
$$ 

## Calcular o primento elemento
$ a_{11} \times C_{11} = $  
$ 1 \times C_{11} = $ 
$ 1 \times (-1)^{i+j} \times M_{11} = $  
$ 1 \times (-1)^{2} \times M_{11} = $  
$ 1 \times 1 \times M_{11} = $  
Como $ M_{11} = $  
$$
\det{\begin{pmatrix}
5 & 6 \\
8 & 9
\end{pmatrix}} = -3
$$
$ 1 \times 1 \times M_{11} = $  
$ 1 \times 1 \times -3 = $  
$ -3 $ 

## Calcular o segundo elemento
$ a_{12} \times C_{12} = $  
$ 2 \times C_{12} = $ 
$ 2 \times (-1)^{i+j} \times M_{12} = $  
$ 2 \times (-1)^{3} \times M_{12} = $  
$ 2 \times -1 \times M_{12} = $  
Como $ M_{12} = $  
$$
\det{\begin{pmatrix}
4 & 6 \\
7 & 9
\end{pmatrix}} = -6
$$
$ 2 \times -1 \times M_{12} = $  
$ 2 \times -1 \times -6 = $  
$ 12 $

## Calcular o terceiro elemento
$ a_{13} \times C_{13} = $  
$ 3 \times C_{13} = $ 
$ 3 \times (-1)^{i+j} \times M_{13} = $  
$ 3 \times (-1)^{4} \times M_{13} = $  
$ 3 \times 1 \times M_{13} = $  
Como $ M_{13} = $  
$$
\det{\begin{pmatrix}
4 & 5 \\
7 & 8
\end{pmatrix}} = -3
$$
$ 3 \times 1 \times M_{13} = $  
$ 3 \times 1 \times -3 = $  
$ - 9 $

### Somar os termos encontrados
-3 + 12 + - 9 = 0