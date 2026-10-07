---
title: "Save"
second_title: "GroupDocs.Editor für .NET API-Referenz"
description: "Konvertiert das angegebene bearbeitete Dokument, das als Instanz von EditableDocumentgroupdocs.editor/editabledocument dargestellt ist, in das resultierende Dokument des angegebenen Formats und speichert dessen Inhalt in den angegebenen Stream."
type: docs
weight: 80
url: /de/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

Konvertiert das angegebene bearbeitete Dokument, das als Instanz von '[`EditableDocument`](../../editabledocument)' dargestellt ist, in das resultierende Dokument des angegebenen Formats und speichert dessen Inhalt in den angegebenen Stream.

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputDocument | EditableDocument | Version des Eingabedokuments, das im WYSIWYG‑HTML‑Editor bearbeitet wurde und als Instanz der Klasse '[`EditableDocument`](../../editabledocument)' gespeichert ist, die in ein Ausgabedokument eines bestimmten Formats konvertiert werden soll. Darf nicht null oder entsorgt sein. |
| outputDocument | Stream | Ausgabestream, in dem der Inhalt des resultierenden Dokuments aufgezeichnet wird. Darf nicht null oder entsorgt sein und muss Schreibzugriff unterstützen. |
| saveOptions | ISaveOptions | Dokument-Speicheroptionen, die das Format des resultierenden Dokuments festlegen, sowie allgemeine und formatbezogene Speicheroptionen. Darf nicht null sein. |

### Hinweise

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Siehe auch

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

Konvertiert das angegebene bearbeitete Dokument, dargestellt als Instanz von '[`EditableDocument`](../../editabledocument)', in das resultierende Dokument des angegebenen Formats und speichert dessen Inhalt in einer Datei am angegebenen Dateipfad.

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputDocument | EditableDocument | Version des Eingabedokuments, das im WYSIWYG‑HTML‑Editor bearbeitet wurde und als Instanz der Klasse '[`EditableDocument`](../../editabledocument)' gespeichert ist, die in ein Ausgabedokument eines bestimmten Formats konvertiert werden soll. Darf nicht null oder entsorgt sein. |
| filePath | String | Pfad zur Datei, in der das Ausgabedokument gespeichert wird. Existiert bereits eine Datei mit demselben Namen, wird sie vollständig überschrieben. Der Pfad-String darf nicht null, leer oder nur aus Leerzeichen bestehen. |
| saveOptions | ISaveOptions | Dokument-Speicheroptionen, die das Format des resultierenden Dokuments festlegen, sowie allgemeine und formatbezogene Speicheroptionen. Darf nicht null sein. |

### Hinweise

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Siehe auch

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

Konvertiert das angegebene bearbeitete Dokument, dargestellt als Instanz von '[`EditableDocument`](../../editabledocument)', in das resultierende Dokument des Formats, das aus der Dateierweiterung ermittelt wird, und speichert dessen Inhalt in einer Datei am angegebenen Dateipfad.

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputDocument | EditableDocument | Version des Eingabedokuments, das im WYSIWYG‑HTML‑Editor bearbeitet wurde und als Instanz der Klasse '[`EditableDocument`](../../editabledocument)' gespeichert ist, die in ein Ausgabedokument eines bestimmten Formats konvertiert werden soll. Darf nicht null oder entsorgt sein. |
| filePath | String | Pfad zur Datei, in der das Ausgabedokument gespeichert wird. Existiert bereits eine Datei mit demselben Namen, wird sie vollständig überschrieben. Der Pfad-String darf nicht null, leer oder nur aus Leerzeichen bestehen. Da die Standard‑Speicheroptionen und das Ausgabeformat aus diesem Dateinamen ermittelt werden, muss er eine gültige Erweiterung besitzen. |

### Siehe auch

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

Konvertiert das Originaldokument nach einer Änderung (z. B. [`FormFieldManager`](../formfieldmanager)) in das resultierende Dokument des angegebenen Formats und speichert dessen Inhalt in den bereitgestellten Stream.

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputDocument | Stream | Der Stream, in dem das Ausgabedokument gespeichert wird. Dieser Stream sollte beschreibbar sein und am Anfang des Dokumentinhalts positioniert sein. Darf nicht null sein. |
| saveOptions | WordProcessingSaveOptions | Dokument‑Speicheroptionen, die das Format des resultierenden Dokuments sowie allgemeine und formatbezogene Speicheroptionen festlegen. Darf nicht null sein. |

### Rückgabewert

Der Stream, der den gespeicherten Dokumentinhalt enthält.

### Hinweise

Wenn *outputDocument* oder *saveOptions* null ist, wird eine ArgumentNullException ausgelöst. Wenn das zu speichernde Dokument fehlt, wird ebenfalls eine ArgumentNullException ausgelöst.

Ausgelöst, wenn *outputDocument* oder *saveOptions* null ist oder wenn das zu speichernde Dokument fehlt.**Learn more:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Siehe auch

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

Speichert den aktuellen Dokumentinhalt in den angegebenen Ausgabestream.

```csharp
public Stream Save(Stream outputDocument)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputDocument | Stream | Der Stream, in dem der Dokumentinhalt gespeichert wird. Dieser darf nicht null sein. |

### Rückgabewert

Der Stream mit dem gespeicherten Dokumentinhalt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Ausgelöst, wenn *outputDocument* null ist oder wenn der Dokumentinhalt fehlt. |

### Hinweise

Diese Methode kopiert den Inhalt aus der internen Dokumentrepräsentation in den bereitgestellten Ausgabestream. Die ursprüngliche Position des Streams wird nach dem Speicher‑Vorgang beibehalten.

### Siehe auch

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
