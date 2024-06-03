---
title: Editor
second_title: GroupDocs.Editor for .NET API Reference
description: Main class which encapsulates conversion methods. Editor class provides methods for loading editing and saving documents of all supportable formats. It is disposable so use a using directive or dispose its resources manually via Dispose method call. Document loading is performed through constructors. Document editing  through method Edit and saving back to the resultant document after edit  through method Save.
type: docs
weight: 20
url: /net/groupdocs.editor/editor/
---
## Editor class

Main class, which encapsulates conversion methods. Editor class provides methods for loading, editing, and saving documents of all supportable formats. It is disposable, so use a 'using' directive or dispose its resources manually via 'Dispose()' method call. Document loading is performed through constructors. Document editing - through method 'Edit', and saving back to the resultant document after edit - through method 'Save'.

```csharp
public sealed class Editor : IAuxDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [Editor](editor#constructor_2)(Func&lt;Stream&gt;) | Initializes new Editor instance with specified input document (as a stream) |
| [Editor](editor#constructor)(IDocumentFormat) | Initializes a new instance of the [`Editor`](../editor) class and creates a new empty document based on the specified format. |
| [Editor](editor#constructor_4)(string) | Initializes new Editor instance with specified input document (as a full file path) |
| [Editor](editor#constructor_3)(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) | Initializes new Editor instance with specified input document (as a stream) with its load options |
| [Editor](editor#constructor_5)(string, Func&lt;ILoadOptions&gt;) | Initializes new Editor instance with specified input document (as a full file path) with its load options |

## Properties

| Name | Description |
| --- | --- |
| [FormFieldManager](../../groupdocs.editor/editor/formfieldmanager) { get; } | Provides access to functionality for managing form fields within the document. |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Indicates whether this Editor instance was already disposed and cannot be used anymore (true) or it was not disposed yet and thus is active (false) |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Disposes this instance of Editor, so that it releases all internal resources and becomes unavailable for further usage |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Opens a previously loaded document for editing using default options by generating and returning an instance of '[`EditableDocument`](../editabledocument)' class, that, in turn, contains methods for producing HTML markup and associated resources. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Opens a previously loaded document for editing using specified format-specific options by generating and returning an instance of '[`EditableDocument`](../editabledocument)' class, that, in turn, contains methods for producing HTML markup and associated resources. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Returns metadata about the document, that was loaded to this 'Editor' instance |
| [Save](../../groupdocs.editor/editor/save#save)(Stream) | Save the current document content to the specified output stream. |
| [Save](../../groupdocs.editor/editor/save#save_1)(Stream, WordProcessingSaveOptions) | Converts the original document after modification (for example, [`FormFieldManager`](./formfieldmanager)), to the resultant document of the specified format and saves its content to the provided stream. |
| [Save](../../groupdocs.editor/editor/save#save_2)(EditableDocument, Stream, ISaveOptions) | Converts specified edited document, represented as instance of '[`EditableDocument`](../editabledocument)', to the resultant document of specified format and saves its content to specified stream |
| [Save](../../groupdocs.editor/editor/save#save_3)(EditableDocument, string, ISaveOptions) | Converts specified edited document, represented as instance of '[`EditableDocument`](../editabledocument)', to the resultant document of specified format and saves its content to file by specified file path |

## Events

| Name | Description |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Event, which occurs when this Editor instance is disposed with all its internal resources |

### Remarks

Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:

1. Load a document into the Editor instance through its constructor.
2. Optionally, detect a document type using a [`GetDocumentInfo`](./getdocumentinfo) method.
3. Open a document for editing by calling an [`Edit`](./edit) method and obtaining an instance of [`EditableDocument`](../editabledocument) class from it.
4. Editing a document content on client-side using any WYSIWYG HTML-editor.
5. Creating a new instance of [`EditableDocument`](../editabledocument) from edited document content.
6. Saving an edited document to some output format by calling a [`Save`](./save) method.
7. Disposing an instance of Editor class via 'using' operator or manually.

### See Also

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
