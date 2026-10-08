---
title: "IsValid"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Kontrollerar om den angivna strömmen är en giltig WMF-bild"
type: docs
weight: 90
url: /sv/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid/
---
## IsValid(Stream) {#isvalid}

Kontrollerar om den angivna strömmen är en giltig WMF-bild

```csharp
public static bool IsValid(Stream binaryContent)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| binaryContent | Stream | Indata‑byte‑ström. Får inte vara NULL, bör stödja läsning och sökning. |

### Returvärde

Sant om den angivna strömmen innehåller en giltig WMF‑bild, annars falskt

### Se även

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## IsValid(string) {#isvalid_1}

Kontrollerar om den angivna base64‑kodade strängen är en giltig WMF-bild

```csharp
public static bool IsValid(string contentInBase64)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| contentInBase64 | String | Indata‑sträng där innehållet i WMF‑bilden lagras i base64‑kodning. Får inte vara NULL eller tom. |

### Returvärde

Sant om den angivna strängen innehåller en giltig WMF‑bild, annars falskt

### Se även

* class [WmfImage](../../wmfimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
