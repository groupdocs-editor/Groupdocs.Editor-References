---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Denna parameterlösa konstruktor skapar en ny instans av DelimitedTextSaveOptions med ett semikolon som standardseparator, som kan modifieras sedan via egenskapen Separatorgroupdocs.editor.options/delimitedtextsaveoptions/separator."
type: docs
weight: 10
url: /sv/net/groupdocs.editor.options/delimitedtextsaveoptions/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions() {#constructor}

Denna parameterlösa konstruktor skapar en ny instans av DelimitedTextSaveOptions med ett semikolon (;) som standardseparator (kan modifieras sedan via egenskapen [`Separator`](../separator)).

```csharp
public DelimitedTextSaveOptions()
```

### Se även

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

---

## DelimitedTextSaveOptions(string) {#constructor_1}

Skapar en instans av alternativklassen för avgränsad text med obligatorisk avgränsare (separator).

```csharp
public DelimitedTextSaveOptions(string separator)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| separator | String | Strängseparator (avgränsare) som inte kan vara NULL eller tom. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när den specificerade separatorn är null eller en tom sträng. |

### Se även

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
