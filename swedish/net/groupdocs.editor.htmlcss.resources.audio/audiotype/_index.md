---
title: "AudioType"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar ett stödjbart ljudtypformat"
type: docs
weight: 320
url: /sv/net/groupdocs.editor.htmlcss.resources.audio/audiotype/
---
## AudioType structure

Representerar en stödbar ljudtyp (format)

```csharp
public struct AudioType : IEquatable<AudioType>, IResourceType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Mp3](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mp3) { get; } | Representerar ett MPEG-1 Audio Layer III-ljudformat |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.audio/audiotype/undefined) { get; } | Speciellt värde som markerar odefinierat, okänt eller ej stödd ljudformat |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/fileextension) { get; } | Filnamnstillägg (utan punkttecken) för detta ljudformat |
| [FormalName](../../groupdocs.editor.htmlcss.resources.audio/audiotype/formalname) { get; } | Formellt namn för detta ljudformat |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mimecode) { get; } | MIME-kod för detta ljudformat |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/parsefromfilenamewithextension)(string) | Returnerar AudioType-värde som motsvarar filnamnstillägget som extraheras från det angivna filnamnet |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals)(AudioType) | Bestämmer om detta objekt är lika med den angivna "AudioType"-instansen |
| override [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals_1)(object) | Bestämmer om detta objekt är lika med det angivna okastade objektet, som sannolikt är en annan "AudioType"-instans |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/gethashcode)() | Returnerar en hashkod som är ett konstant tal för denna specifika värdetyp |
| [operator ==](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_equality) | Kontrollerar om två "AudioType"-värden är lika |
| [operator !=](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_inequality) | Kontrollerar om två "AudioType"-värden inte är lika |

### Se även

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
