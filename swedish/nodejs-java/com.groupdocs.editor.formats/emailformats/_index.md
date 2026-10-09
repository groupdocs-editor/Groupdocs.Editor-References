---
title: "EmailFormats"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Innesluter alla e‑postformat."
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

Innesluter alla e-postformat. Inkluderar följande filtyper:
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

Läs mer om e-postformatet [här](../https://docs.fileformat.com/email/).

<br />


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Tnef](#Tnef) | Transport Neutral Encapsulation Format (TNEF) är ett Microsoft-ägda format för att kapsla in e-postbilagor baserat på Messaging Application Programming Interface (MAPI). |
|
|  | [Eml](#Eml) | EML-filformatet representerar e-postmeddelanden som sparats med Outlook och andra relevanta program. |
|
|  | [Emlx](#Emlx) | EMLX-filformatet är implementerat och utvecklat av Apple. |
|
|  | [Msg](#Msg) | MSG är ett filformat som används av Microsoft Outlook och Exchange för att lagra e-postmeddelanden, kontakter, möten eller andra uppgifter. |
|
|  | [Html](#Html) | HTML-formaterade e‑postmeddelanden. |
|
|  | [Mhtml](#Mhtml) | MHTML, en förkortning av "MIME encapsulation of aggregate HTML documents". |
|
|  | [Ics](#Ics) | Internet Calendaring and Scheduling Core Object Specification (iCalendar) är en internetstandard (RFC 2445) för utbyte och distribution av kalenderhändelser och schemaläggning. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) eller vCard är ett digitalt filformat för lagring av kontaktinformation. |
|
|  | [Pst](#Pst) | Filer med .pst‑tillägg representerar Outlook Personal Storage Files (även kallade Personal Storage Table) som lagrar en mängd användarinformation. |
|
|  | [Mbox](#Mbox) | MBox‑filformatet är en generell term som representerar en behållare för en samling e‑postmeddelanden. |
|
|  | [Oft](#Oft) | Filer med .oft‑tillägg är mallfiler som skapas med Microsoft Outlook. |
|
|  | [Ost](#Ost) | Offline Storage Table (OST)-fil representerar användarens brevlådedata i offline‑läge på den lokala maskinen vid registrering mot Exchange Server med Microsoft Outlook. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAll()](#getAll--) | Hämtar en enumererbar samling av alla [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Hämtar en instans av den angivna typen [EmailFormats](../../com.groupdocs.editor.formats/emailformats) som har den angivna filändelsen. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Konverterar en sträng som representerar en filändelse till ett [EmailFormats](../../com.groupdocs.editor.formats/emailformats)-objekt. |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format (TNEF) är ett Microsoft-ägda format för att kapsla in e-postbilagor baserat på Messaging Application Programming Interface (MAPI).
Läs mer om detta filformat
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


EML-filformatet representerar e-postmeddelanden som sparats med Outlook och andra relevanta program.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


EMLX‑filformatet är implementerat och utvecklat av Apple. Apple Mail‑applikationen använder EMLX‑filformatet för att exportera e‑postmeddelandena.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG är ett filformat som används av Microsoft Outlook och Exchange för att lagra e-postmeddelanden, kontakter, möten eller andra uppgifter.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


HTML-formaterade e‑postmeddelanden.


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML, en förkortning av "MIME encapsulation of aggregate HTML documents".


### Ics {#Ics}
```
public static final EmailFormats Ics
```


Internet Calendaring and Scheduling Core Object Specification (iCalendar) är en internetstandard (RFC 2445) för utbyte och distribution av kalenderhändelser och schemaläggning.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (Virtual Card Format) eller vCard är ett digitalt filformat för lagring av kontaktinformation.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


Filer med .pst‑tillägg representerar Outlook Personal Storage Files (även kallade Personal Storage Table) som lagrar en mängd användarinformation.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


MBox‑filformatet är en generell term som representerar en behållare för en samling e‑postmeddelanden.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


Filer med .oft‑tillägg är mallfiler som skapas med Microsoft Outlook.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


Offline Storage Table (OST)-fil representerar användarens brevlådedata i offline‑läge på den lokala maskinen vid registrering mot Exchange Server med Microsoft Outlook.
Läs mer om detta filformat
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


Hämtar en enumererbar samling av alla [EmailFormats](../../com.groupdocs.editor.formats/emailformats).
Värde: En  IEnumerable{EmailFormats}  som innehåller alla instanser av [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


Hämtar en instans av den angivna typen [EmailFormats](../../com.groupdocs.editor.formats/emailformats) som har den angivna filändelsen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filändelse | java.lang.String | Filändelsen för dokumentformatet. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


Konverterar en sträng som representerar en filändelse till ett [EmailFormats](../../com.groupdocs.editor.formats/emailformats)-objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filändelse | java.lang.String | Filändelsen att konvertera. Om filändelsen innehåller flera punkter används delen efter den sista punkten. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

