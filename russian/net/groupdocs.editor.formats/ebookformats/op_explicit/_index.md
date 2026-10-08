---
title: "op_Explicit"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Преобразует строку, представляющую расширение файла, в объект EBookFormatsgroupdocs.editor.formats/ebookformats."
type: docs
weight: 60
url: /ru/net/groupdocs.editor.formats/ebookformats/op_explicit/
---
## EBookFormats Explicit operator

Преобразует строку, представляющую расширение файла, в объект [`EBookFormats`](../../ebookformats).

```csharp
public static explicit operator EBookFormats(string extension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| расширение | String | Расширение файла для преобразования. Если расширение содержит несколько точек, используется часть после последней точки. |

### Возвращаемое значение

Объект [`EBookFormats`](../../ebookformats), соответствующий указанному расширению файла.

### Исключения

| исключение | условие |
| --- | --- |
| [EBookFormats](../../ebookformats) | Выбрасывается, когда указанное расширение файла равно null. |

### См. также

* class [EBookFormats](../../ebookformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
