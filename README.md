# Deteccao_Fake_News

# Detectando notícias falsas com Python

Para construir um modelo para classificar com precisão uma notícia como REAL ou FALSIFICADA.

Sobre a detecção de notícias falsas com Python

Este projeto Python avançado de detecção de notícias falsas lida com notícias falsas e reais. Usando sklearn, construímos um TfidfVectorizer em nosso conjunto de dados. Em seguida, inicializamos um Classificador PassiveAggressive e ajustamos o modelo. No final, a pontuação de precisão e a matriz de confusão nos dizem o quão bem nosso modelo se sai.

# O conjunto de dados de notícias falsas

O conjunto de dados que usaremos para este projeto Python - vamos chamá-lo de news.csv. Os dados podem ser encontrados em https://www.kaggle.com/c/fake-news/data e trabalhados de várias maneiras. Neste caso, fiz a junção dos arquivos train e test em 1 só para aplicar a função train_test_split do sklearn.

Portanto, este conjunto de dados tem o formato de 7796 × 4. 
1. A primeira coluna identifica a notícia, 
2. título 
3. texto
4. e a quarta coluna possui rótulos que indicam se a notícia é REAL ou FALSIFICADA.

# Ferramentas utilizadas neste projeto
* NumPy
* Pandas
* itertools
* sklearn
* searborn
* matplotlib

