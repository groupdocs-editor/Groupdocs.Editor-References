---
title: "GetCssContent"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Returnerar innehållet i alla externa stilmallar som en lista med strängar där varje sträng representerar en stilmall. Returnerar en tom lista om det inte finns någon CSS för detta dokument."
type: docs
weight: 140
url: /sv/net/groupdocs.editor/editabledocument/getcsscontent/
---
## GetCssContent() {#getcsscontent}

Returnerar innehållet i alla externa stilmallar som en lista med strängar, där en sträng representerar en stilmall. Returnerar en tom lista om det inte finns någon CSS för detta dokument.

```csharp
public List<string> GetCssContent()
```

### Returvärde

En lista med strängar, där varje sträng innehåller innehållet i ett CSS‑dokument.

### Se även

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetCssContent(string, string) {#getcsscontent_1}

Returnerar innehållet i alla externa stilmallar som en lista med strängar, där en sträng representerar en stilmall. Angivet prefix kommer att tillämpas på varje länk till den externa resursen i varje resulterande stilmall. Returnerar en tom lista om det inte finns någon CSS för detta dokument.

```csharp
public List<string> GetCssContent(string externalImagesPrefix, string externalFontsPrefix)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| externalImagesPrefix | String | Genom den här parametern kan du ange ett prefix som läggs till länkarna till alla externa bilder som finns i CSS-deklarationer i de resulterande CSS-strängarna. Om NULL eller tomt läggs inga prefix till. |
| externalFontsPrefix | String | Genom den här parametern kan du ange ett prefix som läggs till länkarna till alla externa teckensnitt i @font-face‑reglerna i de resulterande CSS‑strängarna. Om NULL eller tomt läggs inga prefix till. |

### Returvärde

En lista med strängar, där varje sträng innehåller innehållet i ett CSS‑dokument.

### Se även

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
