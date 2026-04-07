---
lang: ru-RU
title: Использование протокола STP. Агрегирование каналов
subtitle: Лабораторная работа №9
author:
  - Абрикосов Артём
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 07 апреля 2026

toc: false
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Цель работы

## Цель лабораторной работы

Изучение протокола STP, механизмов отказоустойчивости сети,  
а также агрегирования каналов и перераспределения нагрузки.

# Работа протокола STP

## Резервное соединение

![Топология сети с резервным соединением](Screenshot_1.png){ width=80% }

## Проверка связности

![Передача ICMP-пакетов](Screenshot_2.png){ width=80% }

## Анализ работы STP

![Состояние STP VLAN 3](Screenshot_4.png){ width=80% }

# Настройка корневого коммутатора

## Назначение root bridge

![Настройка root bridge](Screenshot_5.png){ width=80% }

## Изменение маршрутов

![Передача пакетов после настройки STP](Screenshot_6.png){ width=80% }

# Настройка PortFast

## Конфигурация портов

![Настройка PortFast](Screenshot_8.png){ width=80% }

# Отказоустойчивость STP

## Потери пакетов при отказе

![Потери пакетов](Screenshot_9.png){ width=80% }

## Переключение режима

![Настройка Rapid PVST+](Screenshot_10.png){ width=80% }

## Работа сети

![Быстрое восстановление](Screenshot_11.png){ width=80% }

# Агрегирование каналов

## Настройка Port-channel

![Настройка EtherChannel](Screenshot_12.png){ width=80% }

## Проверка ping

![Успешная передача пакетов](Screenshot_13.png){ width=80% }

# Вывод

## Итоги работы

- Изучен протокол STP и его поведение  
- Исследована отказоустойчивость сети  
- Настроен Rapid PVST+  
- Реализован EtherChannel  
- Повышена надежность и производительность сети  

 