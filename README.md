# hse22_hw5

https://colab.research.google.com/drive/1MMSmK8tF0y_3jSoVY5K5PEbAMZjqffmI?usp=sharing

## Метод нормализации данных

Данные были нормализованы следующим методом TMP, так как длина транскрипции нам неизвестна:

<img src="https://render.githubusercontent.com/render/math?math={\Large TPM_i = \frac{q_i}{\sum q_j} \cdot 10^6}#gh-light-mode-only">

Изначально метод TMP выглядит так:

<img src="https://render.githubusercontent.com/render/math?math={\Large TPM_i = \frac{q_i / l_i}{\sum (q_j / l_j)} \cdot 10^6}#gh-light-mode-only">

## Heatmap
Как мы видим, несмотря на отсутсвие длин, мы получили такой же Heatmap, как и ожидалось
![Image](/img/heatmap.png)

## UMAP и PCA
UMAP | PCA 
 --- | ---
![Image](/img/UMAP.png) | ![Image](/img/PCA.png)

Данные разбиты по группам cTEC, mTEC-I, mTEC-II, mTEC-III, mTEC-IV, понижена размерность данных и получено деление на группы
