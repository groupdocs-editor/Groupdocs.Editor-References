---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Utökar det standardmässiga IDisposable‑gränssnittet och möjliggör att erhålla ett objekts aktuella tillstånd samt prenumerera på avyttringshändelsen"
type: docs
weight: 420
url: /sv/net/groupdocs.editor.htmlcss.resources/iauxdisposable/
---
## IAuxDisposable interface

Utökar det standardmässiga IDisposable-gränssnittet, tillåter att erhålla ett aktuellt tillstånd för ett objekt och prenumerera på avyttringshändelsen

```csharp
public interface IAuxDisposable : IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources/iauxdisposable/isdisposed) { get; } | Avgör om en resurs är stängd (true) eller inte (false) |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources/iauxdisposable/disposed) | Uppstår när objektet avyttras |

### Se även

* namespace [GroupDocs.Editor.HtmlCss.Resources](../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
