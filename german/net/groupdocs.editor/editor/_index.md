---
title: "Editor"
second_title: "GroupDocs.Editor für .NET API-Referenz"
description: "Hauptklasse, die Konvertierungsmethoden kapselt. Die Editor-Klasse stellt Methoden zum Laden, Bearbeiten und Speichern von Dokumenten aller unterstützten Formate bereit. Sie ist freigebbar, daher sollte eine using‑Anweisung verwendet oder ihre Ressourcen manuell über den Dispose‑Methodenaufruf freigegeben werden. Das Laden von Dokumenten erfolgt über Konstruktoren. Die Dokumentbearbeitung erfolgt über die Methode Edit und das anschließende Speichern des resultierenden Dokuments über die Methode Save."
type: docs
weight: 20
url: /de/net/groupdocs.editor/editor/
---
## Editor class

Hauptklasse, die Konvertierungsmethoden kapselt. Die Editor‑Klasse stellt Methoden zum Laden, Bearbeiten und Speichern von Dokumenten aller unterstützten Formate bereit. Sie ist freigebbar, daher verwenden Sie eine 'using'-Anweisung oder geben Sie ihre Ressourcen manuell über den Aufruf der Methode 'Dispose()' frei. Das Laden von Dokumenten erfolgt über Konstruktoren. Die Dokumentbearbeitung – über die Methode 'Edit' – und das anschließende Speichern des resultierenden Dokuments nach der Bearbeitung – über die Methode 'Save'.

```csharp
public sealed class Editor : IAuxDisposable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Editor](editor#constructor)(DocumentFormatBase) | Initialisiert eine neue Instanz der Klasse [`Editor`](../editor) und erstellt ein neues leeres Dokument basierend auf dem angegebenen Format. |
| [Editor](editor#constructor_1)(Stream) | Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als Stream). |
| [Editor](editor#constructor_3)(string) | Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als vollständiger Dateipfad) und den Editor-Einstellungen. |
| [Editor](editor#constructor_2)(Stream, ILoadOptions) | Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als Stream) und dessen Ladeoptionen. |
| [Editor](editor#constructor_4)(string, ILoadOptions) | Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als vollständiger Dateipfad) und dessen Ladeoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FormFieldManager](../../groupdocs.editor/editor/formfieldmanager) { get; } | Bietet Zugriff auf Funktionen zur Verwaltung von Formularfeldern im Dokument. |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Gibt an, ob diese Editor-Instanz bereits freigegeben wurde und nicht mehr verwendet werden kann (true) oder noch nicht freigegeben ist und daher aktiv ist (false). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Gibt diese Editor-Instanz frei, sodass sie alle internen Ressourcen freigibt und für weitere Verwendung nicht mehr verfügbar ist. |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Öffnet ein zuvor geladenes Dokument zur Bearbeitung mit den Standardoptionen, indem eine Instanz der Klasse '[`EditableDocument`](../editabledocument)' erzeugt und zurückgegeben wird, die wiederum Methoden zur Erzeugung von HTML-Markup und zugehörigen Ressourcen enthält. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Öffnet ein zuvor geladenes Dokument zur Bearbeitung mit den angegebenen formatbezogenen Optionen, indem eine Instanz der Klasse '[`EditableDocument`](../editabledocument)' erzeugt und zurückgegeben wird, die wiederum Methoden zur Erzeugung von HTML-Markup und zugehörigen Ressourcen enthält. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Gibt Metadaten über das Dokument zurück, das in diese 'Editor'-Instanz geladen wurde. |
| [Save](../../groupdocs.editor/editor/save#save)(Stream) | Speichert den aktuellen Dokumentinhalt in den angegebenen Ausgabestream. |
| [Save](../../groupdocs.editor/editor/save#save_3)(EditableDocument, string) | Konvertiert das angegebene bearbeitete Dokument, dargestellt als Instanz von '[`EditableDocument`](../editabledocument)', in das resultierende Dokument des Formats, das aus der Dateierweiterung ermittelt wird, und speichert dessen Inhalt in eine Datei unter dem angegebenen Dateipfad. |
| [Save](../../groupdocs.editor/editor/save#save_1)(Stream, WordProcessingSaveOptions) | Konvertiert das Originaldokument nach der Modifikation (zum Beispiel, [`FormFieldManager`](./formfieldmanager)), in das resultierende Dokument des angegebenen Formats und speichert dessen Inhalt in den bereitgestellten Stream. |
| [Save](../../groupdocs.editor/editor/save#save_2)(EditableDocument, Stream, ISaveOptions) | Konvertiert das angegebene bearbeitete Dokument, dargestellt als Instanz von '[`EditableDocument`](../editabledocument)', in das resultierende Dokument des angegebenen Formats und speichert dessen Inhalt in den angegebenen Stream. |
| [Save](../../groupdocs.editor/editor/save#save_4)(EditableDocument, string, ISaveOptions) | Konvertiert das angegebene bearbeitete Dokument, dargestellt als Instanz von '[`EditableDocument`](../editabledocument)', in das resultierende Dokument des angegebenen Formats und speichert dessen Inhalt in eine Datei über den angegebenen Dateipfad. |

## Ereignisse

| Name | Beschreibung |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Ereignis, das auftritt, wenn diese Editor-Instanz mit allen internen Ressourcen freigegeben wird. |

### Hinweise

Die Editor-Klasse sollte als Einstiegspunkt und Root-Objekt von GroupDocs.Editor betrachtet werden. Alle Vorgänge werden über diese Klasse ausgeführt. Die typische Verwendung der Editor-Klasse für die Durchführung einer vollständigen Dokumentenbearbeitungspipeline ist wie folgt:

1. Laden Sie ein Dokument in die Editor-Instanz über deren Konstruktor.
2. Optional können Sie den Dokumenttyp mit der Methode [`GetDocumentInfo`](./getdocumentinfo) ermitteln.
3. Öffnen Sie ein Dokument zur Bearbeitung, indem Sie die Methode [`Edit`](./edit) aufrufen und daraus eine Instanz der Klasse [`EditableDocument`](../editabledocument) erhalten.
4. Bearbeiten Sie den Dokumentinhalt clientseitig mit einem beliebigen WYSIWYG-HTML-Editor.
5. Erstellen Sie eine neue Instanz von [`EditableDocument`](../editabledocument) aus dem bearbeiteten Dokumentinhalt.
6. Speichern Sie ein bearbeitetes Dokument in ein Ausgabeformat, indem Sie die Methode [`Save`](./save) aufrufen.
7. Freigeben einer Instanz der Editor-Klasse über den 'using'-Operator oder manuell.

### Siehe auch

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
