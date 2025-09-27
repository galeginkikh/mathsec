---
## Front matter
title: "Отчет по лабораторной работе №2"
subtitle: "Структуры данных"
author: "Легиньких Галина Андреевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"
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

Основная цель работы — изучить несколько структур данных, реализованных в Julia, научиться применять их и операции над ними для решения задач.

# Задание

1. Используя Jupyter Lab, повторите примеры из раздела 2.2.
2. Выполните задания для самостоятельной работы (раздел 2.4).

# Выполнение лабораторной работы

**1.** Для начала я повторила все примеры из документа. В начале был дан перечень функций (методов), которые я использовала при повторении примеров. (рис. [-@fig:001])

![Перечень методов](image/1.png){ #fig:001 width=70% }

**2.** Рассмотрела примеры кортежей. Комментарии ко всем примерам на скриншотах. (рис. [-@fig:002])

![Кортежи](image/2.png){ #fig:002 width=70% }

**3.** Повторила примеры операция над кортежами. (рис. [-@fig:003])

![Операции над кортежами](image/3.png){ #fig:003 width=70% }

**4.** Перешла к словарям и операциями над ними. Повторила примеры операция над словарями. (рис. [-@fig:004]) (рис. [-@fig:005])

![Словари 1](image/4.png){ #fig:004 width=70% }

![Словари 2](image/5.png){ #fig:005 width=70% }

**5.** Далее множества и операции над ними. (рис. [-@fig:006]) (рис. [-@fig:007]) (рис. [-@fig:008])

![Множества 1](image/6.png){ #fig:006 width=70% }

![Множества 2](image/7.png){ #fig:007 width=70% }

![Множества 3](image/8.png){ #fig:008 width=70% }

**6.** Повторила примеры массивов и операции для работы с ними. (рис. [-@fig:009]) (рис. [-@fig:010]) (рис. [-@fig:011]) (рис. [-@fig:012]) (рис. [-@fig:013]) (рис. [-@fig:014]) (рис. [-@fig:015]) (рис. [-@fig:016])

![Массивы 1](image/9.png){ #fig:009 width=70% }

![Массивы 2](image/10.png){ #fig:010 width=70% }

![Массивы 3](image/11.png){ #fig:011 width=70% }

![Массивы 4](image/12.png){ #fig:012 width=70% }

![Массивы 5](image/13.png){ #fig:013 width=70% }

![Массивы 6](image/14.png){ #fig:014 width=70% }

![Массивы 7](image/15.png){ #fig:015 width=70% }

![Массивы 8](image/16.png){ #fig:016 width=70% }

**7.** Перешла к выполнению самостоятельных заданий. Дублировать сами задания я не буду, это масимально проблематично. Я просто буду придерживаться их нумерации. Все объяснения в видео выполнение.

- Задания 1 и 2 (рис. [-@fig:017])

![Задания 1 и 2](image/17.png){ #fig:017 width=70% }

- Задания 3.1 - 3.5 (рис. [-@fig:018])

![Задания 3.1-3.5](image/18.png){ #fig:018 width=70% }

- Задания 3.6 - 3.10 (рис. [-@fig:019])

![Задания 3.6-3.10](image/19.png){ #fig:019 width=70% }

- Задание 3.11 (рис. [-@fig:020])

![Задание 3.11](image/20.png){ #fig:020 width=70% }

- Задания 3.12 - 3.13 (рис. [-@fig:021])

![Задания 3.12-3.13](image/21.png){ #fig:021 width=70% }

- Задание 3.14.1 (рис. [-@fig:022])

![Задание 3.14.1](image/22.png){ #fig:022 width=70% }

- Задание 3.14.2 (рис. [-@fig:023])

![Задание 3.14.2](image/23.png){ #fig:023 width=70% }

- Задание 3.14.3 (рис. [-@fig:024])

![Задание 3.14.3](image/24.png){ #fig:024 width=70% }

- Задание 3.14.4 - 3.14.5 (рис. [-@fig:025])

![Задание 3.14.4-3.14.5](image/25.png){ #fig:025 width=70% }

- Задание 3.14.6 - 3.14.7 (рис. [-@fig:026])

![Задание 3.14.6-3.14.7](image/26.png){ #fig:026 width=70% }

- Задание 3.14.8 - 3.14.10 (рис. [-@fig:027])

![Задание 3.14.8-3.14.10](image/27.png){ #fig:027 width=70% }

- Задание 3.14.11 - 3.14.12 (рис. [-@fig:028])

![Задание 3.14.11-3.14.12](image/28.png){ #fig:028 width=70% }

- Задание 4 (рис. [-@fig:029])

![Задание 4](image/29.png){ #fig:029 width=70% }

- Задание 5 (рис. [-@fig:030])

![Задание 5](image/30.png){ #fig:030 width=70% }

- Задание 6 (рис. [-@fig:031])

![Задание 6](image/31.png){ #fig:031 width=70% }

# Вывод

Изучила несколько структур данных, реализованных в Julia, научилась применять их и операции над ними для решения задач.