---
title: "GetEmbeddedHtml"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Returnerar allt innehåll i detta HTML‑dokument med alla relaterade resurser i form av en enda sträng där alla resurser är inbäddade i HTML‑markupen i base64‑kodad form."
type: docs
weight: 150
url: /sv/net/groupdocs.editor/editabledocument/getembeddedhtml/
---
## EditableDocument.GetEmbeddedHtml method

Returnerar allt innehåll i detta HTML‑dokument med alla relaterade resurser i form av en enda sträng, där alla resurser är inbäddade i HTML markup i base64‑kodad form.

```csharp
public string GetEmbeddedHtml()
```

### Returvärde

Sträng som i alla fall inte är NULL eller tom

### Undantag

| undantag | villkor |
| --- | --- |
| ObjectDisposedException | Denna EditableDocument‑instans har redan avyttrats |

### Anmärkningar

Denna metod konverterar detta EditableDocument till HTML och serialiserar det till en enda sträng, där alla resurser är inbäddade i strängen tillsammans med HTML‑markupen:

* All images from HTML-&gt;BODY are converted to base64 format and are located in the IMG 'src' attribute
* All stylesheets are stored in the STYLE elements inside HTML-&gt;HEAD sections
* All images from stylesheets are converted to base64 format and located in the appropriate CSS declarations
* All fonts from stylesheets are converted to base64 format and located in the appropriate @font-face at-rules

### Se även

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
