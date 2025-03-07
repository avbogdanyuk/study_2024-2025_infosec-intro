---
## Front matter
lang: ru-RU
title: Индивидуальный проект. Этап 1
subtitle: "Установка Kali Linux"
author:
  - Богданюк А.В., НКАбд-01-23
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 7 марта 2025

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
---

## Цель работы

Научиться основным способам тестирования веб приложений.

## Задание

1. Установить дистрибутив Kali Linux в виртуальную машину.

## Выполнение лабораторной работы

Скачиваю с сайта Kali Linux Installer Image iso (рис. 1).

![Kali Linux](image/1.png){#fig:001 width=70%}

## Выполнение лабораторной работы

Создаю новую виртуальную машину, называю её avbogdanyuk_kali, тип ОС Linux, версию Debian (64-bit) (рис. 2).

![Новая виртуальная машина](image/2.png){#fig:002 width=70%}

## Выполнение лабораторной работы

Настраиваю основную память и количество процессоров (рис. 3).

![Настройки ВС](image/3.png){#fig:003 width=70%}

## Выполнение лабораторной работы

Настраиваю размер виртуального жесткого диска (рис. 4).

![Настройки ВС](image/4.png){#fig:004 width=70%}

## Выполнение лабораторной работы

Подключаю ранее скаченный образ диска (рис. 5).

![Образ диска](image/5.png){#fig:005 width=70%}

## Выполнение лабораторной работы

Устанавливаю Kali Linux (рис. 6).

![Kali Linux](image/6.png){#fig:006 width=70%}

## Выполнение лабораторной работы

Успешно получилось всё установить (рис. 7).

![Kali Linux](image/7.png){#fig:007 width=70%}

## Вывод

Установила дистрибутив Kali Linux в виртуальную машину.

## Список литературы{.unnumbered}

::: {#refs}
1. Dash P. Getting started with oracle vm virtualbox. Packt Publishing Ltd, 2013. 86 p.
2. Colvin H. Virtualbox: An ultimate guide book on virtualization with virtualbox. CreateSpace Independent Publishing Platform, 2015. 70 p.
3. van Vugt S. Red hat rhcsa/rhce 7 cert guide : Red hat enterprise linux 7 (ex200 and ex300). Pearson IT Certification, 2016. 1008 p.
4. Робачевский А., Немнюгин С., Стесик О. Операционная система unix. 2-е изд. Санкт-Петербург: БХВ-Петербург, 2010. 656 p.
5. Немет Э. et al. Unix и Linux: руководство системного администратора. 4-е изд. Вильямс, 2014. 1312 p.
6. Колисниченко Д.Н. Самоучитель системного администратора Linux. СПб.: БХВ-Петербург, 2011. 544 p.
7. Robbins A. Bash pocket reference. O’Reilly Media, 2016. 156 p.
:::