---
## Front matter
title: "Лабораторная работа №4"
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

Получение навыков правильной работы с репозиториями git.

# Задание

Выполнить работу для тестового репозитория.
Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.

# Выполнение лабораторной работы

Установка git-flow

![Установка git flow](image/1.png){#fig:001 width=70%}

Установим Node.js

![Установка Node.js](image/2.png){#fig:002 width=70%}

Для работы с Node.js добавим каталог с исполняемыми файлами, устанавливаемыми yarn, в переменную PATH.

![Настройка Node.js](image/3.png){#fig:003 width=70%}

Форматируем коммиты и создаем логы

![Общепринятые коммиты](image/4.png){#fig:004 width=70%}

Создаём репозиторий на GitHub, делаем первый коммит и выкладываем на github

![Создание репозитория git](image/5.png){#fig:005 width=70%}

Сконфигурим формат коммитов. Для этого добавим в файл package.json команду для формирования коммитов

![Редактируем package.json](image/6.png){#fig:006 width=70%}

Добавим новые файлы, выполним коммит и отправим на github

![отправляем файлы на github](image/7.png){#fig:007 width=70%}

Инициализируем git-flow, загрузите весь репозиторий в хранилище и установите внешнюю ветку как вышестоящую для этой ветки

![Конфигурация git-flow](image/8.png){#fig:008 width=70%}

Создадим релиз с версией 1.0.0, следующей командой создадим журнал изменений,добавим журнал изменений в индекс, зальём релизную ветку в основную ветку и отправим данные на github

![Создадим релиз с версией 1.0.0 и отправим данные на гитхаб](image/9.png){#fig:009 width=70%}

Создадим ветку для новой функциональности,создадим релиз с версией 1.2.3, зальём релизную ветку в основную ветку и отправим данные на гитхаб

![Работа с репозиторием git и отправка данных на гитхаб](image/10.png){#fig:010 width=70%}

# Выводы

Мы научились правильно работать с репозиторием
