UtdToSend
=========

Документ на отправку *Универсальный передаточный документ* в формате приказа `ММВ-7-15/155@ <https://normativ.kontur.ru/document?moduleId=1&documentId=271958>`_.
Является производным объектом от :doc:`DocumentToSend <DocumentToSend>`

.. deprecated:: 5.27.0
  Используйте :doc:`CustomDocumentToSend`


.. rubric:: Свойства

:Type:
  **Строка, чтение** - тип документа. |UtdToSend-Type|_

:Comment:
  **Строка, чтение/запись** - комментарий к документу

:CustomDocumentId:
  **Строка, чтение/запись** - внешний идентификатор документа

:Content:
  :doc:`UtdSellerContent <UtdSellerContent>` **, чтение** - содержимое документа


.. rubric:: Дополнительная информация

.. |UtdToSend-Type| replace:: Возможные значения
.. _UtdToSend-Type:

========================= ============================================
Значение *Type*           Описание
========================= ============================================
UniversalTrasnferDocument УПД в формате приказа ММВ-7-15/155@
UtdInvoice                Счёт-фактура в формате приказа ММВ-7-15/155@
UtdTorg12                 Торг-12 в формате приказа ММВ-7-15/155@
UtdAcceptanceCertificate  Акт в формате приказа ММВ-7-15/155@
========================= ============================================
