---
title: "FromStartPageWithCount"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт диапазон страниц, который начинается с указанного номера страницы и имеет заданное количество страниц или неограниченное количество страниц до конца"
type: docs
weight: 50
url: /ru/net/groupdocs.editor.options/pagerange/fromstartpagewithcount/
---
## PageRange.FromStartPageWithCount method

Создаёт диапазон страниц, начинающийся с указанного номера страницы и содержащий указанное количество страниц, либо неограниченное количество страниц (до конца).

```csharp
public static PageRange FromStartPageWithCount(ushort startPageNumber, ushort pageCount)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startPageNumber | UInt16 | Номер страницы, с которой начинается диапазон страниц, включительно. Номера страниц начинаются с 1, поэтому они должны быть строго больше нуля |
| pageCount | UInt16 | Количество страниц, должно быть строго больше нуля. Если ноль — это означает все страницы до конца документа |

### Возвращаемое значение

Новый экземпляр PageRange

### См. также

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
