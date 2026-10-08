---
title: "TextResourceBase"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Basklass för alla stödda textresurser med textinnehåll och kodning"
type: docs
weight: 630
url: /sv/net/groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
## TextResourceBase class

Basklass för alla stödda textresurser med textinnehåll och kodning

```csharp
public abstract class TextResourceBase : IHtmlResource
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | Returnerar innehållet i denna textresurs som en byte‑ström med originalkodning |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | Returnerar kodningen för denna textresurs. Returnerar vanligtvis UTF-8. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | Returnerar korrekt filnamn för denna textresurs, som består av namn och filändelse |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | Bestämmer om denna textresurs har frigjorts eller inte |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | Returnerar namnet på denna textresurs utan filändelse |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | Returnerar innehållet i denna textresurs som en standardsträng |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/type) { get; } | Den implementerande typen bör returnera information om typen av textresursen |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/dispose)() | Frigör denna textresurs, frigör dess innehåll och gör de flesta metoder och egenskaper obrukbara. Tolerant mot flera anrop. |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/equals#equals)(IHtmlResource) | Kontrollerar denna instans mot den angivna för likhet. |
| [Save](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/save)(string) | Sparar denna textresurs till den angivna filen |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/disposed) | Händelse som inträffar när denna textresurs har frigjorts |

### Se även

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
