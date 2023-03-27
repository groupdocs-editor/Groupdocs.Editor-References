---
title: EmailFormats
second_title: GroupDocs.Editor för .NET API-referens
description: Kapslar in alla epostformat. Inkluderar följande filtyper Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml .
type: docs
weight: 60
url: /sv/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

Kapslar in alla e-postformat. Inkluderar följande filtyper: [`Tnef`](./tnef) , [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Html`](./html) , [`Mhtml`](./mhtml) .

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | Vid implementering ska typen returnera filtillägget i formatet (utan inledande punkttecken). |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | Vid implementering ska typen returnera en MIME-kod för det givna formatet |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | I implementeringstypen ska returnera fullt formellt format name |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Returnerar instans av[`EmailFormats`](../emailformats) struktur, kopplad till angivet filnamnstillägg, eller ger ett undantag, om tillägget inte kan analyseras korrekt |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | Avgör om denna instans är lika med den andra angivna e-postinstansen |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | Bestämmer om denna instans är lika med den andra specificerade IDocumentFormat-instansen |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | Bestämmer om denna instans är lika med det andra angivna objektet, det vill säga antagligen av boxed Email |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | Returnerar en hash-kod, som är oföränderlig för denna instans |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | Returnerar ett formatnamn för detta format |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | Kontrollerar två givna e-postinstanser på equality |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | Kontrollerar två givna e-postinstanser på inequality |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | EML-filformat representerar e-postmeddelanden som sparats med Outlook och andra relevanta applikationer. Läs mer om detta filformat[här](https://docs.fileformat.com/email/eml/) . |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | EMLX-filformatet är implementerat och utvecklat av Apple. Apple Mail-applikationen använder EMLX-filformatet för att exportera e-postmeddelanden. Läs mer om detta filformat[här](https://docs.fileformat.com/email/emlx/) . |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML-formaterade e-postmeddelanden. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Internet Calendar and Scheduling Core Object Specification (iCalendar) är en internetstandard (RFC 2445) för utbyte och distribution av kalenderhändelser och schemaläggning. Läs mer om detta filformat[här](https://docs.fileformat.com/email/ics/) . |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBox-filformat är en generisk term som representerar en behållare för insamling av elektroniska postmeddelanden. Läs mer om detta filformat[här](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, en initialism av "MIME-inkapsling av aggregerade HTML-dokument" |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG är ett filformat som används av Microsoft Outlook och Exchange för att lagra e-postmeddelanden, kontakter, möten eller andra uppgifter. Läs mer om detta filformat[här](https://docs.fileformat.com/email/msg/) . |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Filer med filtillägget .oft är mallfiler som skapas med Microsoft Outlook. Läs mer om detta filformat[här](https://docs.fileformat.com/email/oft/) . |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Offline Storage Table-fil (OST) representerar användarens postlådedata i offlineläge på lokal dator vid registrering med Exchange Server med Microsoft Outlook. Läs mer om detta filformat[här](https://docs.fileformat.com/email/ost/) . |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Filer med tillägget .pst representerar Outlook Personal Storage Files (även kallad Personal Storage Table) som lagrar olika användarinformation. Läs mer om detta filformat[här](https://docs.fileformat.com/email/pst/) . |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) är ett patentskyddat Microsoft, för att kapsla in e-postbilagor baserade på Messaging Application Programming Interface (MAPI). Läs mer om detta filformat[här](https://docs.fileformat.com/email/tnef/) . |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) eller vCard är ett digitalt filformat för att lagra kontaktinformation. Läs mer om detta filformat[här](https://docs.fileformat.com/email/vcf/) . |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | Returnerar en intern klass som ger otaliga möjligheter över alla befintliga e-postformat |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | Implementerar IEnumerable generiskt gränssnitt, som möjliggör en "foreach"-möjlighet för e-posttypen |

### Anmärkningar

Läs mer om e-postformat[här](https://docs.fileformat.com/email/) .

### Se även

* interface [IDocumentFormat](../idocumentformat)
* namnutrymme [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
