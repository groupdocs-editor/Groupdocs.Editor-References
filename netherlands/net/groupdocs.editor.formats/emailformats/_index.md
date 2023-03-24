---
title: EmailFormats
second_title: GroupDocs.Editor voor .NET API-referentie
description: Bevat alle emailindelingen. Bevat de volgende bestandstypen Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml .
type: docs
weight: 60
url: /nl/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

Bevat alle e-mailindelingen. Bevat de volgende bestandstypen: [`Tnef`](./tnef) , [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Html`](./html) , [`Mhtml`](./mhtml) .

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | Bij het implementeren moet type de formaatbestandsextensie retourneren (zonder voorlooppuntteken). |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | Bij implementatie moet type een MIME-code retourneren voor het opgegeven formaat |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | Bij implementatie moet het volledige formele formaat name worden geretourneerd |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Retourneert instantie van[`EmailFormats`](../emailformats) structuur, gekoppeld aan de opgegeven bestandsnaamextensie, of genereert een uitzondering als de extensie niet correct kan worden geparseerd |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | Bepaalt of deze instantie gelijk is aan de andere opgegeven e-mailinstantie |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | Bepaalt of deze instantie gelijk is aan de andere opgegeven IDocumentFormat-instantie |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | Bepaalt of deze instantie gelijk is aan het andere gespecificeerde object, dat is vermoedelijk een boxed Email |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | Retourneert een hash-code, die onveranderlijk is voor deze instantie |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | Retourneert een formaatnaam van dit formaat |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | Controleert twee gegeven e-mailinstanties op gelijkheid |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | Controleert twee gegeven e-mailinstanties op ongelijkheid |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | EML-bestandsindeling vertegenwoordigt e-mailberichten die zijn opgeslagen met behulp van Outlook en andere relevante toepassingen. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/email/eml/) . |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Het EMLX-bestandsformaat is geïmplementeerd en ontwikkeld door Apple. De Apple Mail-applicatie gebruikt het EMLX-bestandsformaat voor het exporteren van de e-mails. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/email/emlx/) . |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML-geformatteerde e-mails. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | De Internet Calendaring and Scheduling Core Object Specification (iCalendar) is een internetstandaard (RFC 2445) voor het uitwisselen en implementeren van agenda-afspraken en planning. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/email/ics/) . |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBox-bestandsindeling is een algemene term die staat voor een container voor het verzamelen van elektronische postberichten. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, een beginletter van "MIME-inkapseling van geaggregeerde HTML-documenten" |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG is een bestandsindeling die wordt gebruikt door Microsoft Outlook en Exchange om e-mailberichten, contacten, afspraken of andere taken op te slaan. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/email/msg/) . |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Bestanden met de extensie .oft zijn sjabloonbestanden die zijn gemaakt met Microsoft Outlook. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/email/oft/) . |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Offline Storage Table (OST)-bestand vertegenwoordigt de postbusgegevens van de gebruiker in offlinemodus op een lokale computer na registratie bij Exchange Server met behulp van Microsoft Outlook. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/email/ost/) . |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Bestanden met de extensie .pst vertegenwoordigen persoonlijke opslagbestanden van Outlook (ook wel persoonlijke opslagtabel genoemd) waarin verschillende gebruikersgegevens worden opgeslagen. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/email/pst/) . |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) is eigendom van Microsoft, voor het inkapselen van e-mailbijlagen op basis van Messaging Application Programming Interface (MAPI). Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/email/tnef/) . |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) of vCard is een digitaal bestandsformaat voor het opslaan van contactgegevens. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/email/vcf/) . |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | Retourneert een interne klasse, die talloze mogelijkheden biedt voor alle bestaande e-mailformaten |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | Implementeert IEnumerable generieke interface, die een 'foreach'-mogelijkheid mogelijk maakt voor het e-mailtype |

### Opmerkingen

Meer informatie over e-mailindeling[hier](https://docs.fileformat.com/email/) .

### Zie ook

* interface [IDocumentFormat](../idocumentformat)
* naamruimte [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
