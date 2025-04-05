---
## Front matter
lang: ru-RU
title: Лабораторная работа № 5
subtitle: Конфигурирование VLAN
author:
  - Шияпова Д.И.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 05 апреля 2025

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


## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Шияпова Дарина Илдаровна
  * Студентка
  * Российский университет дружбы народов
  * [1132226458@pfur.ru](mailto:1132226458@pfur.ru)


:::
::: {.column width="30%"}

![](./image/dishiyapova.jpeg)

:::
::::::::::::::

## Цель работы

Получить основные навыки по настройке VLAN на коммутаторах сети.


## Задание

1. На коммутаторах сети настроить Trunk-порты на соответствующих интерфейсах, связывающих коммутаторы между собой.

2. Коммутатор msk-donskaya-sw-1 настроить как VTP-сервер и прописать на
нём номера и названия VLAN.

3. Коммутаторы msk-donskaya-sw-2 — msk-donskaya-sw-4, mskpavlovskaya-sw-1 настроить как VTP-клиенты, на интерфейсах указать
принадлежность к соответствующему VLAN.

## Задание

4. На серверах прописать IP-адреса.

5. На оконечных устройствах указать соответствующий адрес шлюза и прописать статические IP-адреса из диапазона соответствующей сети, следуя регламенту выделения ip-адресов.

6. Проверить доступность устройств, принадлежащих одному VLAN, и недоступность устройств, принадлежащих разным VLAN.

7. При выполнении работы необходимо учитывать соглашение об именовании.

## Выполнение лабораторной работы

![Настройка Trunk-порта на msk-donskaya-dishiyapova-sw-1](image/1.png){#fig:001 width=70%}

## Выполнение лабораторной работы

![Настройка Trunk-порта на msk-donskaya-dishiyapova-sw-2](image/2.png){#fig:002 width=70%}

## Выполнение лабораторной работы

![Настройка Trunk-порта на msk-donskaya-dishiyapova-sw-3](image/3.png){#fig:003 width=70%}

## Выполнение лабораторной работы

![Настройка Trunk-порта на msk-donskaya-dishiyapova-sw-4](image/4.png){#fig:004 width=70%}

## Выполнение лабораторной работы

![Настройка Trunk-порта на msk-pavlovskaya-dishiyapova-sw-1](image/6.png){#fig:005 width=70%}

## Выполнение лабораторной работы

![Задания VLAN](image/7.png){#fig:006 width=70%}

## Выполнение лабораторной работы

![Конфигурация VTP msk-donskaya-dishiyapova-sw-1](image/9.png){#fig:007 width=70%}

## Выполнение лабораторной работы

![Конфигурация VTP msk-donskaya-dishiyapova-sw-2](image/10.png){#fig:008 width=70%}

## Выполнение лабораторной работы

![Конфигурация VTP msk-donskaya-dishiyapova-sw-3](image/11.png){#fig:009 width=70%}

## Выполнение лабораторной работы

![Конфигурация VTP msk-donskaya-dishiyapova-sw-4](image/12.png){#fig:010 width=70%}

## Выполнение лабораторной работы

![Конфигурация VTP msk-pavlovskaya-dishiyapova-sw-1](image/15.png){#fig:011 width=70%}

## Выполнение лабораторной работы

![Конфигурация диапазона портов и указание принадлежности к VLAN для  msk-donskaya-dishiyapova-sw-4](image/16.png){#fig:012 width=70%}

## Выполнение лабораторной работы

![Конфигурация диапазона портов и указание принадлежности к VLAN для  msk-pavlovskaya-dishiyapova-sw-1](image/17.png){#fig:013 width=70%}

## Выполнение лабораторной работы

![Конфигурация диапазона портов и указание принадлежности к VLAN для  msk-donskaya-dishiyapova-sw-2](image/18.png){#fig:014 width=70%}

## Выполнение лабораторной работы

![Конфигурация диапазона портов и указание принадлежности к VLAN для  msk-donskaya-dishiyapova-sw-3](image/19.png){#fig:015 width=70%}

## Выполнение лабораторной работы

![Задание IP-адреса шлюзу](image/20.png){#fig:016 width=70%}

## Выполнение лабораторной работы

![Задание IP-адреса](image/21.png){#fig:017 width=70%}

## Выполнение лабораторной работы

![Пингование](image/27.png){#fig:018 width=70%}

## Выполнение лабораторной работы

![Режим симуляции](image/28.png){#fig:019 width=70%}

## Выводы

В процессе выполнения данной лабораторной работы я получила основные навыки по настройке VLAN на коммутаторах сети.
