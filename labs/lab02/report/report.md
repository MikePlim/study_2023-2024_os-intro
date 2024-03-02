---
## Front matter
title: "Отчёт по лабораторной работе №2"
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

1. Изучить идеологию и применение средств контроля версий
2. Освоить умения по работе с git.

# Выполнение лабораторной работы

1. Устанавливаю git и gh.

![рис.1](/media/sf_Work/lab2/1.png)

2. Задаю имя и email владельца, а также utf-8 в выводе сообщений git.

![рис.2](/media/sf_Work/lab2/2.png)

3. Задаю имя начальной ветки(master), а также параметры autocrlf и safecrlf.

![рис.3](/media/sf_Work/lab2/3.png)

4. Создаю ssh-ключ размером 4096 бит, далее по алгоритму ed25519.

![рис.4](/media/sf_Work/lab2/4.png)

5. Создаю pgp ключ, в предложенных вариантах выбираю RSA, 4096 бит, бессрочный срок.

![рис.5](/media/sf_Work/lab2/5.png)

6. Выводим список ключей и копируем отпечаток приватного ключа.

![рис.6](/media/sf_Work/lab2/6.png)

7. В настройках github добавляю новый gpg ключ.

![рис.7](/media/sf_Work/lab2/7.png)

8. Указываю git для применения его в подписи коммитов.

![рис.8](/media/sf_Work/lab2/8.png)

9. Авторизуюсь в gh.

![рис.9](/media/sf_Work/lab2/9.png)

10. Ввожу команды, чтобы создать шаблон рабочего пространства.

![рис.10](/media/sf_Work/lab2/10.png)

11. Перехожу в каталог курса os-intro, удаляю в нём необходимые файлы.

![рис.11](/media/sf_Work/lab2/11.png)

12. Создаю необходимые каталоги и с помощью git add, git commit, git push отправляю файлы на сервер.

![рис.12](/media/sf_Work/lab2/12.png)


# Выводы

В лабораторной работе №2 я создал базовую конфигурацию для работы с git, настроил его и создал локальный каталог для выполнения заданий.


::: {#refs}
:::
