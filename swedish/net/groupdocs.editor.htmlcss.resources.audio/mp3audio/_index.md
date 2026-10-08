---
title: "Mp3Audio"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar en ljudresurs av godtyckligt format"
type: docs
weight: 330
url: /sv/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
## Mp3Audio class

Representerar en ljudresurs av godtyckligt format

```csharp
public sealed class Mp3Audio : IEquatable<Mp3Audio>, IHtmlResource
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Mp3Audio](mp3audio)(string, Stream) | Skapar en ny Mp3Audio‑klass från MP3‑innehåll, representerat som en byte‑ström, och med angivet namn |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/bytecontent) { get; } | Returnerar innehållet i detta typsnitt som en byte‑ström |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/filenamewithextension) { get; } | Returnerar korrekt filnamn för detta MP3‑innehåll, som består av namn och filändelse. Teoretiskt kan det skilja sig från namnet. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isdisposed) { get; } | Avgör om detta MP3‑innehåll är avyttrat eller inte |
| [Name](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/name) { get; } | Returnerar namn på detta MP3‑innehåll. Innehåller vanligtvis inte filändelse och kan teoretiskt skilja sig från filnamnet. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/textcontent) { get; } | Returnerar innehållet i denna MP3‑resurs som en base64‑kodad sträng. Detta värde cachas efter första anropet. |
| [Type](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/type) { get; } | Returnerar en AudioType.Mp3 |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/dispose)() | Avyttrar denna MP3‑resurs, avyttrar dess innehåll och gör de flesta metoder och egenskaper oanvändbara |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals_1)(IHtmlResource) | Kontrollerar om denna instans är referenslik med angiven HTML‑resurs |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals)(Mp3Audio) | Kontrollerar om denna instans är referenslik med angiven typsnitt‑resurs |
| [Save](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/save)(string) | Sparar denna MP3‑resurs till den angivna filen |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isvalid)(Stream) | Kontrollerar om den angivna strömmen är ett giltigt MP3-innehåll |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/disposed) | Händelse som inträffar när detta MP3-innehåll har frigjorts |

### Se även

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
