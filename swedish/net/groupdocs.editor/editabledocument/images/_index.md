---
title: "Bilder"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Gör det möjligt att hämta externa bildresurser, raster‑ och vektorbilder som används av detta HTML‑dokument"
type: docs
weight: 80
url: /sv/net/groupdocs.editor/editabledocument/images/
---
## EditableDocument.Images property

Tillåter att hämta externa bildresurser (raster- och vektorbilder) som används av detta HTML-dokument.

```csharp
public List<IImageResource> Images { get; }
```

### Anmärkningar

Denna metod returnerar en ytlig kopia av alla använda bildresurser: `List` är en ny instans för varje anrop, men resursinstanserna är desamma.

### Se även

* interface [IImageResource](../../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
