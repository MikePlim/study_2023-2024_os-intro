---
## Front matter
lang: ru-RU
title: Лабораторная работа №1
subtitle: Простейший шаблон
author:
  - Янушкевич М.Д.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 01 марта 2024

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
 
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
---

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Янушкевич Михаил Денисович
  * Студент, НПИбд-02-23
  * Российский университет дружбы народов
  * [1132231840.ru](mailto:1132231840@rudn.ru)

:::
::: {.column width="30%"}

:::
::::::::::::::


## Цель

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Выполенение лабораторной работы

## Переключаюсь на роль супер-пользователя и устанавливаю tmux.
![Рис.1](/media/sf_Work/1.png)

## Устанавливаю необходимое ПО и запускаю таймер.
![Рис.2](/media/sf_Work/2.png)

## Устанавливаю пакет DKMS.
![Рис.3](/media/sf_Work/3.png)

## В меню ВМ подключаю образ гостевой ОС и подмонирую диск.
![Рис.4](/media/sf_Work/4.png)

## Устанавливаю драйвера.
![Рис.5](/media/sf_Work/5.png)

## Перехожу в tmux и создаю конфигурационный файл.
![Рис.6](/media/sf_Work/6.png)

## Редактирую конфигурационный файл.
![Рис.7](/media/sf_Work/7.png)

## Переключаюсь на роль супер-пользоателя и редактриую конфигурационный файл.
![Рис.8](/media/sf_Work/8.png)

## Запускаю tmux, переключаюсь на супер-пользователя и создаю пользователя.
![Рис.9](/media/sf_Work/9.png)

## Задаю пароль, устанавливаю имя хоста и проверяю.
![Рис.10](/media/sf_Work/10.png)

## В хостовой системе через cmd подключаю разделяемую папку.
![Рис.11](/media/sf_Work/11.png)

## Устнанавливаю pandoc. Для этого скачиваю необходимый релиз, разархивирую его и помещаю в каталог bin.
![Рис.12](/media/sf_Work/12.png)

## Устанавливаю дистрибутив texlive.
![Рис.13](/media/sf_Work/13.png)

## Выводы

В лабораторной работе №1 я приобрел навыки по устрановки ВМ и ёё первончально настройке.



:::

