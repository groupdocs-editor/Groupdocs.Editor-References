---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет задавать пользовательские параметры для создания и сохранения электронных почтовых документов"
type: docs
weight: 15
url: /ru/java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

Позволяет задавать пользовательские параметры для создания и сохранения документов электронной почты (email).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | Инициализирует новый экземпляр класса [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), где все параметры установлены в значения по умолчанию |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | Инициализирует новый экземпляр класса [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) с |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) параметр
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Позволяет управлять тем, какие части почтового сообщения должны быть включены в выходной email‑документ, который будет сгенерирован и сохранён с помощью метода [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Позволяет управлять тем, какие части почтового сообщения должны быть включены в выходной email‑документ, который будет сгенерирован и сохранён с помощью метода [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


Инициализирует новый экземпляр класса [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), где все параметры установлены в значения по умолчанию


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


Инициализирует новый экземпляр класса [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) с
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


Позволяет управлять тем, какие части почтового сообщения должны быть включены в выходной email‑документ, который будет сгенерирован и сохранён с помощью метода [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-)
Значение: Флаговое перечисление, которое управляет частями почтового сообщения, которые должны быть обработаны. Значение по умолчанию — MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Позволяет управлять тем, какие части почтового сообщения должны быть включены в выходной email‑документ, который будет сгенерирован и сохранён с помощью метода [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-)
Значение: Флаговое перечисление, которое управляет частями почтового сообщения, которые должны быть обработаны. Значение по умолчанию — MailMessageOutput.All


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

