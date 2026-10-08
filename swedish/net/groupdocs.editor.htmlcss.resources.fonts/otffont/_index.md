---
title: "OtfFont"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar ett teckensnitt i OTF Open Type Format-formatet"
type: docs
weight: 370
url: /sv/net/groupdocs.editor.htmlcss.resources.fonts/otffont/
---
## OtfFont class

Representerar ett teckensnitt i OTF (Open Type Format)-formatet

```csharp
public sealed class OtfFont : FontResourceBase
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [OtfFont](otffont#constructor)(string, Stream) | Skapar en ny OtfFont-klass från innehåll, representerat som byte-ström, och med angivet namn |
| [OtfFont](otffont#constructor_1)(string, string) | Skapar en ny OtfFont-klass från innehåll, representerat som base64-kodad sträng, och med angivet namn |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Returnerar innehållet i detta typsnitt som en byte‑ström |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Returnerar korrekt filnamn för denna teckensnittresurs, som består av namn och filändelse. Teoretiskt kan det skilja sig från namnet. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Bestämmer om detta teckensnitt är avyttrat eller inte |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Returnerar namn på denna teckensnittresurs. Innehåller vanligtvis inte filändelse och kan teoretiskt skilja sig från filnamnet. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Returnerar innehållet i detta teckensnitt som en base64-kodad sträng. Detta värde cachas efter första anropet. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/otffont/type) { get; } | Returnerar [`Otf`](../fonttype/otf) |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Avslutar denna teckensnittresurs, frigör dess innehåll och gör de flesta metoder och egenskaper oanvändbara |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | Kontrollerar om denna instans är referenslik med angiven typsnitt‑resurs |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | Kontrollerar om denna instans är referenslik med angiven HTML‑resurs |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Sparar detta teckensnitt till den angivna filen |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/otffont/isvalid#isvalid)(Stream) | Kontrollerar om den angivna strömmen är ett giltigt OTF-teckensnitt |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/otffont/isvalid#isvalid_1)(string) | Kontrollerar om den angivna base64-kodade strängen är ett giltigt OTF-teckensnitt |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/otffont/requiredheadersize) | OTF-huvudstorlek (i byte), som krävs för dess validering |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Händelse som inträffar när detta teckensnitt avslutas |

### Se även

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
