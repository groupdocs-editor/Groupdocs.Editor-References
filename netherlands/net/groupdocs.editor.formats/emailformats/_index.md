---
title: "EmailFormats"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Omvat alle e‑mailformaten. Bevat de volgende bestandstypen Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml."
type: docs
weight: 90
url: /nl/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

Omvat alle e‑mailformaten. Bevat de volgende bestandstypen: [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public class EmailFormats : DocumentFormatBase
```

## Properties

| Name | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Haalt de bestandsextensie van het documentformaat op. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Haalt de formatfamilie op waartoe het documentformaat behoort. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Haalt de unieke identifier op voor de formatfamilie. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Haalt het MIME-type van het documentformaat op. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Haalt de naam van de formatfamilie op. |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | Haalt een doorzoekbare collectie op van alle [`EmailFormats`](../emailformats). |

## Methods

| Name | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Haalt een instantie op van het opgegeven type [`EmailFormats`](../emailformats) dat de opgegeven bestandsextensie heeft. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bepaalt of deze instantie gelijk is aan de opgegeven [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) instantie. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bepaalt of deze instantie gelijk is aan de opgegeven [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) instantie. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bepaalt of deze instantie gelijk is aan de opgegeven [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) instantie. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Retourneert een hashcode voor het huidige object. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Retourneert een tekenreeks die het huidige object vertegenwoordigt. |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | Converteert een tekenreeks die een bestandsextensie vertegenwoordigt naar een [`EmailFormats`](../emailformats)-object. |

## Velden

| Name | Beschrijving |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | EML-bestandsformaat vertegenwoordigt e‑mailberichten die zijn opgeslagen met Outlook en andere relevante toepassingen. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Het EMLX-bestandsformaat is geïmplementeerd en ontwikkeld door Apple. De Apple Mail-toepassing gebruikt het EMLX-bestandsformaat voor het exporteren van e‑mails. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML-geformatteerde e‑mails. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | De Internet Calendaring and Scheduling Core Object Specification (iCalendar) is een internetstandaard (RFC 2445) voor het uitwisselen en implementeren van agenda‑evenementen en planning. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBox-bestandsformaat is een algemene term die een container voor een verzameling elektronische e‑mailberichten vertegenwoordigt. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, een afkorting van "MIME encapsulation of aggregate HTML documents". |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG is een bestandsformaat dat door Microsoft Outlook en Exchange wordt gebruikt om e‑mailberichten, contactpersonen, afspraken of andere taken op te slaan. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Bestanden met de .oft-extensie zijn sjabloonbestanden die zijn gemaakt met Microsoft Outlook. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Het Offline Storage Table (OST)-bestand vertegenwoordigt de mailboxgegevens van de gebruiker in offline‑modus op de lokale machine bij registratie bij Exchange Server met Microsoft Outlook. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/email/ost/). |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Bestanden met de extensie .pst vertegenwoordigen Outlook Personal Storage Files (ook wel Personal Storage Table genoemd) die verschillende gebruikersinformatie opslaan. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/email/pst/). |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) is een door Microsoft gepatenteerd formaat voor het encapsuleren van e‑mailbijlagen op basis van Messaging Application Programming Interface (MAPI). Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) of vCard is een digitaal bestandsformaat voor het opslaan van contactinformatie. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/email/vcf/). |

### Opmerkingen

Meer informatie over e‑mailformaten [hier](https://docs.fileformat.com/email/).

### Zie ook

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
