---
title: "EmailFormats"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Omvat alle e‑mail‑formaten."
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

Omvat alle e-mailformaten. Bevat de volgende bestandstypen:
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

Meer informatie over e-mailformaten [hier](../https://docs.fileformat.com/email/).

<br />


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Tnef](#Tnef) | Transport Neutral Encapsulation Format (TNEF) is een Microsoft‑eigen formaat voor het encapsuleren van e‑mailbijlagen op basis van Messaging Application Programming Interface (MAPI). |
|
|  | [Eml](#Eml) | Het EML‑bestandsformaat vertegenwoordigt e‑mailberichten die zijn opgeslagen met Outlook en andere relevante toepassingen. |
|
|  | [Emlx](#Emlx) | Het EMLX‑bestandsformaat is geïmplementeerd en ontwikkeld door Apple. |
|
|  | [Msg](#Msg) | MSG is een bestandsformaat dat door Microsoft Outlook en Exchange wordt gebruikt om e‑mailberichten, contactpersonen, afspraken of andere taken op te slaan. |
|
|  | [Html](#Html) | HTML‑geformatteerde e‑mails. |
|
|  | [Mhtml](#Mhtml) | MHTML, een afkorting van "MIME encapsulation of aggregate HTML documents". |
|
|  | [Ics](#Ics) | De Internet Calendaring and Scheduling Core Object Specification (iCalendar) is een internetstandaard (RFC 2445) voor het uitwisselen en implementeren van agenda‑evenementen en planning. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) of vCard is een digitaal bestandsformaat voor het opslaan van contactinformatie. |
|
|  | [Pst](#Pst) | Bestanden met de extensie .pst vertegenwoordigen Outlook Personal Storage Files (ook wel Personal Storage Table genoemd) die diverse gebruikersinformatie opslaan. |
|
|  | [Mbox](#Mbox) | MBox‑bestandsformaat is een algemene term die een container voor een verzameling elektronische e‑mailberichten vertegenwoordigt. |
|
|  | [Oft](#Oft) | Bestanden met de extensie .oft zijn sjabloonbestanden die zijn gemaakt met Microsoft Outlook. |
|
|  | [Ost](#Ost) | Offline Storage Table (OST)‑bestand vertegenwoordigt de mailboxgegevens van de gebruiker in offline‑modus op de lokale machine na registratie bij Exchange Server met Microsoft Outlook. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAll()](#getAll--) | Haalt een doorzoekbare collectie op van alle [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Haalt een instantie op van het opgegeven type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) dat de opgegeven bestandsextensie heeft. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Converteert een tekenreeks die een bestandsextensie vertegenwoordigt naar een [EmailFormats](../../com.groupdocs.editor.formats/emailformats)‑object. |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format (TNEF) is een Microsoft‑eigen formaat voor het encapsuleren van e‑mailbijlagen op basis van Messaging Application Programming Interface (MAPI).
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


Het EML‑bestandsformaat vertegenwoordigt e‑mailberichten die zijn opgeslagen met Outlook en andere relevante toepassingen.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


Het EMLX‑bestandsformaat is geïmplementeerd en ontwikkeld door Apple. De Apple Mail‑applicatie gebruikt het EMLX‑bestandsformaat voor het exporteren van e‑mails.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG is een bestandsformaat dat door Microsoft Outlook en Exchange wordt gebruikt om e‑mailberichten, contactpersonen, afspraken of andere taken op te slaan.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


HTML‑geformatteerde e‑mails.


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML, een afkorting van "MIME encapsulation of aggregate HTML documents".


### Ics {#Ics}
```
public static final EmailFormats Ics
```


De Internet Calendaring and Scheduling Core Object Specification (iCalendar) is een internetstandaard (RFC 2445) voor het uitwisselen en implementeren van agenda‑evenementen en planning.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (Virtual Card Format) of vCard is een digitaal bestandsformaat voor het opslaan van contactinformatie.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


Bestanden met de extensie .pst vertegenwoordigen Outlook Personal Storage Files (ook wel Personal Storage Table genoemd) die diverse gebruikersinformatie opslaan.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


MBox‑bestandsformaat is een algemene term die een container voor een verzameling elektronische e‑mailberichten vertegenwoordigt.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


Bestanden met de extensie .oft zijn sjabloonbestanden die zijn gemaakt met Microsoft Outlook.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


Offline Storage Table (OST)‑bestand vertegenwoordigt de mailboxgegevens van de gebruiker in offline‑modus op de lokale machine na registratie bij Exchange Server met Microsoft Outlook.
Meer informatie over dit bestandsformaat
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


Haalt een doorzoekbare collectie op van alle [EmailFormats](../../com.groupdocs.editor.formats/emailformats).
Waarde: Een IEnumerable{EmailFormats} die alle instanties van [EmailFormats](../../com.groupdocs.editor.formats/emailformats) bevat.


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


Haalt een instantie op van het opgegeven type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) dat de opgegeven bestandsextensie heeft.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | extensie | java.lang.String | De bestandsextensie van het documentformaat. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


Converteert een tekenreeks die een bestandsextensie vertegenwoordigt naar een [EmailFormats](../../com.groupdocs.editor.formats/emailformats)‑object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | extensie | java.lang.String | De bestandsextensie om te converteren. Als de extensie meerdere punten bevat, wordt het deel na het laatste punt gebruikt. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

