---
title: "Версия: 1.892.14"
date: 2022-06-20
toc: true
categories:
  - version
tags:
  - Диспетчерский центр
  - Депо
  - Расходы
  - Адреса
  - Платежный календарь

---

-   ARC_DEV-2638. Наша компания. Настройки. Добавлен флаг “Рассчитывать ПРР по плановой дате прибытия” (влияет на время ПРР на складе и отображается в ДЦ):
	1.  Без флага (по-умолчанию). Время ПРР = [Время убытия (факт)] - [Время прибытия (факт)]
	2.  С флагом. Время ПРР = [Время убытия (факт)] - [Время прибытия (план)]
-   ARC_DEV-2640. Депо. В журналы добавлена колонка “Тент”
-   ARC_DEV-2641. Журналы расходов. Добавлен менеджер, ведущий клиента
-   ARC_DEV-2642. Платежный календарь. Возможность вручную изменять состояние "Акцептовано" -> "Передано в 1С" (при наличии разрешения)
-   ARC_DEV-2648. Адреса складов. Исключен дубликат улицы в адресе (формат “Для склада”)
-   ARC_DEV-2649. Журналы расходов. Добавлен менеджер, ответственный за документ поставщика
