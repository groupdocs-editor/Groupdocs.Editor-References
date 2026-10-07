---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor für .NET API-Referenz"
description: "Kapselt alle WordProcessing-Formate. Enthält die folgenden Dateitypen"
type: docs
weight: 150
url: /de/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

Kapselt alle WordProcessing-Formate. Enthält die folgenden Dateitypen:

* [`Doc`](./doc)
* [`Docm`](./docm)
* [`Docx`](./docx)
* [`Dot`](./dot)
* [`Dotm`](./dotm)
* [`Dotx`](./dotx)
* [`FlatOpc`](./flatopc)
* [`Odt`](./odt)
* [`Ott`](./ott)
* [`Rtf`](./rtf)
* [`WordML`](./wordml)

Erfahren Sie mehr über Word Processing-Formate [here](https://wiki.fileformat.com/word-processing).

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Ermittelt die Dateierweiterung des Dokumentformats. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Ermittelt die Formatfamilie, zu der das Dokumentformat gehört. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Ermittelt die eindeutige Kennung für die Formatfamilie. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Ermittelt den MIME-Typ des Dokumentformats. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Ermittelt den Namen der Formatfamilie. |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | Gibt eine aufzählbare Sammlung aller [`WordProcessingFormats`](../wordprocessingformats) zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Ruft eine Instanz des angegebenen Typs [`WordProcessingFormats`](../wordprocessingformats) ab, die die angegebene Dateierweiterung hat. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bestimmt, ob diese Instanz gleich der angegebenen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase)-Instanz ist. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bestimmt, ob diese Instanz gleich der angegebenen [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat)-Instanz ist. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bestimmt, ob diese Instanz gleich der angegebenen [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase)-Instanz ist. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Gibt einen Hashcode für das aktuelle Objekt zurück. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [`WordProcessingFormats`](../wordprocessingformats)-Objekt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | Das MS Word 97-2007 Binärdateiformat (DOC) stellt Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsprogrammen im Binärformat erzeugt wurden. Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML-Dokumente mit Makros (DOCM) sind von Microsoft Word 2007 oder höher erzeugte Dokumente mit der Möglichkeit, Makros auszuführen. Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML-Dokument ohne Makros (DOCX) ist ein bekanntes Format für Microsoft Word-Dokumente. Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007-Vorlage (DOT) sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vordefinierte Einstellungen für die Erstellung weiterer DOC- oder DOCX-Dateien zu besitzen. Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML-Vorlage mit Makros (DOTM) stellt Vorlagendateien dar, die mit Microsoft Word 2007 oder höher erstellt wurden. Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML-Vorlage ohne Makros (DOTX) sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vordefinierte Einstellungen für die Erstellung weiterer DOCX-Dateien zu besitzen. Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML, gespeichert in einer flachen XML-Datei anstelle eines ZIP-Pakets. |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Open Document Format Textdokumente (ODT) sind Dokumente, die mit Textverarbeitungsprogrammen erstellt werden, die auf dem OpenDocument-Textdateiformat basieren. Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format Text Document Template (OTT) stellt Vorlagendokumente dar, die von Anwendungen in Übereinstimmung mit dem OASIS‑OpenDocument‑Standardformat erzeugt werden. Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) ist ein Verfahren zur Kodierung von formatiertem Text und Grafiken zur Verwendung in Anwendungen. Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML‑Format — WordProcessingML oder WordML (.XML). |

### Siehe auch

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
