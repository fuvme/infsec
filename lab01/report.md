---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №1"
subtitle: "Развертывание виртуальной машины"
author: "Виноградова варвара Станиславовна НФИбд-01-18"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Приобретение практических навыков установки операционной системы на виртуальную машину, размещение файлов на сервисе Git и подготовка отчета в формате Markdown.

# Выполнение лабораторной работы

Создаю виртуальную машину, выбираю тип конфигурации

![Выбор типа конфигурации](image/01.png){ #fig:001 width=70% }

Выбираю файл образа, скаченный заранее.

![Выбор образа](image/02.png){ #fig:002 width=70% }

Называю виртуальную машину по своему имени. 

![vsvinogradova](image/03.png){ #fig:003 width=70% }

Увеличиваю число ядер до 4-х. 

![4 ядра](image/04.png){ #fig:004 width=70% }

Оставляю по умолчанию память для виртуальной машины. 

![2048 МБ](image/05.png){ #fig:005 width=70% }

Создаю новый виртуальный диск. 

![Создаю новый виртуальный диск](image/06.png){ #fig:006 width=70% }

Увеличиваю память виртуального диска до 40 Гб. 

![40 Гб](image/07.png){ #fig:007 width=70% }

Следующие настройки оставляю по умолчанию и запускаю виртуальную машину.

![Приветственный экран](image/08.png){ #fig:008 width=70% }

Устанавливаю жесткий диск. Выбираю язык.

![Установка языка](image/09.png){ #fig:009 width=70% }

Указываю параметры установки

![Установка разбиения диска](image/10.png){ #fig:010 width=70% }

![Установка разбиения диска](image/11.png){ #fig:011 width=70% }

![Установка имени хоста](image/12.png){ #fig:012 width=70% }

![Установка часового пояса](image/13.png){ #fig:013 width=70% }

Создаю пароль суперпользователя

![Установка пароля root](image/14.png){ #fig:014 width=70% }
 
Перехожу к этапу установки и дожидаюсь его завершения.

![Разбиение диска](image/15.png){ #fig:015 width=70% }

![Этап установки](image/16.png){ #fig:016 width=70% }

![Завершение установки](image/17.png){ #fig:017 width=70% }

Загружаю с жесткого диска установленную систему

![Приветственный экран](image/18.png){ #fig:018 width=70% }

![Лицензионное соглашение](image/19.png){ #fig:019 width=70% }

![Создание пользователя](image/20.png){ #fig:020 width=70% }

![Установка даты и времени](image/21.png){ #fig:021 width=70% }

![Запущенная CentOS](image/22.png){ #fig:022 width=70% }

# Вывод

Я приобрела навыкустановки операционной системы на виртуальную машину, разместила файлы работы на сервисе Git и подготовила отчет в формате Markdown.