# Группа: М8О-410Б-21
# Студент: Катин Иван Вячеславович

- Ссылка на датасет для регрессии: https://www.kaggle.com/datasets/ruthgn/beer-profile-and-ratings-data-set
- Ссылка на датасет для классификации: https://www.kaggle.com/datasets/ivan314sh/prices-of-moscow-apartment

## Классификация

|Алгоритм|  Бейзлайн  | Улучшенный бейзлайн | Самостоятельная имплементация алгоритм (СИА) | СИА с улучшенным бейзлайном |
|:------:|:----------:|:-------------------:|:------------------------------------------:|:----------------------------|
|KNN     |    0.84    |          0.8536            |                    0.8403                  | 0.838                       |
|Линейные модели|   07308    |       0.779       |                    0.7367                  |               0.807              |
|Решающее дерево|   0.8564   |        0.841         |                    **0.8573**           |              0.8487               |
|Случайный лес  | **0.8913** |     **0.8871**     |                    0.809                   |                 **0.8633**          |
|Градиентный бустинг|   0.8597   |       0.8562     |                     0.845                        |     0.845                        |


## Регрессия
|     Алгоритм      |          Бейзлайн           |     Улучшенный бейзлайн      | Самостоятельная имплементация алгоритма | СИА с улучшенным бейзлайном      |
|:-----------------:|:---------------------------:|:----------------------------:|:---------------------------------------:|:---------------------------------|
|     KNN           |           0.2709            |            0.2523            |                 0.2709                  | 0.2523                           | 
|  Линейные модели  |           0.2683            |           0.2747             |                 0.2683                  | 0.2751                           |
|  Решающее дерево  |           0.3167            |   0.3209  |                 0.3084                  | 0.3158                           |
|   Случайный лес   |           0.2336            | **0.2263** |                 **0.2379**                  | **0.2365**                         |
|Градиентный бустинг|          **0.2303**           |   0.2326   |       0.3060    | 0.3201                           | 