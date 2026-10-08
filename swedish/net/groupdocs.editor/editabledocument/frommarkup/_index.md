---
title: "FromMarkup"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Statisk fabrik som skapar en instans av EditableDocumentgroupdocs.editor/editabledocument från specificerad HTML‑markup."
type: docs
weight: 20
url: /sv/net/groupdocs.editor/editabledocument/frommarkup/
---
## FromMarkup(string) {#frommarkup}

Statisk fabrik som skapar en instans av [`EditableDocument`](../../editabledocument) från specificerad HTML‑markup.

```csharp
public static EditableDocument FromMarkup(string newHtmlContent)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| newHtmlContent | String | Sträng som innehåller rå HTML‑markup som ska parsas. Får inte vara NULL, tom eller ogiltig. |

### Returvärde

Ny icke‑null‑instans av EditableDocument

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Sträng med inmatad rå HTML‑markup får inte vara null eller tom. |

### Anmärkningar

Denna statiska metod är användbar för att skapa [`EditableDocument`](../../editabledocument)-instansen från en enkelsträngs HTML‑markup, där alla resurser är inbäddade med base64‑kodning.

### Se även

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## FromMarkup(string, IEnumerable&lt;IHtmlResource&gt;) {#frommarkup_1}

Statisk fabrik som skapar en instans av EditableDocument från specificerad HTML-markup och en uppsättning motsvarande länkade resurser.

```csharp
public static EditableDocument FromMarkup(string newHtmlContent, 
    IEnumerable<IHtmlResource> resources)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| newHtmlContent | String | Sträng som innehåller rå HTML‑markup som ska parsas. Får inte vara NULL, tom eller ogiltig. |
| resources | IEnumerable`1 | Samling av alla resurser (bilder, stilmallar, teckensnitt) som används i HTML‑dokumentet, specificerade i *newHtmlContent*-parametern. Kan vara frånvarande (NULL eller tom samling). |

### Returvärde

Ny icke‑null‑instans av EditableDocument

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Sträng med inmatad rå HTML‑markup får inte vara null eller tom. |

### Se även

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
