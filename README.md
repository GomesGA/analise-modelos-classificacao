# 📊 Comparação de Algoritmos de Classificação em Ciência de Dados

Este projeto foi desenvolvido como trabalho final para a disciplina de Ciência de Dados na **Universidade Federal de Uberlândia (UFU)**. O objetivo principal foi aplicar, avaliar e interpretar o desempenho de três algoritmos de classificação supervisionada em duas bases de dados distintas do repositório UCI.

## 🎯 Objetivos
* **Pré-processamento:** Realizar o tratamento detalhado de bases de dados reais.
* **Implementação:** Aplicar e justificar a escolha de algoritmos de classificação específicos.
* **Avaliação Crítica:** Comparar resultados utilizando métricas de desempenho e validação robusta.

## 📂 Bases de Dados Utilizadas
* **Adult Data Set (Census Income):** Previsão se o rendimento anual de um indivíduo excede $50.000 com base em dados demográficos.
* **Heart Disease UCI:** Previsão da presença de doenças cardíacas com base em atributos clínicos e demográficos.

## 🤖 Algoritmos Implementados
Foram testados e comparados os seguintes modelos:
* **Naive Bayes:** Escolhido pela sua simplicidade e eficiência em modelagem de probabilidades.
* **K-Nearest Neighbors (K-NN):** Algoritmo baseado em instâncias e métricas de distância.
* **Random Forest:** Modelo de conjunto (*ensemble*) robusto para lidar com dados complexos e desbalanceados.

## 🛠️ Tecnologias e Técnicas
| Categoria | Descrição |
| :--- | :--- |
| **Linguagem** | Python |
| **Bibliotecas** | Pandas, Scikit-Learn, Matplotlib e Seaborn |
| **Pré-processamento** | Imputação pela moda, One-Hot Encoding e Normalização |
| **Validação** | Validação Cruzada (Cross-Validation) |



## 📈 Principais Conclusões
* **Dependência de Contexto:** Não existe um "melhor algoritmo" universal; a escolha depende das características dos dados (tamanho e complexidade).
* **Base Adult:** O **Random Forest** apresentou o melhor desempenho em cenários mais complexos e desbalanceados.
* **Base Heart Disease:** O **Naive Bayes** destacou-se pela eficácia na modelagem de probabilidades condicionais após parametrização correta.

## 👥 Autores
* **Guilherme Gomes Alves**
* **Vinícius Ferreira Salge**

---
*Este projeto faz parte do portfólio acadêmico desenvolvido durante o curso de Sistemas de Informação - UFU.*
