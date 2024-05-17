---
## Front matter
title: "Индивидуальный проект этап 6"
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

Целью моей работы было написать два новых поста 

# Задание 

- Размещение двуязычного сайта на Github.

- Сделать поддержку английского и русского языков.

- Разместить элементы сайта на обоих языках.

- Разместить контент на обоих языках.

- Сделать пост по прошедшей неделе.

- Добавить пост на тему по выбору (на двух языках).

# Выполнение лабораторной работы 

1. Создали новый пост по прошедшей неделе в каталоге ~/work/blog, с помощью ~/bin/hugo new post/название.( (рис. [-@fig:001]).

![Создание поста](image/1.jpg){#fig:001 width=70%}

* Перешли в папку ~/work/blog/content/post/last_week_4 и написали пост в папке index.md (рис. [-@fig:002]).

![Пост](image/3.jpg){#fig:002 width=70%}

* Вот так выглядит наш сайт теперь (рис. [-@fig:003]).

![Сайт](image/4.jpg){#fig:003 width=70%}

 Тоже самое проделываем для поста на тему дистрибутив Федора  (рис. [-@fig:004]).

![Пост](image/5.jpg){#fig:004 width=70%}

* Теперь можем посмотреть отредактированный пост на сайте (рис. [-@fig:005]).

![Сайт](image/6.jpg){#fig:005 width=70%}

Далее отправляем наши изменения на сервер и проверяем изменения на сайте  (рис. [-@fig:006]).

![Сайт](image/7.jpg){#fig:006 width=70%} 

# Вывод

В данной работе мы написали два новых поста. 

::: {#refs}
:::
