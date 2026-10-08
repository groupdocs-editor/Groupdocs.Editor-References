---
title: "Ratio"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет тип данных CSS ratio, который используется для описания соотношений сторон в медиазапросах и для растровых изображений, обозначая пропорцию между двумя безразмерными значениями, называемыми числителем и знаменателем. Неизменяемая структура."
type: docs
weight: 250
url: /ru/net/groupdocs.editor.htmlcss.css.datatypes/ratio/
---
## Ratio structure

Представляет тип данных CSS "ratio", который используется для описания соотношений сторон в медиа‑запросах и для растровых изображений, обозначая пропорцию между двумя безразмерными значениями, называемыми "numerator" и "denominator". Неизменяемая структура.

```csharp
public struct Ratio : ICloneable, ICssDataType, IEquatable<Ratio>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Denominator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/denominator) { get; } | Возвращает знаменатель этого отношения |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/isdefault) { get; } | Определяет, имеет ли это отношение значение по умолчанию или является \"1/1\" (единственное). |
| [Numerator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/numerator) { get; } | Возвращает числитель этого отношения |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../groupdocs.editor.htmlcss.css.datatypes/ratio/create)(ushort, ushort) | Создаёт и возвращает один экземпляр Ratio из указанных числителя и знаменателя |
| [Calculate](../../groupdocs.editor.htmlcss.css.datatypes/ratio/calculate)() | Вычисляет и возвращает это отношение как одно число с плавающей точкой |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/ratio/clone)() | Возвращает полную копию этого отношения |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals_1)(object) | Определяет, равен ли этот экземпляр указанному неконвертированному объекту, который предположительно является другим экземпляром \"Ratio\" |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals)(Ratio) | Определяет, равен ли этот экземпляр указанному экземпляру \"Ratio\" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/ratio/gethashcode)() | Возвращает хеш-код для данного экземпляра, который не может быть изменён в течение его жизни |
| [GetInverseRatio](../../groupdocs.editor.htmlcss.css.datatypes/ratio/getinverseratio)() | Создаёт и возвращает обратное (взаимное) отношение для этого отношения |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/serializedefault)() | Сериализует это отношение в строку и возвращает её |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/ratio/tostring)() | Возвращает строковое представление этого отношения; то же, что и \"SerializeDefault()\" |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_equality) | Сравнивает два отношения и возвращает логическое значение, указывающее, совпадают ли они. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_inequality) | Сравнивает два отношения и возвращает логическое значение, указывающее, не совпадают ли они. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Single](../../groupdocs.editor.htmlcss.css.datatypes/ratio/single) | Единственное значение отношения по умолчанию 1/1 |

### Замечания

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

### См. также

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
