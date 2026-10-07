---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor für .NET API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von WordProcessing‑konformen Dokumenten, nachdem sie bearbeitet wurden"
type: docs
weight: 1240
url: /de/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Ermöglicht das Angeben benutzerdefinierter Optionen zum Erzeugen und Speichern von WordProcessing-konformen Dokumenten nach deren Bearbeitung

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | Dieser parameterlose Konstruktor erstellt eine neue Instanz von WordProcessingSaveOptions mit dem DOCX‑Ausgabeformat (kann anschließend über die Eigenschaft [`OutputFormat`](./outputformat) geändert werden) |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(WordProcessingFormats) | Erstellt eine neue Instanz von WordProcessingSaveOptions mit dem angegebenen obligatorischen WordProcessing‑Ausgabeformat, wobei alle anderen Parameter standardmäßig sind |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Ermöglicht das Aktivieren oder Deaktivieren der Seitennummerierung, die beim Speichern des WordProcessing‑Dokuments verwendet wird. Wenn das Originaldokument im Seitennummerierungsmodus geöffnet und bearbeitet wurde, sollte diese Option ebenfalls aktiviert sein. Standardmäßig ist sie deaktiviert. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Verantwortlich für das Einbetten von Schriftartressourcen in das Ausgabedokument von WordProcessing. Standardmäßig werden keine Schriftarten eingebettet (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Ermöglicht das Überschreiben der Standard‑Locale (Sprache) für das WordProcessing‑Dokument, die bei dessen Erstellung angewendet wird. Wenn sie nicht angegeben ist (Standardwert), erkennt (oder wählt) MS Word (oder ein anderes Programm) die Dokument‑Locale anhand seiner eigenen Einstellungen oder anderer Faktoren. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Ermöglicht das Überschreiben der Locale (Sprache) für das WordProcessing‑Dokument für RTL‑Text (right‑to‑left), die bei dessen Erstellung angewendet wird. Wenn sie nicht angegeben ist (Standardwert), erkennt (oder wählt) MS Word (oder ein anderes Programm) die RTL‑Locale des Dokuments anhand seiner eigenen Einstellungen oder anderer Faktoren. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Ermöglicht das Überschreiben der Locale (Sprache) für das WordProcessing‑Dokument für ostasiatischen Text, die bei dessen Erstellung angewendet wird. Wenn sie nicht angegeben ist (Standardwert), erkennt (oder wählt) MS Word (oder ein anderes Programm) die ostasiatische Locale des Dokuments anhand seiner eigenen Einstellungen oder anderer Faktoren. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Aktiviert Speicheroptimierungsmechanismen während der Dokumenterstellung aus HTML, die die Leistung zugunsten einer verringerten Speichernutzung beeinträchtigen. Das Setzen dieser Option auf true kann den Speicherverbrauch bei der Erstellung großer Dokumente erheblich reduzieren, allerdings auf Kosten einer langsameren Speicherzeit. Standard ist false (Speicheroptimierung ist deaktiviert, um eine bessere Leistung zu erzielen). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Ermöglicht das Angeben eines WordProcessing‑Formats, das zum Speichern des Dokuments verwendet wird |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Ermöglicht das Angeben, Ändern, Abrufen oder Entfernen eines Passworts, das zum Verschlüsseln des erzeugten WordProcessing‑Dokuments verwendet wird. Geben Sie NULL oder einen leeren String an, um das Passwort zu entfernen (zu bereinigen). |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Ermöglicht die Steuerung und Anwendung von Dokumentenschutzoptionen für das WordProcessing‑Dokument beliebigen Formats, das Dokumentenschutz unterstützt. Standardmäßig ist NULL – Dokumentenschutz wird nicht verwendet. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Erstellt und gibt eine vollständige Kopie dieser Instanz der Klasse WordProcessingSaveOptions zurück |

### Hinweise

WordProcessingSaveOptions wird in Situationen angewendet, wenn es eine Instanz der Klasse EditableDocument gibt, die bearbeitete Dokumentinhalte enthält, und es erforderlich ist, diesen Inhalt in ein neues Dokument im WordProcessing-Format zu speichern.

### Siehe auch

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
