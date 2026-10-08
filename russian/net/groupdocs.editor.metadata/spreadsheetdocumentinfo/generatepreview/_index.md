---
title: "GeneratePreview"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт и возвращает предварительный просмотр выбранного листа в виде SVG‑изображения"
type: docs
weight: 60
url: /ru/net/groupdocs.editor.metadata/spreadsheetdocumentinfo/generatepreview/
---
## SpreadsheetDocumentInfo.GeneratePreview method

Создаёт и возвращает предварительный просмотр выбранного листа в виде SVG‑изображения

```csharp
public SvgImage GeneratePreview(int worksheetIndex)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | Int32 | Индекс нужного листа, начиная с 0. Не может быть меньше 0 и не может превышать количество листов в этой таблице. |

### Возвращаемое значение

SVG‑изображение как ненулевой экземпляр класса [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Указанный *worksheetIndex* меньше 0 или больше количества листов в этой таблице. |

### См. также

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [SpreadsheetDocumentInfo](../../spreadsheetdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
