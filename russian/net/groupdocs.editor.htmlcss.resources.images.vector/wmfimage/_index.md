---
title: "WmfImage"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет одно векторное изображение в формате WMF Windows MetaFile с его метаданными и дополнительными методами"
type: docs
weight: 600
url: /ru/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
## WmfImage class

Представляет один векторный образ в формате WMF (Windows MetaFile) вместе с его метаданными и дополнительными методами

```csharp
public sealed class WmfImage : MetaImageBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WmfImage](wmfimage#constructor)(string, Stream) | Создаёт новый экземпляр WmfImage из содержимого, представленного в виде потока байтов, и с указанным именем |
| [WmfImage](wmfimage#constructor_1)(string, string) | Создаёт новый экземпляр WmfImage из содержимого, представленного в виде строки, закодированной в base64, и с указанным именем |

## Свойства

| Имя | Описание |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Возвращает соотношение сторон этого векторного изображения |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/bytecontent) { get; } | Возвращает содержимое этого WMF‑изображения в виде бинарного потока |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Возвращает корректное имя файла этого векторного изображения, состоящее из имени и расширения. Теоретически может отличаться от имени. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Определяет, освобождено ли это растровое изображение (`true`) или нет (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Возвращает линейные размеры этого векторного изображения (ширина и высота) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Возвращает имя этого векторного изображения. Обычно не содержит расширения файла и теоретически может отличаться от имени файла. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/textcontent) { get; } | Возвращает содержимое этого WMF‑изображения в виде обычного текста |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/type) { get; } | Возвращает ImageType.Wmf |

## Методы

| Имя | Описание |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/dispose)() | Освобождает ресурсы этого WMF‑изображения, удаляя его содержимое и делая большинство его методов и свойств неработоспособными |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Проверяет данный экземпляр на равенство ссылки с указанным. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/save)(string) | Сохраняет это WMF‑изображение в файл |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetopng)(Stream) | Сохраняет это векторное WMF‑изображение в растровое PNG‑изображение |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetosvg)(Stream) | Сохраняет это векторное WMF‑изображение в векторное SVG‑изображение |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid)(Stream) | Проверяет, является ли указанный поток действительным WMF‑изображением |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid_1)(string) | Проверяет, является ли указанная строка, закодированная в base64, действительным WMF‑изображением |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Событие, которое происходит, когда это растровое изображение освобождается |

### См. также

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
