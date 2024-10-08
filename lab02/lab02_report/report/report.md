---
## Front matter
title: "Лабораторная работа №2"
subtitle: "Отчёт к лабораторной работе"
author: "Зайцева Анна Дмитриевна"

## Generic options
lang: ru-RU

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
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
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

Цель работы --- Научиться оформлять отчёты с помощью легковесного языка Markdown.

# Задание

- Сделать отчёт по предыдущей лабораторной работе в формате Markdown.
- Предоставить отчёты в 3 форматах: docx, pdf, md.

# Выполнение лабораторной работы

1) В каталоге OS создадим каталог lab03 (Рис. [-@fig:001]) и скопируем в него шаблоны для отчёта (Рис. [-@fig:002]) и презентации (Рис. [-@fig:003]) в формате .md:

![Рис. 1](lab03-изображения/1.png){ #fig:001 width=70% }

![Рис. 2](lab03-изображения/2.png){ #fig:002 width=70% }

![Рис. 3](lab03-изображения/3.png){ #fig:003 width=70% }

2) Редактируем скопированный документ с шаблоном отчёта и делаем это на основе отчёта к лабораторной работе №2 (Рис. [-@fig:004]):

![Рис. 4](lab03-изображения/4.png){ #fig:004 width=70% }

3) Сохраняем отчёт в 3 форматах: docx, pdf, md.

4) Обновляем данные на GitHub (Рис. [-@fig:005]):

![Рис. 5](lab03-изображения/5.png){ #fig:005 width=70% }

# Вывод

Я научилась оформлять отчёты с помощью легковесного языка Markdown.
