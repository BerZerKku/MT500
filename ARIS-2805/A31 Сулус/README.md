﻿Вега
====

Архив конфигурации для проекта **[Э-398 Шкаф Авант К400-088-В Сулус](Э-398_Шкаф_Авант_К400-088-В_Сулус.pdf)**

> !!! При установке на новое устройство необходимо снять галочки "Система", "Состав крейта" и "Настройки модуля". !!!

> !!! При установке на новое устройство необходимо установить галочку "Подстановка".!!!


# ARIS-2805

Версия прошивки: 1.9.162.249654870U /M1.4.1  
Код: A2.4-B1.4-D1.4-D1.4-F2.4  
Настройки LAN1: 10.1.1.1/24

Подключение B1.X1.A1B1 (COM1):
- Сетевой адрес 1, АВАНТ К400-088-В

Подключение к слоту 3:
- D1.X1.1  (IN1),  Положение SA1, 2001
- D1.X1.2  (IN2),  Положение SA2, 2002
...
- D1.X1.10 (IN10), Положение SA10, 2010
- D1.X2.1  (IN11), Положение SA11, 2011
- D1.X2.2  (IN12), Положение SA12, 2012
...
- D1.X2.10 (IN20), Положение SA20, 2020

Подключение к слоту 4:
- D1.X1.1  (IN1),  Положение SA21, 2021
- D1.X1.1  (IN2),  Положение SA22, 2022
...
- D1.X1.10 (IN10), Положение SA30, 2030
- D1.X2.1  (IN11), Положение SA31, 2031
- D1.X2.2  (IN12), Положение SA32, 2032
- D1.X2.3  (IN13), -
...
- D1.X2.10 (IN20), -

Подключение к слоту 5:
- F2.X2.1  (IN1),  Положение SAC1, 2101
- F2.X2.2  (IN2),  Контроль ОП ПРМ, 2108
- F2.X2.3  (IN3),  Контроль ОП ПРД, 2107
- F2.X2.4  (IN4),  Дверь открыта, 2109
- F2.X2.5  (COM),  220-
- F2.X2.6  (IN5),  ---
- F2.X2.7  (IN6),  Неисправность, 2104
- F2.X2.8  (IN7),  Срабатывание ПРМ, 2103
- F2.X2.9  (IN8),  Предупреждение, 2105
- F2.X2.10 (COM),  220-
- F2.X2.11 (IN9),  Срабатывание ПРД, 2102
- F2.X2.12 (IN10), ---
- F2.X2.13 (IN11), ---
- F2.X2.14 (IN12), ---
- F2.X2.15 (COM),  220-

# 104 протокол

**Протокол 101_104 A19 Бам**, к типовой карте добавлены сигналы :
- 2033, вход SA23.1
- 2034, вход SA24.1
- 2105, Предупреждение
- 2109, Дверь открыта


# Версии конфигурации

## A31v0 - 2023.09.22

Вновь.  
Сделано на базе конфигурации A19v0 (отлчичие в подключении цепей "Контроль ОП...").  
Конфигурация проверялась с версией меню **PIg_1v47**.

