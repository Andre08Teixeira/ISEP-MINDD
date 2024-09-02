# PL4 - EnsembLearning

O conjunto de dados a ser analisado inclui medições de imagens digitalizadas de aspirado com agulha fina de uma massa mamária. Os valores representam características dos núcleos celulares presentes na imagem digital.
Os dados sobre câncer de mama incluem 569 exemplos de biópsias de câncer, cada uma com 32 características. Uma característica é um número de identificação, outra é o diagnóstico de câncer e 30 são medições laboratoriais com valor numérico. O diagnóstico é codificado como M para indicar célula maligna ou B para indicar célula benigna. As 30 medidas numéricas compreendem a média, o erro padrão e o pior (ou seja, o maior) valor para 10 características diferentes dos núcleos celulares digitalizados, que incluem: raio, textura, perímetro, área, suavidade, compacidade, concavidade, pontos côncavos, simetria e dimensão fractal.

1. Comece carregando o conjunto de dados ”wisc_bc_data.csv”.
2. Fazer a exploração gráfica dos atributos médios em função do atributo objetivo: diagnóstico, através de boxplots e histogramas.
3. Desenvolva modelos para previsão de diagnóstico usando os seguintes algoritmos:
   1. Naive Bayes
   2. k-Nearest Neighbors
4. Otimize os parâmetros dos algoritmos anteriores usando a estratégia de **grid search**.
5. Usando a classe VotingClassifier do sklearn, faça a **voting combination** dos modelos otimizados:
   1. Majority vote 
   2. Weighted majority vote 
6. Faça uma combinação de meta-aprendizagem (**stacking**) dos modelos otimizados usando os algoritmos:
   1. LogisticRegression 
   2. Support Vector Machines 
7. Desenvolva modelos de previsão de diagnóstico por amostragem:
   1. Bagging
      1. BaggingClassifier
      2. Random forest
   2. Boosting
      1. Adaboost
      2. Gradient Boosting
      3. XGBoost2
      4. LightGBM
8. Compare o desempenho de diferentes algoritmos.

