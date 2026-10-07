---
title: "Editor"
second_title: "GroupDocs.Editor für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Klasse Editorgroupdocs.editor/editor und erstellt ein neues leeres Dokument basierend auf dem angegebenen Format."
type: docs
weight: 10
url: /de/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

Initialisiert eine neue Instanz der Klasse [`Editor`](../../editor) und erstellt ein neues leeres Dokument basierend auf dem angegebenen Format.

```csharp
public Editor(DocumentFormatBase format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Format | DocumentFormatBase | Stellt das Dateiformat des zu erstellenden Dokuments dar. |

### Hinweise

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Beispiele

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // Verwenden Sie die Editor‑Instanz, um Dokumente zu bearbeiten und zu speichern.
}
```

### Siehe auch

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als Stream).

```csharp
public Editor(Stream document)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | Stream | Stream, der den Dokumentinhalt enthält. Sollte nicht null sein. |

### Hinweise

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Beispiele

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // Verwenden Sie die Editor‑Instanz, um Dokumente zu bearbeiten und zu speichern.
    }
}
```

### Siehe auch

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als Stream) und dessen Ladeoptionen.

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | Stream | Stream, der den Dokumentinhalt enthält. Sollte nicht null sein. |
| loadOptions | ILoadOptions | Optionen zum Laden des Dokuments. Können null sein. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn der Dokumenten‑Stream null ist. |
| ArgumentException | Wird ausgelöst, wenn der Dokumenten‑Stream ungültig ist. |

### Hinweise

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Beispiele

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // Verwenden Sie die Editor‑Instanz, um Dokumente zu bearbeiten und zu speichern.
    }
}
```

### Siehe auch

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als vollständiger Dateipfad) und dessen Ladeoptionen.

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Vollständiger Pfad zur Datei. Sollte nicht null, leer oder nur aus Leerzeichen bestehen. Sollte gültig sein und die Datei muss existieren. |
| loadOptions | ILoadOptions | Optionen zum Laden des Dokuments. Können null sein. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn der Dateipfad ungültig ist. |
| FileNotFoundException | Wird ausgelöst, wenn die Datei nicht existiert. |

### Hinweise

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Beispiele

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // Verwenden Sie die Editor‑Instanz, um Dokumente zu bearbeiten und zu speichern.
}
```

### Siehe auch

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

Initialisiert eine neue Editor-Instanz mit dem angegebenen Eingabedokument (als vollständiger Dateipfad) und den Editor-Einstellungen.

```csharp
public Editor(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Vollständiger Pfad zur Datei. Sollte nicht NULL sein. Sollte gültig sein und die Datei muss existieren. |

### Siehe auch

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
