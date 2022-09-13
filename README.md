# Get movie distance
Проект по предмету Data Scraping.

Задача: написать функции get_actors_by_movie_soup (возвращает список актеров для страницы фильма с сайта imdb.com) и get_movies_by_actor_soup(возвращает список фильмов, в которых снимался актер)

Для данного списка из 10 актеров посчитать расстояния между парами, составить графы дистанций между актерами. Дистанция между актерами - количество фильмов между ними. Например, нужно найти расстояние между Робертом Дауни Мл. И Крисом Эвансом. Для этого получаем список фильмов Роберта Дауни Младшего и для каждого фильма получаем список актеров. Если среди них есть искомый актер (Крис Эванс), то расстояние между этими актерами - 1. 

Во второй части необходимо для каждого актера составить Wordcloud: для этого проходим по всем фильмам, в которых снимался актер, собираем их описание в один текст и использем библиотеку wordcloud. 

Мой проект представлен в файле report.ipynb

Подробное описание задания: 

https://github.com/magnitofonov/hse-coursera-data-scraping/blob/master/week10/week_10_project_description.md

https://github.com/magnitofonov/hse-coursera-data-scraping/blob/master/week11/week_11_project_description.md

https://github.com/magnitofonov/hse-coursera-data-scraping/blob/master/week12/week_12_project_description.md


__________________
English version

This is the course project at first year of Master of Data Science.

The idea is to count movie distances between actors using imdb.com and use collected information. How distance is measured? If two actors played in the same movie, the distance between them is 1. If two actors never played in the same move, but there is some actor, who played in some movies with each of the actors, then the distance between the actors is 2. And so on.

My project is in file report.ipynb

Full task description:

https://github.com/magnitofonov/hse-coursera-data-scraping/blob/master/week10/week_10_project_description.md

https://github.com/magnitofonov/hse-coursera-data-scraping/blob/master/week11/week_11_project_description.md

https://github.com/magnitofonov/hse-coursera-data-scraping/blob/master/week12/week_12_project_description.md
