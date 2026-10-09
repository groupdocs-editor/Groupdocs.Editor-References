---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет базовый класс для семейств форматов, предоставляющий общую функциональность для экземпляров семейств форматов."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

Представляет базовый класс для семейств форматов, предоставляющий общую функциональность для экземпляров семейства форматов.

<br />

*** ** * ** ***

Этот класс является абстрактным и должен быть унаследован производным классом, который задает фактические детали семейства форматов.

<br />


## Методы

| Метод | Описание |
| --- | --- |
|  | [getId()](#getId--) | Получает уникальный идентификатор семейства форматов. |
|
|  | [getName()](#getName--) | Получает название семейства форматов. |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Определяет, равен ли данный экземпляр указанному экземпляру [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [toString()](#toString--) | Возвращает строку, представляющую текущий объект. |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | Получает все экземпляры указанного типа |
T
которые наследуются от [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли данный экземпляр указанному экземпляру [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [hashCode()](#hashCode--) | Возвращает хеш‑код текущего объекта. |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | Получает экземпляр указанного типа |
T
который имеет указанный идентификатор.
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | Получает экземпляр указанного типа |
T
который имеет указанное название.
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Определяет, равны ли два экземпляра [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Определяет, не равны ли два экземпляра [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Определяет, равен ли экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) указанному строковому имени. |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Определяет, не равен ли экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) указанному строковому имени. |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Неявно преобразует экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) в целое число. |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Неявно преобразует экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) в строку. |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | Преобразует строку, представляющую название семейства форматов, в объект [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [fromId(int id)](#fromId-int-) | Преобразует целое число, представляющее идентификатор семейства форматов, в объект [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
### getId() {#getId--}
```
public final int getId()
```


Получает уникальный идентификатор семейства форматов.


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Получает название семейства форматов.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


Определяет, равен ли данный экземпляр указанному экземпляру [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) для сравнения с текущим экземпляром. |
|

**Returns:**
boolean — true, если указанный [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) равен текущему экземпляру; в противном случае — false.

### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую текущий объект.


**Returns:**
java.lang.String — строка, представляющая текущий объект, значение свойства  Name .

<br />

*** ** * ** ***

Этот метод переопределяет  object.ToString , чтобы вернуть свойство  Name  объекта.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


Получает все экземпляры указанного типа
T
которые наследуются от [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> — перечисляемая коллекция экземпляров указанного типа  T .


T
: Тип семейства форматов.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли данный экземпляр указанному экземпляру [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) для сравнения с текущим экземпляром. |
|

**Returns:**
boolean — true, если указанный [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) равен текущему экземпляру; в противном случае — false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код текущего объекта.


**Returns:**
int — хеш-код текущего объекта, подходящий для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.

<br />

*** ** * ** ***

Этот метод переопределяет  object.GetHashCode . Хеш-код вычисляется с использованием свойств  Id  и  Name  объекта. Контекст  unchecked  допускает переполнение, что приемлемо в контексте вычисления хеш-кода.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


Получает экземпляр указанного типа
T
который имеет указанный идентификатор.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | значение | int | Идентификатор семейства форматов. |


T
: Тип семейства форматов.
|

**Returns:**
T - Экземпляр указанного типа  T  с указанным идентификатором.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


Получает экземпляр указанного типа
T
который имеет указанное название.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | name | java.lang.String | Имя семейства форматов. |


T
: Тип семейства форматов.
|

**Returns:**
T - Экземпляр указанного типа  T  с указанным именем.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Определяет, равны ли два экземпляра [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Первый экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) для сравнения. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Второй экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) для сравнения. |
|

**Returns:**
boolean - true, если два экземпляра [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) равны; иначе — false.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Определяет, не равны ли два экземпляра [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Первый экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) для сравнения. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Второй экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) для сравнения. |
|

**Returns:**
boolean - true, если два экземпляра [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) не равны; иначе — false.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


Определяет, равен ли экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) указанному строковому имени.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) для сравнения. |
|
|  | name | java.lang.String | Строковое имя для сравнения с экземпляром [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - true, если имя экземпляра [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) равно указанному строковому имени; иначе — false.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


Определяет, не равен ли экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) указанному строковому имени.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) для сравнения. |
|
|  | name | java.lang.String | Строковое имя для сравнения с экземпляром [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - true, если имя экземпляра [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) не равно указанному строковому имени; иначе — false.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


Неявно преобразует экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) в целое число.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) для преобразования. |
|

**Returns:**
int - Уникальный идентификатор экземпляра [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


Неявно преобразует экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) в строку.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Экземпляр [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) для преобразования. |
|

**Returns:**
java.lang.String - Имя экземпляра [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


Преобразует строку, представляющую название семейства форматов, в объект [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | family | java.lang.String | Имя семейства форматов для преобразования. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


Преобразует целое число, представляющее идентификатор семейства форматов, в объект [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | id | int | Идентификатор (ID) семейства форматов для преобразования. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

