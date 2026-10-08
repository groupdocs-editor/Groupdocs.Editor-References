---
title: "FontStyle"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Определяет, как шрифт должен быть оформлен: обычный, курсивный или наклонный, из его семейства шрифтов."
type: docs
weight: 270
url: /ru/net/groupdocs.editor.htmlcss.css.properties/fontstyle/
---
## FontStyle structure

Определяет, как шрифт должен быть оформлен: обычный, курсивный или наклонный начертание из его семейства шрифтов.

```csharp
public struct FontStyle
```

## Свойства

| Имя | Описание |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontstyle/isinitial) { get; } | Указывает, имеет ли этот font-style начальное значение (Normal) |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontstyle/value) { get; } | Возвращает значение этого стиля шрифта в виде строки |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals)(FontStyle) | Определяет, равен ли этот экземпляр font-style указанному |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals_1)(object) | Определяет, равен ли этот экземпляр font-style указанному без приведения типов |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontstyle/gethashcode)() | Возвращает хеш‑код для этого экземпляра |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse)(string, out FontStyle) | Пытается распознать указанное ключевое слово как корректное значение ключевого слова 'font-style' и возвращает его при успехе или NULL при неудаче. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_equality) | Проверяет, равны ли два значения "FontStyle" |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_inequality) | Проверяет, не равны ли два значения "FontStyle" |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Italic](../../groupdocs.editor.htmlcss.css.properties/fontstyle/italic) | Выбирает шрифт, классифицированный как курсивный. Если курсивная версия шрифта недоступна, используется версия, классифицированная как наклонная. Если ни одна из них недоступна, стиль имитируется искусственно. |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontstyle/normal) | Выбирает шрифт, классифицированный как обычный в рамках семейства шрифтов. Начальное значение. |
| static readonly [Oblique](../../groupdocs.editor.htmlcss.css.properties/fontstyle/oblique) | Выбирает шрифт, классифицированный как наклонный. Если наклонная версия шрифта недоступна, используется версия, классифицированная как курсивная. Если ни одна из них недоступна, стиль имитируется искусственно. |

### См. также

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
