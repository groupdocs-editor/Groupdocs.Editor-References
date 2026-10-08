---
title: "EmailFormats"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Innesluter alla e-postformat. Inkluderar följande filtyper Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml."
type: docs
weight: 90
url: /sv/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

Innesluter alla e-postformat. Inkluderar följande filtyper: [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public class EmailFormats : DocumentFormatBase
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Hämtar filändelsen för dokumentformatet. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Hämtar formatfamiljen som dokumentformatet tillhör. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Hämtar det unika identifieraren för formatfamiljen. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Hämtar MIME-typen för dokumentformatet. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Hämtar namnet på formatfamiljen. |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | Hämtar en uppräkningsbar samling av alla [`EmailFormats`](../emailformats). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Hämtar en instans av den angivna typen [`EmailFormats`](../emailformats) som har den angivna filändelsen. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bestämmer om denna instans är lika med den angivna [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase)-instansen. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bestämmer om denna instans är lika med den angivna [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat)-instansen. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bestämmer om denna instans är lika med den angivna [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase)-instansen. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Returnerar en hashkod för det aktuella objektet. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | Konverterar en sträng som representerar en filändelse till ett [`EmailFormats`](../emailformats)-objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | EML-filformatet representerar e-postmeddelanden som sparats med Outlook och andra relevanta program. Läs mer om detta filformat [här](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | EMLX-filformatet är implementerat och utvecklat av Apple. Apple Mail-applikationen använder EMLX-filformatet för att exportera e-postmeddelanden. Läs mer om detta filformat [här](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML-formaterade e-postmeddelanden. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Internet Calendaring and Scheduling Core Object Specification (iCalendar) är en internetstandard (RFC 2445) för utbyte och distribution av kalenderhändelser och schemaläggning. Läs mer om detta filformat [här](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBox-filformatet är en generell term som representerar en behållare för en samling av elektroniska e-postmeddelanden. Läs mer om detta filformat [här](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, en förkortning för "MIME encapsulation of aggregate HTML documents". |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG är ett filformat som används av Microsoft Outlook och Exchange för att lagra e-postmeddelanden, kontakter, möten eller andra uppgifter. Läs mer om detta filformat [här](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Filer med .oft-tillägget är mallfiler som skapas med Microsoft Outlook. Läs mer om detta filformat [här](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Offline Storage Table (OST)-filen representerar användarens brevlådedata i offline‑läge på den lokala datorn vid registrering med Exchange Server via Microsoft Outlook. Läs mer om detta filformat [här](https://docs.fileformat.com/email/ost/). |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Filer med .pst‑extension representerar Outlook Personal Storage Files (även kallade Personal Storage Table) som lagrar en mängd användarinformation. Läs mer om detta filformat [här](https://docs.fileformat.com/email/pst/). |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) är ett Microsoft‑ägt format för inkapsling av e‑postbilagor baserat på Messaging Application Programming Interface (MAPI). Läs mer om detta filformat [här](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) eller vCard är ett digitalt filformat för lagring av kontaktinformation. Läs mer om detta filformat [här](https://docs.fileformat.com/email/vcf/). |

### Anmärkningar

Läs mer om e‑postformat [här](https://docs.fileformat.com/email/).

### Se även

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
