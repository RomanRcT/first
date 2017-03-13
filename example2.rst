Это пример 2
===============

________

1. Внешние ссылки выглядят так: ссылка_.

.. _ссылка: http://librerussia.blogspot.ru/

2. Если несколько слов, тогда так: `ссылка в несколько слов`_.

.. _`ссылка в несколько слов`: http://librerussia.blogspot.ru/

3. `Более компактная запись ссылок <http://librerussia.blogspot.ru/>`_


Внутренние ссылки делаются так_

.. _так:

Ссылка на раздел создается так `Еще заголовок`_ .
Достаточно в обратных кавычках написать название заголовка.


Еще заголовок
-------------

.. table:: Заголовок таблицы (Внимание! Отступ таблицы относительно
           команды ..``table::`` обязателен)

    +------------------------+------------+----------+----------+
    | Header row, column 1   | Header 2   | Header 3 | Header 4 |
    | (header rows optional) |            |          |          |
    +========================+============+==========+==========+
    | body row 1, column 1   | column 2   | column 3 | column 4 |
    +------------------------+------------+----------+----------+
    | body row 2             | Cells may span columns.          |
    +------------------------+------------+---------------------+
    | body row 3             | Cells may  | - Table cells       |
    +------------------------+ span rows. | - contain           |
    | body row 4             |            | - body elements.    |
    +------------------------+------------+---------------------+

.. table:: Простая таблица
    =====  =====  =======
      A      B    A and B
    =====  =====  =======
    False  False  False
    True   False  False
    False  True   False
    True   True   True
    =====  =====  =======

.. table:: Простая таблица со сложной шапкой

    =====  =====  ======
       Inputs     Output
    ------------  ------
      A      B    A or B
    =====  =====  ======
    False  False  False
    True   False  True
    False  True   True
    True   True   True
    =====  =====  ======

.. csv-table:: CSV-таблица
   :header: "Treat", "Quantity", "Description"
   :widths: 15, 10, 30

   "Albatross", 2.99, "On a stick!"
   "Crunchy Frog", 1.49, "If we took the bones out, it wouldn't be
   crunchy, now would it?"
   "Gannet Ripple", 1.99, "On a stick!"

Третий заголовок
~~~~~~~~~~~~~~~~

.. math::

   \alpha_t(i) = P(O_1, O_2, … O_t, q_t = S_i \lambda)

.. attention:: Внимание

.. caution:: Осторожно

.. danger:: Опасность

.. error:: Ошибка

.. hint:: Подсказка

.. important:: Важно

.. note:: Примечание

.. tip:: Совет

.. warning:: Предупреждение



