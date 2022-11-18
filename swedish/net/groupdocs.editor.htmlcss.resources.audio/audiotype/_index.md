---
title: AudioType
second_title: GroupDocs.Editor för .NET API-referens
description: Representerar en stödbar ljudtyp format
type: docs
weight: 240
url: /sv/net/groupdocs.editor.htmlcss.resources.audio/audiotype/
---
## AudioType structure

Representerar en stödbar ljudtyp (format)

```csharp
public struct AudioType : IEquatable<AudioType>, IResourceType
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [Mp3](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mp3) { get; } | Representerar ett MPEG-1 Audio Layer III ljudformat |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.audio/audiotype/undefined) { get; } | Specialvärde, som markerar odefinierat, okänt eller ostödd ljudformat |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/fileextension) { get; } | Filnamnstillägg (utan punkttecken) för detta ljudformat |
| [FormalName](../../groupdocs.editor.htmlcss.resources.audio/audiotype/formalname) { get; } | Formella namn på detta ljudformat |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mimecode) { get; } | MIME-kod för detta ljudformat |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/parsefromfilenamewithextension)(string) | Returnerar AudioType-värdet, vilket motsvarar filnamnstillägget, som extraheras från specificerat filnamn |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals)(AudioType) | Bestämmer om denna instans är lika med specificerad "AudioType" instans |
| override [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals_1)(object) | Bestämmer om den här instansen är lika med det angivna ocastade objektet, vilket förmodligen är en annan "AudioType"-instans |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/gethashcode)() | Returnerar en hash-kod, som är ett konstant tal för detta specifika värde type |
| [operator ==](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_equality) | Kontrollerar om två "AudioType"-värden är lika |
| [operator !=](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_inequality) | Kontrollerar om två "AudioType"-värden inte är lika |

### Se även

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namnutrymme [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->