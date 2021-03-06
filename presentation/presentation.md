---
## Front matter
title: Лабораторная работа №5
author: |
	Силкина Мария Александровна
date: 12.11.2021

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Дискреционное разграничение прав в Linux. Исследование влияния дополнительных атрибутов


## Цель выполнения лабораторной работы

- Приобрести практические навыки работы в консоли с дополнительными атрибутами файлов. Изучение механизмов изменения идентификаторов, применения SetUID- и Sticky-битов. Рассмотрение работы механизма смены идентификатора процессов пользователей, а также влияние бита Sticky на запись и удаление файлов.

## Задачи выполнения работы

1. Выполнить лабораторную работу согласно порядку выполнения работы.

2. Занести свои наблюдения в отчет и ознакомиться на практиками с основными атрибутами и идентификаторами.

## Выполнение лабораторной работы

- Создала файлы  simpleid.c и  simpleid2.c, написанные на языке C. Их различие в наличии вывода действительных идентификаторов. Скомпилировала их и сравнила с системной программой id

- Изменяла права и владельцов при помощи команд chown и chmod от имени суперпользователя.

- Узнала установлен ли атрибут Sticky на директории /tmp. Создала файл от пользователя guest и записала в него слово test. Далее изменила на него права для категории пользователей "others" 

- Зашла от пользователя guest2 и попыталась выполнить запись в файл, чтение файла, удаление файла. Убрала атрибут t и повторила проделанные ранее действия.

- Вернула атрибут t

## Результаты выполнения лабораторной работы

- При выполнении данной лабораторной работы я получила практические навыки работы в консоли с дополнительными атрибутами файлов. Я изучила механизмы изменения идентификаторов, применения SetUID- и Sticky-битов. Получение практических навыков работы в консоли с дополнительными атрибутами. Рассмотрела работу механизма смены идентификатора процессов пользователей, а также влияние бита Sticky на запись и удаление файлов.