---
## Front matter
title: "Отчёт по лабораторной работе №8"
subtitle: "НПМбв-02-21"
author: "Гугульян Ксения Александровна"

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

Приобретение навыков написания программ с использованием циклов и обработкой
аргументов командной строки.

# Задание

1. Создайте каталог для программам лабораторной работы № 8, перейдите в него и создайте
файл lab8-1.asm. Введите в файл lab8-1.asm текст программы из листинга 8.1. Создайте исполняемый файл и проверьте его работу. Измените текст программы добавив изменение
значение регистра ecx в цикле. Создайте исполняемый файл и проверьте его работу. Внесите изменения в текст программы добавив команды push
и pop (добавления в стек и извлечения из стека) для сохранения значения счетчика цикла
loop.

2. Создайте файл lab8-2.asm в каталоге ~/work/arch-pc/lab08 и введите в него текст программы из листинга 8.2. Создайте исполняемый файл и запустите его, указав аргументы. Создайте файл lab8-3.asm в каталоге ~/work/archpc/lab08 и введите в него текст программы из листинга 8.3. Создайте исполняемый файл и запустите его, указав аргументы.

# Выполнение лабораторной работы

1. Создаём каталог для программам лабораторной работы № 8, перейдём в него и создаём
файл lab8-1.asm (рис. @fig:001).

![Создание каталога и переход в него](image/8-1.png){#fig:001 width=70%}

Введём в файл lab8-1.asm текст программы из листинга 8.1 (рис. @fig:002).

![Ввод текста в файл](image/8-2.png){#fig:002 width=70%}

Создаём исполняемый файл и проверяем его работу (рис. @fig:003).

![Создание исп. файла](image/8-3.png){#fig:003 width=70%}

Изменим текст программы добавив изменение значение регистра ecx в цикле (рис. @fig:004).

![Изменение текста](image/8-4.png){#fig:004 width=70%}

Создаём исполняемый файл и проверяем его работу (рис. @fig:005).

![Создание исп. файла](image/8-5.png){#fig:005 width=70%}

Внесём изменения в текст программы добавив команды push и pop (добавления в стек и извлечения из стека) для сохранения значения счетчика цикла loop (рис. @fig:006).

![Внеснение изменений в текст](image/8-6.png){#fig:006 width=70%}

Создаём исполняемый файл и проверяем его работу (рис. @fig:007).

![Создание исп. файла](image/8-7.png){#fig:007 width=70%}

В данном случае число проходов соответствует циклу значений 𝑁 введенному с клавиатуры.

2. Создаём файл lab8-2.asm в каталоге ~/work/arch-pc/lab08 и введём в него текст программы из листинга 8.2 (рис. @fig:008).

![Создание файла](image/8-8.png){#fig:008 width=70%}

Создаём исполняемый файл и запускаем его, указав аргументы (рис. @fig:009).

![Создание исп. файла](image/8-9.png){#fig:009 width=70%}

3 аргумента было обработано программой.

Создаём файл lab8-3.asm в каталоге ~/work/archpc/lab08 и введём в него текст программы из листинга 8.3 (рис. @fig:010).

![Создание файла](image/8-10.png){#fig:010 width=70%}

Создаём исполняемый файл и запускаем его, указав аргументы (рис. @fig:011).

![Создание исп. файла](image/8-11.png){#fig:011 width=70%}

# Выводы

В ходе выполнения лабораторной работы я приобрела навыки написания программ с использованием циклов и обработкой аргументов командной строки.

# Список литературы{.unnumbered}

::: {#refs}
:::
