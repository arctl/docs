---
title: "Версия: 1.952.0"
date: 2023-04-09
toc: true
categories:
  - version
tags:
  - Адреса
  - Шаблоны
  - 1С
  - Документ поставщика
  - Счет на оплату
  - Реестр НДС
    
---

-   ARC_DEV-2987. Адреса. Добавление адреса в справочник путем его указания в произвольном виде и получением подсказки для выбора нужного варианта
-   ARC_DEV-3025. Шаблон заявки. Добавлена дата актуальности. Проверяется при копировании заявки (если дата актуальности шаблона позднее даты создания исходной заявки, то такую заявку скопировать нельзя)
-   ARC_DEV-3026. 1С. Прием документов поставщиков с учетом связи с реализацией
-   ARC_DEV-3027. Документ поставщика. Подстановка даты для нового документа для доступности выбора договора
-   ARC_DEV-3029. Счет на оплату. Подстановка расчетного счета (если в договоре с клиентом указан расчетный счет и он не архивный, то он будет подставлен в счет; в ином случае используется - расчетный счет нашей компании, указанный по-умолчанию)
-   ARC_DEV-3030. Реестр НДС 0%. Добавлена сумма по счету-фактуре
