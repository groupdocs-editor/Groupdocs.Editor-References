---
title: "op_Explicit"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Konverterar en sträng som representerar ett formatfamiljenamn till ett FormatFamilyBasegroupdocs.editor.formats.abstraction/formatfamilybase-objekt."
type: docs
weight: 100
url: /sv/net/groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit/
---
## explicit operator {#op_explicit_1}

Konverterar en sträng som representerar ett formatfamiljenamn till ett [`FormatFamilyBase`](../../formatfamilybase) objekt.

```csharp
public static explicit operator FormatFamilyBase(string family)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| familj | String | Namnet på formatfamiljen att konvertera. |

### Returvärde

Ett [`FormatFamilyBase`](../../formatfamilybase) objekt som motsvarar det angivna formatfamiljenamnet.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när det angivna formatfamiljenamnet är ogiltigt. |

### Se även

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

Konverterar ett heltal som representerar ett formatfamilje-ID till ett [`FormatFamilyBase`](../../formatfamilybase) objekt.

```csharp
public static explicit operator FormatFamilyBase(int id)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| id | Int32 | ID för formatfamiljen att konvertera. |

### Returvärde

Ett [`FormatFamilyBase`](../../formatfamilybase)‑objekt som motsvarar det angivna formatfamilj‑ID:t.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när det angivna formatfamilj‑ID:t är ogiltigt. |

### Se även

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
