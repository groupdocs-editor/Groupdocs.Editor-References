---
title: "Mp3Audio"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "任意のフォーマットのオーディオリソースを表します。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

任意のフォーマットのオーディオリソースを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | バイトストリームとして表現されたMP3コンテンツと指定された名前から新しい Mp3Audio クラスを作成します |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | 指定されたストリームが有効なMP3コンテンツかどうかをチェックします |
|
|  | [getName()](#getName--) | このMP3コンテンツの名前を返します。 |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 名前と拡張子からなるこのMP3コンテンツの正しいファイル名を返します。 |
|
|  | [getType()](#getType--) | AudioFormat.Mp3 を返します（共変戻り値により IHtmlResource.getFormat() も満たします） |
|
|  | [getByteContent()](#getByteContent--) | このフォントの内容をバイトストリームとして返します |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | この MP3 オーディオリソースの内容を元の位置からのバイトストリームとして返します |
|
|  | [getTextContent()](#getTextContent--) | この MP3 リソースの内容を base64 エンコードされた文字列として返します。 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | この MP3 リソースを指定されたファイルに保存します |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | このインスタンスと指定された HTML リソースが参照等価かどうかをチェックします |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | このインスタンスと指定されたフォントリソースが参照等価かどうかをチェックします |
|
|  | [dispose()](#dispose--) | この MP3 リソースを破棄し、その内容も破棄して、ほとんどのメソッドとプロパティが機能しなくなります |
|
|  | [isDisposed()](#isDisposed--) | この MP3 コンテンツが破棄されているかどうかを判断します |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


バイトストリームとして表現されたMP3コンテンツと指定された名前から新しい Mp3Audio クラスを作成します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | MP3 コンテンツの名前。null、空文字、または空白のみであってはなりません。 |
|
|  | binaryContent | com.aspose.ms.System.IO.Stream | バイトストリームとしてのコンテンツ。読み取りは元の位置から開始します。null であってはなりません。読み取り可能かつシーク可能である必要があります。このインスタンスが破棄されると、このストリームも破棄されます。 |
|
|  | leaveOpen | ブール | Mp3Audio インスタンスが破棄される際に、指定されたストリームを破棄するかどうかを決定します |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


指定されたストリームが有効なMP3コンテンツかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | binaryContent | com.aspose.ms.System.IO.Stream | MP3 コンテンツを含むと推測されるバイトストリーム |
|

**Returns:**
boolean - 指定されたストリームが有効な MP3 コンテンツを含む場合は true、そうでない場合は false

### getName() {#getName--}
```
public String getName()
```


この MP3 コンテンツの名前を返します。通常はファイル名拡張子を含まず、理論的にはファイル名と異なる場合があります。


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


この MP3 コンテンツの正しいファイル名（名前と拡張子から構成）を返します。理論的には名前と異なる場合があります。


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


AudioFormat.Mp3 を返します（共変戻り値により IHtmlResource.getFormat() も満たします）


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


このフォントの内容をバイトストリームとして返します


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


この MP3 オーディオリソースの内容を元の位置からのバイトストリームとして返します


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


この MP3 リソースの内容を base64 エンコードされた文字列として返します。この値は最初の呼び出し後にキャッシュされます。


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


この MP3 リソースを指定されたファイルに保存します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 作成または上書きされるファイルへのフルパス |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


このインスタンスと指定された HTML リソースが参照等価かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | IHtmlResource インターフェイスの他の継承クラス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


このインスタンスと指定されたフォントリソースが参照等価かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Mp3Audio クラスの他のインスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### dispose() {#dispose--}
```
public void dispose()
```


この MP3 リソースを破棄し、その内容も破棄して、ほとんどのメソッドとプロパティが機能しなくなります


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


この MP3 コンテンツが破棄されているかどうかを判断します


**Returns:**
ブール
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

