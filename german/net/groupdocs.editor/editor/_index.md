---
title: Editor
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Hauptklasse die Konvertierungsmethoden kapselt. EditorKlasse bietet Methoden zum Laden Bearbeiten und Speichern von Dokumenten aller unterstützten Formate. Es ist wegwerfbar verwenden Sie also eine usingDirektive oder entsorgen Sie seine Ressourcen manuell über den Methodenaufruf Dispose. Das Laden von Dokumenten erfolgt über Konstruktoren. Dokumentbearbeitung  durch die Methode Bearbeiten und Zurückspeichern in das resultierende Dokument nach der Bearbeitung  durch die Methode Speichern.
type: docs
weight: 20
url: /de/net/groupdocs.editor/editor/
---
## Editor class

Hauptklasse, die Konvertierungsmethoden kapselt. Editor-Klasse bietet Methoden zum Laden, Bearbeiten und Speichern von Dokumenten aller unterstützten Formate. Es ist wegwerfbar, verwenden Sie also eine 'using'-Direktive oder entsorgen Sie seine Ressourcen manuell über den Methodenaufruf 'Dispose()'. Das Laden von Dokumenten erfolgt über Konstruktoren. Dokumentbearbeitung – durch die Methode „Bearbeiten“ und Zurückspeichern in das resultierende Dokument nach der Bearbeitung – durch die Methode „Speichern“.

```csharp
public sealed class Editor : IAuxDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Editor](editor#constructor)(Func&lt;Stream&gt;) | Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als Stream) |
| [Editor](editor#constructor_2)(string) | Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als vollständiger Dateipfad) |
| [Editor](editor#constructor_1)(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) | Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als Stream) mit seinen Ladeoptionen |
| [Editor](editor#constructor_3)(string, Func&lt;ILoadOptions&gt;) | Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als vollständiger Dateipfad) mit seinen Ladeoptionen |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Gibt an, ob diese Editor-Instanz bereits verworfen wurde und nicht mehr verwendet werden kann (true) oder noch nicht verworfen wurde und somit aktiv ist (false) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Verwirft diese Instanz des Editors, sodass alle internen Ressourcen freigegeben werden und für die weitere Verwendung nicht mehr verfügbar ist |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Öffnet ein zuvor geladenes Dokument zur Bearbeitung unter Verwendung von Standardoptionen durch Generieren und Zurückgeben einer Instanz von '[`EditableDocument`](../editabledocument) -Klasse, die wiederum Methoden zum Erzeugen von HTML-Markup und zugehörigen Ressourcen enthält. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Öffnet ein zuvor geladenes Dokument zur Bearbeitung unter Verwendung angegebener formatspezifischer Optionen durch Generieren und Zurückgeben einer Instanz von '[`EditableDocument`](../editabledocument) -Klasse, die wiederum Methoden zum Erzeugen von HTML-Markup und zugehörigen Ressourcen enthält. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Gibt Metadaten über das Dokument zurück, das in diese 'Editor'-Instanz geladen wurde |
| [Save](../../groupdocs.editor/editor/save#save)(EditableDocument, Stream, ISaveOptions) | Konvertiert das angegebene bearbeitete Dokument, dargestellt als Instanz von '[`EditableDocument`](../editabledocument) , in das resultierende Dokument des angegebenen Formats und speichert seinen Inhalt im angegebenen stream |
| [Save](../../groupdocs.editor/editor/save#save_1)(EditableDocument, string, ISaveOptions) | Konvertiert das angegebene bearbeitete Dokument, dargestellt als Instanz von '[`EditableDocument`](../editabledocument) , in das resultierende Dokument des angegebenen Formats und speichert seinen Inhalt in der Datei unter dem angegebenen Dateipfad |

## Veranstaltungen

| Name | Beschreibung |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Ereignis, das eintritt, wenn diese Editor-Instanz mit all ihren internen Ressourcen verworfen wird |

### Bemerkungen

Die Klasse Editor sollte als Einstiegspunkt und Stammobjekt von GroupDocs.Editor betrachtet werden. Alle Operationen werden mit dieser Klasse ausgeführt. Die typische Verwendung der Editor-Klasse zum Durchführen einer vollständigen Dokumentbearbeitungspipeline ist die nächste:

1. Laden Sie ein Dokument über seinen Konstruktor in die Editor-Instanz.
2. Ermitteln Sie optional einen Dokumenttyp mithilfe von a[`GetDocumentInfo`](./getdocumentinfo) Methode.
3. Öffnen Sie ein Dokument zur Bearbeitung, indem Sie an aufrufen[`Edit`](./edit) -Methode und Abrufen einer Instanz von[`EditableDocument`](../editabledocument) Klasse daraus.
4. Clientseitiges Bearbeiten eines Dokumentinhalts mit einem beliebigen WYSIWYG-HTML-Editor.
5. Erstellen einer neuen Instanz von[`EditableDocument`](../editabledocument) aus bearbeitetem Dokumentinhalt.
6. Speichern eines bearbeiteten Dokuments in einem Ausgabeformat durch Aufrufen von a[`Save`](./save) Methode.
7. Entsorgen einer Instanz der Editor-Klasse über den Operator „using“ oder manuell.

### Siehe auch

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namensraum [GroupDocs.Editor](../../groupdocs.editor)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
