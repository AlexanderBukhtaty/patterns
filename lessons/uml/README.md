## UML

**UML** – унифицированный язык моделирования – это система обозначений, которую можно применять для объектно-ориентированного анализа и проектирования.​
Его можно использовать для визуализации, спецификации, конструирования и документирования программных систем.​

### Типы UML-диаграмм
Существует множество типов диаграмм которые можно создать при помощи uml. Ниже приведен краткий список таких:
* Диаграмма вариантов использования (use case diagram)​
* Диаграмма классов (class diagram)​
* Диаграмма состояний (statechart diagram)​
* Диаграмма последовательности (sequence diagram)​
* Диаграмма кооперации (collaboration diagram)​
* Диаграмма компонентов (component diagram)​
* Диаграмма развертывания (deployment diagram)​
* и много других.

### Диаграмма классов (class diagram)
**Диаграмма классов** (англ. Static Structure diagram) — структурная диаграмма языка моделирования UML, демонстрирующая общую структуру иерархии классов системы, их коопераций, атрибутов (полей), методов, интерфейсов и взаимосвязей между ними. Широко применяется не только для документирования и визуализации, но также для конструирования посредством прямого или обратного проектирования.

### Структура класса в UML
Класс в UML обозначается вытянутым по вертикали прямоугольником разделенным на части от 1 до 3.

**Первая часть** содержит имя класса, абстрактного класса или интерфейса.

**Вторая часть** содержит аттрибуты/поля класса

**Третья часть** содержит методы класса

Сущестуют разные уровни детализации. Например можно указывать модификаторы доступа (public, private, protected), типы аттрибутов, типы аргументов или возвращаемые типы у функций.

### Отношения классов
Отношения классов обозначаются линиями
* **Ассоциация** (простая линия) - показывает, что объекты одной сущности (класса) связаны с объектами другой сущности таким образом, что можно перемещаться от объектов одного класса к другому. Является общим случаем композиции и агрегации.
* **Обобщение** (линия с треугольником на конце) - показывает, что один из двух связанных классов (подтип) является частной формой другого (надтипа), который называется обобщением первого. На практике это означает, что любой экземпляр подтипа является также экземпляром надтипа.
* **Реализация** (пунктирная линия с треугольником на конце) -отношение между двумя элементами модели, в котором один элемент (клиент) реализует поведение, заданное другим (поставщиком). 
* **Зависимость** (пунктирная линия со стрелкой на конце) - это слабая форма отношения использования, при котором изменение в спецификации одного влечёт за собой изменение другого, причём обратное не обязательно. Возникает, когда объект выступает, например, в форме параметра или локальной переменной.​
* **Агрегация** (линия с незакрашенным ромбом на конце) - это разновидность ассоциации при отношении между целым и его частями. Как тип ассоциации агрегация может быть именованной. Одно отношение агрегации не может включать более двух классов (контейнер и содержимое).
* **Композиция** (линия с закрашенным ромбом на конце) - более строгий вариант агрегации. Известна также как агрегация по значению.​Композиция имеет жёсткую зависимость времени существования экземпляров класса контейнера и экземпляров содержащихся классов. Если контейнер будет уничтожен, то всё его содержимое будет также уничтожено.

### Кратность отношений классов
```1```   - один

```0-1``` - ноль либо один

```*  ``` - может быть как один так и много

```1..*```- от одного и более

### Ссылки
[Презентация](https://solitclouds-my.sharepoint.com/:p:/g/personal/abuhtatyy_solit-clouds_ru/EbsRx0KL3bxMo6V3ZeGbdd8B0ogqvtTU_bRw7tSuz9zT0Q?e=7Be63k)
