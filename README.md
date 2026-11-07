# Projeto de Machine Learning — Previsão de Desempenho Acadêmico

## Sobre o Projeto

Este projeto tem como objetivo desenvolver uma solução baseada em Inteligência Artificial e Machine Learning para prever o desempenho acadêmico de estudantes, auxiliando na identificação antecipada de possíveis dificuldades de aprendizagem e riscos de baixo rendimento escolar.

A proposta utiliza dados relacionados ao histórico acadêmico e ao engajamento dos estudantes para construir modelos preditivos capazes de estimar suas notas e apoiar ações preventivas no ambiente educacional.

## Objetivos

- Desenvolver modelos de Machine Learning para previsão de desempenho acadêmico.
- Identificar padrões relacionados ao rendimento e ao engajamento dos estudantes.
- Avaliar diferentes configurações de treinamento e desempenho dos modelos.
- Utilizar as previsões como ferramenta de apoio à gestão pedagógica preventiva.

## Base de Dados

O projeto utiliza uma base de dados obtida no Kaggle, contendo 10.000 registros de estudantes.

Foram selecionados seis atributos relacionados ao histórico de desempenho e ao engajamento acadêmico, utilizando `exam_score` como variável-alvo para a previsão.

O pré-processamento inclui a divisão dos dados em conjuntos de treinamento, validação e teste, além da normalização das variáveis utilizando `StandardScaler`.

## Tecnologias e Bibliotecas

- **Python:** linguagem utilizada no desenvolvimento.
- **Google Colab:** ambiente de desenvolvimento e execução do notebook.
- **TensorFlow:** construção e treinamento de redes neurais artificiais.
- **Scikit-learn:** pré-processamento e ferramentas de Machine Learning.
- **Pandas:** manipulação e análise dos dados.
- **NumPy:** operações numéricas.
- **Matplotlib:** geração de gráficos.
- **Grid Search:** experimentação e comparação de configurações de treinamento.
- **Livelossplot:** acompanhamento visual das métricas durante o treinamento.

## Desenvolvimento e Avaliação

Foram realizados experimentos com diferentes quantidades de épocas de treinamento (2, 5, 40 e 50), buscando identificar uma configuração adequada para o desempenho do modelo.

Também foram avaliadas técnicas de tratamento do desbalanceamento dos dados, incluindo SMOTE e Undersampling, além do ajuste do limiar de decisão (*Threshold Tuning*).

A configuração de 40 épocas apresentou o equilíbrio mais satisfatório entre as alternativas avaliadas. O limiar de decisão de 68,0 pontos foi utilizado como referência para a identificação de estudantes em situação de risco acadêmico.

## Resultados e Aplicabilidade

A solução desenvolvida demonstra o potencial da utilização de Machine Learning na análise do desempenho acadêmico, permitindo identificar estudantes que podem necessitar de acompanhamento pedagógico adicional.

Como possibilidade de evolução, o projeto poderá ser integrado futuramente a sistemas acadêmicos e plataformas educacionais, ampliando sua aplicação em instituições de ensino.

## Como Executar

1. Acesse o notebook `Trabalho_Machine_Learning.ipynb` disponível neste repositório.
2. Abra o arquivo utilizando o Google Colab.
3. Disponibilize a base de dados `student_dataset_10000_rows.csv` no ambiente de execução.
4. Execute as células do notebook na sequência apresentada.

## Autores

Projeto acadêmico desenvolvido como atividade de estudo e aplicação prática de conceitos de Inteligência Artificial e Machine Learning.
