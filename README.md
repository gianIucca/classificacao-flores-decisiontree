
Banco de dados próprio da biblioteca sklearn contendo 150 entradas de dados de flores da família Iris para o desenvolvimento e treinamento de modelos de Machine Learning. O primeiro passo é importar esses dados e atribuir eles a um dataframe do Pandas, e realizar a visualização gráfica das features do dataframe para verificar visualmente e entender os tipos diferentes de flores. Após a criação dos gráficos com plotly, matplotlib e seaborn, os dados foram separados em treino e teste para o treinamento dos classificadores. <br>

Modelos de classificação desenvolvidos: <br>

1)Decision Trees Classifier <br>
2)K-Neighbors  <br>
3)Support Vector Machines  <br>
4)Random Forest  <br>
5)XGboost <br>

Após o desenvolvimento dos classificadores, também foi realizado o tuning dos hiperparametros com o método GridSearch (https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html) dos modelos de SVC, RandomForest e GradientBoosting, e após isso, foi verificada a interpretabilidade e as predições feitas pelo modelo com a biblioteca do lime (https://lime-ml.readthedocs.io/en/latest/lime.html#module-lime.lime_tabular).
