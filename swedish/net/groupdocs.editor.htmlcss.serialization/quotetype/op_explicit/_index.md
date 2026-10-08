---
title: "op_Explicit"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Kastar specificerad QuoteTypegroupdocs.editor.htmlcss.serialization/quotetype-instans till Char"
type: docs
weight: 100
url: /sv/net/groupdocs.editor.htmlcss.serialization/quotetype/op_explicit/
---
## explicit operator {#op_explicit}

Kastar specificerad [`QuoteType`](../../quotetype) instans till Char

```csharp
public static explicit operator char(QuoteType quote)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| citat | QuoteType | Citattypinstans att kasta |

### Se även

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit_1}

Kastar specifik Char till motsvarande [`QuoteType`](../../quotetype), kastar ett undantag om omvandlingen är ogiltig

```csharp
public static explicit operator QuoteType(char character)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| tecken | Char | Ett enkelt citattecken (U+0027 APOSTROPHE) eller ett dubbelt citattecken (U+0022 QUOTATION MARK) tecken. Ett undantag kommer att kastas om något annat tecken anges. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | Angiven Char är varken ett citattecken eller ett apostrof |

### Se även

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
