---
title: op_Explicit
second_title: GroupDocs.Editor voor .NET API-referentie
description: Casts gespecificeerdQuoteTypegroupdocs.editor.htmlcss.serialization/quotetype bijvoorbeeld naar deChar
type: docs
weight: 90
url: /nl/net/groupdocs.editor.htmlcss.serialization/quotetype/op_explicit/
---
## explicit operator {#op_explicit}

Casts gespecificeerd[`QuoteType`](../../quotetype) bijvoorbeeld naar deChar

```csharp
public static explicit operator char(QuoteType quote)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| quote | QuoteType | Quote type instantie om te casten |

### Zie ook

* struct [QuoteType](../../quotetype)
* naamruimte [GroupDocs.Editor.HtmlCss.Serialization](../../quotetype)
* montage [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit_1}

Cast specifiekChar naar de corresponderende[`QuoteType`](../../quotetype) , genereert een uitzondering als casten invalid is

```csharp
public static explicit operator QuoteType(char character)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| character | Char | Een enkel aanhalingsteken (U+0027 APOSTROPHE) of dubbel aanhalingsteken (U+0022 QUOTATION MARK). Er wordt een uitzondering gegenereerd als een ander teken wordt opgegeven. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | GespecificeerdChar is geen aanhalingsteken of apostrof |

### Zie ook

* struct [QuoteType](../../quotetype)
* naamruimte [GroupDocs.Editor.HtmlCss.Serialization](../../quotetype)
* montage [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
