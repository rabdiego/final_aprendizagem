# Rotulagem de Imagens para Projetos de Visão Computacional

## Motivação
No contexto de projetos de visão computacional, é comum a tarefa de rotular imagens para treinar modelos de aprendizado de máquina. No entanto, nem sempre as imagens estão prontas para serem rotuladas de forma direta e prática. Muitas vezes, é necessário descartar a maior parte das imagens devido à sua baixa qualidade.

Existem dois fatores principais que contribuem para a baixa qualidade das imagens: desfoque e falta de iluminação adequada. Esses problemas podem prejudicar a capacidade dos modelos de aprender com eficácia a partir das imagens.

## Objetivo
O objetivo deste projeto é construir um modelo de aprendizado de máquina capaz de prever se uma imagem é de boa qualidade ou não. Para isso, serão utilizadas técnicas de processamento de imagem e aprendizado de máquina para extrair características relevantes das imagens e treinar um modelo que possa realizar essa classificação de forma automatizada.

## Funcionamento
O projeto segue os seguintes passos:

  1. Organização das imagens: As imagens são organizadas em diferentes diretórios, cada um representando uma categoria de qualidade (por exemplo, "boa_qualidade" e "baixa_qualidade").

  2. Extração de características: Utilizando bibliotecas como OpenCV, as imagens são carregadas e processadas para extrair características relevantes, como estatísticas de pixel, texturas ou informações de borda.

  3. Construção do conjunto de dados: Com base nas características extraídas, um conjunto de dados é construído, onde cada imagem é representada por um conjunto de atributos numéricos que descrevem sua qualidade.

  4. Treinamento do modelo: O conjunto de dados é dividido em conjuntos de treinamento e teste. Em seguida, um modelo de aprendizado de máquina é treinado utilizando algoritmos como árvores de decisão, SVM ou redes neurais, para aprender a distinguir entre imagens de boa qualidade e baixa qualidade.

  5. Avaliação do modelo: O modelo treinado é avaliado usando métricas de desempenho, como acurácia, precisão e recall. Isso permite determinar o quão bem o modelo é capaz de prever a qualidade das imagens.

  6. Predição de novas imagens: O modelo final é aplicado para realizar previsões em novas imagens, atribuindo-lhes uma classificação de qualidade (boa qualidade ou baixa qualidade) com base em suas características.

## Datasets de Apoio

## Requisitos

## Colaboradores
* Cecília Hélen Nunes Câmara - 500593
* Diego Rabelo de Sá - 539664
* Louis Ian Silva dos Santos - 402525
