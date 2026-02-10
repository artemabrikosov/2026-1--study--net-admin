---
## Front matter
lang: ru-RU
title: Администрирование локальных сетей
subtitle: Построение сети в Cisco Packet Tracer
author:
  - Абрикосов Артём
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 10 февраля 2026

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Цели и задачи работы

## Цель лабораторной работы

Изучить интерфейс Cisco Packet Tracer и получить практические навыки  
построения простейшей локальной сети с использованием концентратора,  
коммутатора и маршрутизатора.

# Построение сети на базе концентратора

## Создание топологии

![Топология сети с концентратором](Screenshot_1.png){ width=80% }

## Назначение IP-адресов

![Настройка IP-адреса на ПК](Screenshot_2.png){ width=80% }

## Передача ARP и ICMP

![Передача пакетов в режиме Simulation](Screenshot_3.png){ width=80% }

## Движение пакетов в сети

![Распространение кадров через концентратор](Screenshot_4.png){ width=80% }

# Анализ передачи данных

## Модель OSI

![Анализ пакета на уровнях OSI](Screenshot_5.png){ width=80% }

## Структура Ethernet и ICMP

![Структура Ethernet-кадра и ICMP](Screenshot_6.png){ width=80% }

## Возникновение коллизии

![Коллизия при одновременной передаче](Screenshot_7.png){ width=80% }

## Повторная передача пакетов

![Повторная отправка кадров](Screenshot_8.png){ width=80% }

# Построение сети на базе коммутатора

## Новая топология

![Топология сети с коммутатором](Screenshot_9.png){ width=80% }

## Настройка IP-адресов

![Настройка IP на ПК](Screenshot_10.png){ width=80% }

## Передача пакетов через коммутатор

![Передача ARP и ICMP через switch](Screenshot_11.png){ width=80% }

## Анализ структуры кадров

![Структура Ethernet при работе коммутатора](Screenshot_12.png){ width=80% }

## Отсутствие коллизий

![Передача без коллизий](Screenshot_13.png){ width=80% }

# Взаимодействие концентратора и коммутатора

## Объединение сегментов сети

![Соединение hub и switch](Screenshot_14.png){ width=80% }

## Возникновение коллизии

![Коллизия при совместной работе](Screenshot_15.png){ width=80% }

## Передача служебных пакетов

![Пакеты STP](Screenshot_16.png){ width=80% }

## Структура BPDU

![Структура STP-кадра](Screenshot_17.png){ width=80% }

# Подключение маршрутизатора

## Настройка интерфейса маршрутизатора

![Настройка IP маршрутизатора](Screenshot_18.png){ width=80% }

## Итоговая топология сети

![Сеть с маршрутизатором](Screenshot_19.png){ width=80% }

## Передача пакетов к маршрутизатору

![Движение пакетов в сети](Screenshot_20.png){ width=80% }

## Структура CDP-кадра

![Структура CDP и Ethernet 802.3](Screenshot_21.png){ width=80% }

# Выводы по проделанной работе

## Вывод

В ходе выполнения лабораторной работы была построена локальная сеть  
в Cisco Packet Tracer с использованием концентратора, коммутатора  
и маршрутизатора.  

