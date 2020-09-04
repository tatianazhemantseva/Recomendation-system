# Recomendation-system
Рекомендательная система
Имеется история оценок пользователя train.csv вместе с его отзывом на товар. Вы можете использовать текст рецензии в качестве дополнительной информации. Все оценки пользователей нормированы для бинарной классификации: если человек поставил оценку продукту 4 и больше, то мы считаем, что продукт ему понравился, если меньше 4, то продукт не понравился.

test.csv - набор данных, для которого вы должны сделать предсказания. У каждого наобора userid, itemid есть свой id, для которого вы должны сделать предсказание.
meta - файл с набором данных для itemid

train.csv:
overall - рейтинг, который поставил пользователь

verified - был ли отзыв верифицирован

reviewTime - когда был отзыв написан

reviewerName - имя пользователя

reviewText - текст отзыва

summary - сжатый отзыв

vote - количество голосований за отзыв

style - метаданные

image - изображение продукта

userid - id пользователя

itemid - id товара

id - id для предсказания

Метрики
В качестве метрики для оценки ваших рекомендаций используется RocAuc.

Результаты соревнования на https://www.kaggle.com/c/recommendationsv4/leaderboard

Выполнено:
EDA
Обучение рекомендательной системы разными алгоритмами. Огромный недостаток при реализации алгоритма с фичами  - не хватает памяти.
Проработка холодного старта.
Построение прототипа
