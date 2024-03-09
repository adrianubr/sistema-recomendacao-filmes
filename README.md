# Sistema de Recomendação de Filmes com Azure ML

## Introdução
Este projeto visa desenvolver um sistema de recomendação de filmes personalizado, utilizando o Azure Machine Learning para analisar o histórico de visualizações dos usuários e suas avaliações de filmes. O objetivo é fornecer recomendações altamente relevantes que melhorem a experiência do usuário em plataformas de streaming.

## Objetivos
- Desenvolver um modelo de recomendação eficaz baseado em preferências de usuários.
- Implementar o modelo no Azure ML, configurando pontos de extremidade para interações.
- Documentar todo o processo, facilitando a replicação e compreensão do projeto.

## Desenvolvimento do Modelo

### Seleção de Dados
Utilizamos o dataset MovieLens, que contém milhões de avaliações de filmes. Este dataset foi escolhido por...

### Escolha do Algoritmo e Processo de Treinamento
O modelo foi desenvolvido utilizando a técnica de Filtro Colaborativo...

## Configuração dos Pontos de Extremidade
Após o modelo ser treinado e avaliado, ele foi implantado no Azure ML...

## Como Interagir com o Modelo
Para interagir com o sistema de recomendação, os desenvolvedores precisam enviar uma requisição HTTP POST para o ponto de extremidade...

