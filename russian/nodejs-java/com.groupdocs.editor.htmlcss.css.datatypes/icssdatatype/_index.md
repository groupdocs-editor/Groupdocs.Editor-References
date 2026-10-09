---
title: "ICssDataType"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Общий интерфейс для всех CSS-типов данных, используемых в свойствах CSS"
type: docs
weight: 15
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

Общий интерфейс для всех типов данных CSS, используемых в свойствах CSS

## Методы

| Метод | Описание |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | Должен возвращать строковое представление значения по умолчанию текущего значения |
тип данных
|
|  | [isDefault()](#isDefault--) | Должно определять, является ли текущее значение типа данных значением по умолчанию |
значение для этого конкретного типа данных или нет
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


Должен возвращать строковое представление значения по умолчанию текущего значения
тип данных


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


Должно определять, является ли текущее значение типа данных значением по умолчанию
значение для этого конкретного типа данных или нет


**Returns:**
boolean —
