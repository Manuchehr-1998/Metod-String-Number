# Table of Contents

# 1 What is a Method in js?

# 2 String

# 3 Number

### Что такое метод в js?

> Метод — это блок кода, который запускается только при вызове.
> Вы можете передавать данные, известные как параметры, в метод.
> Методы используются для выполнения определенных действий, и они
> также известные как функции.

### Создавать js-строки

![N|Solid](./img/dve-konstrukczii-vstavki-dlya-dvuh-peremennyh-javascript.png)

# СТРОКОВЫЕ МЕТОДЫ JAVA-СЦЕНАРИЯ

#### 1 String length

> ![N|Solid](./img/Screenshot_1.png)

#### 2 String slice

> slice(start, end)
> JavaScript считает позиции с нуля. Первая позиция 0. Вторая позиция 1.
> ![N|Solid](./img/Screenshot_2.png) > ![N|Solid](./img/Screenshot_3.png) > ![N|Solid](./img/Screenshot_4.png)

#### 3 String substring()

> Разница в том, что начальное и конечное значения меньше 0 обрабатываются как 0 в substring().
> ![N|Solid](./img/Substring_1.png)
> Если вы опустите второй параметр, substring() удалит остальную часть строки.
> ![N|Solid](./img/Substring_2.png)

#### 4 String substr()

> Разница в том, что второй параметр указывает длину извлеченной части.
> ![N|Solid](./img/substr_1.png) > ![N|Solid](./img/Substr_2.png) > ![N|Solid](./img/Substr_3.png)

#### Replacing String Content Замена строкового содержимого

> Метод replace() заменяет указанное значение другим значением в строке:
> ![N|Solid](./img/replace_1.png)
> Метод replace() не изменяет строку, для которой он вызывается.Метод replace() возвращает новую строку.
> Метод replace() заменяет только первое совпадение
> По умолчанию метод replace() заменяет только первое совпадение.
> По умолчанию метод replace() чувствителен к регистру. Написание MICROSOFT (с заглавными буквами) не будет работать:
> ![N|Solid](./img/replace_2.png)

#### JavaScript String ReplaceAll() Заменить все строки JavaScript()

> В 2021 году в JavaScript появился строковый метод replaceAll().
> ![N|Solid](./img/replaceAll_1.png)

#### JavaScript String toUpperCase() Строка JavaScript toUpperCase()

![N|Solid](./img/toUpperCase_1.png)

#### JavaScript String toLowerCase()

![N|Solid](./img/toLowerCase_1.png)

#### JavaScript String concat()

![N|Solid](./img/concat_1.png)

#### JavaScript String trim() Обрезка строки JavaScript()

![N|Solid](./img/trim_1.png)

#### JavaScript String charAt()

> Метод charAt() возвращает символ по указанному индексу (позиции) в строке:
> ![N|Solid](./img/charAt_1.png)

#### JavaScript String charCodeAt()

> Метод charCodeAt() возвращает юникод символа по указанному индексу в строке:

Метод возвращает код UTF-16 (целое число от 0 до 65535).
![N|Solid](./img/charCodeAtt_5.png)

#### JavaScript String split() Разделение строки JavaScript()

> text.split(",") // Split on commas Разделить запятыми
> text.split(" ") // Split on spaces Разделить на пробелы
> text.split("|") // Split on pipe Разделить на трубу
> text.split()
> ![N|Solid](./img/split_1.png)

#### indexOf a string for "welcome"

> ![N|Solid](./img/indexOf_1.png)

#### includes

![N|Solid](./img/includes_1.png)

#### repeat

![N|Solid](./img/repeat_1.png)

#### toString

![N|Solid](./img/toString_1.png)
