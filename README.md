# Sistema de Recomendação de Filmes CinemaX

O CinemaX é um sistema avançado de recomendação de filmes desenvolvido para ajudar os amantes de cinema a descobrir novos filmes com base em suas preferências anteriores. Utilizando algoritmos de aprendizado de máquina no Azure AI, o sistema analisa as avaliações e preferências dos usuários para fornecer recomendações personalizadas.

## Objetivo

Nosso objetivo é melhorar a experiência de escolha de filmes para os usuários, fornecendo sugestões altamente relevantes que correspondam aos seus gostos e preferências cinematográficas.

## Como Funciona

Os usuários fornecem avaliações para os filmes que assistiram. O sistema então usa essas informações, junto com o histórico de avaliações de outros usuários, para prever e recomendar novos filmes que os usuários provavelmente irão gostar.
### Tecnologias e Ferramentas

- **Azure AI**: Usado para hospedar e treinar o modelo de machine learning.
- **Azure Machine Learning Studio**: Utilizado para criar, treinar e implantar o modelo de recomendação.
- **Python**: Linguagem de programação para scripting e análise de dados.
- **Pandas & NumPy**: Bibliotecas de Python para manipulação de dados.
- **SciKit-Learn**: Biblioteca de Python para machine learning.
- ### Criação do Modelo no Azure AI

1. **Coleta de Dados**: Compilamos um conjunto de dados abrangente de avaliações de filmes de várias fontes.
2. **Análise e Preparação de Dados**: Usamos Pandas e NumPy para limpar e preparar os dados para o treinamento.
3. **Treinamento do Modelo**: Utilizamos o Azure Machine Learning Studio para criar e treinar nosso modelo de recomendação, usando o algoritmo de filtragem colaborativa.
4. **Avaliação do Modelo**: Testamos o modelo com um conjunto de dados de teste para avaliar sua precisão.
5. **Deploy do Modelo**: Após a satisfação com o desempenho do modelo, realizamos o deploy no Azure como um serviço, gerando os pontos de extremidade de API para integração.

