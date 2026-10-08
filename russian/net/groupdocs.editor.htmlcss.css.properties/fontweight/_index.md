---
title: "FontWeight"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Свойство FontWeight задает вес или жирность шрифта. Доступные веса зависят от текущего установленного fontfamily."
type: docs
weight: 280
url: /ru/net/groupdocs.editor.htmlcss.css.properties/fontweight/
---
## FontWeight structure

Свойство font-weight задаёт толщину (или жирность) шрифта. Доступные толщины зависят от текущего семейства шрифтов.

```csharp
public struct FontWeight : IEquatable<FontWeight>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.properties/fontweight/isabsolute) { get; } | Указывает, сохраняет ли данный экземпляр font-weight абсолютное значение веса (жирности) шрифта в виде целого числа. |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontweight/isinitial) { get; } | Указывает, имеет ли этот размер шрифта начальное значение (Средний). |
| [IsRelative](../../groupdocs.editor.htmlcss.css.properties/fontweight/isrelative) { get; } | Указывает, сохраняет ли данный экземпляр font-weight относительное значение веса (жирности) шрифта — по сравнению с жирностью родительского элемента. |
| [Number](../../groupdocs.editor.htmlcss.css.properties/fontweight/number) { get; } | Возвращает число — целое значение от 1 до 1000 включительно, описывающее жирность шрифта, или генерирует исключение, если текущая жирность не абсолютна, а относительна. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontweight/value) { get; } | Возвращает значение этого font-weight в виде строки. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromNumber](../../groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber)(ushort) | Создаёт font-weight из указанного числа. |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals)(FontWeight) | Определяет, равны ли указанные экземпляры FontWeight. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals_1)(object) | Определяет, равен ли данный экземпляр FontWeight указанному неконвертированному. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontweight/gethashcode)() | Возвращает хеш‑код для этого экземпляра |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontweight/tryparse)(string, out FontWeight) | Пытается разобрать указанную строку и вернуть корректный экземпляр FontWeight при успехе. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_equality) | Проверяет, равны ли два значения \"FontWeight\". |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_inequality) | Проверяет, не равны ли два значения \"FontWeight\". |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Bold](../../groupdocs.editor.htmlcss.css.properties/fontweight/bold) | Жирный вес шрифта. То же, что 700. |
| static readonly [Bolder](../../groupdocs.editor.htmlcss.css.properties/fontweight/bolder) | Относительный вес шрифта, на один уровень тяжелее, чем у родительского элемента. |
| static readonly [Lighter](../../groupdocs.editor.htmlcss.css.properties/fontweight/lighter) | Относительный вес шрифта, на один уровень легче, чем у родительского элемента. |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontweight/normal) | Обычный вес шрифта. То же, что 400. |

### См. также

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
