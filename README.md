# Basics
Alguns agoritmos úteis e conceitos básicos de machine learning.

## Basic Python
Algumas ferramentas úteis do python.

## Perceptron:
Algoritmo simples de classificação binária. Funciona somente para classes linearmente separáveis.

## Ajuste de Função (força bruta)
Aplicação do método de mínimos quadrados para encontrar os melhores parâmetros que se ajustam à uma função. Aqui o problema é resolvido por força bruta, o que significa que é inviável aplicá-lo para determinar muitos parâmetros de uma vez.

## Regressão Linear
Introdução ao algoritmo de descida gradiente aplicado ao problema do ajuste de função. Encontra os parâmetros de maneira muito mais rápida do que o ajuste por força bruta. Infelizmente, na forma que está apresentado aqui o algoritmo só resolve parâmetros e combinações lineares de funções; é preciso modificar a arquitetura para ajustar funções mais complicadas.

## Regressão Logística
Aplica a descida gradiente para o problema de classificação binária, dessa vez com a vantagem de que ele classifica com base na probabilidade de pertencer a uma classe ou à  outra, e portanto consegue lidar com pontos náo linearmente separáveis.

## K-means e Mean-shift clustering
Implementação e discussão sobre dois algoritmos de agrupamento interessantes. No K-means você fornece  k, o número de classes que acredita existir nos dados que está olhando, e ele encontra essas classes pra você. No Mean-shift não sabemos quantas classes existem, e o computador encontra possíveis soluções.

## Algoritmo Genético
Tentamos imitar o processo da evolução natural para encontrar a melhor solução para um dado problema. Como exemplo, usamos o algoritmo para resolver o problema do vendedor ambulante, onde queremos encontrar a rota mais curta que passa por N pontos e volta para o ponto inicial.

## Basic Keras NN
Exemplo simples de como processar dados, montar, treinar, e avaliar uma rede neural para classificação binária construída com o módulo Keras do Tensorflow.

## Basic Torch CNN
Exemplo de como construir uma rede neural convolucional através do Pytorch e treiná-la para identificar números escritos à mão (base de dados MNIST) e também peças de roupa (base de dados Fashion MNIST).

