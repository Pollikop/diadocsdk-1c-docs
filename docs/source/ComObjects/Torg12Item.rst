Torg12Item
==========

`Табличные сведения товарной накладной <https://normativ.kontur.ru/document?moduleId=1&documentId=261859&rangeId=233861>`_

.. rubric:: Свойства

:Product:
  **Строка, чтение/запись** - наименование товара

:ProductCode:
  **Строка, чтение/запись** - код товара

:Feature:
  **Строка, чтение/запись** - характеристика товара

:Sort:
  **Строка, чтение/запись** - сорт товара

:Article:
  **Строка, чтение/запись** - артикул товара

:UnitCode:
  **Строка, чтение/запись** - код единицы измерения товара

:UnitName:
  **Строка, чтение/запись** - наименование единицы измерения

:ParcelsQuantity:
  **Строка, чтение/запись** - количество мест

:ParcelType:
  **Строка, чтение/запись** - вид упаковки

:ParcelCapacity:
  **Строка, чтение/запись** - количество в одном месте

:GrossQuantity:
  **Строка, чтение/запись** - масса брутто

:Quantity:
  **Строка, чтение/запись** - количество (масса нетто)

:Price:
  **Строка, чтение/запись** - цена

:TotalWithVatExcluded:
  **Число, чтение/запись** - сумма без учета НДС

:TaxRate:
  **Строка, чтение/запись** - ставка НДС. |Torg12Item-TaxRate|_

:Vat:
  **Число, чтение/запись** - сумма НДС

:Total:
  **Число, чтение/запись** - сумма с учетом НДС

:AdditionalInfo:
  **Строка, чтение/запись** - произвольная дополнительная информация

:ExternalCode:
  **Строка, чтение/запись** - внешний идентификатор товара. Может быть установлен только покупателем товара.


.. rubric:: Дополнительная информация

.. |Torg12Item-TaxRate| replace:: Возможные значения
.. _Torg12Item-TaxRate:

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
