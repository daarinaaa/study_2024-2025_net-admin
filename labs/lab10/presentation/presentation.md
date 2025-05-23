---
## Front matter
lang: ru-RU
title: Лабораторная работа № 10
subtitle: Настройка списков управления доступом (ACL)
author:
  - Шияпова Д.И.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 19 апреля 2025

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

Освоить настройку прав доступа пользователей к ресурсам сети.

## Задание

1. Требуется настроить следующие правила доступа:
   - web-сервер: разрешить доступ всем пользователям по протоколу HTTP
через порт 80 протокола TCP, а для администратора открыть доступ
по протоколам Telnet и FTP;
   - файловый сервер: с внутренних адресов сети доступ открыт по портам
для общедоступных каталогов, с внешних — доступ по протоколу FTP;

## Задание

   - почтовый сервер: разрешить пользователям работать по протоколам
SMTP и POP3 (соответственно через порты 25 и 110 протокола TCP),
а для администратора — открыть доступ по протоколам Telnet и FTP;
   - DNS-сервер: открыть порт 53 протокола UDP для доступа из внутренней сети;
   - разрешить icmp-сообщения, направленные в сеть серверов;
   - запретить для сети Other любые запросы за пределы сети, за исключением администратора;
   - разрешить доступ в сеть управления сетевым оборудованием только
администратору сети.

## Задание

2. Требуется проверить правильность действия установленных правил доступа.
3. Требуется выполнить задание для самостоятельной работы по настройке
прав доступа администратора сети на Павловской.
4. При выполнении работы необходимо учитывать соглашение об именовании.



## Выполнение лабораторной работы

![Размещение ноутбука администратора в сети other-donskaya-1](image/1.png){#fig:001 width=70%}

## Выполнение лабораторной работы

![Задание статического ip-адреса ноутбуку admin](image/3.png){#fig:002 width=70%}

## Выполнение лабораторной работы

![Задание gateway-адреса и адреса DNS-сервера ноутбуку admin](image/2.png){#fig:003 width=70%}

## Выполнение лабораторной работы

![Проверка работоспособности соединения ноутбука admin](image/4.png){#fig:004 width=70%}

## Выполнение лабораторной работы
  
![Настройка доступа к web-серверу по порту tcp 80](image/5.png){#fig:005 width=70%}

## Выполнение лабораторной работы

![Добавление списка управления доступом к интерфейсу](image/6.png){#fig:006 width=70%}

## Выполнение лабораторной работы

![Проверка доступа к web-серверу через протокол HTTP](image/7.png){#fig:007 width=70%}

## Выполнение лабораторной работы

![Проверка недоступности web-сервера через ping](image/8.png){#fig:008 width=70%}

## Выполнение лабораторной работы

![Настройка дополнительного доступа для администратора по протоколам Telnet и FTP](image/9.png){#fig:009 width=70%}

## Выполнение лабораторной работы

![Проверка работы ftp у администратора](image/10.png){#fig:010 width=70%}

## Выполнение лабораторной работы

![Проверка недоступности подключения по ftp у просто пользователя](image/11.png){#fig:011 width=70%}

## Выполнение лабораторной работы

![Настройка доступа к файловому серверу](image/12.png){#fig:012 width=70%}

## Выполнение лабораторной работы

![Настройка доступа к почтовому серверу](image/13.png){#fig:013 width=70%}

## Выполнение лабораторной работы

![Настройка доступа к DNS-серверу](image/14.png){#fig:014 width=70%}

## Выполнение лабораторной работы

![Проверка доступности web-сервера по ip-адресу](image/15.png){#fig:015 width=70%}

## Выполнение лабораторной работы

![Проверка доступности web-сервера по имени](image/16.png){#fig:016 width=70%}

## Выполнение лабораторной работы

![Разрешение icmp-запросов](image/17.png){#fig:017 width=70%}

## Выполнение лабораторной работы

![Просмотр строк в списке контроля доступа](image/18.png){#fig:018 width=70%}

## Выполнение лабораторной работы

![Настройка доступа для сети Other](image/19.png){#fig:019 width=70%}

## Выполнение лабораторной работы

![Настройка доступа администратора к сети сетевого оборудования](image/20.png){#fig:020 width=70%}


## Самостоятельная работа


![Пингование устройств с dep-donskaya-dishiyapova-1](image/22.png){#fig:022 width=70%}

## Самостоятельная работа

![Проверка доступности устройств с dep-donskaya-dishiyapova-1](image/41.png){#fig:023 width=70%}

## Самостоятельная работа

![Проверка доступности устройств с dk-donskaya-dishiyapova-1](image/24.png){#fig:024 width=70%}

## Самостоятельная работа

![Логическая область с размещенным ноутбуком admin на Павловской](image/25.png){#fig:025 width=70%}

## Самостоятельная работа

![Настройка доступов для admin-pavlovskaya](image/26.png){#fig:026 width=70%}

## Самостоятельная работа

![Проверка корректности настроенного доступа](image/28.png){#fig:028 width=60%}

## Выводы

В процессе выполнения данной лабораторной работы я освоила настройку прав доступа пользователей к ресурсам сети.

