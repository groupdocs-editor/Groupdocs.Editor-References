---
title: "FromName"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Hämtar en instans av den angivna typen T som har det angivna namnet."
type: docs
weight: 60
url: /sv/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromname/
---
## FormatFamilyBase.FromName&lt;T&gt; method

Hämtar en instans av den angivna typen *T* som har det angivna namnet.

```csharp
public static T FromName<T>(string name)
    where T : FormatFamilyBase
```

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av formatfamilj. |
| namn | Namnet på formatfamiljen. |

### Returvärde

En instans av den angivna typen *T* med det angivna namnet.

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidOperationException | Kastas när ingen matchande formatfamilj hittas. |

### Se även

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
