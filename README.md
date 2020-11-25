# Projeto2-Cdados

## Integrantes do grupo:
* Fabricio Neri Lima
* Wilgner Lopes

## Descrição dos arquivos presentes no GITHUB do grupo:

O arquivo contendo o relatório e o desenvolvimento do projeto está na pasta [SRC](https://github.com/wilgnerl/Projeto2-Cdados/tree/main/src).
Na pasta [DATA](https://github.com/wilgnerl/Projeto2-Cdados/tree/main/data) estão os datasets utilizados para o projeto.

## Sobre o projeto:

A empresa InsperAnalytics contratou dois engenheiros do Insper para prestar um serviço de exploração, análise e previsão de uma variável em uma base de dados referente ao consumo de alcool dos estudantes com base nas suas informações pessoais, informações academicas e as materias estudadas no colegio.

O objetivo dos engenheiros é fazer uma analise exploratoria completa na base de dados e conseguir informações suficientes para poder gerar uma hipotese sobre a relação da variavel escolhida com as demais e com isso prever possiveis resultados com a hipotese gerada.

A base de dados que foi dadas ao engenheiro contem variaveis quantitativas e qualititativas, ou seja variaveis numericas e variaveis de categorias/ rotulos. 
Todo o trabalho usará o conhecimento que os engenheiros adquiriram na materia de Ciencia de Dados, e usará a linguagem de programação python como ferramenta para esse serviço.

O metodo de previsão será a partir de classificadores, por conta da maioria das variaveis serem qualitativas.

## Objetivo do projeto:

Através do dataset escolhido, queremos descobrir se o **consumo de álcool** dos estudantes  é influenciado pelas **características familiares e sociais** como citam as principais bibliografias sobre o assunto. Para isso, utilizamos dois classificados, **MultinomialNB e Random Forest** para prever os rótulos e alçancar o objetivo que almejamos através da nossa pergunta.

## Cronograma
- [x] 10/11 - Leitura do Dataset e Início do JupyterNotebook
- [x] 15/11 - Análise exploratória do DataSet
- [x] 17/11 - Primeira versão do algoritmo escolhido
- [x] 19/11 - Entrega dos resultados
- [ ] 24/11 - Entrega do projeto finalizado

## Bibliografias utilizadas para a fundamentação do projeto

[Sociedade Brasileira de Pediatria - Manual de Orientação](https://www.sbp.com.br/fileadmin/user_upload/publicacoes/N-ManOrient-Alcoolismo.pdf)

[Brazilian Journal of Psychiatry - Uso de álcool entre adolescentes](https://www.scielo.br/scielo.php?script=sci_arttext&pid=S1516-44462004000500005)

[Revista Latino Americana de Enfermagem - 
Programa para fortalecer factores protectores que limitan el consumo de tabaco y alcohol en estudiantes de educación media](https://www.scielo.br/scielo.php?script=sci_arttext&pid=S0104-11692004000700005&lng=es&tlng=es)

[Departamento científico de adolescência](https://www.sbp.com.br/especiais/pediatria-para-familias/adolescencia/adolescencia-e-alcool/)

[Ensinando Máquinas - Modelos Preditivos de Notas de Redação do ENEM 2015](https://ensinandomaquinasblog.wordpress.com/2017/12/15/modelos-preditivos-de-notas-de-redacao-do-enem-2015/)

[Machina Sapiens - Aprendendo em uma Floresta Aleatória](https://medium.com/machina-sapiens/o-algoritmo-da-floresta-aleat%C3%B3ria-3545f6babdf8#:~:text=Conclus%C3%A3o-,Como%20Funciona,com%20o%20m%C3%A9todo%20de%20bagging)

[Orgânica, Natural Marketing - Algoritmo de Classificação Naive Bayes
](https://www.organicadigital.com/blog/algoritmo-de-classificacao-naive-bayes/#:~:text=O%20algoritmo%20de%20Naive%20Bayes,dado%20que%20tem%20a%20doen%C3%A7a%E2%80%9D.)

[Regressão Logística - USP](https://edisciplinas.usp.br/pluginfile.php/3769787/mod_resource/content/1/09_RegressaoLogistica.pdf)

[Sklearn - Regressão Logística](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)

[Sklearn - MultinomialNB](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html)

[Sklearn - RandomForest Classificador](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)

[Matheusfacure - Regressão Logística](https://matheusfacure.github.io/2017/02/25/regr-log/)

[DataVisualization - SeaBorn](https://seaborn.pydata.org/)
