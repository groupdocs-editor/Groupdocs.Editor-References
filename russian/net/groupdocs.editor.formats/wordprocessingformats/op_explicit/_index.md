---
title: "op_Explicit"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Преобразует строку, представляющую расширение файла, в объект WordProcessingFormatsgroupdocs.editor.formats/wordprocessingformats."
type: docs
weight: 140
url: /ru/net/groupdocs.editor.formats/wordprocessingformats/op_explicit/
---
## WordProcessingFormats Explicit operator

Преобразует строку, представляющую расширение файла, в объект [`WordProcessingFormats`](../../wordprocessingformats).

```csharp
public static explicit operator WordProcessingFormats(string extension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| расширение | String | Расширение файла для преобразования. Если расширение содержит несколько точек, используется часть после последней точки. |

### Возвращаемое значение

Объект [`WordProcessingFormats`](../../wordprocessingformats), соответствующий указанному расширению файла.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда указанное расширение файла равно null. |

### См. также

* class [WordProcessingFormats](../../wordprocessingformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
