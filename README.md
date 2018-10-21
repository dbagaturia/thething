# Комментарии к заданиям

## Оцифровка черновика Пушкина
[Ссылка на файл xml](https://github.com/dbagaturia/vertigo/blob/master/%D0%A3%D0%B2%D1%8B_%20%D1%8F%D0%B7%D1%8B%D0%BA!_%D0%9F%D1%80%D0%B5%D0%B4%D1%87%D1%83%D0%B2%D1%81%D1%82%D0%B2%D0%B8%D0%B5.xml)
## Карта 
На [карте](https://github.com/dbagaturia/vertigo/blob/master/Tropic_of_Cancer.geojson), созданной с помощью [geojson.io](http://geojson.io/#map=2/20.0/0.0), изображен парижский маршрут главного героя романа Генри Миллера "Тропик Рака". Герой подробно и последовательно описывает места, которые ему доводилось посещать в Париже. Маршруты разных дней размечены разными цветами. Так, мы выделили девять маршрутов: **синий**, **голубой**, **зеленый**, **бирюзовый**, **бежевый**, **фиолетовый**, **малиновый**, **розовый**, **желтый**. Вилла Боргезе, которая в большинстве случаев служила отправной точкой для путешествий героя по городу, вокзал Сан-Лазар, улица Шато и сад Тюильри, где любил бродить персонаж, кафе "Дом", где собиралась парижская эмиграция, обозначены **красным** цветом, поскольку они неоднократно упоминались в романе. **Черным** цветом помечены любимые места героя в Париже, которые не примыкают ни к одному из маршрутов. 

### Источники
[Текст романа](https://github.com/dbagaturia/vertigo/blob/master/Genri_Miller_-_Tropik_Raka.pdf)

[Карта Парижа 1928 года](https://github.com/dbagaturia/vertigo/blob/master/20150819155713_paris_1928_geo_preview_0.jpg)

### Что показывает карта
Карта визуализирует сложносочиненный маршрут героя "Тропика Рака" и показывает самые посещаемые им округа. Также она демонстирует разнообразие обозначений каждого маркера (дом, кафе, улица,театр etc) и, как следствие, дает понимание о том, в какие места чаще всего ходил герой и какие топонимы связаны с американскими эмигрантами. Благодаря связкам между пунктами маршрутов мы можем увидеть, насколько длинные дистанции преодолевал герой.

## Граф персонажей
1. [Граф](https://github.com/dbagaturia/vertigo/blob/master/Pir.pdf) по пьесе Луиджи Пиранделло "Это так (если вам так кажется)".

2. [Исходные данные графа](https://github.com/dbagaturia/vertigo/blob/master/ezlinavis.csv).

3. Скриншоты экрана во время работы с Gephi: [1](https://github.com/dbagaturia/vertigo/blob/master/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202018-10-21%20%D0%B2%2012.26.11.png), [2](https://github.com/dbagaturia/vertigo/blob/master/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202018-10-21%20%D0%B2%2012.26.36.png), [3](https://github.com/dbagaturia/vertigo/blob/master/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202018-10-21%20%D0%B2%2012.26.45.png). Как видно на **снимке №2**, в режиме предпросмотра не отображался результат. Также в нашей версии не обновлялись настроенные параметры.

### Метрики

**Плотность графа** - 1. Все персонажи взаимодействуют друг с другом. Даже дворецкий, у которого всего несколько реплик, появляется в каждом действии.

[Отчет по кластеризации](https://github.com/dbagaturia/vertigo/blob/master/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202018-10-21%20%D0%B2%2012.53.24.png) показывает, что актуализированных взаимодействий в пьесе 680. В пьесе Пиранделло три действия, и она не делится на явления, что несколько затрудняет ее обработку в Gephi. Как и в других произведениях итальянского драматурга (например, в "Шести персонажах в поиске автора"), все герои задействованы на сцене и взаимодействуют друг с другом.
Как видно на графе, **основной узел** составляют Амалия Агацци, ее муж Агацци, их дочь Дина, сеньор и сеньора Сирелли, Ламберто Лаудизи, дворецкий, сеньор Понца, вокруг которого разгорается конфликт, сеньора Чинни и сеньора Ненни. Именно они начинают сплетничать о сеньоре Фролле, сеньоре Понца и о его жене, которая появляется лишь в финале пьесы в образе леди в вуали. Несмотря на то что жена сеньора Понца и дочь сеньоры Фролы упоминается каждым действующим персонажем, **узел** ее героини один их самых маленьких.

## Работа с Национальным корпусом русского языка и Google Ngram Viewer
Мы предлагаем проследить **историю слова "синенькие" в русской литературе** с помощью [Google Ngram Viewer](https://books.google.com/ngrams) и [Национального корпуса русского языка](http://www.ruscorpora.ru/). Для начала посмотрим, в какие года слово использовалось чаще всего (выборка 1800-2000 гг.):

![Alt-текст](https://github.com/dbagaturia/vertigo/blob/master/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202018-10-21%20%D0%B2%2013.36.14.png "Заголовок изображения")

Как видно, слово "синенькие" начало широко использоваться только с 1920 годов, до этого встречалось в текстах 1860-х и 1880-х годов. Далее узнаем, с какими словами слово "синенькие" употреблялось чаще:

![Alt-текст](https://github.com/dbagaturia/vertigo/blob/master/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202018-10-21%20%D0%B2%2013.29.29.png "Заголовок изображения")

Чаще всего слово "синенькие" употреблялось в качестве эпитета (синенькие и, синенькие глазки, синенькие цветочки), однако также можно было встретить "синенькие бумажки" и "синенькие книжечки". За более подробной информацией обратимся к Национальному корпусу русского языка. Поскольку нас интресует именно множественное число, выберем соответствующий параметр в окне грамматических признаков и упорядочим результат по дате создания.
Первый пример употребления датируется 1799-1806 годами, когда издавалась "Повесть о рождении моем, происхождении и всей моей жизни, писанная мной самим и начатая в Москве, 1788-го года в августе месяце, на 25-ом году моей жизни" И. М. Долгорукого:
><blockquote>Пускай, думал я, они режутся между собою; на таком стотысячном поле не воинов, кровь лиющих, но купцов, сыплющих червонные, беленькие, красные и синенькие бумажки...</blockquote>
"Синенькими бумажками" или просто "синенькими" обозначались пятирублевые ассигнации синего цвета. Национальный поэтический корпус выдает множество подобных примеров употребления слова "синенькие" (также "синенькие бумажки" и "синенькие книжечки"): у А. И. Герцена (1841-1846), В. Ф. Одоевского (1841), Ф. М. Достоевского (1846), Н. И. Греча (1849-1856), Л. Н. Толстого (1856), А. Ф. Писемского и многих других. Здесь данные несколько расходятся с тем, что выдает Google Ngram Viewer.
Наряду с примерами употребления слова "синенькие" в качестве эпитета и в смысле пятирублевых кредитных билетов в Национальном корпусе русского языка наличествуют и другие варианты использования слова в ином значении. Так, сперва в переписке Ал. П. Чехова с А. П. Чеховым не раз встречается слово "синенькие" в значении "баклажаны":
![Alt-текст](https://github.com/dbagaturia/vertigo/blob/master/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202018-10-21%20%D0%B2%2014.14.54.png "Заголовок изображения")
![Alt-текст](https://github.com/dbagaturia/vertigo/blob/master/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202018-10-21%20%D0%B2%2014.14.59.png "Заголовок изображения")
![Alt-текст](https://github.com/dbagaturia/vertigo/blob/master/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202018-10-21%20%D0%B2%2014.15.33.png "Заголовок изображения")
Напомним, что А. П. Чехов и его брат, Ал. П. Чехов, родились в Таганроге: именно в южных регионах России и можно услышать такое употребление. Через несколько лет после вышеприведенных писем  "синенькие" возникнут в чеховских рассказах "Мужики" (1897) и "Человек в футляре" (1898). Согласно Национальному корпусу русского языка, это первое употребление слова "синенькие" в значении "баклажаны" в русской литературе. Поэтому автор воспоминаний о Чехове А. А. Хотяинцева, работая над текстом с 1904 по 1942 годы, видит необходимость в пояснении слов:
><blockquote>Тут же около роз находился огород с любимыми «красненькими» (помидоры) и «синенькими» (баклажаны) и другими овощами.</blockquote>

 ## Презентация "Цифровое воссоздание Великой Пергаментной Книги (The Great Parchment Book): 3D восстановление исторических документов, поврежденных от пожара"
[Ссылка на презентацию](https://github.com/dbagaturia/vertigo/blob/master/3D%20%D0%B2%D0%BE%D1%81%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%BE%D0%B2%D1%80%D0%B5%D0%B6%D0%B4%D0%B5%D0%BD%D0%BD%D1%8B%D1%85%20%D0%B2%20%D0%BF%D0%BE%D0%B6%D0%B0%D1%80%D0%B5%20%D0%B4%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%BE%D0%B2.pdf)


