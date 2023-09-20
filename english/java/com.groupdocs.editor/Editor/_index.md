---
title: Editor
second_title: GroupDocs.Editor for Java API Reference
description: Main class which encapsulates conversion methods.
type: docs
weight: 11
url: /java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

Main class, which encapsulates conversion methods. Editor class provides methods for loading, editing, and saving documents of all supportable formats. It is disposable, so use a 'using' directive or dispose its resources manually via 'Dispose()' method call. Document loading is performed through constructors. Document editing - through method 'Edit', and saving back to the resultant document after edit - through method 'Save'.

Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:

 *  Load a document into the Editor instance through its constructor.
 *  Optionally, detect a document type using a  method.
 *  Open a document for editing by calling an  method and obtaining an instance of  class from it..
 *  Editing a document content on client-side using any WYSIWYG HTML-editor.
 *  Creating a new instance of  from edited document content.
 *  Saving an edited document to some output format by calling a  method.
 *  Disposing an instance of Editor class via 'using' operator or manually.
## Constructors

| Constructor | Description |
| --- | --- |
| [Editor(InputStream document)](#Editor-java.io.InputStream-) | Initializes new Editor instance with specified input document (as a stream) |
| [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | Initializes new Editor instance with specified input document (as a stream) with its load options |
| [Editor(String filePath)](#Editor-java.lang.String-) | Initializes new Editor instance with specified input document (as a full file path) |
| [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | Initializes new Editor instance with specified input document (as a full file path) with its load options |
## Methods

| Method | Description |
| --- | --- |
| [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | Opens a previously loaded document for editing using specified format-specific options by generating and returning an instance of '' class, that, in turn, contains methods for producing HTML markup and associated resources. |
| [edit()](#edit--) | Opens a previously loaded document for editing using default options by generating and returning an instance of 'EditableDocument' class, that, in turn, contains methods for producing HTML markup and associated resources. |
| [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | Converts specified edited document, represented as instance of 'EditableDocument', to the resultant document of specified format and saves its content to specified stream |
| [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | Converts specified edited document, represented as instance of '', to the resultant document of specified format and saves its content to file by specified file path |
| [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | Returns metadata about the document, that was loaded to this 'Editor' instance |
| [dispose()](#dispose--) | Disposes this instance of Editor, so that it releases all internal resources and becomes unavailable for further usage |
| [isDisposed()](#isDisposed--) | Indicates whether this Editor instance was already disposed and cannot be used anymore (true) or not and is active (false) |
### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


Initializes new Editor instance with specified input document (as a stream)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | Delegate, that should return a stream with document content. Should not be NULL. **Learn more**

 *  More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor][]
 *  More about GroupDocs.Editor for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Editor]: https://docs.groupdocs.com/display/editornet/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/editor/java/developer-guide/ |

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


Initializes new Editor instance with specified input document (as a stream) with its load options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | Delegate, that should return a stream with document content. Should not be NULL. |
| loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate, that should return a document load options. May be NULL and may return null - in that case document type will be detected automatically and default load options for that type will be applied. **Learn more**

 *  More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor][]
 *  More about GroupDocs.Editor for Java features: [Developer Guide][]
 *  More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor][]


[Document formats supported by GroupDocs.Editor]: https://docs.groupdocs.com/editor/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/editor/java/developer-guide/
[Load and edit documents using GroupDocs.Editor]: https://docs.groupdocs.com/editor/java/load-document/ |

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


Initializes new Editor instance with specified input document (as a full file path)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Full path to the file. Should not be NULL. Should be valid, and file should exist. **Learn more**

 *  More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor][]
 *  More about GroupDocs.Editor for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Editor]: https://docs.groupdocs.com/editor/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/editor/java/developer-guide/ |

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


Initializes new Editor instance with specified input document (as a full file path) with its load options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Full path to the file. Should not be NULL. Should be valid, and file should exist. |
| loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate, that should return a document load options. May be NULL and may return null - in that case document type will be detected automatically and default load options for that type will be applied. **Learn more**

 *  More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor][]
 *  More about GroupDocs.Editor for Java features: [Developer Guide][]
 *  More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor][]


[Document formats supported by GroupDocs.Editor]: https://docs.groupdocs.com/editor/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/editor/java/developer-guide/
[Load and edit documents using GroupDocs.Editor]: https://docs.groupdocs.com/editor/java/load-document/ |

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


Opens a previously loaded document for editing using specified format-specific options by generating and returning an instance of '' class, that, in turn, contains methods for producing HTML markup and associated resources.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | Format-specific document options, which allows to tune-up conversion process. Should not be NULL. Should not conflict with previously applied load options.

--------------------

When input original document is loaded to the 'Editor' instance through the constructor, this method allows to open document for editing by converting it to intermediate format, which is encapsulated within instance of 'EditableDocument' class. 'EditableDocument', returned from this method, contains all necessary methods and properties for producing HTML markup and corresponding resources (like images, fonts and stylesheets) in all necessary configurations for subsequent passing them into any WYSIWYG HTML-editor. This overload obtains edit options, which are specific for family formats.

--------------------

**Learn more**

 *  More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor][]


[How to edit document using GroupDocs.Editor]: https://docs.groupdocs.com/display/editornet/Edit+document |

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument)
### edit() {#edit--}
```
public final EditableDocument edit()
```


Opens a previously loaded document for editing using default options by generating and returning an instance of 'EditableDocument' class, that, in turn, contains methods for producing HTML markup and associated resources.

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.

--------------------

When input original document is loaded to the 'Editor' instance through the constructor, this method allows to open document for editing by converting it to intermediate format, which is encapsulated within instance of 'EditableDocument' class. 'EditableDocument', returned from this method, contains all necessary methods and properties for producing HTML markup and corresponding resources (like images, fonts and stylesheets) in all necessary configurations for subsequent passing them into any WYSIWYG HTML-editor. This overload applies edit options, which are default for the format, to which the input document belongs.

**Learn more**

 *  More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor][]


[How to edit document using GroupDocs.Editor]: https://docs.groupdocs.com/editor/java/edit-document/
### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


Converts specified edited document, represented as instance of 'EditableDocument', to the resultant document of specified format and saves its content to specified stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Version of the input document, that was edited in WYSIWYG HTML-editor and is stored as instance of 'EditableDocument' class, which should be converted to output document of some specific format |
| outputDocument | java.io.OutputStream | Output stream, in which the content of the resultant document will be recorded. Should not be NULL, disposed, should support writing. |
| saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Document saving options, which define the format of the resultant document, and also general and format-specific saving options. **Learn more**

 *  More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor][]


[How to save edited document using GroupDocs.Editor]: https://docs.groupdocs.com/display/editornet/Save+document |

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


Converts specified edited document, represented as instance of '', to the resultant document of specified format and saves its content to file by specified file path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Version of the input document, that was edited in WYSIWYG HTML-editor and is stored as instance of '' class, which should be converted to output document of some specific format. Must not be null or disposed. |
| filePath | java.lang.String | Path to the file, in which the output document will be saved. It file with the same name exists, it will be completely rewritten. String with path must not be null, empty or contain only whitespaces. |
| saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Document saving options, which define the format of the resultant document, and also general and format-specific saving options. Must not be null. **Learn more**

 *  More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor][]


[How to save edited document using GroupDocs.Editor]: https://docs.groupdocs.com/display/editornet/Save+document |

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


Returns metadata about the document, that was loaded to this 'Editor' instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | User can specify a password for a document, if this document is encrypted with the password. May be NULL or empty string, that is equivalent to the absent password. For those document formats, which do not have a password protection feature, this argument will be ignored. If the document is encrypted, and password in not specified in this parameter, but it was specified before in the load options while creating this  instance, it will be used. **Learn more**

 *  Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor][]


[How to get document info using GroupDocs.Editor]: https://docs.groupdocs.com/editor/java/extracting-document-metainfo/ |

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Disposes this instance of Editor, so that it releases all internal resources and becomes unavailable for further usage

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Indicates whether this Editor instance was already disposed and cannot be used anymore (true) or not and is active (false)

**Returns:**
boolean
