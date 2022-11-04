---
title: WordProcessingSaveOptions
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Ermöglicht das Festlegen benutzerdefinierter Optionen zum Generieren und Speichern von WordProcessingkompatiblen Dokumenten nachdem sie bearbeitet wurden
type: docs
weight: 1010
url: /de/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Ermöglicht das Festlegen benutzerdefinierter Optionen zum Generieren und Speichern von WordProcessing-kompatiblen Dokumenten, nachdem sie bearbeitet wurden

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions)(WordProcessingFormats) | Erstellt eine neue Instanz von WordProcessingSaveOptions mit dem angegebenen obligatorischen WordProcessing-Ausgabeformat, während alle anderen Parameter default sind. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Ermöglicht das Aktivieren oder Deaktivieren der Paginierung, die zum Speichern des WordProcessing-Dokuments verwendet wird. Wenn das Originaldokument im Paginierungsmodus geöffnet und bearbeitet wurde, sollte diese Option ebenfalls aktiviert werden. Standardmäßig ist deaktiviert. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Verantwortlich für das Einbetten von Schriftartressourcen in das ausgegebene WordProcessing-Dokument. Standardmäßig werden keine Schriftarten eingebettet (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Ermöglicht das Überschreiben des Standardgebietsschemas (Sprache) für das WordProcessing-Dokument, das während seiner Erstellung angewendet wird. Wenn nicht angegeben (Standardwert), erkennt (oder wählt) MS Word (oder ein anderes Programm) das Dokumentgebietsschema entsprechend aus an seine eigenen Einstellungen oder andere Faktoren. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Ermöglicht das Überschreiben des Gebietsschemas (Sprache) für das WordProcessing-Dokument für den RTL-Text (von rechts nach links), der während seiner Erstellung angewendet wird. Wenn nicht angegeben (Standardwert), MS Word (oder ein anderes Programm) erkennt (oder wählt) das Dokument RTL locale gemäß seinen eigenen Einstellungen oder anderen Faktoren. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Ermöglicht das Überschreiben des Gebietsschemas (Sprache) für das WordProcessing-Dokument für den ostasiatischen Text, der während seiner Erstellung angewendet wird. Wenn nicht angegeben (Standardwert), erkennt (oder wählt) MS Word (oder ein anderes Programm). ) das Dokument Ostasiatisches Gebietsschema gemäß seinen eigenen Einstellungen oder anderen Faktoren. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Aktiviert Speicheroptimierungsmechanismen während der Dokumentgenerierung aus HTML, wodurch die Leistung durch die Verringerung der Speichernutzung beeinträchtigt wird. Wenn Sie diese Option auf „true“ setzen, kann die Speichernutzung erheblich verringert werden, während große Dokumente auf Kosten einer langsameren Speicherzeit erstellt werden. Der Standardwert ist „false“. (Speicheroptimierung ist zwecks besserer Leistung deaktiviert). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Ermöglicht die Angabe eines WordProcessing-Formats, das zum Speichern des Dokuments verwendet wird |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Ermöglicht das Angeben, Ändern, Abrufen oder Entfernen eines Kennworts, das zum Codieren des generierten Textverarbeitungsdokuments verwendet wird. Geben Sie NULL oder eine leere Zeichenfolge zum Entfernen (Reinigen) des Kennworts an. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Ermöglicht das Steuern und Anwenden der Dokumentenschutzoptionen für das WordProcessing-Dokument eines beliebigen Formats, das den Dokumentenschutz unterstützt. Standardmäßig ist NULL - der Dokumentenschutz wird nicht verwendet. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Erstellt eine vollständige Kopie dieser Instanz von WordProcessingSaveOptions class und gibt sie zurück |

### Bemerkungen

WordProcessingSaveOptions wird in Situationen angewendet, in denen es eine Instanz der EditableDocument-Klasse gibt, die einen bearbeiteten Dokumentinhalt enthält, und es erforderlich ist, diesen Inhalt im neuen Dokument im WordProcessing-Format zu speichern.

### Siehe auch

* interface [ISaveOptions](../isaveoptions)
* namensraum [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
