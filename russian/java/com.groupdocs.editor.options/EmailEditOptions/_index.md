---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет задавать пользовательские параметры для редактирования документов в различных форматах электронных писем"
type: docs
weight: 14
url: /ru/java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

Позволяет задавать пользовательские параметры для редактирования документов в различных форматах электронной почты (email).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | Создаёт новый экземпляр класса [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), где все параметры установлены в значения по умолчанию |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | Создаёт новый экземпляр класса [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) с |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) параметр
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Позволяет контролировать, какие части почтового сообщения должны быть переданы в выходной [EditableDocument](../../com.groupdocs.editor/editabledocument), а затем в генерируемый HTML |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Позволяет контролировать, какие части почтового сообщения должны быть переданы в выходной [EditableDocument](../../com.groupdocs.editor/editabledocument), а затем в генерируемый HTML |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


Создаёт новый экземпляр класса [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), где все параметры установлены в значения по умолчанию


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


Создаёт новый экземпляр класса [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) с
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) параметр


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | mailMessageOutput | int | Вывод почтового сообщения, который также может быть указан через свойство |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Позволяет контролировать, какие части почтового сообщения должны быть переданы в выходной [EditableDocument](../../com.groupdocs.editor/editabledocument), а затем в генерируемый HTML
Значение: Флаговое перечисление, которое управляет частями почтового сообщения, которые должны быть обработаны. Значение по умолчанию — MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Позволяет контролировать, какие части почтового сообщения должны быть переданы в выходной [EditableDocument](../../com.groupdocs.editor/editabledocument), а затем в генерируемый HTML
Значение: Флаговое перечисление, которое управляет частями почтового сообщения, которые должны быть обработаны. Значение по умолчанию — MailMessageOutput.All


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

