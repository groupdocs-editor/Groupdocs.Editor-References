---
title: "PdfLoadOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Содержит параметры для загрузки PDF‑документов в класс Editor."
type: docs
weight: 30
url: /ru/java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

Содержит параметры для загрузки PDF‑документов в класс Editor.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPassword()](#getPassword--) | Позволяет задавать, изменять и получать пароль, который будет использоваться для открытия PDF‑документа, если он зашифрован. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Позволяет задавать, изменять и получать пароль, который будет использоваться для открытия PDF‑документа, если он зашифрован. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Позволяет задавать, изменять и получать пароль, который будет использоваться для открытия PDF‑документа, если он зашифрован.
Установите NULL или пустую строку, чтобы не использовать пароль (значение по умолчанию).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Позволяет задавать, изменять и получать пароль, который будет использоваться для открытия PDF‑документа, если он зашифрован.
Установите NULL или пустую строку, чтобы не использовать пароль (значение по умолчанию).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

