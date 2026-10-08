---
title: "SvgImage"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет одно векторное изображение в формате SVG Scalable Vector Graphics с его метаданными размеров и дополнительными методами сохранения в PNG"
type: docs
weight: 580
url: /ru/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
## SvgImage class

Представляет один векторный образ в формате SVG (Scalable Vector Graphics) с его метаданными (размерами) и дополнительными методами (сохранение в PNG)

```csharp
public sealed class SvgImage : VectorImageResourceBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SvgImage](svgimage#constructor)(string, Stream) | Создаёт новый экземпляр SvgImage из содержимого, представленного в виде байтового потока, и с указанным именем |
| [SvgImage](svgimage#constructor_1)(string, string) | Создаёт новый экземпляр SvgImage из содержимого, представленного в виде обычной строки, и с указанным именем |

## Свойства

| Имя | Описание |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Возвращает соотношение сторон этого векторного изображения |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/bytecontent) { get; } | Возвращает содержимое этого SVG‑изображения в виде бинарного потока с оригинальной позицией |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Возвращает корректное имя файла этого векторного изображения, состоящее из имени и расширения. Теоретически может отличаться от имени. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Определяет, освобождено ли это растровое изображение (`true`) или нет (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Возвращает линейные размеры этого векторного изображения (ширина и высота) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Возвращает имя этого векторного изображения. Обычно не содержит расширения файла и теоретически может отличаться от имени файла. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/textcontent) { get; } | Возвращает содержимое этого SVG‑изображения в виде бинарных данных, закодированных в base64 (не в виде необработанного текста в формате XML) |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/type) { get; } | Возвращает [`Svg`](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) |
| [XmlContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/xmlcontent) { get; } | Возвращает содержимое этого SVG‑изображения в его оригинальном текстовом виде, соответствующем XML |

## Методы

| Имя | Описание |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/dispose)() | Освобождает ресурсы этого растрового изображения, освобождая его содержимое и делая большинство методов и свойств нерабочими |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Проверяет данный экземпляр на равенство ссылки с указанным. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/save)(string) | Сохраняет это SVG‑изображение в файл |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/savetopng)(Stream) | Сохраняет это векторное SVG‑изображение в растровое PNG‑изображение |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/isvalid)(string) | Выполняет поверхностную проверку, является ли указанное текстовое содержимое, соответствующее XML, представлением SVG‑изображения |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Событие, которое происходит, когда это растровое изображение освобождается |

### См. также

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
