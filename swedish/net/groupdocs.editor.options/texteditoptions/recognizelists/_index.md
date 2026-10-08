---
title: "RecognizeLists"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange hur numrerade listobjekt identifieras när dokumentet importeras från enkelt textformat. Standardvärdet är true."
type: docs
weight: 60
url: /sv/net/groupdocs.editor.options/texteditoptions/recognizelists/
---
## TextEditOptions.RecognizeLists property

Tillåter att ange hur numrerade listobjekt identifieras när dokumentet importeras från enkelt textformat. Standardvärdet är true.

```csharp
public bool RecognizeLists { get; set; }
```

### Anmärkningar

Om detta alternativ är satt till false upptäcker listigenkänningsalgoritmen listparagrafer när listnumren avslutas med antingen punkt, höger parentes eller punkttecken (såsom \"•\", \"*\", \"-\" eller \"o\"). Om alternativet är satt till true används även blanksteg som avgränsare för listnummer: listigenkänningsalgoritmen för arabiskt numreringsstil (1., 1.1.2.) använder både blanksteg och punkt (\".\") som symboler.

### Se även

* class [TextEditOptions](../../texteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
