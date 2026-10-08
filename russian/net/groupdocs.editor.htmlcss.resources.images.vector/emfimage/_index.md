---
title: "EmfImage"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет одно векторное изображение в формате Enhanced Metafile (EMF) с его метаданными и дополнительными методами"
type: docs
weight: 560
url: /ru/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
## EmfImage class

Представляет один векторный образ в формате Enhanced Metafile (EMF) вместе с его метаданными и дополнительными методами

```csharp
public sealed class EmfImage : MetaImageBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfImage](emfimage#constructor)(string, Stream) | Создаёт новый экземпляр EmfImage из содержимого, представленного в виде потока байтов, и с указанным именем |
| [EmfImage](emfimage#constructor_1)(string, string) | Создаёт новый экземпляр EmfImage из содержимого, представленного в виде строки, закодированной в base64, и с указанным именем |

## Свойства

| Имя | Описание |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Возвращает соотношение сторон этого векторного изображения |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/bytecontent) { get; } | Возвращает содержимое этого EMF‑изображения в виде бинарного потока |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Возвращает корректное имя файла этого векторного изображения, состоящее из имени и расширения. Теоретически может отличаться от имени. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Определяет, освобождено ли это растровое изображение (`true`) или нет (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Возвращает линейные размеры этого векторного изображения (ширина и высота) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Возвращает имя этого векторного изображения. Обычно не содержит расширения файла и теоретически может отличаться от имени файла. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/textcontent) { get; } | Возвращает содержимое этого EMF‑изображения в виде обычного текста |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/type) { get; } | Возвращает ImageType.Emf |

## Методы

| Имя | Описание |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/dispose)() | Освобождает ресурсы этого EMF‑изображения, удаляя его содержимое и делая большинство его методов и свойств неработоспособными. |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Проверяет данный экземпляр на равенство ссылки с указанным. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/save)(string) | Сохраняет это EMF‑изображение в файл |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetopng)(Stream) | Сохраняет это векторное EMF‑изображение в растровое PNG‑изображение |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetosvg)(Stream) | Сохраняет это векторное изображение EMF в векторное изображение SVG |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid)(Stream) | Проверяет, является ли указанный поток действительным изображением EMF |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid_1)(string) | Проверяет, является ли указанная строка, закодированная в base64, действительным изображением EMF |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Событие, которое происходит, когда это растровое изображение освобождается |

### См. также

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
