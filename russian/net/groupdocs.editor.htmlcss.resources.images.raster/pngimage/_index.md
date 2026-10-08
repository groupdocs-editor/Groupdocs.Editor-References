---
title: "PngImage"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет одно изображение в формате PNG Portable Network Graphics с его метаданными и дополнительными методами"
type: docs
weight: 530
url: /ru/net/groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
## PngImage class

Представляет одно изображение в формате PNG (Portable Network Graphics) с его метаданными и дополнительными методами.

```csharp
public sealed class PngImage : RasterImageResourceBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PngImage](pngimage#constructor)(string, Stream) | Создаёт новый экземпляр PngImage из содержимого, представленного в виде байтового потока, и с указанным именем |
| [PngImage](pngimage#constructor_1)(string, string) | Создаёт новый экземпляр PngImage из содержимого, представленного в виде строки, закодированной в base64, и с указанным именем |

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
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/pngimage/type) { get; } | Возвращает ImageType.Png |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Освобождает ресурсы этого растрового изображения, освобождая его содержимое и делая большинство методов и свойств нерабочими |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | Проверяет данный экземпляр на равенство ссылки с указанным. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Сохраняет это растровое изображение в указанный файл |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/pngimage/isvalid#isvalid)(Stream) | Проверяет, является ли указанный поток действительным изображением PNG |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/pngimage/isvalid#isvalid_1)(string) | Проверяет, является ли указанная строка в формате base64 допустимым PNG‑изображением |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Событие, которое происходит, когда это растровое изображение освобождается |

### См. также

* class [RasterImageResourceBase](../rasterimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
