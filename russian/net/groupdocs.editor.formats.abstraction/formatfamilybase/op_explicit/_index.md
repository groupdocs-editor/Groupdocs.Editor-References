---
title: "op_Explicit"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Преобразует строку, представляющую имя семейства форматов, в объект FormatFamilyBasegroupdocs.editor.formats.abstraction/formatfamilybase."
type: docs
weight: 100
url: /ru/net/groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit/
---
## explicit operator {#op_explicit_1}

Преобразует строку, представляющую имя семейства форматов, в объект [`FormatFamilyBase`](../../formatfamilybase).

```csharp
public static explicit operator FormatFamilyBase(string family)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| семейство | String | Имя семейства форматов для преобразования. |

### Возвращаемое значение

Объект [`FormatFamilyBase`](../../formatfamilybase), соответствующий указанному имени семейства форматов.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда указанное имя семейства форматов недействительно. |

### См. также

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

Преобразует целое число, представляющее идентификатор семейства форматов, в объект [`FormatFamilyBase`](../../formatfamilybase).

```csharp
public static explicit operator FormatFamilyBase(int id)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | Int32 | Идентификатор семейства форматов для преобразования. |

### Возвращаемое значение

Объект [`FormatFamilyBase`](../../formatfamilybase), соответствующий указанному идентификатору семейства форматов.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда указанный идентификатор семейства форматов недействителен. |

### См. также

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
