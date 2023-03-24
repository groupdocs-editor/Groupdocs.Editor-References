---
title: FontWeight
second_title: Справочник по API GroupDocs.Editor для .NET
description: Свойство Fontweight устанавливает толщину или жирность шрифта. Доступные веса зависят от семейства шрифтов которое установлено в данный момент.
type: docs
weight: 310
url: /ru/net/groupdocs.editor.htmlcss.css.properties/fontweight/
---
## FontWeight structure

Свойство Font-weight устанавливает толщину (или жирность) шрифта. Доступные веса зависят от семейства шрифтов, которое установлено в данный момент.

```csharp
public struct FontWeight : IEquatable<FontWeight>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.properties/fontweight/isabsolute) { get; } | Указывает, хранит ли этот экземпляр font-weight абсолютное значение веса (жирности) шрифта в виде целого числа |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontweight/isinitial) { get; } | Указывает, имеет ли этот размер шрифта начальное значение (Medium) |
| [IsRelative](../../groupdocs.editor.htmlcss.css.properties/fontweight/isrelative) { get; } | Указывает, хранит ли этот экземпляр font-weight относительное значение веса (жирности) шрифта по сравнению с жирностью родительского element |
| [Number](../../groupdocs.editor.htmlcss.css.properties/fontweight/number) { get; } | Возвращает число - целочисленное значение от 1 до 1000 включительно, которое описывает жирность шрифта, или выдает исключение, если текущая жирность не абсолютная, а относительная |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontweight/value) { get; } | Возвращает значение этого шрифта в виде строки |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromNumber](../../groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber)(ushort) | Создает толщину шрифта из указанного числа |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals)(FontWeight) | Определяет, равны ли указанные экземпляры FontWeight |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals_1)(object) | Определяет, равен ли этот экземпляр FontWeight указанному uncasted |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontweight/gethashcode)() | Возвращает хэш-код для этого экземпляра |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontweight/tryparse)(string, out FontWeight) | Пытается проанализировать указанную строку и вернуть действительный экземпляр FontWeight при успешном выполнении |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_equality) | Проверяет, равны ли два значения «FontWeight» |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_inequality) | Проверяет, не равны ли два значения «FontWeight» |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Bold](../../groupdocs.editor.htmlcss.css.properties/fontweight/bold) | Вес полужирного шрифта. То же, что и 700. |
| static readonly [Bolder](../../groupdocs.editor.htmlcss.css.properties/fontweight/bolder) | На один относительный вес шрифта больше, чем у родительского элемента |
| static readonly [Lighter](../../groupdocs.editor.htmlcss.css.properties/fontweight/lighter) | На один относительный вес шрифта легче родительского элемента |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontweight/normal) | Обычный вес шрифта. То же, что и 400. |

### Смотрите также

* пространство имен [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->