### 1.Счетчик Instruction.

Покрытие инструкций предоставляет информацию об объеме кода, который был выполнен или пропущен. Эта метрика полностью независима от исходного форматирования и всегда доступна, даже при отсутствии отладочной информации в файлах классов.

### 2.Счетчик Line.

СЧетчик рассчитывает покрытие для отдельных строк кода. Исходная строка считается выполненной, если была выполнена хотя бы одна инструкция, назначенная этой строке.выделение исходного кода показывает три разных состояния для каждой строки, содержащей исходный код:

* Нет покрытия: ни одна инструкция в строке не была выполнена (красный фон)
* Частичное покрытие: выполнена только часть инструкции в строке (желтый фон)
* Полное покрытие: все инструкции в строке выполнены (зеленый фон)

### 3.Счетчик Branch.

Счетчик подсчитывает общее количество  ветвей в методе и определяет количество выполненных или пропущенных ветвей.

Строки выделены соответствующим образом:

* Нет покрытия: нет ответвлений в линии (красный ромб)
* Частичное покрытие: выполнена только часть ветвей в линии (желтый ромб)
* Полное покрытие: Все ответвления в линии выполнены (зеленый ромб)