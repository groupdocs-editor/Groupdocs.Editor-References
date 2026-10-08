---
title: "op_Explicit"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Преобразует строку, представляющую расширение файла, в объект PresentationFormatsgroupdocs.editor.formats/presentationformats."
type: docs
weight: 150
url: /ru/net/groupdocs.editor.formats/presentationformats/op_explicit/
---
## PresentationFormats Explicit operator

Преобразует строку, представляющую расширение файла, в объект [`PresentationFormats`](../../presentationformats).

```csharp
public static explicit operator PresentationFormats(string extension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| расширение | String | Расширение файла для преобразования. Если расширение содержит несколько точек, используется часть после последней точки. |

### Возвращаемое значение

Объект [`PresentationFormats`](../../presentationformats), соответствующий указанному расширению файла.

### Исключения

| исключение | условие |
| --- | --- |
| [PresentationFormats](../../presentationformats) | Выбрасывается, когда указанное расширение файла равно null. |

### См. также

* class [PresentationFormats](../../presentationformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
