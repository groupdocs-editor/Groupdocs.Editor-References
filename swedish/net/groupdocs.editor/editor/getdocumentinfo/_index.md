---
title: "GetDocumentInfo"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Returnerar metadata om dokumentet som laddades till denna Editor‑instans"
type: docs
weight: 70
url: /sv/net/groupdocs.editor/editor/getdocumentinfo/
---
## Editor.GetDocumentInfo method

Returnerar metadata om dokumentet som laddades till denna 'Editor'-instans.

```csharp
public IDocumentInfo GetDocumentInfo(string password)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| password | String | Användaren kan ange ett lösenord för ett dokument, om dokumentet är krypterat med lösenordet. Får vara NULL eller en tom sträng, vilket är ekvivalent med avsaknad av lösenord. För de dokumentformat som inte har ett lösenordsskydd, kommer detta argument att ignoreras. Om dokumentet är krypterat och lösenordet inte anges i denna parameter, men det angavs tidigare i laddningsalternativen när denna [`Editor`](../../editor)-instans skapades, kommer det att användas. |

### Returvärde

Format‑specifik ärvning av [`IDocumentInfo`](../../../groupdocs.editor.metadata/idocumentinfo)-gränssnittet, som indikerar det upptäckta formatet med format‑specifik metadata, eller NULL, om dokumentet inte identifierades som stödjande eller är korrupt.

### Undantag

| undantag | villkor |
| --- | --- |
| ObjectDisposedException | Kastas när Editor‑instansen redan har disponerats när "GetDocumentInfo" anropas |
| [PasswordRequiredException](../../passwordrequiredexception) | Kastas när det laddade dokumentet är lösenordsskyddat, men lösenordet inte angavs i parametern "*password*" och i laddningsalternativen under skapandet av instansen |
| [IncorrectPasswordException](../../incorrectpasswordexception) | Kastas när det inlästa dokumentet är lösenordsskyddat, lösenordet har angetts men är felaktigt |
| InvalidOperationException | Kastas när ett oväntat fel av okänd natur har inträffat |

### Anmärkningar

GetDocumentInfo‑metoden är användbar när det är oklart vilket format inmatningsdokumentet har, om det är lösenordsskyddat och/eller hur många sidor/arbetsblad/diapositiver det innehåller. Baserat på denna metadata, som returneras av GetDocumentInfo, är det möjligt att korrekt justera laddnings‑ och redigeringsalternativen för huvudprocessens pipeline.

GetDocumentInfo‑metoden returnerar alltid fullständig data, den påverkas inte av provläget, och dess användning drar inte av de förbrukade byte‑ eller kredit‑värdena.

**Learn more**

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Extracting+document+metainfo)

### Se även

* interface [IDocumentInfo](../../../groupdocs.editor.metadata/idocumentinfo)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
