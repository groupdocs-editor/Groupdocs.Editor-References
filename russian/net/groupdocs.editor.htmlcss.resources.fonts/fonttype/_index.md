---
title: "FontType"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет один поддерживаемый тип шрифта"
type: docs
weight: 360
url: /ru/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
## FontType structure

Представляет один поддерживаемый тип шрифта

```csharp
public struct FontType : IEquatable<FontType>, IResourceType
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [Eot](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/eot) { get; } | Представляет тип шрифта EOT (Embedded OpenType) |
| static [Otf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/otf) { get; } | Представляет тип шрифта OTF (OpenType Font) |
| static [Ttc](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttc) { get; } | Представляет шрифт TrueType Collection (TTC) |
| static [Ttf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttf) { get; } | Представляет тип шрифта TTF (TrueType Font) |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/undefined) { get; } | Специальное значение, обозначающее неопределённый, неизвестный или неподдерживаемый ресурс шрифта |
| static [Woff](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff) { get; } | Представляет тип шрифта WOFF (Web Open Font Format) |
| static [Woff2](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff2) { get; } | Представляет тип шрифта WOFF2 (Web Open Font Format version 2) |
| [CssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/cssname) { get; } | Возвращает совместимое с CSS имя этого типа шрифта, которое используется в директиве @font-face |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fileextension) { get; } | Расширение имени файла (без символа точки) для этого типа шрифта |
| [FontFormat](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fontformat) { get; } | Формат шрифта для формата @font-face |
| [FormalName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/formalname) { get; } | Возвращает официальное название этого типа шрифта |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/mimecode) { get; } | MIME‑код конкретного типа шрифта |

## Методы

| Имя | Описание |
| --- | --- |
| static [GetFirstDefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined)(params FontType[]) | Возвращает первый тип шрифта из указанного набора, который не имеет значения "Undefined", или тип шрифта "Undefined" в противном случае (когда все элементы имеют значение "Undefined") |
| static [ParseFromCssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromcssname)(string) | Возвращает значение FontType, которое эквивалентно указанному совместимому с CSS имени типа шрифта |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromfilenamewithextension)(string) | Возвращает значение FontType, которое эквивалентно расширению имени файла, извлечённому из указанного имени файла |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefrommime)(string) | Возвращает значение FontType, которое эквивалентно указанному MIME‑коду |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals)(FontType) | Определяет, равен ли данный экземпляр указанному экземпляру "FontType" |
| override [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals_1)(object) | Определяет, равен ли данный экземпляр указанному неконвертированному объекту, который предположительно является другим экземпляром "FontType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/gethashcode)() | Возвращает хеш‑код, который является постоянным числом для этого конкретного типа значения |
| [operator ==](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_equality) | Проверяет, равны ли два значения "FontType" |
| [operator !=](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_inequality) | Проверяет, не равны ли два значения "FontType" |

### См. также

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
