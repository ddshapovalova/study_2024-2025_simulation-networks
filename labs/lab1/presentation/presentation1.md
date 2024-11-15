---
## Front matter
lang: ru-RU
title: "Лаб №1 по дисциплине 

Компьютерный практикум по статистическому анализу данных"
subtitle: Введение в Mininet
author:
  - Шаповалова Диана Дмитриевна
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 14 ноября 2024

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
---


# Вводная часть

## Цели и задачи

Основной целью работы является развёртывание в системе виртуализации (например, в VirtualBox) mininet, знакомство с основными командами для работы с Mininet через 
командную строку и через графический интерфейс.

# Выполнение лабораторной работы

## Настройка образа VirtualBox

![Настройка виртуальной машины](image/1.png){#fig:001 width=100% height=100%}

![Настройка виртуальной машины](image/2.png){#fig:002 width=100% height=100%}

## Подключение к виртуальной машине

![Логинимся в виртуальной машине](image/3.png){#fig:003 width=100% height=100%}

![Настраиваем подсоединение по ключу, снова подключаемся](image/4.png){#fig:004 width=100% height=100%}

## Настройка mc

![Уcтанавливаем mc](image/5.png){#fig:005 width=100% height=100%}

## Настройка параметров XTerm

![Редактируем файл /etc/X11/app-defaults/XTerm](image/6.png){#fig:006 width=100% height=100%}

## Настройка соединения X11 для суперпользователя

![Настраиваем соединение X11](image/7.png){#fig:007 width=100% height=100%}

## Работа с Mininet из-под Windows

![Устанавливаем putty](image/8.png){#fig:008 width=100% height=100%}

![Устанавливаем VcXsrv](image/9.png){#fig:009 width=100% height=100%}

## Основы работы в Mininet

![Выполняем команды](image/10.png){#fig:010 width=100% height=100%}

![Выполняем команды](image/11.png){#fig:011 width=100% height=100%}

![Выполняем команды](image/12.png){#fig:012 width=100% height=100%}

## Построение и эмуляция сети в Mininet с использованием графического интерфейса

![Открываем Miniedit, строим топологию](image/13.png){#fig:013 width=100% height=100%}

![Настраиваем IP-адрес h1, по аналогии и у h2](image/14.png){#fig:014 width=100% height=100%}

![Проверяем соединение между хостами](image/15.png){#fig:015 width=100% height=100%}

![Настраиваем автоматическое назначение IP-адресов](image/16.png){#fig:016 width=100% height=100%}

![Проверяем IP-адрес у h1](image/17.png){#fig:017 width=100% height=100%}

![Создаем каталог, сохраняем файл](image/18.png){#fig:018 width=100% height=100%}

# Выводы

Мы развернули в системе виртуализации mininet, познакомились с основными командами для работы с Mininet через командную строку и через графический интерфейс.
