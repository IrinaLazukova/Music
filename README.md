# Музыка в Москве и Санкт-Петербурге

Сравнение Москвы и Петербурга окружено мифами. Например:
- Москва — мегаполис, подчинённый жёсткому ритму рабочей недели;
- Петербург — культурная столица, со своими вкусами.

Попробуем сравнить музыкальные предпочтения пользователей двух столиц.

## Данные 
В наличии были следующие данные о прослушиваниях треков в сервисе Яндекс.Музыка:

- `userID` — идентификатор пользователя;
- `Track` — название трека;  
- `artist` — имя исполнителя;
- `genre` — название жанра;
- `City` — город пользователя;
- `time` — время начала прослушивания;
- `Day` — день недели.

## Задача — проверить три гипотезы:
1. Активность пользователей зависит от дня недели. Причём в Москве и Петербурге это проявляется по-разному.
2. В понедельник утром в Москве преобладают одни жанры, а в Петербурге — другие. Так же и вечером пятницы преобладают разные жанры — в зависимости от города. 
3. Москва и Петербург предпочитают разные жанры музыки. В Москве чаще слушают поп-музыку, в Петербурге — русский рэп.

## Используемые библиотеки

pandas
