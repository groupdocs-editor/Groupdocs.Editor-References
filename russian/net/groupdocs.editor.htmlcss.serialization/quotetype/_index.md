---
title: "QuoteType"
second_title: "GroupDocs.Editor для .NET справочник API"
description: "Представляет символы кавычек одинарную кавычку и двойную кавычку"
type: docs
weight: 660
url: /ru/net/groupdocs.editor.htmlcss.serialization/quotetype/
---
## QuoteType structure

Представляет символы кавычек — одинарную кавычку (') и двойную кавычку (\")

```csharp
public struct QuoteType : IEquatable<QuoteType>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Character](../../groupdocs.editor.htmlcss.serialization/quotetype/character) { get; } | Символ для заключения в кавычки |
| [Code](../../groupdocs.editor.htmlcss.serialization/quotetype/code) { get; } | Кодовая точка текущего символа (U+0027 или U+0022) |
| [HtmlEncoded](../../groupdocs.editor.htmlcss.serialization/quotetype/htmlencoded) { get; } | HTML‑закодированный символ |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals_1)(object) | Указывает, равен ли данный экземпляр типа кавычки указанному без приведения типов |
| [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals)(QuoteType) | Указывает, равен ли данный экземпляр типа кавычки указанному |
| override [GetHashCode](../../groupdocs.editor.htmlcss.serialization/quotetype/gethashcode)() | Возвращает хеш‑код для этого символа |
| override [ToString](../../groupdocs.editor.htmlcss.serialization/quotetype/tostring)() | Возвращает строку "SingleQuote" или "DoubleQuote" в зависимости от текущего значения |
| [operator ==](../../groupdocs.editor.htmlcss.serialization/quotetype/op_equality) | Проверяет, равны ли два значения "QuoteType" |
| [explicit operator](../../groupdocs.editor.htmlcss.serialization/quotetype/op_explicit#op_explicit) | Преобразует указанный экземпляр [`QuoteType`](../quotetype) в тип Char (2 оператора) |
| [operator !=](../../groupdocs.editor.htmlcss.serialization/quotetype/op_inequality) | Проверяет, не равны ли два значения "QuoteType" |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [DoubleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/doublequote) | Двойная кавычка (символ U+0022 QUOTATION MARK) |
| static readonly [SingleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/singlequote) | Одинарная кавычка (символ U+0027 APOSTROPHE) |

### См. также

* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.editor.dll -->
