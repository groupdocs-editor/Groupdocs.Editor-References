---
title: Ratio
second_title: Справочник по API GroupDocs.Editor для .NET
description: Представляет тип данных CSS ratio который используется для описания соотношений сторон в медиазапросах и для растровых изображений путем обозначения пропорции между двумя безразмерными значениями называемыми числителем и знаменателем. Неизменная структура.
type: docs
weight: 280
url: /ru/net/groupdocs.editor.htmlcss.css.datatypes/ratio/
---
## Ratio structure

Представляет тип данных CSS «ratio», который используется для описания соотношений сторон в медиа-запросах и для растровых изображений путем обозначения пропорции между двумя безразмерными значениями, называемыми «числителем» и «знаменателем». Неизменная структура.

```csharp
public struct Ratio : ICloneable, ICssDataType, IEquatable<Ratio>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Denominator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/denominator) { get; } | Возвращает знаменатель этого отношения |
| [Numerator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/numerator) { get; } | Возвращает числитель этого отношения |

## Методы

| Имя | Описание |
| --- | --- |
| static [Create](../../groupdocs.editor.htmlcss.css.datatypes/ratio/create)(ushort, ushort) | Создает и возвращает один экземпляр Ratio из указанных числителя и знаменателя |
| [Calculate](../../groupdocs.editor.htmlcss.css.datatypes/ratio/calculate)() | Вычисляет и возвращает это отношение как одно число с плавающей запятой |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/ratio/clone)() | Возвращает полную копию этого ratio |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals_1)(object) | Определяет, равен ли этот экземпляр указанному неприведенному объекту, который предположительно является другим "Ratio" instance |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals)(Ratio) | Определяет, равен ли этот экземпляр заданному «Отношению» instance |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/ratio/gethashcode)() | Возвращает хэш-код для этого экземпляра, который нельзя изменить в течение всего срока его службы |
| [GetInverseRatio](../../groupdocs.editor.htmlcss.css.datatypes/ratio/getinverseratio)() | Генерирует и возвращает обратное (обратное) отношение для этого отношения |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/serializedefault)() | Сериализирует это соотношение в строку и возвращает it |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/ratio/tostring)() | Возвращает строковое представление этого соотношения; то же, что и "SerializeDefault()" |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_equality) | Сравнивает два соотношения и возвращает логическое значение, указывающее, совпадают ли они. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_inequality) | Сравнивает два соотношения и возвращает логическое значение, указывающее, не совпадают ли они. |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Single](../../groupdocs.editor.htmlcss.css.datatypes/ratio/single) | Одно соотношение по умолчанию 1/1 |

### Примечания

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

### Смотрите также

* interface [ICssDataType](../icssdatatype)
* пространство имен [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* сборка [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
