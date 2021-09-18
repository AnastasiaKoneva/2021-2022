---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №1"
subtitle: "Развертывание виртуальной машины"
author: "Конева Анастасия НБИбд-02-18"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.


## Задание

1. Запустить терминал. Перейти в каталог /var/tmp

2. Создать каталог с именем пользователя (желательно совпадающим с логином студента в дисплейном классе)

3. Скопировать образ виртуальной машины в папку, созданную на предыдущем шаге.

4. Ностроить VirtualBox

5. Запустить виртуальную машину и установить систему

# Выполнение лабораторной работы

1. Загрузить операционную систему Oracle VM VirtualBox. 

2. Запустил терминал и создала каталог с именем пользователя

3. Проверила в свойствах VirtualBox месторасположение каталога для вирту альных машин. 

4. Запустил виртуальную машину и создаю свою виртуальную машину ([рис. 1](image/1.png))

![Имя машины и тип ОС](image/1.jpg){ #fig:001 }

![Окно «Размер основной памяти»](image/2.jpg){ #fig:002 }

![Окно «Виртуальный жёсткий диск»](image/3.PNG){ #fig:003 }

![Окно «Дополнительные атрибуты виртуального диска»](image/4.PNG){ #fig:004 }

![Окно «Расположение и размер виртуального диска»](image/5.PNG){ #fig:005 }

5. Выбрала в VirtualBox Свойства Носители виртуальной машины Base. Доба вила новый привод оптических дисков и выбрал образ.([рис. 6](image/7.png))

![Добавляю образ](image/7.PNG){ #fig:006 }

6. Запустила установку системы ([рис. 7](image/8.png))

![Запуск системы](image/8.PNG){ #fig:007 }

7. Выбрала «Test this»

![Выбираю вариант 2](image/9.PNG){ #fig:008 }

8. Установила русский язык для интерфейса и раскладку клавиатуры ([рис. 9](image/11.png))

![Выбираю русский язык](image/11.PNG){ #fig:009 }

9. Указала часовой пояс([рис. 10](image/13.png))

![Выбираю часовой пояс](image/13.PNG){ #fig:010 }

10. Выбрала программы для установки ([рис. 11](image/14.png))

![Выбираю программу](image/14.PNG){ #fig:011 }

![Окно настроек](image/16.PNG){ #fig:012 }

11. Начала установку. ([рис. 13](image/17.png)) Задал root пароль ([рис. 14](image/17.1.png)) и создал пользователя-администратора со своим именем ([рис. 15](image/18.png))

![Начало установки](image/17.PNG){ #fig:013 }

![Установка root пароля](image/17.1.PNG){ #fig:014 }

![Создание пользователя](image/18.PNG){ #fig:015 }

![Установка](image/19.PNG){ #fig:016 }

12. Приняла лицензию ([рис. 17](image/20.perezagryzka.PNG))

![Принятие лицензионного соглашения](image/20.perezagryzka.PNG){ #fig:017 }

![Принятие лицензионного соглашения](image/21.PNG){ #fig:018 }

13. Войти в систему

![Вход в систему](image/22.PNG){ #fig:019 }

14. Установить обновления

![Rоманда установки обновления](image/26.PNG){ #fig:020 }

15. Перезагрузила систему ([рис. 21](image/27.png))

![Перезагрузка системы](image/27.PNG){ #fig:021 }

![Вход в систему](image/28.PNG){ #fig:022 }

16. Все установлено

![Система готова к работе](image/28.PNG){ #fig:023 }

# Вывод

Выполняя данную лабораторную работу, я приобрела навыки установки CentOS 7 на виртуальную машину и настройки минимально необходимых для дальней шей работы сервисов.

# Список литературы

1.	CentOS [Электронный ресурс]. Википедия.Свободная энциклопедия., 2021. URL: <https://ru.wikipedia.org/wiki/CentOS>.
