---
title: "FromMime"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Получает экземпляр указанного типа T, имеющий указанный MIME‑тип."
type: docs
weight: 60
url: /ru/net/groupdocs.editor.formats.abstraction/documentformatbase/frommime/
---
## DocumentFormatBase.FromMime&lt;T&gt; method

Получает экземпляр указанного типа *T*, имеющий указанный MIME‑тип.

```csharp
public static T FromMime<T>(string mime)
    where T : DocumentFormatBase
```

| Параметр | Описание |
| --- | --- |
| T | Тип формата документа. |
| mime | MIME‑тип формата документа. |

### Возвращаемое значение

Экземпляр указанного типа *T* с указанным MIME‑типом.

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Выбрасывается, когда не найден подходящий формат документа. |

### См. также

* class [DocumentFormatBase](../../documentformatbase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
