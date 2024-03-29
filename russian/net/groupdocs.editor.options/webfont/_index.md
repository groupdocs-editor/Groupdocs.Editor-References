---
title: WebFont
second_title: Справочник по API GroupDocs.Editor для .NET
description: Представляет настройки шрифта для web
type: docs
weight: 1180
url: /ru/net/groupdocs.editor.options/webfont/
---
## WebFont class

Представляет настройки шрифта для web

```csharp
public sealed class WebFont : ICloneable, IEquatable<WebFont>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Color](../../groupdocs.editor.options/webfont/color) { get; set; } | Цвет шрифта в формате ARGB32 |
| [Line](../../groupdocs.editor.options/webfont/line) { get; set; } | Устанавливает строку или комбинацию строк, применяемую к text |
| [Name](../../groupdocs.editor.options/webfont/name) { get; set; } | Устанавливает имя шрифта. Если не указано, будет использоваться шрифт по умолчанию |
| [Size](../../groupdocs.editor.options/webfont/size) { get; set; } | Устанавливает размер шрифта в абсолютных или относительных единицах |
| [Style](../../groupdocs.editor.options/webfont/style) { get; set; } | Устанавливает, должен ли шрифт быть оформлен обычным, курсивным или наклонным шрифтом из его семейства шрифтов. |
| [Weight](../../groupdocs.editor.options/webfont/weight) { get; set; } | Устанавливает вес (или жирность) шрифта |

## Методы

| Имя | Описание |
| --- | --- |
| [Clone](../../groupdocs.editor.options/webfont/clone)() | Создает и возвращает полную глубокую копию этого[`WebFont`](../webfont) instance |
| override [Equals](../../groupdocs.editor.options/webfont/equals#equals_1)(object) | Определяет, равен ли этот экземпляр WebFont указанному неприведенному объекту object |
| [Equals](../../groupdocs.editor.options/webfont/equals#equals)(WebFont) | Определяет, равен ли этот экземпляр WebFont указанному |

## Другие члены

| Имя | Описание |
| --- | --- |
| [Flags] enum [TextDecorationLine](webfont.textdecorationline) | Виды декоративной линии, которая используется в тексте в элементе, например, подчеркивание, надчеркивание или сквозная линия. Можно совмещать вместе или ни с кем. |

### Смотрите также

* пространство имен [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
