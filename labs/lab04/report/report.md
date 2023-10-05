---
## Front matter
title: "Лабораторная работа №4"
subtitle: 
author: "Гугульян Ксения Александровна. НПМбв-02-21"

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

Освоение процедуры компиляции и сборки программ, написанных на ассемблере NASM.

# Задание

1. Рассмотрим пример простой программы на языке ассемблера NASM.
2. Транслятор NASM.
3. Полный вариант командной строки nasm.
4. Компоновщик LD.
5. Запустить на выполнение созданный исполняемый файл, находящийся в текущем каталоге.



# Выполнение лабораторной работы

Создаём каталог для работы с программами на языке ассемблера NASM. Перейдём в созданный каталог. Создаём текстовый файл с именем hello.asm. Откроем этот файл с помощью любого текстового редактора и вводим текст.
![Программа Hello world](image/4-1.png){#fig:001 width=70%}

Для компиляции приведённого выше текста программы «Hello World» напишем и проверим файлы.
![Транслятор NASM](image/4-2.png){#fig:001 width=70%}

Напишем полный вариант командной строки nasm и проверим файлы.
![Расширенный синтаксис NASM](image/4-3.png){#fig:001 width=70%}

Чтобы получить исполняемую программу, объектный файл
необходимо передать на обработку компоновщику. Проверяем, чтобы файл hello был создан.
![Компоновщик LD](image/4-4.png){#fig:001 width=70%}

Запустим на выполнение созданный исполняемый файл, находящийся в текущем каталоге.
![Запуск исполняемого файла](image/4-5.png){#fig:001 width=70%}

# Выводы

В ходе лабораторной работы я усвоила процедуры компиляции и сборки программ, написанных на ассемблере NASM.

# Список литературы{.unnumbered}

::: {#refs}
:::
