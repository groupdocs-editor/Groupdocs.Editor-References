---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет типы линий оформления текста underline underscore overline и linethrough strikethrough."
type: docs
weight: 290
url: /ru/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

Представляет типы линии текстового декора: подчеркивание (нижнее подчеркивание), надчеркивание и зачеркивание (перечёркивание)

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | Указывает, имеет ли данный экземпляр начальное значение — None. |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | Указывает, включено ли line-through (strikethrough). |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | Указывает, включено ли overline. |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | Указывает, включено ли underline (underscore). |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | Возвращает значение всех флагов в данном экземпляре в виде текста. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | Создаёт и возвращает экземпляр [`TextDecorationLineType`](../textdecorationlinetype) с флагами, определёнными указанными параметрами. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | Указывает, равен ли этот экземпляр [`TextDecorationLineType`](../textdecorationlinetype) указанному неприведенному |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | Указывает, равен ли этот экземпляр [`TextDecorationLineType`](../textdecorationlinetype) указанному |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | Возвращает хеш-код этого экземпляра |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | Возвращает значение всех флагов в данном экземпляре в виде текста. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | Пытается разобрать указанную строку и вернуть действительный экземпляр [`TextDecorationLineType`](../textdecorationlinetype) |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | Объединяет (сливает) два указанных типа линий и создает новый результирующий тип линии, где флаги объединены (union) |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | Возвращает пересечение между первым и вторым типами линий, где включены только те флаги, которые одновременно включены в обоих операндах. Имеет наивысший приоритет среди всех операторов (выше, чем union и difference) |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | Проверяет, равны ли два значения "TextDecorationLineType" |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | Преобразует конкретный Byte (8‑битный октет) в соответствующий [`TextDecorationLineType`](../textdecorationlinetype), бросает исключение, если приведение недействительно (2 оператора) |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | Проверяет, не равны ли два значения "TextDecorationLineType" |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | Вычитает второй указанный тип линии из первого указанного типа линии и создает новый результирующий тип линии, в котором присутствуют только те флаги из первого операнда, которые не найдены во втором операнде (difference) |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | Каждая строка текста имеет линию посередине. |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | Не создает текстовое оформление. Начальное значение. |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | Каждая строка текста имеет линию над ней. |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | Каждая строка текста подчеркнута. |

### Замечания

Неизменяемая структура. Похожа на https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

### См. также

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
