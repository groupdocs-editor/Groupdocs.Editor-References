---
title: Editor
second_title: GroupDocs.Editor for .NET API Reference
description: Initializes a new instance of the Editorgroupdocs.editor/editor class and creates a new empty document based on the specified format.
type: docs
weight: 10
url: /net/groupdocs.editor/editor/editor/
---
## Editor(Action&lt;Stream&gt;, IDocumentFormat) {#constructor}

Initializes a new instance of the [`Editor`](../../editor) class and creates a new empty document based on the specified format.

```csharp
public Editor(Action<Stream> newDocumentAction, IDocumentFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newDocumentAction | Action`1 | delegate that allows saving or performing some action with a stream of the new document. |
| format | IDocumentFormat | represents the file format of the document that will be created. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### See Also

* interface [IDocumentFormat](../../../groupdocs.editor.formats/idocumentformat)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Func&lt;Stream&gt;) {#constructor_1}

Initializes new Editor instance with specified input document (as a stream)

```csharp
public Editor(Func<Stream> document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`1 | Delegate, that should return a stream with document content. Should not be NULL. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### See Also

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) {#constructor_2}

Initializes new Editor instance with specified input document (as a stream) with its load options

```csharp
public Editor(Func<Stream> document, Func<ILoadOptions> loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Func`1 | Delegate, that should return a stream with document content. Should not be NULL. |
| loadOptions | Func`1 | Delegate, that should return a document load options. May be NULL and may return null - in that case document type will be detected automatically and default load options for that type will be applied. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### See Also

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

Initializes new Editor instance with specified input document (as a full file path)

```csharp
public Editor(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | Full path to the file. Should not be NULL. Should be valid, and file should exist. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### See Also

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, Func&lt;ILoadOptions&gt;) {#constructor_4}

Initializes new Editor instance with specified input document (as a full file path) with its load options

```csharp
public Editor(string filePath, Func<ILoadOptions> loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | Full path to the file. Should not be NULL. Should be valid, and file should exist. |
| loadOptions | Func`1 | Delegate, that should return a document load options. May be NULL and may return null - in that case document type will be detected automatically and default load options for that type will be applied. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### See Also

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
