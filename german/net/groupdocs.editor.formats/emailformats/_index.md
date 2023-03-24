---
title: EmailFormats
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Kapselt alle EMailFormate. Enthält die folgenden Dateitypen Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml .
type: docs
weight: 60
url: /de/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

Kapselt alle E-Mail-Formate. Enthält die folgenden Dateitypen: [`Tnef`](./tnef) , [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Html`](./html) , [`Mhtml`](./mhtml) .

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | Beim Implementieren des Typs sollte die Formatdateierweiterung (ohne führendes Punktzeichen) zurückgegeben werden. |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | Bei der Implementierung sollte der Typ einen MIME-Code für das angegebene Format zurückgeben |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | Beim Implementieren des Typs sollte das vollständige formale Format name zurückgegeben werden |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Gibt eine Instanz von zurück[`EmailFormats`](../emailformats) Struktur, die der angegebenen Dateinamenerweiterung zugeordnet ist, oder löst eine Ausnahme aus, wenn die Erweiterung nicht richtig analysiert werden kann |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | Bestimmt, ob diese Instanz gleich der anderen angegebenen E-Mail-Instanz ist |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | Bestimmt, ob diese Instanz gleich dem anderen angegebenen IDocumentFormat ist instance |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | Ermittelt, ob diese Instanz gleich dem anderen angegebenen Objekt ist, das vermutlich eine Boxed Email ist |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | Gibt einen Hash-Code zurück, der für diese Instanz unveränderlich ist |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | Gibt einen Formatnamen dieses Formats zurück |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | Prüft zwei angegebene E-Mail-Instanzen auf Gleichheit |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | Prüft zwei angegebene E-Mail-Instanzen auf Ungleichheit |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | Das EML-Dateiformat stellt E-Mail-Nachrichten dar, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/email/eml/) . |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Das EMLX-Dateiformat wird von Apple implementiert und entwickelt. Die Apple Mail-Anwendung verwendet das EMLX-Dateiformat zum Exportieren der E-Mails. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/email/emlx/) . |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML-formatierte E-Mails. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Die Internet Calendaring and Scheduling Core Object Specification (iCalendar) ist ein Internetstandard (RFC 2445) zum Austauschen und Bereitstellen von Kalenderereignissen und Zeitplänen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/email/ics/) . |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | Das MBox-Dateiformat ist ein allgemeiner Begriff, der einen Container zum Sammeln von E-Mail-Nachrichten darstellt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, ein Initialismus von „MIME-Kapselung von aggregierten HTML-Dokumenten“ |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG ist ein Dateiformat, das von Microsoft Outlook und Exchange zum Speichern von E-Mail-Nachrichten, Kontakten, Terminen oder anderen Aufgaben verwendet wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/email/msg/) . |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Dateien mit der Erweiterung .oft sind Vorlagendateien, die mit Microsoft Outlook erstellt werden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/email/oft/) . |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Die Offlinespeichertabellendatei (OST) stellt die Postfachdaten des Benutzers im Offlinemodus auf dem lokalen Computer nach der Registrierung bei Exchange Server mit Microsoft Outlook dar. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/email/ost/) . |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Dateien mit der Erweiterung .pst stellen persönliche Outlook-Speicherdateien (auch als persönliche Speichertabelle bezeichnet) dar, die verschiedene Benutzerinformationen speichern. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/email/pst/) . |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) ist ein Microsoft-eigenes Format zum Verkapseln von E-Mail-Anhängen auf Basis von Messaging Application Programming Interface (MAPI). Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/email/tnef/) . |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) oder vCard ist ein digitales Dateiformat zum Speichern von Kontaktinformationen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/email/vcf/) . |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | Gibt eine interne Klasse zurück, die aufzählbare Möglichkeiten über alle existierenden E-Mail-Formate bietet |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | Implementiert die generische IEnumerable-Schnittstelle, die eine „Foreach“-Möglichkeit für den E-Mail-Typ ermöglicht |

### Bemerkungen

Weitere Informationen zum E-Mail-Format[Hier](https://docs.fileformat.com/email/) .

### Siehe auch

* interface [IDocumentFormat](../idocumentformat)
* namensraum [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
