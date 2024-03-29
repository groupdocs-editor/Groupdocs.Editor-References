---
title: WordProcessingEditOptions
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Ermöglicht das Festlegen benutzerdefinierter Optionen zum Bearbeiten von Dokumenten aller unterstützten WordProcessing Wordskompatiblen Formate wie DOCX RTF ODT usw.
type: docs
weight: 1200
url: /de/net/groupdocs.editor.options/wordprocessingeditoptions/
---
## WordProcessingEditOptions class

Ermöglicht das Festlegen benutzerdefinierter Optionen zum Bearbeiten von Dokumenten aller unterstützten WordProcessing (Words-kompatiblen) Formate wie DOC(X), RTF, ODT usw.

```csharp
public class WordProcessingEditOptions : IEditOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor)() | Erstellt eine neue Instanz der WordProcessingEditOptions-Klasse und gibt sie zurück, wobei alle Optionen auf ihre Standardwerte gesetzt werden |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor_1)(bool) | Erstellt und gibt eine neue Instanz der WordProcessingEditOptions-Klasse mit angegebener Paginierung und Standardeinstellung für alle anderen Optionen zurück |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/wordprocessingeditoptions/enablelanguageinformation) { get; set; } | Gibt an, ob Sprachinformationen in Form von „lang“-HTML-Attributen in das HTML-Markup exportiert werden. Diese Option kann für die Roundtrip-Konvertierung der mehrsprachigen Dokumente nützlich sein. Standardmäßig ist es deaktiviert (false). |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingeditoptions/enablepagination) { get; set; } | Ermöglicht das Aktivieren oder Deaktivieren der Paginierung im resultierenden HTML-Dokument. Standardmäßig ist deaktiviert (false). |
| [ExtractOnlyUsedFont](../../groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob nur Schriftartressourcen extrahiert werden sollen, die im Textinhalt des Dokuments verwendet werden. |
| [FontExtraction](../../groupdocs.editor.options/wordprocessingeditoptions/fontextraction) { get; set; } | Verantwortlich für das Extrahieren von Schriftartressourcen, die im eingegebenen WordProcessing-Dokument verwendet werden. Extrahiert standardmäßig keine Schriftarten (NotExtract). |
| [InputControlsClassName](../../groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname) { get; set; } | Ermöglicht die Angabe eines Klassennamens, der in jedem HTML-Element zu den 'class'-Attributen hinzugefügt wird, das ein Feld im eingegebenen WordProcessing-Dokument darstellt. Standardmäßig ist NULL – „class“-Attribute werden nicht angewendet. |

### Siehe auch

* interface [IEditOptions](../ieditoptions)
* namensraum [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
