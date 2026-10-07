---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Содержит параметры для загрузки двоичных документов Spreadsheet Cells, совместимых с Excel, таких как XLSX, ODS и т.д."
type: docs
weight: 36
url: /ru/java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

Содержит параметры для загрузки двоичных документов Spreadsheet (Cells, совместимых с Excel)
документов, таких как XLS(X), ODS и т.п., в класс Editor

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Конструктор без параметров по умолчанию — все параметры имеют значения по умолчанию |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPassword()](#getPassword--) | Позволяет указать, изменить и получить пароль, который будет использоваться для |
открытие документа Spreadsheet, если он закодирован.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Позволяет указать, изменить и получить пароль, который будет использоваться для |
открытие документа Spreadsheet, если он закодирован.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Включает механизмы оптимизации памяти во время обработки входного документа, |
что может ухудшить производительность в некоторых особых случаях, но с другой стороны
ручное уменьшение использования памяти.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Включает механизмы оптимизации памяти во время обработки входного документа, |
что может ухудшить производительность в некоторых особых случаях, но с другой стороны
ручное уменьшение использования памяти.
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Конструктор без параметров по умолчанию — все параметры имеют значения по умолчанию


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Позволяет указать, изменить и получить пароль, который будет использоваться для
открытие документа Spreadsheet, если он закодирован. Установите в NULL или пустой
строка, чтобы не использовать пароль (значение по умолчанию).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Позволяет указать, изменить и получить пароль, который будет использоваться для
открытие документа Spreadsheet, если он закодирован. Установите в NULL или пустой
строка, чтобы не использовать пароль (значение по умолчанию).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Включает механизмы оптимизации памяти во время обработки входного документа,
что может ухудшить производительность в некоторых особых случаях, но с другой стороны
ручное уменьшение использования памяти. Полезно при обработке огромных документов и
при возникновении OutOfMemoryException. По умолчанию false (оптимизация памяти
отключено ради лучшей производительности).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Включает механизмы оптимизации памяти во время обработки входного документа,
что может ухудшить производительность в некоторых особых случаях, но с другой стороны
ручное уменьшение использования памяти. Полезно при обработке огромных документов и
при возникновении OutOfMemoryException. По умолчанию false (оптимизация памяти
отключено ради лучшей производительности).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

