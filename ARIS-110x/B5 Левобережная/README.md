﻿Левобережная
============

Архив конфигурации для проекта **[Э-411 Шкаф Авант К400-004-В Левобережная](Э-411_Шкаф_Авант_К400-004-В_Левобережная.pdf)**

> !!! При установке на новое устройство необходимо снять галочки "Система", "Состав крейта" и "Настройки модуля". !!!


# ARIS-1105

Версия прошивки: 1.10.2.261368020 /M1.4.1  
Код: A2.1-B1.1-D1.1-D1.1  
Настройки LAN1: 10.1.1.1/24

Подключение B1.X1.A1B1 (COM1):
- Сетевой адрес 1, АВАНТ К400-004-В
- Пауза между запросами 10 мс
- В ретроархив добавлен сигнал Connection

Подключение к слоту 1:
- A1.X3.1 (DI1), Положение SAC1,   2101
- A1.X3.2 (DI2), Неисправность,    2104
- A1.X3.3 (DI3), Контроль ОП ПРМ,  2108
- A1.X3.4 (DI4), Срабатывание ПРМ, 2103
- A1.X3.5 (DI5), Контроль ОП,      2107
- A1.X3.6 (DI6), ---

Подключение к слоту 3:
- D1.X1.1 (DI1),  Положение SA1,   2001
- D1.X1.2 (DI2),  Положение SA2,   2002
...
- D1.X1.6 (DI6),  Положение SA6,   2006
- D1.X2.1 (DI7),  Положение SA7,   2007
- D1.X2.2 (DI8),  Положение SA8,   2008
...
- D1.X2.6 (DI12),  Положение SA12, 2012

Подключение к слоту 4:
- D1.X1.1 (DI1),  Положение SA13,  2013
- D1.X1.2 (DI2),  Положение SA14,  2014
- D1.X1.3 (DI3),  Положение SA15,  2015
- D1.X1.4 (DI4),  Положение SA16,  2016
- D1.X1.5 (DI5),  ---
...
- D1.X2.6 (DI12), ---


# 104 протокол

Типовая карта адресов **Протокол 101_104 v1.1 ARIS-2805**.  
Вместо "Контроль ОП ПРД" сигнал "Контроль ОП".  
Отключена передача сигналов ПРД и лишних команд ПРМ.


# Версии конфигурации

## B5v0 - 2023.12.01

Вновь.  
Сделано на базе типовой конфигурации v1.  
Конфигурация проверялась с версией меню **PIg_1v47**.

