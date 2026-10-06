---
title: "EmailFormats"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Kapselt alle E‑Mail-Formate."
type: docs
weight: 11
url: /de/java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

Kapselt alle E‑Mail‑Formate. Enthält die folgenden Dateitypen:
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

Erfahren Sie mehr über das E‑Mail‑Format [hier](../https://docs.fileformat.com/email/).

<br />


## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Tnef](#Tnef) | Transport Neutral Encapsulation Format (TNEF) ist ein proprietäres Microsoft‑Format zum Kapseln von E‑Mail‑Anhängen, basierend auf der Messaging Application Programming Interface (MAPI). |
|
|  | [Eml](#Eml) | Das EML-Dateiformat stellt E‑Mail‑Nachrichten dar, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. |
|
|  | [Emlx](#Emlx) | Das EMLX-Dateiformat wird von Apple implementiert und entwickelt. |
|
|  | [Msg](#Msg) | MSG ist ein Dateiformat, das von Microsoft Outlook und Exchange verwendet wird, um E‑Mail‑Nachrichten, Kontakte, Termine oder andere Aufgaben zu speichern. |
|
|  | [Html](#Html) | HTML‑formatierte E‑Mails. |
|
|  | [Mhtml](#Mhtml) | MHTML, ein Akronym für „MIME encapsulation of aggregate HTML documents“. |
|
|  | [Ics](#Ics) | Die Internet Calendaring and Scheduling Core Object Specification (iCalendar) ist ein Internetstandard (RFC 2445) zum Austausch und zur Bereitstellung von Kalenderereignissen und Terminplanung. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) oder vCard ist ein digitales Dateiformat zum Speichern von Kontaktinformationen. |
|
|  | [Pst](#Pst) | Dateien mit der Erweiterung .pst stellen Outlook Personal Storage Files (auch Personal Storage Table genannt) dar, die verschiedene Benutzerdaten speichern. |
|
|  | [Mbox](#Mbox) | Das MBox-Dateiformat ist ein generischer Begriff für einen Container, der eine Sammlung von elektronischen Nachrichten enthält. |
|
|  | [Oft](#Oft) | Dateien mit der Erweiterung .oft sind Vorlagendateien, die mit Microsoft Outlook erstellt werden. |
|
|  | [Ost](#Ost) | Die Offline Storage Table (OST)-Datei stellt die Postfachdaten des Benutzers im Offline‑Modus auf dem lokalen Rechner nach der Registrierung beim Exchange‑Server mit Microsoft Outlook dar. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getAll()](#getAll--) | Liefert eine aufzählbare Sammlung aller [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ruft eine Instanz des angegebenen Typs [EmailFormats](../../com.groupdocs.editor.formats/emailformats) ab, die die angegebene Dateierweiterung besitzt. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [EmailFormats](../../com.groupdocs.editor.formats/emailformats)-Objekt. |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format (TNEF) ist ein proprietäres Microsoft‑Format zum Kapseln von E‑Mail‑Anhängen, basierend auf der Messaging Application Programming Interface (MAPI).
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


Das EML-Dateiformat stellt E‑Mail‑Nachrichten dar, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


Das EMLX-Dateiformat wird von Apple implementiert und entwickelt. Die Apple‑Mail‑Anwendung verwendet das EMLX-Dateiformat zum Exportieren von E‑Mails.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG ist ein Dateiformat, das von Microsoft Outlook und Exchange verwendet wird, um E‑Mail‑Nachrichten, Kontakte, Termine oder andere Aufgaben zu speichern.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


HTML‑formatierte E‑Mails.


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML, ein Akronym für „MIME encapsulation of aggregate HTML documents“.


### Ics {#Ics}
```
public static final EmailFormats Ics
```


Die Internet Calendaring and Scheduling Core Object Specification (iCalendar) ist ein Internetstandard (RFC 2445) zum Austausch und zur Bereitstellung von Kalenderereignissen und Terminplanung.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (Virtual Card Format) oder vCard ist ein digitales Dateiformat zum Speichern von Kontaktinformationen.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


Dateien mit der Erweiterung .pst stellen Outlook Personal Storage Files (auch Personal Storage Table genannt) dar, die verschiedene Benutzerdaten speichern.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


Das MBox-Dateiformat ist ein generischer Begriff für einen Container, der eine Sammlung von elektronischen Nachrichten enthält.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


Dateien mit der Erweiterung .oft sind Vorlagendateien, die mit Microsoft Outlook erstellt werden.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


Die Offline Storage Table (OST)-Datei stellt die Postfachdaten des Benutzers im Offline‑Modus auf dem lokalen Rechner nach der Registrierung beim Exchange‑Server mit Microsoft Outlook dar.
Erfahren Sie mehr über dieses Dateiformat
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


Liefert eine aufzählbare Sammlung aller [EmailFormats](../../com.groupdocs.editor.formats/emailformats).
Wert: Ein IEnumerable{EmailFormats}, das alle Instanzen von [EmailFormats](../../com.groupdocs.editor.formats/emailformats) enthält.


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


Ruft eine Instanz des angegebenen Typs [EmailFormats](../../com.groupdocs.editor.formats/emailformats) ab, die die angegebene Dateierweiterung besitzt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Erweiterung | java.lang.String | Die Dateierweiterung des Dokumentformats. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [EmailFormats](../../com.groupdocs.editor.formats/emailformats)-Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Erweiterung | java.lang.String | Die Dateierweiterung zum Konvertieren. Wenn die Erweiterung mehrere Punkte enthält, wird der Teil nach dem letzten Punkt verwendet. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

