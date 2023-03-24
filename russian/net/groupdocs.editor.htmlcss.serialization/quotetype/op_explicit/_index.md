---
title: op_Explicit
second_title: Справочник по API GroupDocs.Editor для .NET
description: Указаны приведенияQuoteTypegroupdocs.editor.htmlcss.serialization/quotetype экземпляр кChar
type: docs
weight: 90
url: /ru/net/groupdocs.editor.htmlcss.serialization/quotetype/op_explicit/
---
## explicit operator {#op_explicit}

Указаны приведения[`QuoteType`](../../quotetype) экземпляр кChar

```csharp
public static explicit operator char(QuoteType quote)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| quote | QuoteType | Экземпляр типа Quote для приведения |

### Смотрите также

* struct [QuoteType](../../quotetype)
* пространство имен [GroupDocs.Editor.HtmlCss.Serialization](../../quotetype)
* сборка [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit_1}

Применяет конкретныеChar соответствующему[`QuoteType`](../../quotetype) , выдает исключение, если кастинг недействителен

```csharp
public static explicit operator QuoteType(char character)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| character | Char | Одинарная кавычка (U+0027 АПОСТРОФ) или двойная кавычка (U+0022 QUOTATION MARK). Исключение будет выдано, если будет указан любой другой символ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | УказанныйChar не является ни кавычкой, ни апострофом |

### Смотрите также

* struct [QuoteType](../../quotetype)
* пространство имен [GroupDocs.Editor.HtmlCss.Serialization](../../quotetype)
* сборка [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->