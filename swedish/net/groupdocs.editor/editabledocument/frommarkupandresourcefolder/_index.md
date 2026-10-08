---
title: "FromMarkupAndResourceFolder"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Statisk fabrik som skapar en instans av EditableDocument från en specificerad HTML‑markup och från resurser som finns i den mapp som anges med fullständig sökväg"
type: docs
weight: 30
url: /sv/net/groupdocs.editor/editabledocument/frommarkupandresourcefolder/
---
## EditableDocument.FromMarkupAndResourceFolder method

Statisk fabrik som skapar en instans av EditableDocument från en specificerad HTML-markup och från resurser som finns i mappen som specificeras av den fullständiga sökvägen.

```csharp
public static EditableDocument FromMarkupAndResourceFolder(string newHtmlContent, 
    string resourceFolderPath)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| newHtmlContent | String | Sträng som innehåller rå HTML‑markup som ska parsas. Får inte vara NULL, tom eller ogiltig. |
| resourceFolderPath | String | Obligatorisk sökväg till mappen med resurser. Alla stilmallar som finns i denna mapp kommer att användas. Får inte vara NULL eller en tom sträng, och mappen måste finnas. |

### Returvärde

Ny icke‑null‑instans av EditableDocument

### Anmärkningar

Denna statiska fabrik är användbar när innehållet i ett HTML‑dokument presenteras som en sträng, men alla resurser finns i någon mapp, och länkarna till dessa resurser i HTML‑markupen ofta är ogiltiga eller saknas. Vid anrop av metoden skannar den den specificerade mappen och applicerar automatiskt alla hittade stilmallar på dokumentet. Metoden är mycket användbar när man hämtar innehåll från olika HTML‑redigerare, som vanligtvis tar bort dokumentets metadata med mera.

### Se även

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
