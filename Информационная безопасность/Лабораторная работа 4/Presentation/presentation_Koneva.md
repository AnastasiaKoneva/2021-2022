---
## Front matter
lang: ru-RU
title: Дискреционное разграничение прав в Linux. Расширенные атрибуты
author: |
	 Конева Анастасия НБИбд-02-18\inst{1}

institute: |
	\inst{1}РУДН

date: 29 октября, 2021, Москва, Россия

## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
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

# Цели и задачи работы

## Цель лабораторной работы

Получение практических навыков работы в консоли с расширенными атрибутами файлов.

# Процесс выполнения лабораторной работы

## Теоретическое введение 

Помимо прав доступа каждый из файлов стандартной файловой системы Linux имеет набор атрибутов, регламентирующих особенности работы с ним. Chattr - это команда в Linux, 
которая позволяет пользователю устанавливать и снимать определенные атрибуты файла.

## Нет прав со стороны гостя

![атрибут -a](figure/1.png){ #fig:001 }

## Расширенный атрибут а от имени гостя

![атрибут -a](figure/2.png){ #fig:002 }

## Расширенные атрибуты -a и -i  от именя суперпользователя

![атрибут -i](figure/3.png){ #fig:003 }

## Вывод

Получены практические навыки работы в консоли с расширенными атрибутами файлов.
Права доступа есть у суперпользователя, но не у гостя
