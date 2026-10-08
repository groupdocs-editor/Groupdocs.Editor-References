---
title: "Dispose"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Avslutar denna instans av Editor så att den frigör alla interna resurser och blir otillgänglig för vidare användning"
type: docs
weight: 50
url: /sv/net/groupdocs.editor/editor/dispose/
---
## Editor.Dispose method

Frigör denna instans av Editor, så att den släpper alla interna resurser och blir otillgänglig för vidare användning.

```csharp
public void Dispose()
```

### Anmärkningar

Efter att denna metod har anropats kommer anrop av alla andra metoder på denna instans att kasta ett ObjectDisposedException. Det är säkert att anropa denna metod flera gånger — alla efterföljande anrop ignoreras.

### Se även

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
