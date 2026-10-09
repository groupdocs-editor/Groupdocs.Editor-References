---
title: "FontResourceBase"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "HTML ドキュメントのリソースとして、すべてのプロパティを持つサポートされるフォントタイプの基底クラス"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

HTML ドキュメントのリソースとして、サポートされるフォントタイプの基底クラス
すべてのプロパティを含む

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Disposed](#Disposed) | このフォントが破棄されるときに発生するイベント |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | このフォントリソースの名前を返します。 |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | このフォントリソースの正しいファイル名を返します。名前で構成され、 |
拡張子で構成されます。
|
|  | [getByteContent()](#getByteContent--) | このフォントの内容をバイトストリームとして返します |
|
|  | [getTextContent()](#getTextContent--) | このフォントの内容を Base64 エンコードされた文字列として返します。 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | このフォントを指定されたファイルに保存します |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | このインスタンスと指定された HTML リソースが参照等価かどうかをチェックします |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | このインスタンスと指定されたフォントリソースが参照等価かどうかをチェックします |
|
|  | [dispose()](#dispose--) | このフォントリソースを破棄し、そのコンテンツも破棄して、ほとんどを解放します |
メソッドとプロパティが機能しなくなります
|
|  | [isDisposed()](#isDisposed--) | このフォントが破棄されているかどうかを判定します |
|
|  | [getType()](#getType--) | 実装時には、特定のタイプに関する情報を返す必要があります |
フォントリソースを特定の FontType 型のインスタンスとして、
すべてのタイプ固有情報をカプセル化します
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


このフォントが破棄されるときに発生するイベント


### getName() {#getName--}
```
public final String getName()
```


このフォントリソースの名前を返します。通常、ファイル名は含まれません
拡張子で、理論的にはファイル名と異なる場合があります。


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


このフォントリソースの正しいファイル名を返します。名前で構成され、
および拡張子。理論的には名前と異なる場合があります。


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


このフォントの内容をバイトストリームとして返します


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


このフォントの内容を base64 エンコードされた文字列として返します。この値は
最初の呼び出し後にキャッシュされます。


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


このフォントを指定されたファイルに保存します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 作成または上書きされるファイルへのフルパス |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


このインスタンスと指定された HTML リソースが参照等価かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | IHtmlResource インターフェイスの他の継承クラス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


このインスタンスと指定されたフォントリソースが参照等価かどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | FontResourceBase 抽象クラスの他の継承クラス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### dispose() {#dispose--}
```
public final void dispose()
```


このフォントリソースを破棄し、そのコンテンツも破棄して、ほとんどを解放します
メソッドとプロパティが機能しなくなります


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


このフォントが破棄されているかどうかを判定します


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


実装時には、特定のタイプに関する情報を返す必要があります
フォントリソースを特定の FontType 型のインスタンスとして、
すべてのタイプ固有情報をカプセル化します


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
