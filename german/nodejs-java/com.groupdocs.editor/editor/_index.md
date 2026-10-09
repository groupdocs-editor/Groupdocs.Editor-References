---
title: "Editor"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Hauptklasse, die Konvertierungsmethoden kapselt."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

Hauptklasse, die Konvertierungsmethoden kapselt.
Die Editor‑Klasse stellt Methoden zum Laden, Bearbeiten und Speichern von Dokumenten aller unterstützten Formate bereit. Sie ist entfernbar, daher verwenden Sie eine 'using'-Anweisung oder geben Sie ihre Ressourcen manuell über den Aufruf der Methode 'Dispose()' frei. Das Laden von Dokumenten erfolgt über Konstruktoren. Das Bearbeiten von Dokumenten – über die Methode 'Edit' – und das anschließende Speichern des resultierenden Dokuments nach der Bearbeitung – über die Methode 'Save'.
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Initialisiert eine neue Instanz der [Editor](../../com.groupdocs.editor/editor)-Klasse und erstellt ein neues leeres Dokument basierend auf dem angegebenen Format. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | Initialisiert eine neue Editor‑Instanz mit dem angegebenen Eingabedokument (als Stream) |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | Initialisiert eine neue Editor‑Instanz mit dem angegebenen Eingabedokument (als ein |
stream) mit seinen Ladeoptionen und Editor-Einstellungen
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als vollständiger Dateipfad) |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als vollständiger Dateipfad) mit dessen Ladeoptionen |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | Öffnet ein zuvor geladenes Dokument zur Bearbeitung unter Verwendung der angegebenen formatbezogenen Optionen, indem eine Instanz der ''-Klasse erzeugt und zurückgegeben wird, die wiederum Methoden zur Erzeugung von HTML-Markup und zugehörigen Ressourcen enthält. |
|
|  | [edit()](#edit--) | Öffnet ein zuvor geladenes Dokument zur Bearbeitung mit Standardoptionen, indem |
eine Instanz der Klasse 'EditableDocument' erzeugt und zurückgibt, die,
wiederum Methoden zur Erzeugung von HTML-Markup und zugehörigen
Ressourcen.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | Konvertiert das angegebene bearbeitete Dokument, dargestellt als Instanz von |
'EditableDocument', in das resultierende Dokument des angegebenen Formats und
speichert dessen Inhalt in den angegebenen Stream
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | Konvertiert das angegebene bearbeitete Dokument, dargestellt als Instanz von '', in das resultierende Dokument des angegebenen Formats und speichert dessen Inhalt in eine Datei über den angegebenen Dateipfad |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | Konvertiert das angegebene bearbeitete Dokument (dargestellt durch ein [EditableDocument](../../com.groupdocs.editor/editabledocument)) in ein Ausgabedokument, dessen Format aus der Dateierweiterung ermittelt wird, und speichert es am angegebenen Dateipfad. |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | Konvertiert das Originaldokument nach der Änderung (zum Beispiel, |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
in das resultierende Dokument des angegebenen Formats und speichert dessen Inhalt in den bereitgestellten Stream.
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | Speichert den aktuellen Dokumentinhalt in den angegebenen Ausgabestream. |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | Gibt Metadaten über das Dokument zurück, das in diese 'Editor'-Instanz geladen wurde |
|
|  | [dispose()](#dispose--) | Gibt diese Editor-Instanz frei, sodass sie alle internen |
Ressourcen freigibt und für weitere Verwendung nicht mehr verfügbar ist
|
|  | [isDisposed()](#isDisposed--) | Gibt an, ob diese Editor-Instanz bereits freigegeben wurde und nicht mehr |
verwendet werden kann (true) oder nicht und aktiv ist (false)
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


Initialisiert eine neue Instanz der [Editor](../../com.groupdocs.editor/editor)-Klasse und erstellt ein neues leeres Dokument basierend auf dem angegebenen Format.

<br />

*** ** * ** ***

> ```
>   IDocumentFormat format = WordProcessingFormats.Docx;
>  Editor editor = new Editor(format);
>  {
>      // Use the editor instance to edit and save documents
>  }
>  
>  
> ```

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | repräsentiert das Dateiformat des zu erstellenden Dokuments. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


Initialisiert eine neue Editor‑Instanz mit dem angegebenen Eingabedokument (als Stream)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Delegat, der einen Stream mit dem Dokumentinhalt zurückgeben soll. Darf nicht NULL sein. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


Initialisiert eine neue Editor‑Instanz mit dem angegebenen Eingabedokument (als ein
stream) mit seinen Ladeoptionen und Editor-Einstellungen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Delegat, der einen Stream mit dem Dokumentinhalt zurückgeben soll. Darf nicht NULL sein. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate, der Dokument-Ladeoptionen zurückgeben soll. Kann NULL sein und null zurückgeben – in diesem Fall wird der Dokumenttyp automatisch erkannt und die Standard-Ladeoptionen für diesen Typ angewendet. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als vollständiger Dateipfad)


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Vollständiger Pfad zur Datei. Sollte nicht NULL sein. Sollte gültig sein und die Datei muss existieren. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als vollständiger Dateipfad) mit dessen Ladeoptionen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Vollständiger Pfad zur Datei. Sollte nicht NULL sein. Sollte gültig sein und die Datei muss existieren. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate, der Dokument-Ladeoptionen zurückgeben soll. Kann NULL sein und null zurückgeben – in diesem Fall wird der Dokumenttyp automatisch erkannt und die Standard-Ladeoptionen für diesen Typ angewendet. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


Öffnet ein zuvor geladenes Dokument zur Bearbeitung unter Verwendung der angegebenen formatbezogenen Optionen, indem eine Instanz der ''-Klasse erzeugt und zurückgegeben wird, die wiederum Methoden zur Erzeugung von HTML-Markup und zugehörigen Ressourcen enthält.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | Formatbezogene Dokumentoptionen, die es ermöglichen, den Konvertierungsprozess zu optimieren. Sollte nicht NULL sein. Sollte nicht mit bereits angewendeten Ladeoptionen in Konflikt stehen. |


*** ** * ** ***

Wenn das ursprüngliche Eingabedokument über den Konstruktor in die 'Editor'-Instanz geladen wird, ermöglicht diese Methode das Öffnen des Dokuments zur Bearbeitung, indem es in ein Zwischenformat konvertiert wird, das in einer Instanz der Klasse 'EditableDocument' gekapselt ist. Die von dieser Methode zurückgegebene 'EditableDocument' enthält alle notwendigen Methoden und Eigenschaften zur Erzeugung von HTML-Markup und entsprechenden Ressourcen (wie Bilder, Schriftarten und Stylesheets) in allen erforderlichen Konfigurationen, um sie anschließend in jeden WYSIWYG‑HTML‑Editor zu übergeben. Diese Überladung ruft Bearbeitungsoptionen ab, die für Familienformate spezifisch sind.

*** ** * ** ***


**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Edit+document)
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument)
### edit() {#edit--}
```
public final EditableDocument edit()
```


Öffnet ein zuvor geladenes Dokument zur Bearbeitung mit Standardoptionen, indem
eine Instanz der Klasse 'EditableDocument' erzeugt und zurückgibt, die,
wiederum Methoden zur Erzeugung von HTML-Markup und zugehörigen
Ressourcen.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

Wenn das ursprüngliche Eingabedokument über den Konstruktor in die 'Editor'-Instanz geladen wird, ermöglicht diese Methode das Öffnen des Dokuments zur Bearbeitung, indem es in ein Zwischenformat konvertiert wird, das in einer Instanz der Klasse 'EditableDocument' gekapselt ist. Die von dieser Methode zurückgegebene 'EditableDocument' enthält alle notwendigen Methoden und Eigenschaften zur Erzeugung von HTML-Markup und entsprechenden Ressourcen (wie Bilder, Schriftarten und Stylesheets) in allen erforderlichen Konfigurationen, um sie anschließend in jeden WYSIWYG‑HTML‑Editor zu übergeben. Diese Überladung wendet Bearbeitungsoptionen an, die standardmäßig für das Format gelten, dem das Eingabedokument zugeordnet ist.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


Konvertiert das angegebene bearbeitete Dokument, dargestellt als Instanz von
'EditableDocument', in das resultierende Dokument des angegebenen Formats und
speichert dessen Inhalt in den angegebenen Stream


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Version des Eingabedokuments, das im WYSIWYG‑HTML‑Editor bearbeitet wurde und als Instanz der Klasse 'EditableDocument' gespeichert ist, die in ein Ausgabedokument eines bestimmten Formats konvertiert werden soll. |
|
|  | outputDocument | java.io.OutputStream | Ausgabestream, in dem der Inhalt des resultierenden Dokuments aufgezeichnet wird. Sollte nicht NULL sein, nicht verworfen sein und Schreibunterstützung bieten. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Dokument-Speicheroptionen, die das Format des resultierenden Dokuments festlegen sowie allgemeine und formatbezogene Speicheroptionen definieren. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


Konvertiert das angegebene bearbeitete Dokument, dargestellt als Instanz von '', in das resultierende Dokument des angegebenen Formats und speichert dessen Inhalt in eine Datei über den angegebenen Dateipfad


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Version des Eingabedokuments, das im WYSIWYG‑HTML‑Editor bearbeitet wurde und als Instanz der ''‑Klasse gespeichert ist, die in ein Ausgabedokument eines bestimmten Formats konvertiert werden soll. Darf nicht null oder verworfen sein. |
|
|  | filePath | java.lang.String | Pfad zur Datei, in der das Ausgabedokument gespeichert wird. Existiert bereits eine Datei mit demselben Namen, wird sie vollständig überschrieben. Der Pfad‑String darf nicht null, leer oder nur aus Leerzeichen bestehen. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Dokument‑Speicheroptionen, die das Format des resultierenden Dokuments festlegen, sowie allgemeine und formatbezogene Speicheroptionen. Darf nicht null sein. **Mehr erfahren** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


Konvertiert das angegebene bearbeitete Dokument (dargestellt durch ein [EditableDocument](../../com.groupdocs.editor/editabledocument)) in ein Ausgabedokument, dessen Format aus der Dateierweiterung ermittelt wird, und speichert es am angegebenen Dateipfad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Version des Eingabedokuments, das in einem WYSIWYG‑HTML‑Editor bearbeitet wurde und als [EditableDocument](../../com.groupdocs.editor/editabledocument)-Instanz gespeichert ist. Darf nicht null oder verworfen sein. |
|
|  | filePath | java.lang.String | Pfad zur Datei, in der das Ausgabedokument gespeichert wird. Existiert bereits eine Datei mit demselben Namen, wird sie vollständig überschrieben. Der Pfadstring darf nicht null, leer oder nur aus Leerzeichen bestehen. Da die Standard‑Speicheroptionen und das Ausgabeformat aus diesem Dateinamen ermittelt werden, muss er eine gültige Erweiterung besitzen. |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


Konvertiert das Originaldokument nach der Änderung (zum Beispiel,
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
in das resultierende Dokument des angegebenen Formats und speichert dessen Inhalt in den bereitgestellten Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Der Stream, in den das Ausgabedokument gespeichert wird. Dieser Stream sollte schreibbar sein und am Anfang des Dokumentinhalts positioniert sein. Darf nicht null sein. |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | Dokument‑Speicheroptionen, die das Format des resultierenden Dokuments festlegen, sowie allgemeine und formatbezogene Speicheroptionen. Darf nicht null sein. |

<br />

*** ** * ** ***

Wenn das  outputDocument  oder  saveOptions  null ist, wird eine NullPointerException ausgelöst. Fehlt das zu speichernde Dokument, wird ebenfalls eine NullPointerException ausgelöst.

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream – Der Stream, der den gespeicherten Dokumentinhalt enthält.

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


Speichert den aktuellen Dokumentinhalt in den angegebenen Ausgabestream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Der Stream, in den der Dokumentinhalt gespeichert wird. Dieser darf nicht null sein. |

<br />

*** ** * ** ***

Diese Methode kopiert den Inhalt aus der internen Dokumentrepräsentation in den bereitgestellten Ausgabestream. Die ursprüngliche Position des Streams bleibt nach dem Speichervorgang erhalten.

<br />

|

**Returns:**
java.io.OutputStream – Der Stream mit dem gespeicherten Dokumentinhalt.

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


Gibt Metadaten über das Dokument zurück, das in diese 'Editor'-Instanz geladen wurde


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Passwort | java.lang.String | Benutzer können ein Passwort für ein Dokument angeben, wenn dieses Dokument mit einem Passwort verschlüsselt ist. Kann NULL oder ein leerer String sein, was dem fehlenden Passwort entspricht. Für Dokumentformate, die keinen Passwortschutz besitzen, wird dieses Argument ignoriert. Ist das Dokument verschlüsselt und das Passwort in diesem Parameter nicht angegeben, aber zuvor in den Ladeoptionen beim Erstellen dieser Instanz angegeben wurde, wird es verwendet. **Mehr erfahren** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Gibt diese Editor-Instanz frei, sodass sie alle internen
Ressourcen freigibt und für weitere Verwendung nicht mehr verfügbar ist


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Gibt an, ob diese Editor-Instanz bereits freigegeben wurde und nicht mehr
verwendet werden kann (true) oder nicht und aktiv ist (false)


**Returns:**
boolesch
