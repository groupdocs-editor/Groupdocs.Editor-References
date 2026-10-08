---
title: "IImageResource"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет ресурс изображения любого типа: растровый или векторный"
type: docs
weight: 470
url: /ru/net/groupdocs.editor.htmlcss.resources.images/iimageresource/
---
## IImageResource interface

Представляет ресурс изображения любого типа, растрового или векторного

```csharp
public interface IImageResource : IHtmlResource, IImage
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/iimageresource/aspectratio) { get; } | В реализации тип должен возвращать соотношение сторон конкретного изображения независимо от его типа. Как векторные, так и растровые изображения имеют внутреннее соотношение сторон между шириной и высотой. |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images/iimageresource/lineardimensions) { get; } | В реализации тип должен возвращать линейные размеры изображения. Для растровых изображений это внутренние размеры в пикселях. Векторные изображения, напротив, не имеют фиксированных размеров, но их метаданные могут содержать некоторые базовые размеры в различных единицах измерения. |
| [Type](../../groupdocs.editor.htmlcss.resources.images/iimageresource/type) { get; } | В реализации тип должен возвращать тип конкретного изображения как экземпляр конкретного ImageType, который инкапсулирует всю типо-специфичную информацию |

### Замечания

https://developer.mozilla.org/en-US/docs/Web/CSS/image

### См. также

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IImage](../iimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
