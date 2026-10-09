---
title: "TextResourceBase"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "テキストコンテンツとエンコーディングを持つ、サポートされるすべてのテキストリソースの基本クラス"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

テキストコンテンツとエンコーディングを持つ、サポートされるすべてのテキストリソースの基本クラス

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | 指定されたテキストコンテンツとエンコーディングから新しいテキストリソースを作成します |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | 指定されたバイトストリームとエンコーディングから新しいテキストリソースを作成します |
|
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Disposed](#Disposed) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | このテキストリソースの名前（拡張子なし）を返します |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | このテキストリソースの正しいファイル名を返します。ファイル名は名前で構成され、 |
および拡張子
|
|  | [getEncoding()](#getEncoding--) | このテキストリソースのエンコーディングを返します。 |
|
|  | [getByteContent()](#getByteContent--) | このテキストリソースの内容を元の |
エンコーディングでバイトストリームとして返します
|
|  | [getTextContent()](#getTextContent--) | このテキストリソースの内容を標準文字列として返します |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | このテキストリソースを指定されたファイルに保存します |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | このインスタンスが指定されたものと等しいかどうかをチェックします。 |
|
|  | [dispose()](#dispose--) | このテキストリソースを破棄し、その内容も破棄して、ほとんどの |
メソッドとプロパティが機能しなくなります。
|
|  | [isDisposed()](#isDisposed--) | このテキストリソースが破棄されているかどうかを判定します |
|
|  | [getType()](#getType--) | 実装型はテキストのタイプに関する情報を返すべきです |
resource
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


指定されたテキストコンテンツとエンコーディングから新しいテキストリソースを作成します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | リソースの必須名で、ユニークな識別子として機能します。通常はファイル名です。 |
|
|  | textualContent | java.lang.String | リソースのテキストコンテンツで、NULLまたは空にできません |
|
|  | originalEncoding | java.nio.charset.Charset | リソースの元のエンコーディングで、NULLまたは空にできません |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


指定されたバイトストリームとエンコーディングから新しいテキストリソースを作成します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | リソースの必須名で、ユニークな識別子として機能します。通常はファイル名です。 |
|
|  | binaryContent | java.io.InputStream | リソースのバイナリコンテンツをバイトストリームとして取得します。NULLであってはならず、破棄されていてはいけません。読み取り可能かつシーク可能である必要があります。 |
|
|  | originalEncoding | java.nio.charset.Charset | リソースの元のエンコーディングで、NULLまたは空にできません |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


このテキストリソースの名前（拡張子なし）を返します


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


このテキストリソースの正しいファイル名を返します。ファイル名は名前で構成され、
および拡張子


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


このテキストリソースのエンコーディングを返します。通常は UTF-8 を返します。


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


このテキストリソースの内容を元の
エンコーディングでバイトストリームとして返します


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


このテキストリソースの内容を標準文字列として返します


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


このテキストリソースを指定されたファイルに保存します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 既に存在する場合は作成または上書きされるファイルへのフルパス |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


このインスタンスが指定されたものと等しいかどうかをチェックします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | 不明なタイプの他のHTMLリソースで、推定されるTextResourceBaseの継承者でもあります |
|

**Returns:**
boolean - 等しい場合はtrue、等しくない場合はfalseを返します

### dispose() {#dispose--}
```
public final void dispose()
```


このテキストリソースを破棄し、その内容も破棄して、ほとんどの
メソッドとプロパティは機能しません。複数回の呼び出しに耐性があります。


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


このテキストリソースが破棄されているかどうかを判定します


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


実装型はテキストのタイプに関する情報を返すべきです
resource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
