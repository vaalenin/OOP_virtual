Дополнительные материалы к лекции
(также есть комментарии в коде)

Пример построения иерархии классов для демонстрации наследования
и использования виртуальных функций.

файл - shape_no_virtual.h
содержит базовый класс Shape и НЕ виртуальную функцию Draw;
файл - figures_no_virtual.h
содержит производные классы, у которых ПЕРЕОПРЕДЕЛЕНА функция Draw;

файл - shape_virtual.h
содержит базовый класс Shape и ВИРТУАЛЬНУЮ функцию Draw;
файл - figures_virtual.h
содержит производные классы, у которых ПЕРЕГРУЖЕНА функция Draw;

файл - main.cpp
содержит пример использования данных классов.
для переключения между разными вариантами наследования - с включенным
и выключенным ПОЛИМОРФИЗМОМ используются директивы компилятора (см комменты в коде)

===================================================================================

файл - shape_interface.h
содержит ВИТУАЛЬНЫЙ базовый класс Shape и ЧИСТУЮ ВИРТУАЛЬНУЮ функцию Draw;

файл - figures_interface.h
содержит производные классы, у которых ПЕРЕГРУЖЕНА функция Draw;

файл - main_interface.cpp
содержит пример использования данных классов.

===================================================================================
ЗАДАНИЯ в файле tasks.txt
