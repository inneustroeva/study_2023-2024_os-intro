---
## Front matter
title: "Индивидуальный проект этап 5"
subtitle: "Персональный сайт"
author: "Неустроева Ирина Николаевна"

## Generic otions
lang: ru-RU 
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью моей работы было: Добавить с сайту все остальные элементы.

# Задание 

1. Сделать записи для персональных проектов.

2. Сделать пост по прошедшей неделе.

3. Добавить пост на тему по выбору. Языки научного программирования.

# Выполнение лабораторной работы 

1. Для начала перешли в папку ~/work/blog/content/project/example и открыли файл index.md чтобы написать проект (рис. [-@fig:001]).

![файл index.md  ](image/1.jpg){#fig:001 width=70%}

* Вот так выглядит наш сайт теперь (рис. [-@fig:002]).

![Сайт](image/2.jpg){#fig:002 width=70%}

2. Далее создали два новых поста по прошедшей неделе и пост по выбору в каталоге ~/work/blog, с помощью ~/bin/hugo new post/название.( (рис. [-@fig:003]).

![Создание постов](image/3.jpg){#fig:003 width=70%}

* Перешли в папку ~/work/blog/content/post/last_week3 и написали пост в папке index.md (рис. [-@fig:004]).

![Пост](image/5.jpg){#fig:004 width=70%}

* Вот так выглядит наш сайт теперь (рис. [-@fig:005]).

![Сайт](image/4.jpg){#fig:005 width=70%}

3. Тоже самое проделываем для поста на тему Языки научного программирования.  (рис. [-@fig:006]).

![Пост](image/6.jpg){#fig:006 width=70%}

* Теперь можем посмотреть отредактированный пост на сайте (рис. [-@fig:007]).

![Сайт](image/7.jpg){#fig:007 width=70%}

Далее отправляем наши изменения на сервер (рис. [-@fig:008]).

![Отправка на сервер](image/8.jpg){#fig:008 width=70%} 

* Проверка изменений на сайте после отправки на сервер (рис. [-@fig:009]).

![Сайт](image/9.jpg){#fig:009 width=70%} 

# Вывод

В данной работе мы написали новые посты и сделали проект

::: {#refs}
:::
