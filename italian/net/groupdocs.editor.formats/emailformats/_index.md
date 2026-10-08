---
title: "EmailFormats"
second_title: "Riferimento API di GroupDocs.Editor per .NET"
description: "Raccoglie tutti i formati email. Include i seguenti tipi di file Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml."
type: docs
weight: 90
url: /it/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

Raccoglie tutti i formati email. Include i seguenti tipi di file: [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public class EmailFormats : DocumentFormatBase
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Ottiene l'estensione del file del formato di documento. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Ottiene la famiglia di formato a cui appartiene il formato di documento. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Ottiene l'identificatore univoco per la famiglia di formato. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Ottiene il tipo MIME del formato di documento. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Ottiene il nome della famiglia di formato. |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | Ottiene una collezione enumerabile di tutti i [`EmailFormats`](../emailformats). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Recupera un'istanza del tipo specificato [`EmailFormats`](../emailformats) che ha l'estensione di file specificata. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determina se questa istanza è uguale all'istanza specificata [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determina se questa istanza è uguale all'istanza specificata [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determina se questa istanza è uguale all'istanza specificata [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Restituisce un codice hash per l'oggetto corrente. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | Converte una stringa che rappresenta un'estensione di file in un oggetto [`EmailFormats`](../emailformats). |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | Il formato file EML rappresenta i messaggi email salvati usando Outlook e altre applicazioni pertinenti. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Il formato file EMLX è implementato e sviluppato da Apple. L'applicazione Apple Mail utilizza il formato file EMLX per esportare le email. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | Email formattate in HTML. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | La specifica Internet Calendaring and Scheduling Core Object (iCalendar) è uno standard internet (RFC 2445) per lo scambio e la distribuzione di eventi di calendario e pianificazione. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | Il formato file MBox è un termine generico che rappresenta un contenitore per una collezione di messaggi di posta elettronica. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, un acronimo di "MIME encapsulation of aggregate HTML documents". |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG è un formato di file usato da Microsoft Outlook e Exchange per archiviare messaggi email, contatti, appuntamenti o altre attività. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | I file con estensione .oft sono file modello creati utilizzando Microsoft Outlook. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Il file Offline Storage Table (OST) rappresenta i dati della casella di posta dell'utente in modalità offline sul computer locale al momento della registrazione con Exchange Server usando Microsoft Outlook. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/email/ost/). |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | I file con estensione .pst rappresentano i Outlook Personal Storage Files (chiamati anche Personal Storage Table) che memorizzano una varietà di informazioni dell'utente. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/email/pst/). |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Il Transport Neutral Encapsulation Format (TNEF) è un formato proprietario di Microsoft per l'incapsulamento degli allegati email basato su Messaging Application Programming Interface (MAPI). Scopri di più su questo formato di file [qui](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | Il VCF (Virtual Card Format) o vCard è un formato di file digitale per la memorizzazione delle informazioni di contatto. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/email/vcf/). |

### Osservazioni

Scopri di più sul formato delle email [qui](https://docs.fileformat.com/email/).

### Vedi anche

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
