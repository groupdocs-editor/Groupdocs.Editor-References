---
title: "TextType"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет один поддерживаемый тип текстового ресурса"
type: docs
weight: 640
url: /ru/net/groupdocs.editor.htmlcss.resources.textual/texttype/
---
## TextType structure

Представляет один поддерживаемый тип текстового ресурса

```csharp
public struct TextType : IEquatable<TextType>, IResourceType
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [Css](../../groupdocs.editor.htmlcss.resources.textual/texttype/css) { get; } | Тип CSS текстового ресурса |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.textual/texttype/undefined) { get; } | Специальное значение, которое обозначает неопределённый, неизвестный или неподдерживаемый текстовый ресурс |
| static [Xml](../../groupdocs.editor.htmlcss.resources.textual/texttype/xml) { get; } | Тип XML текстового ресурса |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/fileextension) { get; } | Расширение файла (без начального символа точки) конкретного текстового ресурса |
| [FormalName](../../groupdocs.editor.htmlcss.resources.textual/texttype/formalname) { get; } | Возвращает официальное название этого типа текстового ресурса |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/mimecode) { get; } | MIME‑код конкретного типа текстового ресурса |

## Методы

| Имя | Описание |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/parsefromfilenamewithextension)(string) | Возвращает значение TextType, которое эквивалентно расширению имени файла, полученному из указанного имени файла с расширением или из чистого расширения |
| override [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals_1)(object) | Определяет, равен ли этот экземпляр указанному неконвертированному объекту, который предположительно является другим экземпляром "TextType" |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals)(TextType) | Определяет, равен ли этот экземпляр указанному экземпляру "TextType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/gethashcode)() | Возвращает хеш‑код, который является постоянным числом для этого конкретного типа значения |
| [operator ==](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_equality) | Определяет, равны ли два конкретных экземпляра "TextType" |
| [operator !=](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_inequality) | Определяет, не равны ли два конкретных экземпляра "TextType" |

### См. также

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
