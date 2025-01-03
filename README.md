﻿Прошивки для аппаратуры ARIS (МТ500, 28xx)
==========================================

# Описание

IP адрес по умолчанию: **10.1.1.1**.

Для урезанных версий АВАНТ используем прошивку как и для полного. Например, для K400-004-B используется K400-088-B.

В названии прошивки содержатся используемые устройства и номер версии (максимум 32 символа).
Например:
TS32_K400-088-B_v1
- TS32
- K400-088-B
- Версия прошивки 1.
TS32_K400-022-B_K400-002-B_v1
- TS32
- K400-022-B
- K400-002-B
- Версия прошивки 1.
TS32_K400-040-B_ВОЛС_v1
- TS32
- K400-040-В
- K400-040-ВОЛС
- Версия прошивки 1.

Для первого аппарата адрес начинается с **2000**.
Для второго аппарата адрес начинается с **3000**.

> Для прошивки меню PIg начиная с 1v44 интервал опроса рекомендуется делать **600 секунд**, до нее **60 секунд**!!! 
Если нет уверенности в том какая будет версия меню ставить 60 секунд. 

> Команды класса 1 появились в К400 в прошивке меню **PIg_1v44** и работают пока только в К400 ВЧ с прошивкой МК БСП **не ранее K400_1_45**.


# Настройки по умолчанию

## TS32

Настройки:
	- Порт: COM3
	- Время ожидания отклика: 500 мс
 	- Число повторов при отсутствии отклика: 3
	- Интервал времени между повторами: 100 мс
	- Скорость обмена: 9600 бод
	- Контроль четности: Без проверки
	- Количество стоп-бит: 1
	- Использовать побайтное чтение: нет
	- Межбайтовый интервал: 100 мс

## Протокол МЭК 60870-5-101:

Настройки:
	- Адрес станции: 200
	- Общий адрес ASDU: 1
	- Длина адреса станции: 1 байт
	- Длина общего адреса ASDU: 1 байт
	- Длина адреса объекта информации: 2 байта
	- Длина кода причины передачи: 1 байт
	- Период общего опроса: 10 с
	- Интервал синхронизации времени: 60 с
	- Пауза перед запросом: 0 мс

## Первый аппарат

Настройки связи:
	- Порт: COM4
	- Время ожидания отклика: 500 мс
 	- Число повторов при отсутствии отклика: 3
	- Интервал времени между повторами: 100 мс
	- Скорость обмена: 19200 бод
	- Контроль четности: Четность
	- Количество стоп-бит: 1
	- Использовать побайтное чтение: нет
	- Межбайтовый интервал: 100 мс

Параметры протокола МЭК 60870-5-101:
	- Адрес станции: 1
	- Общий адрес ASDU: 1
	- Длина адреса станции: 1 байт
	- Длина общего адреса ASDU: 1 байт
	- Длина адреса объекта информации: 2 байта
	- Длина кода причины передачи: 1 байт
	- Период общего опроса: 60 с
	- Интервал синхронизации времени: 60 с
	- Пауза перед запросом: 0 мс

## Второй аппарат:

Настройки связи:
	- Порт: COM5
	- ...

Параметры протокола МЭК 60870-5-101:
	- ...


# Дополнительно

[Карты адресов 104 протокола](101_104/README.md)

 