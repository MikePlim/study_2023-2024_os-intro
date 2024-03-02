---
## Front matter
lang: ru-RU
title: Лабораторная работа №2
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

1. Изучить идеологию и применение средств контроля версий
2. Освоить умения по работе с git.

# Выполенение лабораторной работы

## Устанавливаю git и gh.

![рис.1](/media/sf_Work/lab2/1.png)

## Задаю имя и email владельца, а также utf-8 в выводе сообщений git.

![рис.2](/media/sf_Work/lab2/2.png)

## Задаю имя начальной ветки(master), а также параметры autocrlf и safecrlf.

![рис.3](/media/sf_Work/lab2/3.png)

## Создаю ssh-ключ размером 4096 бит, далее по алгоритму ed25519.

![рис.4](/media/sf_Work/lab2/4.png)

## Создаю pgp ключ, в предложенных вариантах выбираю RSA, 4096 бит, бессрочный срок.

![рис.5](/media/sf_Work/lab2/5.png)

## Выводим список ключей и копируем отпечаток приватного ключа.

![рис.6](/media/sf_Work/lab2/6.png)

## В настройках github добавляю новый gpg ключ.

![рис.7](/media/sf_Work/lab2/7.png)

## Указываю git для применения его в подписи коммитов.

![рис.8](/media/sf_Work/lab2/8.png)

## Авторизуюсь в gh.

![рис.9](/media/sf_Work/lab2/9.png)

## Ввожу команды, чтобы создать шаблон рабочего пространства.

![рис.10](/media/sf_Work/lab2/10.png)

## Перехожу в каталог курса os-intro, удаляю в нём необходимые файлы.

![рис.11](/media/sf_Work/lab2/11.png)

## Создаю необходимые каталоги и с помощью git add, git commit, git push отправляю файлы на сервер.

![рис.12](/media/sf_Work/lab2/12.png)


# Выводы

В лабораторной работе №2 я создал базовую конфигурацию для работы с git, настроил его и создал локальный каталог для выполнения заданий.


:::
