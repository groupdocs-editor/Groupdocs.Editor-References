---
title: "op_Explicit"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Преобразует указанный экземпляр QuoteTypegroupdocs.editor.htmlcss.serialization/quotetype в Char."
type: docs
weight: 100
url: /ru/net/groupdocs.editor.htmlcss.serialization/quotetype/op_explicit/
---
## explicit operator {#op_explicit}

Преобразует указанный экземпляр [`QuoteType`](../../quotetype) в Char.

```csharp
public static explicit operator char(QuoteType quote)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| кавычка | QuoteType | Экземпляр типа Quote для приведения |

### См. также

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit_1}

Преобразует конкретный Char в соответствующий [`QuoteType`](../../quotetype), бросает исключение, если приведение недопустимо.

```csharp
public static explicit operator QuoteType(char character)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| символ | Символ | Одинарная кавычка (U+0027 APOSTROPHE) или двойная кавычка (U+0022 QUOTATION MARK) символ. Исключение будет выброшено, если будет указан любой другой символ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Указанный символ не является ни кавычкой, ни апострофом |

### См. также

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
