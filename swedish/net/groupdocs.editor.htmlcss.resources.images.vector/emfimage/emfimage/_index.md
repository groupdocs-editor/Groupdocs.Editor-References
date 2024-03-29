---
title: EmfImage
second_title: GroupDocs.Editor för .NET API-referens
description: Skapar ny EmfImageinstans från innehåll representerad som base64kodad sträng och med specificerat namn
type: docs
weight: 10
url: /sv/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/emfimage/
---
## EmfImage(string, string) {#constructor_1}

Skapar ny EmfImage-instans från innehåll, representerad som base64-kodad sträng och med specificerat namn

```csharp
public EmfImage(string name, string contentInBase64)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | String | Namn på EMF-bilden. Kan inte vara null, tom eller blanksteg. |
| contentInBase64 | String | Innehåll som base64-kodad sträng. Kan inte vara null, tom eller blanksteg. Om det inte är ett EMF-innehåll kommer undantag att kastas. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [EmfImage](../../emfimage)
* namnutrymme [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../emfimage)
* hopsättning [GroupDocs.Editor](../../../)

---

## EmfImage(string, Stream) {#constructor}

Skapar ny EmfImage-instans från innehåll, representerad som byteström och med specificerat namn

```csharp
public EmfImage(string name, Stream binaryContent)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | String | Namn på EMF-bilden. Kan inte vara null, tom eller blanksteg. |
| binaryContent | Stream | Innehåll som byteström. Läsningen börjar från den ursprungliga positionen. Kan inte vara null. Bör vara läsbar och sökbar. Om den här instansen kommer att kasseras kommer även denna ström att kasseras. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Se även

* class [EmfImage](../../emfimage)
* namnutrymme [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../emfimage)
* hopsättning [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
