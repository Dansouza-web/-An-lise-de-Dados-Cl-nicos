# -An-lise-de-Dados-Cl-nicos
🫀 Análise de Dados Clínicos
Projeto desenvolvido por Daniel de Souza como parte do estudo de Python para Data Science.

🎯 Objetivo
Analisar dados clínicos de pacientes com o intuito de detectar padrões que indiquem a ocorrência de ataques cardíacos. Para isso, são utilizadas técnicas como:

-Análise exploratória

-Estatística descritiva

-Visualização de dados

-Modelagem preditiva com Árvore de Decisão

📂 Base de Dados
A base utilizada está disponível no Kaggle:
🔗 Heart Attack Dataset - Tarik A. Rashid
https://www.kaggle.com/datasets/fatemehmohammadinia/heart-attack-dataset-tarik-a-rashid

🧪 Dados Utilizados
A base contém variáveis clínicas e fisiológicas, incluindo:

Idade

Gênero

Frequência Cardíaca

Pressão Arterial (sistólica e diastólica)

Nível de Glicose

Enzima Cardíaca

Proteína Cardíaca

Resultado (0 = Sem Ataque, 1 = Com Ataque)

🧰 Tecnologias e Bibliotecas
Python

Pandas

NumPy

Seaborn

Matplotlib

Scikit-learn para Machine Learning

📊 Etapas do Projeto

Carregamento e limpeza dos dados

Renomeação de colunas

Conversão de dados categóricos

Verificação de valores nulos

Análise exploratória

Estatísticas descritivas

Visualizações: violin plot, scatter plot, heatmap

Geração de insights estatísticos

Comparação de médias e medianas por diagnóstico

Modelagem preditiva com Árvore de Decisão

Treinamento e teste com train_test_split

Avaliação com matriz de confusão e relatório de classificação

Visualização da árvore

Identificação das variáveis mais importantes


🌳 Resultado da Modelagem
A árvore de decisão foi capaz de identificar padrões significativos para distinguir pacientes com maior risco de ataque cardíaco.
As variáveis mais relevantes para o modelo foram:

-Proteína Cardíaca
-Enzima Cardíaca
-Frequência Cardíaca

