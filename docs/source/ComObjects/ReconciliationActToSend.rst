ReconciliationActToSend
=======================

Документ на отправку *Акт сверки*.
Является производным объектом от :doc:`DocumentToSend <DocumentToSend>`

.. versionadded:: 5.5.0

.. deprecated:: 5.27.0
  Используйте :doc:`CustomDocumentToSend`


.. rubric:: Свойства

:Type:
  **Строка, чтение** - тип документа. Константа ``ReconciliationAct``

:Comment:
  **Строка, чтение/запись** - комментарий к документу

:CustomDocumentId:
  **Строка, чтение/запись** - внешний идентификатор документа

:FileName:
  **Строка, чтение/запись** - имя файла вложения

:DocumentDate:
  **Дата, чтение/запись** - дата документа

:DocumentNumber:
  **Строка, чтение/запись** - номер документа
