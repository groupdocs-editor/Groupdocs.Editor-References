---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет указать пользовательские параметры для создания и сохранения электронных почтовых сообщений."
type: docs
weight: 860
url: /ru/net/groupdocs.editor.options/emailsaveoptions/
---
## EmailSaveOptions class

Позволяет задавать пользовательские параметры для создания и сохранения документов электронной почты (email)

```csharp
public sealed class EmailSaveOptions : ISaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmailSaveOptions](emailsaveoptions#constructor)() | Инициализирует новый экземпляр класса [`EmailSaveOptions`](../emailsaveoptions), где все параметры установлены в значения по умолчанию. |
| [EmailSaveOptions](emailsaveoptions#constructor_1)(MailMessageOutput) | Инициализирует новый экземпляр класса [`EmailSaveOptions`](../emailsaveoptions) с параметром [`MailMessageOutput`](./mailmessageoutput). |

## Свойства

| Имя | Описание |
| --- | --- |
| [MailMessageOutput](../../groupdocs.editor.options/emailsaveoptions/mailmessageoutput) { get; set; } | Позволяет управлять тем, какие части почтового сообщения должны быть включены в выходной email‑документ, который будет сгенерирован и сохранён с помощью метода [`Save`](../../groupdocs.editor/editor/save). |

### См. также

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
