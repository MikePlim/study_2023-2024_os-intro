---
## Front matter
title: "Отчёт по лабораторной работе №5"
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

1. Получить навыки правильной настройки рабочей среды.

# Выполнение лабораторной работы

1. Устанавливаю pass и gopass.

![](/media/sf_Work/lab4/1.png)

2. Инициализирую хранилище.

![](/media/sf_Work/lab4/2.png)

3. Синхронизирую с git.

![](/media/sf_Work/lab4/3.png)

4. Устанавливаю плагин.

![](/media/sf_Work/lab4/4.png)

5. Добавляю новый пароль.

![](/media/sf_Work/lab4/5.png)

6. Отображаю пароль.

![](/media/sf_Work/lab4/6.png)

7. Заменяю существующий пароль.

![](/media/sf_Work/lab4/7.png)

8. Устанавливаю дополнительно ПО.

![](/media/sf_Work/lab4/8.png)

9. Устанавливаю шрифты.

![](/media/sf_Work/lab4/9.png)

10. Устанавливаю бинарный файл.

![](/media/sf_Work/lab4/10.png)

11. Создаю свой репозиторий.	

![](/media/sf_Work/lab4/11.png)

12. Подключаю репозиторий к своей системе.

![](/media/sf_Work/lab4/12.png)


# Выводы

В лабораторной работе №5 я освоил навыки по правильной настройке рабочей среды. 


::: {#refs}
:::
