---
title: "FromMime"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Hämtar en instans av den angivna typen T som har den angivna MIME-typen."
type: docs
weight: 60
url: /sv/net/groupdocs.editor.formats.abstraction/documentformatbase/frommime/
---
## DocumentFormatBase.FromMime&lt;T&gt; method

Hämtar en instans av den angivna typen *T* som har den angivna MIME-typen.

```csharp
public static T FromMime<T>(string mime)
    where T : DocumentFormatBase
```

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av dokumentformat. |
| mime | MIME-typen för dokumentformatet. |

### Returvärde

En instans av den angivna typen *T* med den angivna MIME-typen.

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidOperationException | Kastas när inget matchande dokumentformat hittas. |

### Se även

* class [DocumentFormatBase](../../documentformatbase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
