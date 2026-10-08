---
title: "GeneratePreview"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Генерирует и возвращает предварительный просмотр выбранного слайда в виде изображения SVG"
type: docs
weight: 50
url: /ru/net/groupdocs.editor.metadata/presentationdocumentinfo/generatepreview/
---
## PresentationDocumentInfo.GeneratePreview method

Генерирует и возвращает предварительный просмотр выбранного слайда в виде изображения SVG

```csharp
public SvgImage GeneratePreview(int slideIndex)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| slideIndex | Int32 | Индекс нужного слайда, начиная с 0. Не может быть меньше 0 и не может превышать количество слайдов в этой презентации. |

### Возвращаемое значение

SVG‑изображение как ненулевой экземпляр класса [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Указанный *slideIndex* меньше 0 или больше количества слайдов в этой презентации. |

### См. также

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [PresentationDocumentInfo](../../presentationdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
