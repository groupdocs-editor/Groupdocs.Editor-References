---
title: "Editor"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "封装转换方法的主类。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

主要类，封装转换方法。
Editor 类提供用于加载、编辑和保存所有支持格式文档的方法。它是可释放的，因此请使用 'using' 指令或通过调用 'Dispose()' 方法手动释放其资源。文档加载通过构造函数完成。文档编辑通过方法 'Edit'，编辑后保存回生成的文档通过方法 'Save'。
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | 初始化 [Editor](../../com.groupdocs.editor/editor) 类的新实例，并基于指定的格式创建一个新的空文档。 |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | 使用指定的输入文档（作为流）初始化新的 Editor 实例 |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | 使用指定的输入文档（作为 |
stream) 以及其加载选项和 Editor 设置
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | 使用指定的输入文档（完整文件路径）初始化新的 Editor 实例 |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | 使用指定的输入文档（完整文件路径）及其加载选项初始化新的 Editor 实例 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | 使用指定的特定格式选项打开先前加载的文档进行编辑，通过生成并返回 '' 类的实例，该实例随后包含用于生成 HTML 标记和相关资源的方法。 |
|
|  | [edit()](#edit--) | 使用默认选项打开先前加载的文档进行编辑，通过 |
生成并返回 'EditableDocument' 类的实例，该实例，
随后包含用于生成 HTML 标记和相关
资源。
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | 将指定的已编辑文档转换为 instance of |
'EditableDocument'，转换为指定格式的结果文档并
将其内容保存到指定的流
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | 将指定的已编辑文档（表示为 '' 的实例）转换为指定格式的结果文档，并将其内容保存到指定文件路径的文件中 |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | 将指定的已编辑文档（由 [EditableDocument](../../com.groupdocs.editor/editabledocument) 表示）转换为其格式由文件扩展名决定的输出文档，并将其保存到指定的文件路径。 |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | 在修改后转换原始文档（例如， |
FormFieldManager
(#getFormFieldManager.getFormFieldManager))，
转换为指定格式的结果文档，并将其内容保存到提供的流中。
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | 将当前文档内容保存到指定的输出流。 |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | 返回已加载到此 'Editor' 实例的文档的元数据 |
|
|  | [dispose()](#dispose--) | 释放此 Editor 实例，以便它释放所有内部 |
资源并变得不可再用于后续使用
|
|  | [isDisposed()](#isDisposed--) | 指示此 Editor 实例是否已被释放且无法 |
再使用（true）或未使用且仍处于活动状态（false）
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


初始化 [Editor](../../com.groupdocs.editor/editor) 类的新实例，并基于指定的格式创建一个新的空文档。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | 表示将要创建的文档的文件格式。**Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


使用指定的输入文档（作为流）初始化新的 Editor 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 委托，应返回包含文档内容的流。不得为 NULL。**Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


使用指定的输入文档（作为
stream) 以及其加载选项和 Editor 设置


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 委托，应返回包含文档内容的流。不得为 NULL。 |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | 委托，应该返回文档加载选项。可能为 NULL 并可能返回 null——在这种情况下，将自动检测文档类型并应用该类型的默认加载选项。 |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


使用指定的输入文档（完整文件路径）初始化新的 Editor 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 文件的完整路径。不应为 NULL。应当有效，并且文件必须存在。**了解更多** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


使用指定的输入文档（完整文件路径）及其加载选项初始化新的 Editor 实例


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 文件的完整路径。不应为 NULL。应当有效，并且文件必须存在。 |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | 委托，应该返回文档加载选项。可能为 NULL 并可能返回 null——在这种情况下，将自动检测文档类型并应用该类型的默认加载选项。**了解更多** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


使用指定的特定格式选项打开先前加载的文档进行编辑，通过生成并返回 '' 类的实例，该实例随后包含用于生成 HTML 标记和相关资源的方法。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | 特定格式的文档选项，允许对转换过程进行微调。不应为 NULL。不得与先前应用的加载选项冲突。 |


*** ** * ** ***

当原始输入文档通过构造函数加载到 'Editor' 实例时，此方法通过将文档转换为中间格式并封装在 'EditableDocument' 类的实例中，允许打开文档进行编辑。由此方法返回的 'EditableDocument' 包含生成 HTML 标记以及相应资源（如图像、字体和样式表）的所有必要方法和属性，能够在所有必需的配置中使用，以便随后传递给任何 WYSIWYG HTML 编辑器。此重载获取针对特定族格式的编辑选项。

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


使用默认选项打开先前加载的文档进行编辑，通过
生成并返回 'EditableDocument' 类的实例，该实例，
随后包含用于生成 HTML 标记和相关
资源。


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

当原始输入文档通过构造函数加载到 'Editor' 实例时，此方法通过将文档转换为中间格式并封装在 'EditableDocument' 类的实例中，允许打开文档进行编辑。由此方法返回的 'EditableDocument' 包含生成 HTML 标记以及相应资源（如图像、字体和样式表）的所有必要方法和属性，能够在所有必需的配置中使用，以便随后传递给任何 WYSIWYG HTML 编辑器。此重载应用该格式的默认编辑选项，该格式即输入文档所属的格式。

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


将指定的已编辑文档转换为 instance of
'EditableDocument'，转换为指定格式的结果文档并
将其内容保存到指定的流


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | 输入文档的版本，该文档在 WYSIWYG HTML 编辑器中被编辑，并存储为 'EditableDocument' 类的实例，应转换为特定格式的输出文档。 |
|
|  | outputDocument | java.io.OutputStream | 输出流，用于记录生成文档的内容。不应为 NULL、已释放，且应支持写入。 |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | 文档保存选项，定义生成文档的格式，以及通用和特定格式的保存选项。**了解更多** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


将指定的已编辑文档（表示为 '' 的实例）转换为指定格式的结果文档，并将其内容保存到指定文件路径的文件中


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | 输入文档的版本，该文档在 WYSIWYG HTML 编辑器中被编辑，并存储为 '' 类的实例，应转换为特定格式的输出文档。不得为 null 或已释放。 |
|
|  | filePath | java.lang.String | 文件路径，输出文档将保存到该文件。如果同名文件已存在，将被完全覆盖。路径字符串不得为 null、为空或仅包含空白字符。 |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | 文档保存选项，定义生成文档的格式，以及通用和特定格式的保存选项。不得为 null。**了解更多** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


将指定的已编辑文档（由 [EditableDocument](../../com.groupdocs.editor/editabledocument) 表示）转换为其格式由文件扩展名决定的输出文档，并将其保存到指定的文件路径。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | 输入文档的版本，该文档在 WYSIWYG HTML 编辑器中被编辑，并存储为一个 [EditableDocument](../../com.groupdocs.editor/editabledocument) 实例。不得为 null 或已释放。 |
|
|  | filePath | java.lang.String | 输出文档将保存的文件路径。如果同名文件已存在，将被完全覆盖。路径字符串不得为 null、为空或仅包含空白字符。由于默认的保存选项和输出格式是根据此文件名确定的，文件必须具有有效的扩展名。 |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


在修改后转换原始文档（例如，
FormFieldManager
(#getFormFieldManager.getFormFieldManager))，
转换为指定格式的结果文档，并将其内容保存到提供的流中。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | 用于保存输出文档的流。该流应可写且定位在文档内容的起始位置。不得为 null。 |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | 文档保存选项，定义生成文档的格式，以及通用和特定格式的保存选项。不得为 null。 |

<br />

*** ** * ** ***

如果  outputDocument  或  saveOptions  为 null，将抛出 NullPointerException。如果要保存的文档缺失，也会抛出 NullPointerException。

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - 包含已保存文档内容的流。

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


将当前文档内容保存到指定的输出流。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | 用于保存文档内容的流。此流不能为空。 |

<br />

*** ** * ** ***

此方法将内部文档表示的内容复制到提供的输出流。保存操作后，流的原始位置将被保留。

<br />

|

**Returns:**
java.io.OutputStream - 包含已保存文档内容的流。

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


返回已加载到此 'Editor' 实例的文档的元数据


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 密码 | java.lang.String | 用户可以为文档指定密码（如果该文档已使用密码加密）。可以为 NULL 或空字符串，这等同于未提供密码。对于那些不具备密码保护功能的文档格式，此参数将被忽略。如果文档已加密且此参数未指定密码，但在创建此实例时的加载选项中已指定密码，则将使用该密码。**Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


释放此 Editor 实例，以便它释放所有内部
资源并变得不可再用于后续使用


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


指示此 Editor 实例是否已被释放且无法
再使用（true）或未使用且仍处于活动状态（false）


**Returns:**
布尔
