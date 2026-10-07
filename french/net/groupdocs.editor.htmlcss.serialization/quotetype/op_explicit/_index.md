---
title: "op_Explicit"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Convertit l'instance spécifiée QuoteTypegroupdocs.editor.htmlcss.serialization/quotetype en Char."
type: docs
weight: 100
url: /fr/net/groupdocs.editor.htmlcss.serialization/quotetype/op_explicit/
---
## explicit operator {#op_explicit}

Convertit l'instance spécifiée [`QuoteType`](../../quotetype) en Char.

```csharp
public static explicit operator char(QuoteType quote)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| citation | QuoteType | Instance du type Quote à convertir |

### Voir aussi

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit_1}

Convertit le Char spécifique en le [`QuoteType`](../../quotetype) correspondant, lève une exception si la conversion est invalide.

```csharp
public static explicit operator QuoteType(char character)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| caractère | Char | Une apostrophe simple (U+0027 APOSTROPHE) ou un guillemet double (U+0022 QUOTATION MARK) caractère. Une exception sera levée si tout autre caractère est spécifié. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Le Char spécifié n’est ni un guillemet ni une apostrophe |

### Voir aussi

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
