---
title: "Css"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att hämta CSS‑resurser för stilmallar, både externa och inbäddade men inte inline, som används av detta HTML‑dokument."
type: docs
weight: 60
url: /sv/net/groupdocs.editor/editabledocument/css/
---
## EditableDocument.Css property

Tillåter att hämta stilmallsresurser (CSS) (både externa och inbäddade, men inte inline) som används av detta HTML-dokument.

```csharp
public List<CssText> Css { get; }
```

### Anmärkningar

Denna metod returnerar en ytlig kopia av alla använda stilmallsresurser: `List` är en ny instans för varje anrop, men resursinstanserna är desamma.

### Se även

* class [CssText](../../../groupdocs.editor.htmlcss.resources.textual/csstext)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
