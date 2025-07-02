---
title: Save
second_title: GroupDocs.Editor for .NET API Reference
description: Converts specified edited document represented as instance of EditableDocumentgroupdocs.editor/editabledocument to the resultant document of specified format and saves its content to specified stream
type: docs
weight: 80
url: /net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

Converts specified edited document, represented as instance of '[`EditableDocument`](../../editabledocument)', to the resultant document of specified format and saves its content to specified stream

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputDocument | EditableDocument | Version of the input document, that was edited in WYSIWYG HTML-editor and is stored as instance of '[`EditableDocument`](../../editabledocument)' class, which should be converted to output document of some specific format. Must not be null or disposed. |
| outputDocument | Stream | Output stream, in which the content of the resultant document will be recorded. Must not be null, disposed, must support writing. |
| saveOptions | ISaveOptions | Document saving options, which define the format of the resultant document, and also general and format-specific saving options. Must not be null. |

### Remarks

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### See Also

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

Converts specified edited document, represented as instance of '[`EditableDocument`](../../editabledocument)', to the resultant document of specified format and saves its content to file by specified file path

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputDocument | EditableDocument | Version of the input document, that was edited in WYSIWYG HTML-editor and is stored as instance of '[`EditableDocument`](../../editabledocument)' class, which should be converted to output document of some specific format. Must not be null or disposed. |
| filePath | String | Path to the file, in which the output document will be saved. It file with the same name exists, it will be completely rewritten. String with path must not be null, empty or contain only whitespaces. |
| saveOptions | ISaveOptions | Document saving options, which define the format of the resultant document, and also general and format-specific saving options. Must not be null. |

### Remarks

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### See Also

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

Converts specified edited document, represented as instance of '[`EditableDocument`](../../editabledocument)', to the resultant document of format, determined from the filename extension, and saves its content to file by specified file path

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputDocument | EditableDocument | Version of the input document, that was edited in WYSIWYG HTML-editor and is stored as instance of '[`EditableDocument`](../../editabledocument)' class, which should be converted to output document of some specific format. Must not be null or disposed. |
| filePath | String | Path to the file, in which the output document will be saved. It file with the same name exists, it will be completely rewritten. String with path must not be null, empty or contain only whitespaces. Because default save options and output format are determined from this filename, it must have the valid extension. |

### See Also

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

Converts the original document after modification (for example, [`FormFieldManager`](../formfieldmanager)), to the resultant document of the specified format and saves its content to the provided stream.

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputDocument | Stream | The stream to which the output document will be saved. This stream should be writable and positioned at the start of the document content. Must not be null. |
| saveOptions | WordProcessingSaveOptions | Document saving options that define the format of the resultant document, as well as general and format-specific saving options. Must not be null. |

### Return Value

The stream containing the saved document content.

### Remarks

If the *outputDocument* or *saveOptions* is null, an ArgumentNullException will be thrown. If the document to save is missing, an ArgumentNullException will be thrown.

Thrown when *outputDocument* or *saveOptions* is null, or when the document to save is missing.**Learn more:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### See Also

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

Save the current document content to the specified output stream.

```csharp
public Stream Save(Stream outputDocument)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputDocument | Stream | The stream to which the document content will be saved. This cannot be null. |

### Return Value

The stream with the saved document content.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *outputDocument* is null or if the document content is missing. |

### Remarks

This method copies the content from the internal document representation to the provided output stream. The stream's original position is preserved after the save operation.

### See Also

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
