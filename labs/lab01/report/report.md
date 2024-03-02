---
## Front matter
title: "Отчёт по лабораторной работе №1"
subtitle: "Простейший вариант"
author: "Янушкевич Михаил Денисович"

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

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.



# Выполнение лабораторной работы

1. Переключаюсь на роль супер-пользователя и устанавливаю tmux.
![Рис.1](/media/sf_Work/1.png)

2. Устанавливаю необходимое ПО и запускаю таймер.
![Рис.2](/media/sf_Work/2.png)

3. Устанавливаю пакет DKMS.
![Рис.3](/media/sf_Work/3.png)

4. В меню ВМ подключаю образ гостевой ОС и подмонирую диск.
![Рис.4](/media/sf_Work/4.png)

5. Устанавливаю драйвера.
![Рис.5](/media/sf_Work/5.png)

6. Перехожу в tmux и создаю конфигурационный файл.
![Рис.6](/media/sf_Work/6.png)

7. Редактирую конфигурационный файл.
![Рис.7](/media/sf_Work/7.png)

8. Переключаюсь на роль супер-пользоателя и редактриую конфигурационный файл.
![Рис.8](/media/sf_Work/8.png)

9. Запускаю tmux, переключаюсь на супер-пользователя и создаю пользователя.
![Рис.9](/media/sf_Work/9.png)

10. Задаю пароль, устанавливаю имя хоста и проверяю.
![Рис.10](/media/sf_Work/10.png)

11. В хостовой системе через cmd подключаю разделяемую папку.
![Рис.11](/media/sf_Work/11.png)

12. Устнанавливаю pandoc. Для этого скачиваю необходимый релиз, разархивирую его и помещаю в каталог bin.
![Рис.12](/media/sf_Work/12.png)

13. Устанавливаю дистрибутив texlive.
![Рис.13](/media/sf_Work/13.png)

# Выводы

В лабораторной работе №1 я приобрел навыки по устрановки ВМ и ёё первончально настройке.


::: {#refs}
:::
