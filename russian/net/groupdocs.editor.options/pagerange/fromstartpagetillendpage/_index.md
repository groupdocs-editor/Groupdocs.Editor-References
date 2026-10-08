---
title: "FromStartPageTillEndPage"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт диапазон страниц, который начинается с указанного номера страницы включительно и продолжается до указанного номера страницы исключительно"
type: docs
weight: 40
url: /ru/net/groupdocs.editor.options/pagerange/fromstartpagetillendpage/
---
## PageRange.FromStartPageTillEndPage method

Создаёт диапазон страниц, начинающийся с указанного номера страницы (включительно) и продолжающийся до указанного номера страницы (исключительно).

```csharp
public static PageRange FromStartPageTillEndPage(ushort startPageNumber, ushort endPageNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startPageNumber | UInt16 | Номер страницы, с которой начинается диапазон страниц, включительно. Номера страниц начинаются с 1, поэтому они должны быть строго больше нуля |
| endPageNumber | UInt16 | Номер страницы, до которой продолжается диапазон страниц, исключительно. Номера страниц начинаются с 1, поэтому они должны быть строго больше нуля и также строго больше *startPageNumber* |

### См. также

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
