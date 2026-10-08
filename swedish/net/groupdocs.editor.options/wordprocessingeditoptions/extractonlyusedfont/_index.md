---
title: "ExtractOnlyUsedFont"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Hämtar eller anger ett värde som indikerar om endast teckensnittresurser som används i dokumentets textinnehåll ska extraheras."
type: docs
weight: 40
url: /sv/net/groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont/
---
## WordProcessingEditOptions.ExtractOnlyUsedFont property

Hämtar eller anger ett värde som indikerar om endast teckensnittresurser som används i dokumentets textinnehåll ska extraheras.

```csharp
public bool ExtractOnlyUsedFont { get; set; }
```

### Property Value

`true` om det krävs att endast extrahera de teckensnittresurser som används i dokumentets textinnehåll; annars `false`. Standardvärdet är `false`.

### Anmärkningar

Inte alla teckensnitt som används i WordProcessing-dokumentet används 100 % direkt (tillämpas på någon text). Det kan finnas en situation där ett teckensnitt refereras i dokumentet och till och med kan vara inbäddat, men inte tillämpas på någon textdel. Till exempel kan ett teckensnitt vara kopplat till en stil, men den stilen tillämpas inte på någon del av texten. Detta alternativ styr hur sådana fall hanteras.

### Se även

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
