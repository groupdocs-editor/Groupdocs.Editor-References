---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет базовый класс для семейств форматов, предоставляющий общую функциональность для экземпляров семейств форматов."
type: docs
weight: 60
url: /ru/net/groupdocs.editor.formats.abstraction/formatfamilybase/
---
## FormatFamilyBase class

Представляет базовый класс для семейств форматов, предоставляя общую функциональность для экземпляров семейств форматов.

```csharp
public abstract class FormatFamilyBase : IEquatable<FormatFamilyBase>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Возвращает уникальный идентификатор семейства форматов. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Возвращает название семейства форматов. |

## Методы

| Имя | Описание |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals)(FormatFamilyBase) | Определяет, равен ли этот экземпляр указанному экземпляру [`FormatFamilyBase`](../formatfamilybase). |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals_1)(object) | Определяет, равен ли этот экземпляр указанному экземпляру [`FormatFamilyBase`](../formatfamilybase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | Возвращает хеш‑код текущего объекта. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Возвращает строку, представляющую текущий объект. |
| static [FromName&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromname)(string) | Получает экземпляр указанного типа *T*, имеющий указанное имя. |
| static [FromValue&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue)(int) | Получает экземпляр указанного типа *T*, имеющий указанный идентификатор. |
| static [GetAll&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/getall)() | Получает все экземпляры указанного типа *T*, наследующиеся от [`FormatFamilyBase`](../formatfamilybase). |
| [operator ==](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_equality#op_equality) | Определяет, равны ли два экземпляра [`FormatFamilyBase`](../formatfamilybase). (2 оператора) |
| [explicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit#op_explicit_1) | Преобразует строку, представляющую название семейства формата, в объект [`FormatFamilyBase`](../formatfamilybase). (2 оператора) |
| [implicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_implicit#op_implicit) | Неявно преобразует экземпляр [`FormatFamilyBase`](../formatfamilybase) в целое число. (2 оператора) |
| [operator !=](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_inequality#op_inequality) | Определяет, не равны ли два экземпляра [`FormatFamilyBase`](../formatfamilybase). (2 оператора) |

### Замечания

Этот класс абстрактный и должен быть унаследован производным классом, который задаёт фактические детали семейства формата.

### См. также

* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
