---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Позволяет задавать пользовательские параметры для создания и сохранения простых текстовых TXT‑документов."
type: docs
weight: 1170
url: /ru/net/groupdocs.editor.options/textsaveoptions/
---
## TextSaveOptions class

Позволяет задавать пользовательские параметры для создания и сохранения простых текстовых (TXT) документов

```csharp
public sealed class TextSaveOptions : ISaveOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextSaveOptions](textsaveoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AddBidiMarks](../../groupdocs.editor.options/textsaveoptions/addbidimarks) { get; set; } | Указывает, следует ли добавлять двунаправленные метки перед каждым BiDi‑блоком при экспорте в формат простого текста. По умолчанию 'false' — не добавлять BiDi‑метки. |
| [Encoding](../../groupdocs.editor.options/textsaveoptions/encoding) { get; set; } | Кодировка символов текстового документа, которая будет применена при его сохранении. |
| [PreserveTableLayout](../../groupdocs.editor.options/textsaveoptions/preservetablelayout) { get; set; } | Указывает, следует ли программе пытаться сохранять макет таблиц при сохранении в формате простого текста. Значение по умолчанию — false. |

### См. также

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
