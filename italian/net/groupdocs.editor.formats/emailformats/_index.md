---
title: EmailFormats
second_title: GroupDocs.Editor per Riferimento API .NET
description: Incapsula tutti i formati di posta elettronica. Include i seguenti tipi di file Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml .
type: docs
weight: 60
url: /it/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

Incapsula tutti i formati di posta elettronica. Include i seguenti tipi di file: [`Tnef`](./tnef) , [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Html`](./html) , [`Mhtml`](./mhtml) .

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | Nell'implementazione del tipo dovrebbe restituire l'estensione del file di formato (senza il carattere punto iniziale). |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | Nell'implementazione il tipo dovrebbe restituire un codice MIME per il formato specificato |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | Nell'implementazione il tipo dovrebbe restituire il formato formale completo name |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Restituisce l'istanza di[`EmailFormats`](../emailformats) struttura, associata all'estensione del nome file specificata o genera un'eccezione, se l'estensione non può essere analizzata correttamente |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | Determina se questa istanza è uguale all'altra istanza email specificata |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | Determina se questa istanza è uguale all'altro IDocumentFormat specificato instance |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | Determina se questa istanza è uguale all'altro oggetto specificato, che è presumibilmente di Email in box |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | Restituisce un codice hash, immutabile per questa istanza |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | Restituisce un nome di formato di questo formato |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | Controlla due istanze Email sull'uguaglianza |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | Controlla due istanze email date sulla disuguaglianza |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | Il formato di file EML rappresenta i messaggi di posta elettronica salvati utilizzando Outlook e altre applicazioni pertinenti. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/email/eml/) . |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Il formato file EMLX è implementato e sviluppato da Apple. L'applicazione Apple Mail utilizza il formato di file EMLX per l'esportazione delle e-mail. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/email/emlx/) . |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | Email in formato HTML. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Internet Calendaring and Scheduling Core Object Specification (iCalendar) è uno standard Internet (RFC 2445) per lo scambio e la distribuzione degli eventi di calendario e della pianificazione. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/email/ics/) . |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | Il formato file MBox è un termine generico che rappresenta un contenitore per la raccolta di messaggi di posta elettronica. Ulteriori informazioni su questo formato file[Qui](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, sigla di "incapsulamento MIME di documenti HTML aggregati" |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG è un formato di file utilizzato da Microsoft Outlook ed Exchange per archiviare messaggi e-mail, contatti, appuntamenti o altre attività. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/email/msg/) . |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | I file con estensione .oft sono file modello creati utilizzando Microsoft Outlook. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/email/oft/) . |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Il file OST (Offline Storage Table) rappresenta i dati della casella di posta dell'utente in modalità offline sul computer locale al momento della registrazione con Exchange Server utilizzando Microsoft Outlook. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/email/ost/) . |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | I file con estensione .pst rappresentano i file di archiviazione personale di Outlook (chiamati anche tabella di archiviazione personale) che memorizzano una varietà di informazioni sull'utente. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/email/pst/) . |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) è un formato proprietario di Microsoft per l'incapsulamento di allegati e-mail basati su Messaging Application Programming Interface (MAPI). Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/email/tnef/) . |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) o vCard è un formato di file digitale per la memorizzazione delle informazioni di contatto. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/email/vcf/) . |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | Restituisce una classe interna, che fornisce possibilità enumerabili su tutti i formati di posta elettronica esistenti |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | Implementa l'interfaccia generica IEnumerable, che abilita una possibilità 'foreach' per il tipo di email |

### Osservazioni

Ulteriori informazioni sul formato delle email[Qui](https://docs.fileformat.com/email/) .

### Guarda anche

* interface [IDocumentFormat](../idocumentformat)
* spazio dei nomi [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assemblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
