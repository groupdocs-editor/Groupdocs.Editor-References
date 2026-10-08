---
title: "FromValue"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Hämtar en instans av den angivna typen T som har det angivna identifieraren."
type: docs
weight: 70
url: /sv/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue/
---
## FormatFamilyBase.FromValue&lt;T&gt; method

Hämtar en instans av den angivna typen *T* som har den angivna identifieraren.

```csharp
public static T FromValue<T>(int value)
    where T : FormatFamilyBase
```

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av formatfamilj. |
| värde | Identifieraren för formatfamiljen. |

### Returvärde

En instans av den angivna typen *T* med det angivna identifieraren.

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidOperationException | Kastas när ingen matchande formatfamilj hittas. |

### Se även

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
