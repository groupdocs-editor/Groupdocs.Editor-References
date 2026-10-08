---
title: "FromFile"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Statisk fabrik som skapar en instans av EditableDocument från en HTML‑fil som anges av en sökväg till själva .html‑filen och en mapp med länkade resurser."
type: docs
weight: 10
url: /sv/net/groupdocs.editor/editabledocument/fromfile/
---
## EditableDocument.FromFile method

Statisk fabrik som skapar en instans av EditableDocument från en HTML-fil, som specificeras av en sökväg till själva *.html-filen och en mapp med länkade resurser.

```csharp
public static EditableDocument FromFile(string htmlFilePath, string resourceFolderPath)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| htmlFilePath | String | String som innehåller en fullständig sökväg till HTML‑filen. Får inte vara null, bör vara en giltig filsökväg, och filen själv måste finnas. |
| resourceFolderPath | String | Valfri sökväg till mappen med HTML‑resurser. Om NULL, ogiltig eller om mappen inte finns, kommer Editor att försöka hitta mappen själv genom att analysera HTML‑markupen. |

### Returvärde

Ny icke‑null‑instans av EditableDocument

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | HTML‑filens sökväg och/eller resursmappens sökväg är ogiltig(a). |
| FileNotFoundException | Den angivna HTML‑filen kunde inte hittas. |

### Se även

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
