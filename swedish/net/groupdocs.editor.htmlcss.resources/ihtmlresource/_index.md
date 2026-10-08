---
title: "IHtmlResource"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar en instans av den okända HTML-resursen raster- eller vektorbild, stilmall, teckensnitt, textresurs, CSS, XML, ljud etc."
type: docs
weight: 430
url: /sv/net/groupdocs.editor.htmlcss.resources/ihtmlresource/
---
## IHtmlResource interface

Representerar en instans av den okända HTML-resursen (raster- eller vektorbild, stilark, teckensnitt, textresurs (CSS, XML), ljud osv.)

```csharp
public interface IHtmlResource : IAuxDisposable, IEquatable<IHtmlResource>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/bytecontent) { get; } | Innehåll av HTML-resursen i form av en byte-ström |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) { get; } | Korrekt filnamn för den angivna resursen med lämplig filändelse |
| [Name](../../groupdocs.editor.htmlcss.resources/ihtmlresource/name) { get; } | Namn på HTML-resursen |
| [TextContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/textcontent) { get; } | Innehåll för HTML-resursen i form av en base64-kodad textsträng för binära resurser eller enkel text för textbaserade resurser |
| [Type](../../groupdocs.editor.htmlcss.resources/ihtmlresource/type) { get; } | Typ av HTML-resurs |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Save](../../groupdocs.editor.htmlcss.resources/ihtmlresource/save)(string) | Sparar den aktuella resursen till den angivna filen |

### Se även

* interface [IAuxDisposable](../iauxdisposable)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
