# kaggle clean vs dirty plate binary classificator
Solution for Kaggle competition on the topic CV binary-classification \
rank - 1576/2924 \
score - 0.87903

link to profile - https://www.kaggle.com/cvbnqq \
link to competition - https://www.kaggle.com/competitions/platesv2/overview

Решение для соревнования на платформе Kaggle на классификацию по картинке грязной посуды и чистой

Особенность соревнования в том, что для обучения дано всего лишь 40 размеченных картинок

Для увеличения датасета я использовал ТОЛЬКО аугментацию, в целях обучения

Дообучал модель ResNet18, брать более глубокую модель я посчитал ошибкой, т к велика вероятность переобучения

Дообучались последний сверточный слой + нейронные слои
