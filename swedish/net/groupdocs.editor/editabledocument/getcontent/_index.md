---
title: "GetContent"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Returnerar det totala innehållet i HTML-dokumentet som en byte‑ström genom att skriva detta innehåll till den angivna strömmen med angiven textkodning."
type: docs
weight: 130
url: /sv/net/groupdocs.editor/editabledocument/getcontent/
---
## GetContent&lt;TStream&gt;(TStream, Encoding) {#getcontent_2}

Returnerar det totala innehållet i HTML-dokumentet som en byte‑ström genom att skriva detta innehåll till den angivna strömmen med angiven textkodning.

```csharp
public TStream GetContent<TStream>(TStream storage, Encoding encoding)
    where TStream : Stream
```

| Parameter | Beskrivning |
| --- | --- |
| TStream | Alla implementationer av Stream |
| storage | Icke‑null byte‑ström som stöder skrivning |
| encoding | Icke‑null textkodning som ska tillämpas när textinnehåll skrivs till angivet *storage* |

### Returvärde

Instans av angivet *storage*

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Något av inmatningsargumenten är null |
| ArgumentException | Angiven ström är inte skrivbar |

### Se även

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent() {#getcontent}

Returnerar det totala innehållet i HTML-dokumentet som en sträng.

```csharp
public string GetContent()
```

### Returvärde

Sträng som innehåller innehållet i HTML‑dokumentet

### Se även

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent(string, string) {#getcontent_1}

Returnerar det totala innehållet i HTML-dokumentet som en sträng, där länkar till externa resurser innehåller angiven mall med platshållare.

```csharp
public string GetContent(string externalImagesTemplate, string externalCssTemplate)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| externalImagesTemplate | String | Genom den här parametern kan du ange en strängmall med en platshållare, som kommer att tillämpas på länkarna till alla externa bilder i IMG‑element som kommer att finnas i den resulterande HTML‑strängen. Om NULL eller tom, kommer mallen inte att läggas till, och rena filnamn kommer att finnas i den resulterande HTML‑markupen. Om mallen är ogiltig kommer den att behandlas som ett prefix, så att filnamnen konkateneras till dess slut. |
| externalCssTemplate | String | Genom den här parametern kan du ange en strängmall med en platshållare, som kommer att läggas till länkarna till alla externa stilmallar i LINK‑element som kommer att finnas i den resulterande HTML‑strängen. Om NULL eller tom, kommer mallen inte att läggas till, och rena filnamn kommer att finnas i den resulterande HTML‑markupen. Om mallen är ogiltig kommer den att behandlas som ett prefix, så att filnamnen konkateneras till dess slut. |

### Returvärde

Sträng som innehåller innehållet i HTML‑dokumentet med länkar, anpassade till de externa resurserna

### Se även

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
