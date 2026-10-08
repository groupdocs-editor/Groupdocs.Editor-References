---
title: "FontSize"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет размер шрифта как специальную единицу или значение длины, которое указывает размер шрифта, исторически равный ширине заглавной буквы M."
type: docs
weight: 260
url: /ru/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Представляет размер шрифта как специальную единицу или значение длины, которое определяет размер шрифта (исторически — ширина заглавной буквы \"M\").

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Указывает, определён ли этот размер шрифта абсолютным размером в виде ключевого слова, основанного на размере шрифта по умолчанию у пользователя (который является средним). |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Указывает, имеет ли этот размер шрифта начальное значение (Средний). |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Указывает, определён ли этот размер шрифта значением [`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length). |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Указывает, определён ли этот размер шрифта относительным размером в виде ключевого слова. Шрифт будет больше или меньше относительно размера шрифта родительского элемента, примерно по соотношению, используемому для разделения абсолютных ключевых слов. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Значение длины, если этот размер шрифта был определён с его помощью, иначе генерируется исключение. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Возвращает значение этого размера шрифта в виде строки. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Создаёт размер шрифта из указанной длины. |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Определяет, равен ли данный экземпляр размера шрифта указанному. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Определяет, равен ли данный экземпляр размера шрифта указанному без приведения типов. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Возвращает хеш‑код для этого экземпляра |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Пытается распознать указанное ключевое слово как корректное значение ключевого слова свойства 'font-size' и возвращает его при успехе или NULL при неудаче. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Проверяет, равны ли два значения \"FontSize\". |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Проверяет, не равны ли два значения \"FontSize\". |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | Обычно большой абсолютный размер. |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Более крупный относительный размер — шрифт будет больше относительно размера шрифта родительского элемента, примерно по соотношению, используемому для разделения вышеуказанных абсолютных ключевых слов. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Средний размер. Начальное значение. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | Обычно маленький абсолютный размер. |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Меньший относительный размер — шрифт будет меньше относительно размера шрифта родительского элемента, примерно по соотношению, используемому для разделения вышеуказанных абсолютных ключевых слов. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | Умеренно большой абсолютный размер. |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | Умеренно маленький абсолютный размер. |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | Очень большой абсолютный размер. |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | Очень маленький абсолютный размер |

### См. также

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
