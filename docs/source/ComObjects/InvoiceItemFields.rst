InvoiceItemFields
=================

Информации о значениях "ДО" и "ПОСЛЕ" в сведениях о товаре

.. rubric:: Свойства

:UnitCode:
  **Строка, чтение/запись** - код единицы измерения товара

:Quantity:
  **Число, чтение/запись** - количество единиц товара

:Price:
  **Число, чтение/запись** - цена за единицу товара (без НДС)

:TaxRate:
  **Строка, чтение/запись** - ставка НДС

:Excise:
  **Строка, чтение/запись** - акциз. Может быть ``без акциза`` или строкой с числом

:TotalWithVatExcluded:
  **Число, чтение/запись** - сумма без учета НДС

:Vat:
  **Число, чтение/запись** - сумма НДС

:Total:
  **Число, чтение/запись** - сумма с учетом НДС


.. rubric:: Дополнительная информация

================== =================================
Значение *TaxRate* Описание
================== =================================
10/110             ставка налога 10/110 (дробь)
18/118             ставка налога 18/118 (дробь)
20/120             ставка налога 20/120 (дробь)
без НДС            без НДС
0                  ставка налога 0%
10                 ставка налога 10%
18                 ставка налога 18%
20                 ставка налога 20%
ИсчНалАг           НДС исчисляется налоговым агентом
================== =================================
