---
title: "Editor"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "変換メソッドをカプセル化するメインクラスです。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

変換メソッドをカプセル化するメインクラス。
Editor クラスは、サポートされているすべての形式のドキュメントの読み込み、編集、保存のためのメソッドを提供します。これは破棄可能なため、'using' ディレクティブを使用するか、'Dispose()' メソッド呼び出しでリソースを手動で破棄してください。ドキュメントの読み込みはコンストラクタを通じて行われます。ドキュメントの編集はメソッド 'Edit' で、編集後に結果のドキュメントに保存するにはメソッド 'Save' を使用します。
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | 指定された形式に基づいて新しい空のドキュメントを作成し、[Editor](../../com.groupdocs.editor/editor) クラスの新しいインスタンスを初期化します。 |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | 指定された入力ドキュメント（ストリームとして）で新しい Editor インスタンスを初期化します。 |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | 指定された入力ドキュメント（として）で新しい Editor インスタンスを初期化します |
stream) とそのロードオプションおよびエディター設定
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | 指定された入力ドキュメント（完全なファイルパスとして）で新しい Editor インスタンスを初期化します |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | 指定された入力ドキュメント（完全なファイルパスとして）とそのロードオプションで新しい Editor インスタンスを初期化します |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | 指定されたフォーマット固有のオプションを使用して、以前にロードされたドキュメントを編集用に開き、'' クラスのインスタンスを生成して返します。このインスタンスは、HTML マークアップと関連リソースを生成するメソッドを含みます |
|
|  | [edit()](#edit--) | デフォルトオプションを使用して、以前にロードされたドキュメントを編集用に開きます |
'EditableDocument' クラスのインスタンスを生成して返します。このインスタンスは、
さらに、HTML マークアップと関連する
リソース。
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | 指定された編集済みドキュメントを、インスタンスとして表現された |
'EditableDocument' を、指定された形式の結果ドキュメントに変換し、
その内容を指定されたストリームに保存します
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | 指定された編集済みドキュメントを、'' のインスタンスとして表現されたものを、指定された形式の結果ドキュメントに変換し、指定されたファイルパスでファイルに内容を保存します |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | 指定された編集済みドキュメント（[EditableDocument](../../com.groupdocs.editor/editabledocument) によって表現される）を、ファイル名拡張子から決定される形式の出力ドキュメントに変換し、指定されたファイルパスに保存します。 |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | 変更後の元ドキュメントを変換します（例として、 |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
指定された形式の結果ドキュメントに変換し、その内容を提供されたストリームに保存します。
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | 現在のドキュメント内容を指定された出力ストリームに保存します。 |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | この 'Editor' インスタンスにロードされたドキュメントに関するメタデータを返します |
|
|  | [dispose()](#dispose--) | この Editor インスタンスを破棄し、内部のすべてを解放します |
リソースを解放し、以降の使用ができなくなります
|
|  | [isDisposed()](#isDisposed--) | この Editor インスタンスが既に破棄されていて、使用できないかどうかを示します |
使用できない場合は true、そうでない場合は false を示します
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


指定された形式に基づいて新しい空のドキュメントを作成し、[Editor](../../com.groupdocs.editor/editor) クラスの新しいインスタンスを初期化します。

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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | 作成されるドキュメントのファイル形式を表します。 **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


指定された入力ドキュメント（ストリームとして）で新しい Editor インスタンスを初期化します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 文書 | java.io.InputStream | ドキュメント内容を含むストリームを返すべきデリゲートです。NULL であってはなりません。 **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


指定された入力ドキュメント（として）で新しい Editor インスタンスを初期化します
stream) とそのロードオプションおよびエディター設定


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 文書 | java.io.InputStream | ドキュメント内容を含むストリームを返すべきデリゲートです。NULL であってはなりません。 |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate は、ドキュメントのロードオプションを返す必要があります。NULL になる可能性があり、null を返すこともあります。その場合、ドキュメントタイプは自動的に検出され、そのタイプのデフォルトロードオプションが適用されます。 |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


指定された入力ドキュメント（完全なファイルパスとして）で新しい Editor インスタンスを初期化します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ファイルへの完全パスです。NULL であってはなりません。有効であり、ファイルが存在する必要があります。**Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


指定された入力ドキュメント（完全なファイルパスとして）とそのロードオプションで新しい Editor インスタンスを初期化します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ファイルへの完全パスです。NULL であってはなりません。有効であり、ファイルが存在する必要があります。 |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate は、ドキュメントのロードオプションを返す必要があります。NULL になる可能性があり、null を返すこともあります。その場合、ドキュメントタイプは自動的に検出され、そのタイプのデフォルトロードオプションが適用されます。**Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


指定されたフォーマット固有のオプションを使用して、以前にロードされたドキュメントを編集用に開き、'' クラスのインスタンスを生成して返します。このインスタンスは、HTML マークアップと関連リソースを生成するメソッドを含みます


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | フォーマット固有のドキュメントオプションで、変換プロセスを調整できます。NULL であってはなりません。以前に適用されたロードオプションと競合しないようにしてください。 |


*** ** * ** ***

入力の元ドキュメントがコンストラクタを通じて 'Editor' インスタンスにロードされると、このメソッドはドキュメントを中間フォーマットに変換して編集用に開くことを可能にします。その中間フォーマットは 'EditableDocument' クラスのインスタンスにカプセル化されます。このメソッドから返される 'EditableDocument' には、HTML マークアップと対応するリソース（画像、フォント、スタイルシートなど）を生成するために必要なすべてのメソッドとプロパティが含まれており、任意の WYSIWYG HTML エディタに渡すためのすべての必要な構成が整っています。このオーバーロードは、ファミリーフォーマット固有の編集オプションを取得します。

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


デフォルトオプションを使用して、以前にロードされたドキュメントを編集用に開きます
'EditableDocument' クラスのインスタンスを生成して返します。このインスタンスは、
さらに、HTML マークアップと関連する
リソース。


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

入力の元ドキュメントがコンストラクタを通じて 'Editor' インスタンスにロードされると、このメソッドはドキュメントを中間フォーマットに変換して編集用に開くことを可能にします。その中間フォーマットは 'EditableDocument' クラスのインスタンスにカプセル化されます。このメソッドから返される 'EditableDocument' には、HTML マークアップと対応するリソース（画像、フォント、スタイルシートなど）を生成するために必要なすべてのメソッドとプロパティが含まれており、任意の WYSIWYG HTML エディタに渡すためのすべての必要な構成が整っています。このオーバーロードは、入力ドキュメントが属するフォーマットのデフォルト編集オプションを適用します。

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


指定された編集済みドキュメントを、インスタンスとして表現された
'EditableDocument' を、指定された形式の結果ドキュメントに変換し、
その内容を指定されたストリームに保存します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | WYSIWYG HTML エディタで編集され、'EditableDocument' クラスのインスタンスとして保存された入力ドキュメントのバージョンで、特定のフォーマットの出力ドキュメントに変換される必要があります。 |
|
|  | outputDocument | java.io.OutputStream | 結果ドキュメントの内容が記録される出力ストリームです。NULL であってはならず、破棄されてはいけません。書き込みをサポートしている必要があります。 |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | 結果ドキュメントの形式を定義し、一般的およびフォーマット固有の保存オプションも含むドキュメント保存オプションです。**Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


指定された編集済みドキュメントを、'' のインスタンスとして表現されたものを、指定された形式の結果ドキュメントに変換し、指定されたファイルパスでファイルに内容を保存します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | WYSIWYG HTML エディタで編集され、'' クラスのインスタンスとして保存された入力ドキュメントのバージョンで、特定のフォーマットの出力ドキュメントに変換される必要があります。null または破棄されていてはなりません。 |
|
|  | filePath | java.lang.String | 出力ドキュメントが保存されるファイルへのパスです。同名のファイルが存在する場合、完全に上書きされます。パス文字列は null、空、または空白のみであってはなりません。 |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | 結果ドキュメントの形式を定義し、一般的およびフォーマット固有の保存オプションも含むドキュメント保存オプションです。null であってはなりません。**Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


指定された編集済みドキュメント（[EditableDocument](../../com.groupdocs.editor/editabledocument) によって表現される）を、ファイル名拡張子から決定される形式の出力ドキュメントに変換し、指定されたファイルパスに保存します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | WYSIWYG HTML エディタで編集され、[EditableDocument](../../com.groupdocs.editor/editabledocument) インスタンスとして保存された入力ドキュメントのバージョンです。null または破棄されていてはなりません。 |
|
|  | filePath | java.lang.String | 出力ドキュメントが保存されるファイルへのパスです。同名のファイルが存在する場合、完全に上書きされます。パス文字列は null、空、または空白のみであってはなりません。デフォルトの保存オプションと出力フォーマットはこのファイル名から決定されるため、有効な拡張子が必要です。 |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


変更後の元ドキュメントを変換します（例として、
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
指定された形式の結果ドキュメントに変換し、その内容を提供されたストリームに保存します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | 出力ドキュメントが保存されるストリームです。このストリームは書き込み可能で、ドキュメント内容の先頭に位置している必要があります。null であってはなりません。 |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | 結果ドキュメントの形式を定義し、一般的およびフォーマット固有の保存オプションも含むドキュメント保存オプションです。null であってはなりません。 |

<br />

*** ** * ** ***

outputDocument または saveOptions が null の場合、NullPointerException がスローされます。保存するドキュメントが存在しない場合も、NullPointerException がスローされます。

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - 保存されたドキュメント内容を含むストリームです。

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


現在のドキュメント内容を指定された出力ストリームに保存します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | ドキュメント内容が保存されるストリームです。null であってはなりません。 |

<br />

*** ** * ** ***

このメソッドは、内部ドキュメント表現から提供された出力ストリームへ内容をコピーします。保存操作後もストリームの元の位置は保持されます。

<br />

|

**Returns:**
java.io.OutputStream - 保存されたドキュメント内容を含むストリームです。

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


この 'Editor' インスタンスにロードされたドキュメントに関するメタデータを返します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | パスワード | java.lang.String | ユーザーは、ドキュメントがパスワードで暗号化されている場合、そのドキュメントにパスワードを指定できます。NULL または空文字列を指定すると、パスワードが存在しないのと同等です。パスワード保護機能を持たないドキュメント形式については、この引数は無視されます。ドキュメントが暗号化されていて、このパラメータでパスワードが指定されていない場合でも、インスタンス作成時のロードオプションで以前に指定されていればそれが使用されます。**Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


この Editor インスタンスを破棄し、内部のすべてを解放します
リソースを解放し、以降の使用ができなくなります


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


この Editor インスタンスが既に破棄されていて、使用できないかどうかを示します
使用できない場合は true、そうでない場合は false を示します


**Returns:**
ブール
