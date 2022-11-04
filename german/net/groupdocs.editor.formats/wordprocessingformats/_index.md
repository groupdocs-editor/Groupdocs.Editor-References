---
title: WordProcessingFormats
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Kapselt alle WordProcessingFormate. Enthält die folgenden Dateitypen Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . Erfahren Sie mehr über Textverarbeitungsformatehierhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 170
url: /de/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

Kapselt alle WordProcessing-Formate. Enthält die folgenden Dateitypen: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . Erfahren Sie mehr über Textverarbeitungsformate[hier](https://wiki.fileformat.com/word-processing) .

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | Gibt eine Erweiterung (ohne führenden Punkt) dieses WordProcessing-Formats in Kleinbuchstaben zurück |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | Gibt einen MIME-Code für dieses Format zurück |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | Gibt einen formalen vollständigen Namen dieses WordProcessing-Formats zurück |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Gibt eine Instanz von zurück[`WordProcessingFormats`](../wordprocessingformats)Struktur, die der angegebenen Dateinamenerweiterung zugeordnet ist, oder löst eine Ausnahme aus, wenn die Erweiterung nicht richtig analysiert werden kann |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | Bestimmt, ob diese Instanz gleich dem anderen angegebenen IDocumentFormat ist instance |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | Bestimmt, ob diese Instanz gleich dem anderen angegebenen Objekt ist, das vermutlich von WordProcessingFormats in Box ist |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | Bestimmt, ob diese Instanz gleich den anderen angegebenen WordProcessingFormats ist instance |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | Gibt einen Hash-Code zurück, der für diese Instanz unveränderlich ist |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | Gibt den Namen dieses bestimmten Formats zurück, genau wie „Name“ property |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | Prüft zwei angegebene WordProcessingFormats-Instanzen auf Gleichheit |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | Gibt einen Bytewert aus dem zugrunde liegenden Feld des angegebenen WordProcessingFormats zurück. instance (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | Prüft zwei angegebene WordProcessingFormats-Instanzen auf Ungleichheit |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 Binary File Format (DOC) stellt Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsdokumenten im binären Dateiformat erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML Macro-Enabled Document (DOCM)-Dateien sind Microsoft Word 2007 oder höher generierte Dokumente mit der Fähigkeit, Makros auszuführen. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) ist ein bekanntes Format für Microsoft Word-Dokumente. Die Struktur dieses neuen Dokumentformats, das 2007 mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde, wurde von einer reinen Binärdatei in eine Kombination aus XML- und Binärdateien geändert. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 Template sind von Microsoft Word erstellte Vorlagendateien mit vorformatierten Einstellungen für die Generierung weiterer DOC- oder DOCX-Dateien. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) stellt eine Vorlagendatei dar, die mit Microsoft Word 2007 oder höher erstellt wurde. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) sind von Microsoft Word erstellte Vorlagendateien mit vorformatierten Einstellungen für die Generierung weiterer DOCX-Dateien. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML gespeichert in einer flachen XML-Datei anstelle eines ZIP-Pakets |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | ODT-Dateien (Open Document Format) sind Dokumenttypen, die mit Textverarbeitungsprogrammen erstellt wurden, die auf dem OpenDocument-Textdateiformat basieren. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format Text Document Template (OTT) stellen Vorlagendokumente dar, die von Anwendungen in Übereinstimmung mit dem OpenDocument-Standardformat von OASIS generiert wurden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) ist eine Methode zur Codierung von formatiertem Text und Grafiken zur Verwendung in Anwendungen. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML-Format – WordProcessingML oder WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | Gibt eine interne Klasse zurück, die aufzählbare Möglichkeiten über alle existierenden WordProcessing-Formate bietet |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | Implementiert die generische IEnumerable-Schnittstelle, die eine „Foreach“-Möglichkeit für die WordProcessingFormats type ermöglicht |

### Bemerkungen

MIME-Codes werden aus den angegebenen Ressourcen abgerufen: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/ previous-versions//cc179224(v=technet.10)

### Siehe auch

* interface [IDocumentFormat](../idocumentformat)
* namensraum [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
