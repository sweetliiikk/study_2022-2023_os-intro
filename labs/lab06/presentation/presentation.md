---
## Front matter
lang: ru-RU
title: "Лабораторная работа №5"
subtitle: 
author:
  - Назирова М.Т.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 16 марта 2023

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

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Назирова Малика Темржоновна
  * студентка группы НКабд-04-22
  * Факультет физико-математических и естественных наук
  * Российский университет дружбы народов
  * [1032225197@pfur.ru](mailto:1032225197@pfur.ru)
  * <https://github.com/sweetliiikk/study_2022-2023_os-intro.git>

:::
::: {.column width="30%"}

![](./image/malika.jpg)

:::
::::::::::::::


## Цели и задачи

Ознакомление с инструментами поиска файлов и фильтрации текстовых данных.
Приобретение практических навыков: по управлению процессами (и заданиями), по
проверке использования диска и обслуживанию файловых систем.

# Выполнение лабораторной работы


## Вход в систему

![](image/1.png){#fig:001 width=70%}


## Создаём файл и записываем туда названия файлов из каталога /etc и из домашнего каталога

![](image/2.png){#fig:002 width=50%}


## Записываем в файл conf.txt имена всех файлов с расширением .conf из file.txt

![](image/3.png){#fig:003 width=50%}


## Используя команду find определяем имена, начинавшиеся с символа с

![](image/4.png){#fig:004 width=70%}


## Используя команду find выводим на экран файлы, начинающееся с символа h, из каталога /etc

![](image/5.png){#fig:005 width=50%}


## Используя команду find запускаем процесс в фоновом режиме, которые будет записывать имена, начинающееся с log в файл ~/logfile

![](image/6.png){#fig:006 width=70%}


## Удаляем файл

![](image/7.png){#fig:007 width=70%}


## Запускаем gedit в фоновом режиме

![](image/8.png){#fig:008 width=70%}


## Используем команду ps для определения идентификатора процесса

![](image/9.png){#fig:009 width=70%}


## Открываем справку о каманде kill

![](image/10.1.png){#fig:010 width=70%}

## Используем её для завершения процесса gedit

![](image/10.2.png){#fig:011 width=70%}


## Получаем подробную информацию о команде df

![](image/11.1.png){#fig:012 width=70%}

## Выполняем команду df

![](image/11.2.png){#fig:013 width=70%}

## Получаем подробную информацию о команде du

![](image/11.3.png){#fig:014 width=70%}

## Выполняем команду du

![](image/11.4.png){#fig:015 width=70%}


## Открываем справку о команде find

![](image/12.1.png){#fig:016 width=70%}

## Выводим имена всех директорий, которые есть в домашнем каталоге

![](image/12.2.png){#fig:017 width=70%}


# Спасибо за внимание
