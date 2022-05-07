---
## Front matter
title: "Отчёт по лабораторной работе №5"
subtitle: "Лабораторная работа №5"
author: "Салимова Эмилия Ринатовна"

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

Ознакомление с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы. 

# Выполнение лабораторной работы

1. Выполняю все примеры, приведённые в первой части описания лабораторной работы. (рис.1) [Выполняю примеры из пунктов 5.2.2. - 5.2.5.]{ #fig:001 width=70% }
2. Выполняю следующие действия:
1) Копирую файл /usr/include/sys/io.h в домашний каталог и называю его equipment. (рис. 2.1)
2) В домашнем каталоге создаю директорию ~/ski.plases. Перемещаю файл equipment в каталог ~/ski.plases. . Переименовываю файл ~/ski.plases/equipment в ~/ski.plases/equiplist. (рис. 2.2)
3) Создаю в домашнем каталоге файл abc1 и копирую его в каталог ~/ski.plases, называю его equiplist2. (рис. 2.3)
4) Создаю каталог с именем equipment в каталоге ~/ski.plases. Перемещаю файлы ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment. (рис. 2.4)
5) Создаю и перемещаю каталог ~/newdir в каталог ~/ski.plases и называю его plans. (рис 2.5)
3. Создаю необходимые файлы. Определяю опции команды chmod, необходимые для того, чтобы присвоить перечисленным ниже файлам выделенные права доступа, считая, что в начале таких прав нет:
drwxr--r-- ... australia 
drwx--x--x ... play 
-r-xr--r-- ... my_os 
-rw-rw-r-- ... feathers
(рис. 3.1)
4. Проделываю приведённые ниже упражнения:
1) Просматривааю содержимое файла /etc/password. (рис. 4.1)
2) Копирую файл ~/feathers в файл ~/file.old. Перемещаю файл ~/file.old в каталог ~/play. Копирую каталог ~/play в каталог ~/fun. Перемещаю каталог ~/fun в каталог ~/play и называю его games. (рис. 4.2)
3) Лишаю владельца файла ~/feathers права на чтение. Пытаюсь просмотреть файл ~/feathers командой cat. Отказано в доступе. Пытаюсь скопировать файл ~/feathers. Даю владельцу файла ~/feathers право на чтение. (рис. 4.3)
4) Лишаю владельца каталога ~/play права на выполнение. Перехожу в каталог ~/play. Даю владельцу каталога ~/play право на выполнение. (рис. 4.4)
5. Читаю man по командам м mount, fsck, mkfs, kill. (рис. 5)


# Выводы

Входе лабораторной работы я ознакомилась с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы. 


