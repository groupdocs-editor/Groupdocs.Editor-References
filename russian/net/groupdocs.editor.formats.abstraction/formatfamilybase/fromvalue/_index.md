---
title: "FromValue"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Получает экземпляр указанного типа T, имеющий указанный идентификатор."
type: docs
weight: 70
url: /ru/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue/
---
## FormatFamilyBase.FromValue&lt;T&gt; method

Получает экземпляр указанного типа *T*, имеющий указанный идентификатор.

```csharp
public static T FromValue<T>(int value)
    where T : FormatFamilyBase
```

| Параметр | Описание |
| --- | --- |
| T | Тип семейства форматов. |
| value | Идентификатор семейства форматов. |

### Возвращаемое значение

Экземпляр указанного типа *T* с указанным идентификатором.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Выбрасывается, когда не найдено подходящее семейство форматов. |

### См. также

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
