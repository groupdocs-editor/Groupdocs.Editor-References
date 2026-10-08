---
title: "MetaImageBase"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Базовый абстрактный класс для форматов изображений WMF и EMF"
type: docs
weight: 570
url: /ru/net/groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
## MetaImageBase class

Базовый абстрактный класс для форматов изображений WMF и EMF

```csharp
public abstract class MetaImageBase : VectorImageResourceBase
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Возвращает соотношение сторон этого векторного изображения |
| abstract [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/bytecontent) { get; } | В реализующем типе следует вернуть содержимое этого векторного изображения в виде потока байтов |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Возвращает корректное имя файла этого векторного изображения, состоящее из имени и расширения. Теоретически может отличаться от имени. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Определяет, освобождено ли это растровое изображение (`true`) или нет (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Возвращает линейные размеры этого векторного изображения (ширина и высота) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Возвращает имя этого векторного изображения. Обычно не содержит расширения файла и теоретически может отличаться от имени файла. |
| abstract [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/textcontent) { get; } | В реализующем типе следует вернуть содержимое этого векторного изображения в текстовой форме: base64‑закодированный XML, соответствующий типу изображения |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/type) { get; } | В реализующем типе следует вернуть информацию о типе векторного изображения |

## Методы

| Имя | Описание |
| --- | --- |
| abstract [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/dispose)() | В реализующем типе следует освободить этот экземпляр |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Проверяет данный экземпляр на равенство ссылки с указанным. |
| abstract [Save](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/save)(string) | В реализующем типе следует сохранить это изображение на диск по указанному пути |
| abstract [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/savetopng)(Stream) | В реализующем типе следует сохранить текущее векторное изображение в растровый формат PNG в указанный поток байтов |
| abstract [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/savetosvg)(Stream) | При реализации типа WMF или EMF следует сохранять текущий векторный мета‑изображение в векторный формат SVG в указанный поток байтов |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Событие, которое происходит, когда это растровое изображение освобождается |

### Замечания

Этот абстрактный класс наследуется классами [`WmfImage`](../wmfimage) и [`EmfImage`](../emfimage)

### См. также

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
