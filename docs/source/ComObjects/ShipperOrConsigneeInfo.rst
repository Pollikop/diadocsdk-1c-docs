ShipperOrConsigneeInfo
======================

Информации о грузоотправителе/грузополучателе

.. rubric:: Свойства


:IsSoleProprietor:
  **Булево, чтение/запись** - организация является индивидуальным предпринимателем

:Name:
  **Строка, чтение/запись** - наименование организации

:Address:
  :doc:`AddressInfo <AddressInfo>` **, чтение** - фактический адрес организации

:SameAsSellerOrBuyer:
  **Булево, чтение/запись** - в документе грузотправитель должен быть указан ``он же``
