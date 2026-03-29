---
lang: ru-RU
title: Настройка сетевых сервисов
subtitle: DNS и DHCP в Cisco Packet Tracer
author:
  - Абрикосов Артём
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 29 марта 2026

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

Изучить принципы работы протоколов DNS и DHCP  
и получить практические навыки их настройки  
в среде Cisco Packet Tracer.

# Настройка DNS-сервера

## Добавление сервера в сеть

![Топология сети](Screenshot_1.png){ width=80% }

## Настройка IP-адреса сервера

![IP-конфигурация DNS](Screenshot_2.png){ width=80% }

## Настройка DNS-записей

![DNS записи](Screenshot_3.png){ width=80% }

# Настройка DHCP

## Конфигурация DHCP на маршрутизаторе

![Настройка DHCP](Screenshot_4.png){ width=80% }

## Пулы DHCP

- dk — 10.128.3.0/24  
- departments — 10.128.4.0/24  
- adm — 10.128.5.0/24  
- other — 10.128.6.0/24  

# Работа клиентов

## Получение адреса по DHCP

![DHCP на ПК](Screenshot_5.png){ width=80% }

## Информация о пулах

![DHCP pools](Screenshot_6.png){ width=80% }

## Таблица выданных адресов

![DHCP binding](Screenshot_7.png){ width=80% }

# Проверка сети

## Проверка доступности

![Ping проверка](Screenshot_8.png){ width=80% }

## Связь между подсетями

![Ping разные сети](Screenshot_9.png){ width=80% }

# Работа DHCP (Simulation)

## Процесс DHCP

![DHCP Simulation](Screenshot_10.png){ width=80% }

## Discover

![DHCP Discover](Screenshot_11.png){ width=80% }

## Offer

![DHCP Offer](Screenshot_12.png){ width=80% }

## Request

![DHCP Request](Screenshot_13.png){ width=80% }

## ACK

![DHCP ACK](Screenshot_14.png){ width=80% }

# Вывод

## Итоги работы

Настроены сервисы DNS и DHCP в сети Cisco Packet Tracer.  

Реализовано автоматическое распределение IP-адресов  
и разрешение доменных имён.  

Исследован процесс DHCP и структура сообщений.  

Подтверждена работоспособность сети и взаимодействие подсетей.