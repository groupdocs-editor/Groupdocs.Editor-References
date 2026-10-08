---
title: "op_Explicit"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Преобразует строку, представляющую расширение файла, в объект EmailFormatsgroupdocs.editor.formats/emailformats."
type: docs
weight: 150
url: /ru/net/groupdocs.editor.formats/emailformats/op_explicit/
---
## EmailFormats Explicit operator

Преобразует строку, представляющую расширение файла, в объект [`EmailFormats`](../../emailformats).

```csharp
public static explicit operator EmailFormats(string extension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| расширение | String | Расширение файла для преобразования. Если расширение содержит несколько точек, используется часть после последней точки. |

### Возвращаемое значение

Объект [`EmailFormats`](../../emailformats), соответствующий указанному расширению файла.

### Исключения

| исключение | условие |
| --- | --- |
| [EmailFormats](../../emailformats) | Выбрасывается, когда указанное расширение файла равно null. |

### См. также

* class [EmailFormats](../../emailformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
