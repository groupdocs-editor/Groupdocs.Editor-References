---
title: "op_Explicit"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Преобразует строку, представляющую расширение файла, в объект TextualFormatsgroupdocs.editor.formats/textualformats."
type: docs
weight: 100
url: /ru/net/groupdocs.editor.formats/textualformats/op_explicit/
---
## TextualFormats Explicit operator

Преобразует строку, представляющую расширение файла, в объект [`TextualFormats`](../../textualformats).

```csharp
public static explicit operator TextualFormats(string extension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| расширение | String | Расширение файла для преобразования. Если расширение содержит несколько точек, используется часть после последней точки. |

### Возвращаемое значение

Объект [`TextualFormats`](../../textualformats), соответствующий указанному расширению файла.

### Исключения

| исключение | условие |
| --- | --- |
| [TextualFormats](../../textualformats) | Выбрасывается, когда указанное расширение файла равно null. |

### См. также

* class [TextualFormats](../../textualformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
