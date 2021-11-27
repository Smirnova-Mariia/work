---
## Front matter
title: Защита лабораторной работы № 6. Мандатное разграничение прав в Linux 
author: Смирнова Мария Александровна
institute: РУДН

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

# Цель работы

## Цель работы

Развитие навыков администрирования ОС Linux. Практическое освоение технологии SELinux. Проверка работы SELinux совместно с веб-сервером Apache.

# Выполнение лабораторной работы

## Выполнение лабораторной работы

![Проверка SELinux](screen/1.png){ #fig:001 width=70% }

## Выполнение лабораторной работы

![Httpd status](screen/2.png){ #fig:002 width=70% }

## Выполнение лабораторной работы

![Контекст безопасности Apache](screen/3.png){ #fig:003 width=70% }

## Выполнение лабораторной работы

![Переключатели](screen/4.png){ #fig:004 width=70% }

## Выполнение лабораторной работы

![Seinfo](screen/5.png){ #fig:005 width=70% }

## Выполнение лабораторной работы

![Директория /var/www/html](screen/6.png){ #fig:006 width=70% }

## Выполнение лабораторной работы

![test.html](screen/7.png){ #fig:007 width=70% }

## Выполнение лабораторной работы

![Контекст test.html](screen/8.png){ #fig:008 width=70% }

## Выполнение лабораторной работы

![http://127.0.0.1/test.html](screen/9.png){ #fig:009 width=70% }

## Выполнение лабораторной работы

![Контексты файлов httpd](screen/10.png){ #fig:010 width=70% }

## Выполнение лабораторной работы

![Изменение контекста test](screen/11.png){ #fig:011 width=70% }

## Выполнение лабораторной работы

![Сообщение об ошибке](screen/12.png){ #fig:012 width=70% }

## Выполнение лабораторной работы

![log-файл](screen/13.png){ #fig:013 width=70% }

## Выполнение лабораторной работы

![audit.log](screen/14.png){ #fig:014 width=70% }

## Выполнение лабораторной работы

![Порт 81](screen/15.png){ #fig:015 width=70% }

## Выполнение лабораторной работы

![Контекст файла test](screen/16.png){ #fig:016 width=70% }

## Выполнение лабораторной работы

![Контекст файла test](screen/9.png){ #fig:016 width=70% }

# Вывод

## Вывод

В процессе выполнения лабораторной работы мы развили навыков администрирования ОС Linux, а также освоили технологии SELinux. Мы проверили работу SELinux совместно с веб-сервером Apache.
