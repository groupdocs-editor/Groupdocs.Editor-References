---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Базовый класс для любого поддерживаемого растрового изображения с фиксированными именем, размерами, соотношением сторон, типом, размером и содержимым"
type: docs
weight: 540
url: /ru/net/groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
## RasterImageResourceBase class

Базовый класс для любого поддерживаемого растрового изображения с фиксированным именем, размерами, соотношением сторон, типом, размером и содержимым.

```csharp
public abstract class RasterImageResourceBase : IImageResource
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | Возвращает соотношение сторон этого изображения как отношение ширины к высоте |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | Возвращает содержимое этого растрового изображения в виде потока байтов |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | Возвращает корректное имя файла этого растрового изображения, которое состоит из имени и расширения. Теоретически может отличаться от имени. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | Определяет, освобождён ли этот растровый образ или нет |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | Возвращает длину файла этого растрового изображения в байтах |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | Возвращает линейные размеры этого растрового изображения (ширина и высота) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | Возвращает имя этого растрового изображения. Обычно не содержит расширения файла и теоретически может отличаться от имени файла. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | Возвращает содержимое этого растрового изображения в виде строки, закодированной в base64 |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/type) { get; } | В реализующем типе следует возвращать информацию о типе растрового изображения |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Освобождает ресурсы этого растрового изображения, освобождая его содержимое и делая большинство методов и свойств нерабочими |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals#equals)(IHtmlResource) | Проверяет данный экземпляр на равенство ссылки с указанным. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Сохраняет это растровое изображение в указанный файл |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Событие, которое происходит, когда это растровое изображение освобождается |

### См. также

* interface [IImageResource](../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
