# Caixeiro Viajante: Roteamento de veículos em São Paulo

<img src="https://github.com/user-attachments/assets/e41d4bf9-acc2-455d-8bf6-f7d947085221" alt="image" width="130" height="100">





## Objetivo: 
Encontre a melhor rota, começando pela capital e retornando até ela no final (problema do caixeiro viajante), sem repetição de cidades.

## Etapas do Projeto
- Estruturação do Dataset

  Utilizamos o arquivo JSON com todos os dados geográficos de todos os municípios de São Paulo.

  Para calcular a distância utilizamos a fórmula Haversine.

  E construimos a matriz de distância sobre todas as cidades.

- Limpeza dos dados

  Remoção das cidades repetidas (origem igual ao destino).

  Remoção de valores duplicados.

- Modelagem:

  Testamos diferentes algoritmos para encontrar o que alcançava melhor resultado, entre eles o Algoritmo Guloso, Genético, OrTools, Christofides e Busca Tabu.

## Conclusão:
  Tivemos alguns obstáculos, como a matriz de distância real e os modelos de rede neural com treinamentos muios longos.

  O melhor resultado obtido foi o utilizando o algoritmo OrTools, com a distância total de 10.279km passando por todos os munícipios de São Paulo

## Mapas do Código: 
### Ortools: 
![image](https://github.com/user-attachments/assets/c398f7dd-32d6-4b25-81a2-28622fe13d63)


