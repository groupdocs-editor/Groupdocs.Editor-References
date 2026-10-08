---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет указать пользовательские параметры для редактирования документов в различных форматах электронной почты"
type: docs
weight: 850
url: /ru/net/groupdocs.editor.options/emaileditoptions/
---
## EmailEditOptions class

Позволяет задавать пользовательские параметры для редактирования документов в различных форматах электронной почты (email)

```csharp
public sealed class EmailEditOptions : IEditOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmailEditOptions](emaileditoptions#constructor)() | Инициализирует новый экземпляр класса [`EmailEditOptions`](../emaileditoptions), где все параметры установлены в значения по умолчанию |
| [EmailEditOptions](emaileditoptions#constructor_1)(MailMessageOutput) | Инициализирует новый экземпляр класса [`EmailEditOptions`](../emaileditoptions) с параметром [`MailMessageOutput`](./mailmessageoutput) |

## Свойства

| Имя | Описание |
| --- | --- |
| [MailMessageOutput](../../groupdocs.editor.options/emaileditoptions/mailmessageoutput) { get; set; } | Позволяет управлять тем, какие части почтового сообщения должны быть доставлены в вывод [`EditableDocument`](../../groupdocs.editor/editabledocument), а затем в сгенерированный HTML |

### См. также

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
