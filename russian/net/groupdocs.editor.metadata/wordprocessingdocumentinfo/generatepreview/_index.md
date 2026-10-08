---
title: "GeneratePreview"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Создаёт и возвращает предварительный просмотр выбранной страницы в виде SVG‑изображения"
type: docs
weight: 60
url: /ru/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview/
---
## WordProcessingDocumentInfo.GeneratePreview method

Создаёт и возвращает предварительный просмотр выбранной страницы в виде SVG‑изображения

```csharp
public SvgImage GeneratePreview(int pageIndex)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageIndex | Int32 | Индекс нужной страницы, начиная с 0. Не может быть меньше 0 и не может превышать количество страниц в этом документе WordProcessing. |

### Возвращаемое значение

SVG‑изображение как ненулевой экземпляр класса [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Указанный *pageIndex* меньше 0 или больше количества страниц в этом документе WordProcessing. |

### См. также

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [WordProcessingDocumentInfo](../../wordprocessingdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
