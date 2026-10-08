---
title: "ArgbColor"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет одно значение цвета в 32‑битном формате ARGB, 8 бит на канал, включая прозрачность, с конвертерами и сериализаторами"
type: docs
weight: 160
url: /ru/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Представляет одно значение цвета в 32-битном формате ARGB (8 бит на канал, включая прозрачность) с конвертерами и сериализаторами

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Получает альфа‑часть цвета. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Получает альфа‑часть цвета в процентах (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Получает синюю часть цвета. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Получает зелёную часть цвета. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isdefault) { get; } | Указывает, является ли данный экземпляр [`ArgbColor`](../argbcolor) значением по умолчанию (Transparent) — все 4 канала установлены в 0 |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Неинициализированный цвет — все 4 канала установлены в 0. То же, что Default и Transparent. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Указывает, является ли данный экземпляр [`ArgbColor`](../argbcolor) полностью непрозрачным, без прозрачности (его альфа‑канал имеет максимальное значение) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Указывает, является ли данный экземпляр [`ArgbColor`](../argbcolor) полностью прозрачным — его альфа‑канал имеет минимальное (0) значение, поэтому остальные каналы R, G и B не оказывают видимого воздействия. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Указывает, является ли данный экземпляр [`ArgbColor`](../argbcolor) полупрозрачным (не полностью прозрачным, но и не полностью непрозрачным) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Получает красную часть цвета. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Получает значение Int32 цвета. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Создает одно значение [`ArgbColor`](../argbcolor) из указанных каналов Red, Green, Blue, при этом канал Alpha полностью непрозрачный. |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Создает одно значение [`ArgbColor`](../argbcolor) из указанных каналов Red, Green, Blue и Alpha. |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Создает полностью непрозрачный (A=255) цвет из одного значения, которое будет применено ко всем каналам. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Проверяет два цвета [`ArgbColor`](../argbcolor) на равенство. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Проверяет, равен ли другой объект этому экземпляру [`ArgbColor`](../argbcolor). |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Возвращает хеш-код, определяющий текущий цвет. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Сериализует этот экземпляр [`ArgbColor`](../argbcolor) в наиболее подходящую нотацию CSS‑функции в зависимости от прозрачности. |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Сериализует этот экземпляр [`ArgbColor`](../argbcolor) в нотацию CSS‑функции 'rgb'. |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Сериализует этот экземпляр [`ArgbColor`](../argbcolor) в нотацию CSS‑функции 'rgba'. |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | То же, что и [`SerializeDefault`](./serializedefault). |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Сравнивает два цвета и возвращает логическое значение, указывающее, совпадают ли они. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Сравнивает два цвета и возвращает логическое значение, указывающее, не совпадают ли они. |

## Другие члены

| Имя | Описание |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Содержит все "известные цвета", которые имеют фиксированное уникальное имя и значение в стандарте CSS |

### Замечания

Этот тип предназначен для использования в CSS‑операциях (но не ограничивается ими). Подробнее: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### См. также

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
