---
title: "WordProcessingFormats"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "すべての WordProcessing 形式をカプセル化します。"
type: docs
weight: 17
url: /ja/nodejs-java/com.groupdocs.editor.formats/wordprocessingformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class WordProcessingFormats extends DocumentFormatBase
```

すべての WordProcessing フォーマットをカプセル化します。以下のファイルタイプが含まれます：
[Doc](../../com.groupdocs.editor.formats/wordprocessingformats#Doc),
[Docm](../../com.groupdocs.editor.formats/wordprocessingformats#Docm),
[Docx](../../com.groupdocs.editor.formats/wordprocessingformats#Docx),
[Dot](../../com.groupdocs.editor.formats/wordprocessingformats#Dot),
[Dotm](../../com.groupdocs.editor.formats/wordprocessingformats#Dotm),
[Dotx](../../com.groupdocs.editor.formats/wordprocessingformats#Dotx),
[FlatOpc](../../com.groupdocs.editor.formats/wordprocessingformats#FlatOpc),
[Odt](../../com.groupdocs.editor.formats/wordprocessingformats#Odt),
[Ott](../../com.groupdocs.editor.formats/wordprocessingformats#Ott),
[Rtf](../../com.groupdocs.editor.formats/wordprocessingformats#Rtf),
[WordML](../../com.groupdocs.editor.formats/wordprocessingformats#WordML).
Word Processing フォーマットの詳細は [here](../https://wiki.fileformat.com/word-processing) で確認できます。

MIME コードは以下のリソースから取得されます：
https://filext.com/faq/office_mime_types.html
https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Doc](#Doc) | MS Word 97-2007 バイナリファイル形式 (DOC) は、Microsoft Word またはその他のワードプロセッシングアプリケーションで生成されたバイナリ形式のドキュメントを表します。 |
|
|  | [Docx](#Docx) | Office Open XML WordProcessingML マクロなしドキュメント (DOCX) は、Microsoft Word ドキュメントのよく知られた形式です。 |
|
|  | [Dot](#Dot) | MS Word 97-2007 テンプレート (DOT) は、Microsoft Word が作成したテンプレートファイルで、今後の DOC または DOCX ファイル生成のために事前にフォーマットされた設定を持ちます。 |
|
|  | [Docm](#Docm) | Office Open XML WordProcessingML マクロ有効ドキュメント (DOCM) ファイルは、マクロを実行できる Microsoft Word 2007 以降で生成されたドキュメントです。 |
|
|  | [Dotx](#Dotx) | Office Open XML WordprocessingML マクロなしテンプレート (DOTX) は、Microsoft Word が作成したテンプレートファイルで、今後の DOCX ファイル生成のために事前にフォーマットされた設定を持ちます。 |
|
|  | [Dotm](#Dotm) | Office Open XML WordprocessingML マクロ有効テンプレート (DOTM) は、Microsoft Word 2007 以降で作成されたテンプレートファイルを表します。 |
|
|  | [FlatOpc](#FlatOpc) | Office Open XML WordprocessingML は、ZIP パッケージの代わりにフラットな XML ファイルとして保存されます。 |
|
|  | [Rtf](#Rtf) | リッチテキストフォーマット (RTF) は、アプリケーション内で使用するための書式設定されたテキストとグラフィックをエンコードする方法を表します。 |
|
|  | [Odt](#Odt) | Open Document Format テキストドキュメント (ODT) ファイルは、OpenDocument テキストファイル形式に基づくワードプロセッシングアプリケーションで作成された文書の一種です。 |
|
|  | [Ott](#Ott) | Open Document Format テキストドキュメントテンプレート (OTT) は、OASIS の OpenDocument 標準フォーマットに準拠したアプリケーションによって生成されたテンプレート文書を表します。 |
|
|  | [WordML](#WordML) | Microsoft Office Word 2003 XML フォーマット — WordProcessingML または WordML (.XML)。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAll()](#getAll--) | すべての [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) の列挙可能なコレクションを取得します。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 指定されたファイル拡張子を持つ、指定されたタイプの [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) インスタンスを取得します。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | ファイル拡張子を表す文字列を [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) オブジェクトに変換します。 |
|
### Doc {#Doc}
```
public static final WordProcessingFormats Doc
```


MS Word 97-2007 バイナリファイル形式 (DOC) は、Microsoft Word またはその他のワードプロセッシングアプリケーションで生成されたバイナリ形式のドキュメントを表します。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/word-processing/doc)
.


### Docx {#Docx}
```
public static final WordProcessingFormats Docx
```


Office Open XML WordProcessingML マクロなしドキュメント (DOCX) は、Microsoft Word ドキュメントのよく知られた形式です。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/word-processing/docx)
.


### Dot {#Dot}
```
public static final WordProcessingFormats Dot
```


MS Word 97-2007 テンプレート (DOT) は、Microsoft Word が作成したテンプレートファイルで、今後の DOC または DOCX ファイル生成のために事前にフォーマットされた設定を持ちます。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/word-processing/dot)
.


### Docm {#Docm}
```
public static final WordProcessingFormats Docm
```


Office Open XML WordProcessingML マクロ有効ドキュメント (DOCM) ファイルは、マクロを実行できる Microsoft Word 2007 以降で生成されたドキュメントです。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/word-processing/docm)
.


### Dotx {#Dotx}
```
public static final WordProcessingFormats Dotx
```


Office Open XML WordprocessingML マクロなしテンプレート (DOTX) は、Microsoft Word が作成したテンプレートファイルで、今後の DOCX ファイル生成のために事前にフォーマットされた設定を持ちます。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/word-processing/dotx)
.


### Dotm {#Dotm}
```
public static final WordProcessingFormats Dotm
```


Office Open XML WordprocessingML マクロ有効テンプレート (DOTM) は、Microsoft Word 2007 以降で作成されたテンプレートファイルを表します。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/word-processing/dotm)
.


### FlatOpc {#FlatOpc}
```
public static final WordProcessingFormats FlatOpc
```


Office Open XML WordprocessingML は、ZIP パッケージの代わりにフラットな XML ファイルとして保存されます。


### Rtf {#Rtf}
```
public static final WordProcessingFormats Rtf
```


リッチテキストフォーマット (RTF) は、アプリケーション内で使用するための書式設定されたテキストとグラフィックをエンコードする方法を表します。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/word-processing/rtf)
.


### Odt {#Odt}
```
public static final WordProcessingFormats Odt
```


Open Document Format テキストドキュメント (ODT) ファイルは、OpenDocument テキストファイル形式に基づくワードプロセッシングアプリケーションで作成された文書の一種です。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/word-processing/odt)
.


### Ott {#Ott}
```
public static final WordProcessingFormats Ott
```


Open Document Format テキストドキュメントテンプレート (OTT) は、OASIS の OpenDocument 標準フォーマットに準拠したアプリケーションによって生成されたテンプレート文書を表します。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/word-processing/ott)
.


### WordML {#WordML}
```
public static final WordProcessingFormats WordML
```


Microsoft Office Word 2003 XML フォーマット — WordProcessingML または WordML (.XML)。

<br />

*** ** * ** ***

https://en.wikipedia.org/wiki/Microsoft_Office_XML_formats

<br />



### getAll() {#getAll--}
```
public static List<WordProcessingFormats> getAll()
```


すべての [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) の列挙可能なコレクションを取得します。
値: すべての [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) インスタンスを含む IEnumerable{WordProcessingFormats}。


**Returns:**
java.util.List<com.groupdocs.editor.formats.WordProcessingFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static WordProcessingFormats fromExtension(String extension)
```


指定されたファイル拡張子を持つ、指定されたタイプの [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) インスタンスを取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | ドキュメント形式のファイル拡張子です。 |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - An instance of the specified type [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static WordProcessingFormats fromString(String extension)
```


ファイル拡張子を表す文字列を [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) オブジェクトに変換します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | 変換するファイル拡張子です。拡張子に複数のピリオドが含まれる場合、最後のピリオド以降の部分が使用されます。 |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - A [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) object corresponding to the specified file extension.

