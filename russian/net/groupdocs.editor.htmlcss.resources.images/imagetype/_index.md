---
title: "ImageType"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет один поддерживаемый формат типа изображения, поддерживающий как растровые, так и векторные форматы"
type: docs
weight: 480
url: /ru/net/groupdocs.editor.htmlcss.resources.images/imagetype/
---
## ImageType structure

Представляет один поддерживаемый тип изображения (формат), поддерживает как растровые, так и векторные форматы

```csharp
public struct ImageType : IEquatable<ImageType>, IResourceType
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [Bmp](../../groupdocs.editor.htmlcss.resources.images/imagetype/bmp) { get; } | Тип изображения BMP |
| static [Emf](../../groupdocs.editor.htmlcss.resources.images/imagetype/emf) { get; } | Тип векторного изображения EMF (Enhanced MetaFile) |
| static [Gif](../../groupdocs.editor.htmlcss.resources.images/imagetype/gif) { get; } | Тип изображения GIF |
| static [Icon](../../groupdocs.editor.htmlcss.resources.images/imagetype/icon) { get; } | Тип изображения ICON |
| static [Jpeg](../../groupdocs.editor.htmlcss.resources.images/imagetype/jpeg) { get; } | Тип изображения JPEG |
| static [Png](../../groupdocs.editor.htmlcss.resources.images/imagetype/png) { get; } | Тип изображения PNG |
| static [Svg](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) { get; } | Тип векторного изображения SVG |
| static [Tiff](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) { get; } | Тип растрового изображения TIFF (Tagged Image File Format) |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.images/imagetype/undefined) { get; } | Неопределённый тип изображения — специальное значение, которое обычно не должно возникать |
| static [Wmf](../../groupdocs.editor.htmlcss.resources.images/imagetype/wmf) { get; } | Тип векторного изображения WMF (Windows MetaFile) |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/fileextension) { get; } | Расширение файла (без начальной точки) конкретного типа изображения в нижнем регистре. Для типа Undefined возвращает строку 'unsefined'. |
| [FormalName](../../groupdocs.editor.htmlcss.resources.images/imagetype/formalname) { get; } | Возвращает официальное название этого формата изображения. Никогда не возвращает NULL. Если экземпляр не повреждён, исключение не выбрасывается. |
| [IsVector](../../groupdocs.editor.htmlcss.resources.images/imagetype/isvector) { get; } | Указывает, является ли данный формат векторным (true) или растровым (false) |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/mimecode) { get; } | Код MIME конкретного типа изображения в виде строки. Для типа Undefined возвращает строку 'unsefined'. |

## Методы

| Имя | Описание |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefromfilenamewithextension)(string) | Возвращает значение ImageType, эквивалентное расширению имени файла, извлечённому из указанного имени файла |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefrommime)(string) | Возвращает значение ImageType, эквивалентное указанному коду MIME |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals)(ImageType) | Определяет, равен ли данный экземпляр указанному экземпляру "ImageType" |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals_1)(object) | Определяет, равен ли данный экземпляр указанному неконвертированному объекту, который предположительно является другим экземпляром "ImageType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/gethashcode)() | Возвращает хеш‑код, представляющий собой неизменяемое число для данного конкретного экземпляра |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/imagetype/tostring)() | Возвращает свойство FormalName |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_equality) | Определяет, равны ли два конкретных экземпляра ImageType |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_inequality) | Определяет, не равны ли два конкретных экземпляра ImageType |

### См. также

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
