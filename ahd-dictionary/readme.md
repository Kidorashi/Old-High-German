## OHG DICT общий to-do list:

<b>еще раз вручную проверить ohg_dictionary</b> (потенциально понадобится, пока не нужно):
* line separation -- сделано
* header word(s)
* исправить смешение cyrillic/latin symbols в словах -- сделано

# Задачи для компьютерщика:

.txt --> .html -- сделано</br>
убрать случайные дупликаты словарных статей -- сделано</br>

1. <b>Разметка латинских & старофранцузских слов в текстах</b>: -- сделано
* [notker.txt](https://github.com/phuuda/Old-High-German/blob/master/ahd-texts/texts/notker.txt),</br>
[tatian.txt](https://github.com/phuuda/Old-High-German/blob/master/ahd-texts/texts/tatian.txt),</br>
[evangelienbuch.txt](https://github.com/phuuda/Old-High-German/blob/master/ahd-texts/texts/evangelienbuch.txt),</br>
[isidor.txt](https://github.com/phuuda/Old-High-German/blob/master/ahd-texts/texts/isidor.txt),</br>
[eide.txt](https://github.com/phuuda/Old-High-German/blob/master/ahd-texts/texts/eide.txt)
* тэг ```<latin>, <rom>```

2. <b>Add semantic tags</b>: -- сделано
* <b>header word(s)</b> -- сделано 

* <b>definition</b>:</br>

```<b>feigi</b>, свн. veige (прил.) <em>обреченный, проклятый, приносящий горе, рнвн. испуганный</em>; нн. feig <em>трусливый</em>; дс. fegi, да. fAE-Ʒe, ди. feigr.```</br></br>

* <b>слова из других языков</b>: ```фр. <lex>adieu</lex>``` -- сделано

* <b>ссылка на другую статью</b>: ```<linked variants="gibur, buan">```см. gibur, buan```</linked>``` -- сделано 
* <b>source</b>:		```<source>— Нотк.—</source>``` -- сделано
* <b>gender</b>:		```<gender>жр</gender>, <gender>мр</gender>, <gender>срр</gender>``` -- сделано
* <b>language</b>:		```<lang>свн.</lang>, <lang>нн.</lang>``` -- сделано

			
<b>remove ```<p>``` tags</b>

<b>check all abbrev. forms</b> -->
* сокр., ср., см.
* etc.

# Задачи для теоретиков: -- сделано (more or less)

<b>Разбить на осмысленные группы те пометки, которые встречаются в скобках</b> -->
Ссылка на таблицу со всеми данными: https://docs.google.com/spreadsheets/d/1j33LH0bfYYutZvy5y7268e4jOhSJafDp4PCbS2Q3pAY/edit#gid=0

* POS:
```
(предл. с дат. вин.)
(предл.)
(нар.)
(прил.)
(числ.)
(межд.)
(гл.)
(прич.)
(мест.)
(пред.)
```
* languages:
```
(франц.)
(свн.)
(греч.)
(бав.)
(лат.)
(вн.)
(сн.)
(рун.)
```
* other grammatical notes (?):
```
(род.)
(заимств.)
(усил.)
(устар.)
(уменьш.)
(возвр.)
(пар.)
(простор.)
(непер.)
(перех.)
(возвр. прпргл.)
(часто в безл. оборотах с дат.)
(с род.)
(обычно с род.)
(также слскл.)
(в этом значении срр к концу свн.)
(при л.)
(из нжн.)
(с инф.)
(предл. с дат.)
(нар. сз.)
(числ. прил.)
(предл. с вин. и нар.)
(субст. прил.)
(прил. прич.)
(снгл. возвр.)
(предл. с дат. вин.)
(отн. мест.)
(неопр. мест.)
(предл. с вин.)
(гл. прил.)
(субст. мест.)
(указ. мест.)
(прил. нар.)
(нескл. прил.)
(нар. предл.)
(прич. прил.)
(предл. с дат. твор. вин.)
(предл. с род. дат.)
(двн. мест.)
(вопр. мест.)
(прил. мест.)
(субст. прич.)
(возвр. мест.)
(прит. мест.)
(нар. предл. сз.)
(субст. гл.)
(предл. с вин. дат.)
(личн. мест.)
(нар. предл. с вин. дат.)
(прил. с род.)
(предл. с дат. род.)
(с вин.)
(снгл. слгл.)
(субст. межд.)
(мест. мн. им.)
```

* uknown:
```
(ô), (i), (n)

(сз.)
(слгл.)
(прпргл.)
(снгл.)
(прнп.)
(нрпл.)
(субст.)
(орил.)
(прнл.)
(зоол.)
(юн.)
(ел.)
(лрил.)
(коррел.)
(корн.)
(преф.)

```
* etc.

## Questions, issues:
* для разделения каких 'кусков' статьи употребляется ';' ?
