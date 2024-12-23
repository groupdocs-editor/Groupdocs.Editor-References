---
title: Editor
second_title: GroupDocs.Editor for .NET API Reference
description: Initializes a new instance of the Editorgroupdocs.editor/editor class and creates a new empty document based on the specified format.
type: docs
weight: 10
url: /net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

Initializes a new instance of the [`Editor`](../../editor) class and creates a new empty document based on the specified format.

```csharp
public Editor(DocumentFormatBase format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| format | DocumentFormatBase | Represents the file format of the document that will be created. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Examples

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // Use the editor instance to edit and save documents
}
```

### See Also

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

Initializes new Editor instance with specified input document (as a stream).

```csharp
public Editor(Stream document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | Stream that contains document content. Should not be null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Examples

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // Use the editor instance to edit and save documents
    }
}
```

### See Also

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

Initializes new Editor instance with specified input document (as a stream) with its load options.

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | Stream that contains document content. Should not be null. |
| loadOptions | ILoadOptions | Document load options. May be null. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when the document stream is null. |
| ArgumentException | Thrown when the document stream is invalid. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Examples

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // Use the editor instance to edit and save documents
    }
}
```

### See Also

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

Initializes new Editor instance with specified input document (as a full file path) with its load options.

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | Full path to the file. Should not be null, empty or contain only whitespaces. Should be valid, and file should exist. |
| loadOptions | ILoadOptions | Document load options. May be null. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when the file path is invalid. |
| FileNotFoundException | Thrown when the file does not exist. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Examples

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // Use the editor instance to edit and save documents
}
```

### See Also

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

Initializes new Editor instance with specified input document (as a full file path) and Editor settings

```csharp
public Editor(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | Full path to the file. Should not be NULL. Should be valid, and file should exist. |

### See Also

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
