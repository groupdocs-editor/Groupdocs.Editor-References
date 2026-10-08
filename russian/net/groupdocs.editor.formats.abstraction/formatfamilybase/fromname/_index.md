---
title: "FromName"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Получает экземпляр указанного типа T, имеющий указанное имя."
type: docs
weight: 60
url: /ru/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromname/
---
## FormatFamilyBase.FromName&lt;T&gt; method

Получает экземпляр указанного типа *T*, имеющий указанное имя.

```csharp
public static T FromName<T>(string name)
    where T : FormatFamilyBase
```

| Параметр | Описание |
| --- | --- |
| T | Тип семейства форматов. |
| name | Имя семейства форматов. |

### Возвращаемое значение

Экземпляр указанного типа *T* с указанным именем.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Выбрасывается, когда не найдено подходящее семейство форматов. |

### См. также

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
