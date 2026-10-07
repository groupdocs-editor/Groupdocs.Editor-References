---
title: "EmailFormats"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Incapsula tutti i formati email."
type: docs
weight: 11
url: /it/java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

Incapsula tutti i formati email. Include i seguenti tipi di file:
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

Scopri di più sul formato delle email [qui](../https://docs.fileformat.com/email/).

<br />


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Tnef](#Tnef) | Transport Neutral Encapsulation Format (TNEF) è un formato proprietario Microsoft per l'incapsulamento degli allegati email basato su Messaging Application Programming Interface (MAPI). |
|
|  | [Eml](#Eml) | Il formato file EML rappresenta i messaggi email salvati utilizzando Outlook e altre applicazioni pertinenti. |
|
|  | [Emlx](#Emlx) | Il formato file EMLX è implementato e sviluppato da Apple. |
|
|  | [Msg](#Msg) | MSG è un formato file usato da Microsoft Outlook e Exchange per archiviare messaggi email, contatti, appuntamenti o altre attività. |
|
|  | [Html](#Html) | Email formattate in HTML. |
|
|  | [Mhtml](#Mhtml) | MHTML, un acronimo di "MIME encapsulation of aggregate HTML documents". |
|
|  | [Ics](#Ics) | Internet Calendaring and Scheduling Core Object Specification (iCalendar) è uno standard internet (RFC 2445) per lo scambio e la distribuzione di eventi di calendario e pianificazione. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) o vCard è un formato file digitale per la memorizzazione delle informazioni di contatto. |
|
|  | [Pst](#Pst) | I file con estensione .pst rappresentano Outlook Personal Storage Files (noti anche come Personal Storage Table) che memorizzano una varietà di informazioni dell'utente. |
|
|  | [Mbox](#Mbox) | Il formato file MBox è un termine generico che rappresenta un contenitore per una collezione di messaggi di posta elettronica. |
|
|  | [Oft](#Oft) | I file con estensione .oft sono file modello creati utilizzando Microsoft Outlook. |
|
|  | [Ost](#Ost) | Il file Offline Storage Table (OST) rappresenta i dati della casella di posta dell'utente in modalità offline sulla macchina locale al momento della registrazione al server Exchange utilizzando Microsoft Outlook. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getAll()](#getAll--) | Ottiene una collezione enumerabile di tutti i [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Recupera un'istanza del tipo specificato [EmailFormats](../../com.groupdocs.editor.formats/emailformats) che ha l'estensione di file specificata. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Converte una stringa che rappresenta un'estensione di file in un oggetto [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format (TNEF) è un formato proprietario Microsoft per l'incapsulamento degli allegati email basato su Messaging Application Programming Interface (MAPI).
Maggiori informazioni su questo formato di file
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


Il formato file EML rappresenta i messaggi email salvati utilizzando Outlook e altre applicazioni pertinenti.
Maggiori informazioni su questo formato di file
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


Il formato file EMLX è implementato e sviluppato da Apple. L'applicazione Apple Mail utilizza il formato file EMLX per esportare le email.
Maggiori informazioni su questo formato di file
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG è un formato file usato da Microsoft Outlook e Exchange per archiviare messaggi email, contatti, appuntamenti o altre attività.
Maggiori informazioni su questo formato di file
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


Email formattate in HTML.


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML, un acronimo di "MIME encapsulation of aggregate HTML documents".


### Ics {#Ics}
```
public static final EmailFormats Ics
```


Internet Calendaring and Scheduling Core Object Specification (iCalendar) è uno standard internet (RFC 2445) per lo scambio e la distribuzione di eventi di calendario e pianificazione.
Maggiori informazioni su questo formato di file
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (Virtual Card Format) o vCard è un formato file digitale per la memorizzazione delle informazioni di contatto.
Maggiori informazioni su questo formato di file
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


I file con estensione .pst rappresentano Outlook Personal Storage Files (noti anche come Personal Storage Table) che memorizzano una varietà di informazioni dell'utente.
Maggiori informazioni su questo formato di file
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


Il formato file MBox è un termine generico che rappresenta un contenitore per una collezione di messaggi di posta elettronica.
Maggiori informazioni su questo formato di file
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


I file con estensione .oft sono file modello creati utilizzando Microsoft Outlook.
Maggiori informazioni su questo formato di file
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


Il file Offline Storage Table (OST) rappresenta i dati della casella di posta dell'utente in modalità offline sulla macchina locale al momento della registrazione al server Exchange utilizzando Microsoft Outlook.
Maggiori informazioni su questo formato di file
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


Ottiene una collezione enumerabile di tutti i [EmailFormats](../../com.groupdocs.editor.formats/emailformats).
Valore: Un IEnumerable{EmailFormats} contenente tutte le istanze di [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


Recupera un'istanza del tipo specificato [EmailFormats](../../com.groupdocs.editor.formats/emailformats) che ha l'estensione di file specificata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | estensione | java.lang.String | L'estensione del file del formato del documento. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


Converte una stringa che rappresenta un'estensione di file in un oggetto [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | estensione | java.lang.String | L'estensione del file da convertire. Se l'estensione contiene più punti, viene utilizzata la parte dopo l'ultimo punto. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

