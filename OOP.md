### ООП - парадигма программирования,
в которой ключевым блоком является объект, 
который соотносится с объектом в конкретной задаче.

### Главные аспекты:
-   любая систкма состоит из объектов
- каждый объект имеет состояние и поведение
- объекты взамидойствуют между собой определенным способом


### Принципы ООП
* Инкапсуляция
* Полиморфизм
* Наследование


Инкапсуляция: 
    -   мехонизм, благодаря которому любой класс или часть системы
    рассматривается как отдельный модуль и пользователь этого модуля может
    взаимодействовать с ним только определенным способом и не видит 
    реализации этого модкля.
    -   сводит к минимуму количество связей между частями системы, тем самым,
    упрощая изменение модулей (рефакторинг).

Полиморфизм:
    - механизм, благодаря которому подклассы могут изменять реализацию методов
    суперкласса, сохраняя его сигнатуру, благодаря чему интерфейс суперкласса 
    остается неизменным
    - позволяет работать с объектами подклассов как с объектами супекласса, даже
    с учетом того, что реализация определенных методов у подклассов может отличаться
    от реализации методоа суперкласса.

Наследование:
    - механизм создания одного класса с помощью другого с использованием всех 
    свойств суперкласса добавляя новые свойства и методов при необходимости.
    - отображает иерархичность окружающего мира.


UML - Unified Modeling Language

Шаблон проектирования - это именованное эфективное решение характерной задачи
    проектирования обеспечения.

DAO - Data Access Object
(объект доступа к данным / пример - реализация CrudRepository) 

