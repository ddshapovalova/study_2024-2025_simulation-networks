---
## Front matter
lang: ru-RU
title: "Лаб №4 по дисциплине Моделирование сетей передачи данных"
subtitle: Эмуляция и измерение задержек в глобальных сетях
author:
  - Шаповалова Диана Дмитриевна
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 5 декабря 2024

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

Основной целью работы является знакомство с NETEM — инструментом для
тестирования производительности приложений в виртуальной сети, а также
получение навыков проведения интерактивного и воспроизводимого экспериментов по измерению задержки и её дрожания (jitter) в моделируемой сети в среде Mininet.

# Выполнение работы
## Запуск лабораторной топологии

![Создаем топологию](image/1.png){width=100% height=100%}

## Интерактивные эксперименты. Добавление/изменение задержки в эмулируемой глобальной сети

![Добавляем задержку](image/2.png){width=100% height=100%}

## Изменение задержки в эмулируемой глобальной сети

![Изменяем задержку](image/3.png){width=100% height=100%}

## Восстановление исходных значений (удаление правил) задержки в эмулируемой глобальной сети

![Восстанавливаем конфигурацию](image/4.png){width=100% height=100%}

## Добавление значения дрожания задержки в интерфейс подключения к эмулируемой глобальной сети

![Добавление значения дрожания задержки](image/5.png){width=100% height=100%}

## Добавление значения корреляции для джиттера и задержки в интерфейс подключения к эмулируемой глобальной сети

![Добавление значения корреляции для джиттера и задержки](image/6.png){width=100% height=100%}

## Распределение задержки в интерфейсе подключения к эмулируемой глобальной сети

![Распределение задержки в интерфейсе подключения](image/7.png){width=100% height=100%}

## Воспроизведение экспериментов. Предварительная подготовка

![Создаем репозитории](image/8.png){width=100% height=100%}

## Добавление задержки для интерфейса, подключающегося к эмулируемой глобальной сети

![Создаем скрипт lab_netem_i.py](image/9.png){width=100% height=100%}

## Добавление задержки для интерфейса, подключающегося к эмулируемой глобальной сети

![Создаем скрипт для визуализации ping_plot](image/10.png){width=100% height=100%}

## Добавление задержки для интерфейса, подключающегося к эмулируемой глобальной сети

![График simple-delay](image/delay.png){width=100% height=100%}

## Добавление задержки для интерфейса, подключающегося к эмулируемой глобальной сети

![График simple-delay без 1ой строчки в ping.dat](image/delay(1).png){width=100% height=100%}

# Задание для самостоятельной работы

## Эксперимент по изменению задержки

![Эксперимент по изменению задержки](image/change-delay2.png){width=100% height=100%}

## Эксперимент по изменению задержки

![Эксперимент по изменению задержки](image/change-delay1.png){width=100% height=100%}

## Эксперимент по изменению задержки

![Эксперимент по изменению задержки](image/change-delay3.png){width=100% height=100%}

## Эксперимент по изменению джиттера

![Эксперимент по изменению джиттера](image/jitter-delay1.png){width=100% height=100%}

## Эксперимент по изменению джиттера

![Эксперимент по изменению джиттера](image/jitter-delay2.png){width=100% height=100%}

## Эксперимент по изменению джиттера

![Эксперимент по изменению джиттера](image/jitter-delay3.png){width=100% height=100%}

## Эксперимент по изменению значения корреляции для джиттера и задержки

![Эксперимент по изменению значения корреляции для джиттера и задержки](image/correlation-delay1.png){width=100% height=100%}

## Эксперимент по изменению значения корреляции для джиттера и задержки

![Эксперимент по изменению значения корреляции для джиттера и задержки](image/correlation-delay2.png){width=100% height=100%}

## Эксперимент по изменению значения корреляции для джиттера и задержки

![Эксперимент по изменению значения корреляции для джиттера и задержки](image/correlation-delay3.png){width=100% height=100%}

## Распределения времени задержки в эмулируемой глобальной сети

![Распределения времени задержки в эмулируемой глобальной сети](image/12.png){width=100% height=100%}

# Выводы

Мы познакомились с NETEM — инструментом для
тестирования производительности приложений в виртуальной сети, а также получили навыки проведения интерактивного и воспроизводимого экспериментов по измерению задержки и её дрожания (jitter) в моделируемой сети в среде Mininet.


