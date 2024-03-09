---
## Front matter
title: "Отчёт по лабораторной работе №4"
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

1. Получить навыки правильной работы с репозиториями git.

# Выполнение лабораторной работы

1. Устанавливаю git-flow.

![](/media/sf_Work/lab4/1.png)

2. Устанавливаю Node.js.

![](/media/sf_Work/lab4/2.png)

3. Настраиваю Node.js.

![](/media/sf_Work/lab4/3.png)

4. Устанавливаю программы для форматирования коммитов и создания логов.

![](/media/sf_Work/lab2/4.png)

5. Создаю репозиторий github.

![](/media/sf_Work/lab4/5.png)

6. Конфигурирую общепринятые коммиты.

![](/media/sf_Work/lab4/6.png)

7. Редактирую файл package.json.

![](/media/sf_Work/lab4/7.png)

8. Добавляю новые файлы, выполняю коммит, отправляю на github.

![](/media/sf_Work/lab4/8.png)

9. Инициализирую git-flow, проверяю ветку, загружаю репозиторий в хранилище, устанавливаю внешнюю ветку.

![](/media/sf_Work/lab4/9.png)

10. Создаю релиз с версией 1.0.0, создаю журнал изменений, добавляю журнал в индекс, добавляюрелизную ветку в основную, отправляю на github.

![](/media/sf_Work/lab4/10.png)

11. Разрабатываю новую функциональность.	

![](/media/sf_Work/lab4/11.png)

12. Создаю релиз git-flow: создаю новый релиз, журнал изменений, добавляю релизную ветку, отправляю данные на github, создаю релиз на github с комментарием.

![](/media/sf_Work/lab4/12.png)


# Выводы

В лабораторной работе №4 я освоил навыки по продвинутому использованию и настройке репозиториев git. 


::: {#refs}
:::
