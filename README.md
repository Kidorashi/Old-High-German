## Древненемецкий корпус 2017

Проект создания корпуса текстов на древневерхненемецких диалектах (VII-XI вв. н.э.), а также на древненижненемецком (древнесаксонском) языке. Работа с оцифрованными прозаическими и поэтическими хрестоматийными текстами.

Над проектом работают студенты 3 и 4 курса [бакалаврской программы «Фундаментальная и компьютерная лингвистика» Высшей школы экономики](https://www.hse.ru/ba/ling/):

Михаил Айсин</br>
Ирина Глазунова</br>
Женя (last name - ???)</br>
Лера Зеленкова</br>
Алина Исламова</br>
Александра Савченко</br>
Полина Сонина</br>
Соня Стырина</br>


под руководством к.ф.н. Пименовой Натальи Борисовны и к.ф.н. [Орехова Бориса Валерьевича](http://nevmenandr.net/bo.php).

### Текущие задачи:
### 1. [Кластеризация словаря-1](https://github.com/phuuda/Old-High-German/tree/master/ahd-codes/clustering-lemmas)</br>

<b>Конечная цель:</b></br>
выделить из массива словоформ лексемы и автоматически сопоставить любую словоформу заголовочному слову из словаря.</br>

<b>Ближайшая цель</b>:</br>
корректирование полученных с помощью расстояния Левенштейна результатов:</br>
* незначащие совпадения по двум произвольным  соседним буквам. 
* элементы буквенно-фонологических сочетаний, не учтенных при автоматической обработке
* устранение латинских слов из списка, слова на hh.</br>

### 2. Кластеризация словаря-2

<b>Конечная цель</b>:</br>
получить соответствия между классическим словом и его вариациями в текстах, используя таблицу буквенно-фонетических переходов между текстами.</br>

<b>Ближайшая цель</b>:</br>
* убрать латинские слова и другие неподходящие моменты; 
* проверить, какие исключения порождает поиск с учетом [буквенно-фонетических переходов](https://docs.google.com/spreadsheets/d/1s1FnKh7CvT6Nz3hwzS2_zJcLeLmsWuIQHvayYSkKlcM/edit?ts=58a73a8a#gid=1033963496); 
* все сложить в словарь типа {современное слово : вариация1, вариация2, … }.

### 3. [Аналитическая обработка словаря](https://github.com/phuuda/Old-High-German/tree/master/ahd-dictionary)

<b>Конечная цель</b>:</br>
унификация документов, приведение текстов к удобному для обработки виду, подготовка к созданию словарных статей на самом сайте.

<b>Ближайшая цель</b>:</br>
* создание списка префиксов для определения корня, в котором действуют чередования, 
* тэггинг/обратное индексирование для поиска по лексеме в словаре формата json; 
* тэггинг толкований, частей речи, письменных источников, лексем на других языках, прочих грамматических пометок


### 4. [Веб-интерфейс](https://github.com/dkbrz/Old_High_German)

<b>Конечная цель</b>:</br>
[интерфейс](http://dkbrz.pythonanywhere.com/) с:</br>
* онлайн-словарем
* текстами с тултипами
* статистикой по документам, возможно - с визуализацией объема тех или иных языковых явлений для разных текстов
удобным поиском, навигацией, подкорпусом</br>

<b>Ближайшая цель</b>:</br>
* работа в режиме сервера
* договориться, в каком виде должны быть тексты и прочая информация, и унифицировать всё это для удобства загрузки на сайт.



