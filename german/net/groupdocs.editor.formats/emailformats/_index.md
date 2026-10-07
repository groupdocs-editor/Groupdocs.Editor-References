---
title: "EmailFormats"
second_title: "GroupDocs.Editor für .NET API-Referenz"
description: "Kapselt alle E‑Mail-Formate. Enthält die folgenden Dateitypen Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml."
type: docs
weight: 90
url: /de/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

Kapselt alle E‑Mail-Formate. Enthält die folgenden Dateitypen: [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public class EmailFormats : DocumentFormatBase
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Ermittelt die Dateierweiterung des Dokumentformats. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Ermittelt die Formatfamilie, zu der das Dokumentformat gehört. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Ermittelt die eindeutige Kennung für die Formatfamilie. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Ermittelt den MIME-Typ des Dokumentformats. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Ermittelt den Namen der Formatfamilie. |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | Liefert eine aufzählbare Sammlung aller [`EmailFormats`](../emailformats). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Ruft eine Instanz des angegebenen Typs [`EmailFormats`](../emailformats) ab, die die angegebene Dateierweiterung hat. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bestimmt, ob diese Instanz gleich der angegebenen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase)-Instanz ist. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bestimmt, ob diese Instanz gleich der angegebenen [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat)-Instanz ist. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bestimmt, ob diese Instanz gleich der angegebenen [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase)-Instanz ist. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Gibt einen Hashcode für das aktuelle Objekt zurück. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [`EmailFormats`](../emailformats)-Objekt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | Das EML-Dateiformat stellt E‑Mail‑Nachrichten dar, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Das EMLX-Dateiformat wird von Apple implementiert und entwickelt. Die Apple‑Mail‑Anwendung verwendet das EMLX-Dateiformat zum Exportieren von E‑Mails. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML‑formatierte E‑Mails. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Die Internet Calendaring and Scheduling Core Object Specification (iCalendar) ist ein Internetstandard (RFC 2445) zum Austausch und zur Bereitstellung von Kalenderereignissen und Terminplanung. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | Das MBox-Dateiformat ist ein generischer Begriff, der einen Container für eine Sammlung von elektronischen Mailnachrichten darstellt. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, eine Abkürzung für "MIME encapsulation of aggregate HTML documents". |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG ist ein Dateiformat, das von Microsoft Outlook und Exchange verwendet wird, um E‑Mail‑Nachrichten, Kontakte, Termine oder andere Aufgaben zu speichern. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Dateien mit der Erweiterung .oft sind Vorlagendateien, die mit Microsoft Outlook erstellt werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Die Offline Storage Table (OST)-Datei stellt die Postfachdaten des Benutzers im Offline‑Modus auf dem lokalen Rechner dar, nachdem er sich mit dem Exchange‑Server über Microsoft Outlook registriert hat. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/email/ost/). |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Dateien mit der Erweiterung .pst stellen Outlook Personal Storage Files (auch Personal Storage Table genannt) dar, die verschiedene Benutzerdaten speichern. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/email/pst/). |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) ist ein proprietäres Microsoft‑Format zum Kapseln von E‑Mail‑Anhängen basierend auf der Messaging Application Programming Interface (MAPI). Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) oder vCard ist ein digitales Dateiformat zum Speichern von Kontaktinformationen. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/email/vcf/). |

### Hinweise

Erfahren Sie mehr über das E‑Mail‑Format [hier](https://docs.fileformat.com/email/).

### Siehe auch

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
