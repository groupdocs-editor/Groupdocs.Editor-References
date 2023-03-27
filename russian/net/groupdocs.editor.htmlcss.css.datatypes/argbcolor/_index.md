---
title: ArgbColor
second_title: Справочник по API GroupDocs.Editor для .NET
description: Представляет одно значение цвета в формате ARGB с преобразователями и сериализаторами
type: docs
weight: 190
url: /ru/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Представляет одно значение цвета в формате ARGB с преобразователями и сериализаторами

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Получает альфа-часть цвета. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Получает альфа-часть цвета в процентах (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Получает синюю часть цвета. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Получает зеленую часть цвета. |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Неинициализированный цвет — все 4 канала установлены на 0. То же, что и по умолчанию и прозрачный. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Указывает, является ли это[`ArgbColor`](../argbcolor) экземпляр полностью непрозрачен, без прозрачности (его альфа-канал имеет максимальное значение) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Указывает, является ли это[`ArgbColor`](../argbcolor) Экземпляр полностью прозрачен — его альфа-канал имеет минимальное (0) значение, поэтому другие каналы R, G и B не имеют видимого эффекта. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Указывает, является ли это[`ArgbColor`](../argbcolor) экземпляр полупрозрачный (не полностью прозрачный, но и не полностью непрозрачный) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Получает красную часть цвета. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Получает значение цвета Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Создает один[`ArgbColor`](../argbcolor) значение из указанных каналов Red, Green, Blue, в то время как альфа-канал полностью непрозрачен |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Создает один[`ArgbColor`](../argbcolor) значение из указанных каналов Red, Green, Blue и Alpha |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Создает полностью непрозрачный (A=255) цвет из одного значения, которое будет применяться ко всем каналам |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Проверяет два[`ArgbColor`](../argbcolor) цвета для равенства |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Проверяет, равен ли другой объект этому[`ArgbColor`](../argbcolor) экземпляр. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Возвращает хэш-код, определяющий текущий цвет. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Сериализирует это[`ArgbColor`](../argbcolor)instance в наиболее подходящее обозначение функции CSS в зависимости от translucency |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Сериализирует это[`ArgbColor`](../argbcolor) экземпляр функции CSS 'rgb' notation |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Сериализирует это[`ArgbColor`](../argbcolor) экземпляр CSS-функции 'rgba' notation |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | То же, что и[`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Сравнивает два цвета и возвращает логическое значение, указывающее, совпадают ли они. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Сравнивает два цвета и возвращает логическое значение, указывающее, не совпадают ли они. |

## Другие члены

| Имя | Описание |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Содержит все "известные цвета", которые имеют фиксированное уникальное имя и значение в CSS стандарт |

### Примечания

Этот тип предназначен для использования (но не только) для операций CSS. Подробнее: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Смотрите также

* interface [ICssDataType](../icssdatatype)
* пространство имен [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
