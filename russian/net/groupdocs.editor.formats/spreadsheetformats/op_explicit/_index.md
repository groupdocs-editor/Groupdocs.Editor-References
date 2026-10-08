---
title: "op_Explicit"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Преобразует строку, представляющую расширение файла, в объект SpreadsheetFormatsgroupdocs.editor.formats/spreadsheetformats."
type: docs
weight: 180
url: /ru/net/groupdocs.editor.formats/spreadsheetformats/op_explicit/
---
## SpreadsheetFormats Explicit operator

Преобразует строку, представляющую расширение файла, в объект [`SpreadsheetFormats`](../../spreadsheetformats).

```csharp
public static explicit operator SpreadsheetFormats(string extension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| расширение | String | Расширение файла для преобразования. Если расширение содержит несколько точек, используется часть после последней точки. |

### Возвращаемое значение

Объект [`SpreadsheetFormats`](../../spreadsheetformats), соответствующий указанному расширению файла.

### Исключения

| исключение | условие |
| --- | --- |
| [SpreadsheetFormats](../../spreadsheetformats) | Выбрасывается, когда указанное расширение файла равно null. |

### См. также

* class [SpreadsheetFormats](../../spreadsheetformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
