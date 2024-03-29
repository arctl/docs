---
layout: default
title: Разграничение видимости на уровне записей
parent: Администрарование
nav_order: 9
---

# Разграничение видимости на уровне записей
{: .no_toc }

Разграничение видимости на уровне записей выполняется через справочник “организационная структура”.

Ограничение видимости доступно для следующих объектов:

- Контрагенты                    - Запросы   
- Контакты                       - Лиды
- Предложения                    - Дела   

      Типы доступа: Чтение; Изменение.

**Важно!**
тип доступа “Чтение” соответствует роли “SR - [Сущность].Просмотр”,
тип доступа “изменение” соответствует роли “SR - [Сущность].Редактор”

**Важно!** Роли типа “SR” имеют наивысший приоритет, независимо от правил описанных ниже, доступ будет определяться по роли “SR” если она назначена пользователю.

Правила доступа представлены в таблице ниже.

Таблица. Правила доступа.

Правило | Описание | Графическое описание
------ | ------ | ------
Свои   | Только записи, где сотрудник ответственный  | ![](../../images/table.png)
------ | ------ | ------
Своей роли   | Все записи с правилом “свои” и записи сотрудников этой же роли  | ![](../../images/table1.png)
------ | ------ | ------
Своей подразделения   | Записи всех сотрудников текущего подразделения  | ![](../../images/table2.png)
------ | ------ | ------
Своей компании   | Записи всех сотрудников компании включая все подразделения  | ![](../../images/table3.png)
------ | ------ | ------
Все  | Все записи  | ![](../../images/table4.png)
------ | ------ | ------
Нет доступа | Без доступа |

Пример:  Сотрудникам сделать доступ только к своим записям контрагентов

1. В организационной структуре устанавливаем правила “Свои”,
как показано ниже

![](../../images/their.png)

2. В безопасности у сотрудника удалить роли:
SR - [Сущность].Просмотр и SR - [Сущность].Редактор

![](../../images/their2.png)
