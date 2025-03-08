---
## Front matter
title: "Индивидуальный проект. Этап 1"
subtitle: "Отчет"
author: "Зубов Иван Александрович"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Размещение на Github pages заготовки для персонального сайта.

# Задание

Установить необходимое программное обеспечение.
Скачать шаблон темы сайта.
Разместить его на хостинге git.
Установить параметр для URLs сайта.
Разместить заготовку сайта на Github pages.

# Выполнение лабораторной работы

Скачиваем Hugo и распаковываем его

![Распаковываем hugo](image/1.png){#fig:001 width=70%}

Создаем новый репозиторий на gihub. Называем его blog. Переходим в директорию work и клонируем репозиторий

![Создаем и клонируем новый репозиторий](image/2.png){#fig:002 width=70%}

Для дальнейшей работы нам понадобится go , поэтому скачиваем его

![Скачиваем go](image/3.png){#fig:003 width=70%}

Переходим в blog удаляем файлы public, потому что они нам не понадобятся

![Удаляем файлы public](image/4.png){#fig:004 width=70%}

Запускаем наш сервер

![Запускаем сервер](image/5.png){#fig:005 width=70%}

Теперь нам нужно сделать другой репозиторий на гитхаб. Создаем его и клонируем

![Создаем репозиторий и клонируем](image/6.png){#fig:006 width=70%}

Переходим в папку iazubov.github.io. Делаем бренч и отправляем файла на гитхаб

![Делаем бренч и отправляем файла на гитхаб](image/7.png){#fig:007 width=70%}

Устанавливаем submodule и прописываем hugo

![Устанавливаем submodule](image/8.png){#fig:008 width=70%}

Проверяем усатновили ли мы submodule и отправляем файлы на github

![отправляем файлы на github](image/9.png){#fig:009 width=70%}


# Выводы
Я разместил заготовки сайта на Github

