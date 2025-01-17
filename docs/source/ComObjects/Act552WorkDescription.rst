Act552WorkDescription
=====================

Описание выполненных работ для *Акта о выполнении работ* в формате приказа `ММВ-7-10/552@ <https://normativ.kontur.ru/document?moduleId=1&documentId=265283>`_


.. rubric:: Свойства

:StartingDate:
  **Дата, чтение/запись** - начало периода выполнения работ

:CompletionDate:
  **Дата, чтение/запись** - окончание периода выполнения работ

:TotalWithVatExcluded:
  **Число, чтение/запись** - сумма без учета НДС - итого

:TotalVat:
  **Число, чтение/запись** - сумма НДС - итого

:Total:
  **Число, чтение/запись** - сумма с учетом НДС - итого

:Items:
  :doc:`Коллекция <Collection>` **объектов** :doc:`Act552WorkItem <Act552WorkItem>` **, чтение** - сведения о произведенной работе


.. rubric:: Методы

+----------------------------------+
| |Act552WorkDescription-AddItem|_ |
+----------------------------------+

.. |Act552WorkDescription-AddItem| replace:: AddItem()

.. _Act552WorkDescription-AddItem:
.. method:: Act552WorkDescription.AddItem()

 Добавляет :doc:`новый элемент <Act552WorkItem>` в коллекцию *Items* и возвращает его


.. note:: Числа рекомендуется записывать строкой в виде XML представления типа `decimal <http://www.w3.org/TR/xmlschema-2/#decimal>`_ .
  В 1С такое представление можно получить с помощью функции глобального контекста XMLСтрока/XMLString
