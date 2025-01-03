Типовой шкаф
============

Прошивки аппаратов для проектов ВЧ и ВОЛС:
- **[Э-331 Шкаф Авант К400-088-ВОЛС Зейская ГЭС](Э-331_Шкаф_Авант_К400-088-ВОЛС_Зейская_ГЭС.pdf)**

> !!! При установке конфигурации на новое устройство необходимо снять галочки "Система", "Время", "Состав крейта", "Настройка модулей" и "Описание устройства". !!!

> !!! При установке на новое устройство необходимо установить галочку "Подстановка".!!!


# ARIS-2805

Версия прошивки:  1.9.162.249654870U /M1.4.1    
Код: A2.4-B1.4-D1.4-D1.4-X  
Настройки LAN1: 10.1.1.1/24

> Модуль B1.4 может меняться на B3.4.

Подключение B1.X1.A1B1 (COM1):
- Сетевой адрес 1, АВАНТ К400-088-В
- Пауза между запросами 10 мс
- В ретроархив добавлен сигнал Connection

Подключение к слоту 3:
- D1.X1.1  (IN1),  Положение SA1, 2001
- D1.X1.2  (IN2),  Положение SA2, 2002
...
- D1.X1.10 (IN10), Положение SA10, 2010
- D1.X2.1  (IN11), Положение SA11, 2011
- D1.X2.2  (IN12), Положение SA12, 2012
...
- D1.X2.10 (IN20), Положение SA20, 2020


Подключение к слоту 4
- D1.X1.1  (IN1),  Положение SA21, 2021
- D1.X1.2  (IN2),  Положение SA22, 2022
...
- D1.X1.10 (IN10), Положение SA30, 2030
- D1.X2.1 (IN11), Положение SA31, 2031
- D1.X2.2 (IN12), Положение SA32, 2032
- D1.X2.3 (IN13), Положение SAC1, 2101
- D1.X2.4 (IN14), Неисправность, 2104
- D1.X2.5 (IN15), ---
- D1.X2.6 (IN16), Срабатывание ПРД, 2102
- D1.X2.7 (IN17), Срабатывание ПРМ, 2103
- D1.X2.8 (IN18), Контроль ОП ПРД, 2107
- D1.X2.9 (IN19), Контроль ОП ПРМ, 2108
- D1.X2.10 (IN20), ---


# 104 протокол

Типовая карта адресов **Протокол 101_104 v1.1 ARIS-2805**.  


# Версии конфигурации ARIS2805_K400-088-В

## v1 - 2023.11.30

Версия прошивки: 1.9.162.249654870U /M1.4.1  
Добавлена пауза 10мс перед запросом по 101 протоколу.  
Сигнал наличия связи по 10 протоколу добавлен в ретроархив.  
Конфигурация проверялась с версией меню **PIg_1v51**.

## v0 - 2021.11.12

Вновь.  
Версия прошивки: 1.9.157.42514@19.02.2021  

Конфигурация проверялась с версией меню **PIg_1v51**.


# Версии конфигурации ARIS2805_K400_088_OPTO

## v2 - 2023.11.30

Версия прошивки: 1.9.162.249654870U /M1.4.1  
Добавлена пауза 10мс перед запросом по 101 протоколу.  
Сигнал наличия связи по 10 протоколу добавлен в ретроархив.  
Конфигурация проверялась с версией меню **PIg_1v51**.

## v1 - 2023.10.19

Версия прошивки: 1.9.162.249654870U /M1.4.1  
Убраны сигналы класса 1 из 104 протокола.  
Конфигурация проверялась с версией меню **PIg_1v44**.

## v0 - 2021.11.12

Вновь.  
Версия прошивки: 1.9.157.42514@19.02.2021  
Конфигурация проверялась с версией меню **PIg_1v51**.


