---
title: "TextualFormats"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "マークアップ XML、HTML などを含むすべてのテキストベースの形式をカプセル化します。"
type: docs
weight: 16
url: /ja/nodejs-java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

マークアップ（XML、HTML）やその他を含む、すべてのテキスト（テキストベース）形式をカプセル化します。
以下の形式が含まれます：
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Html](#Html) | HyperText Markup Language ドキュメント（HTML）は、ブラウザで表示されるウェブページ用の拡張子です。 |
|
|  | [Xml](#Xml) | eXtensible Markup Language ドキュメント（XML）は、HTML に似ていますが、オブジェクトを定義するタグの使用方法が異なります。 |
|
|  | [Txt](#Txt) | プレーンテキストドキュメント（TXT）は、行形式のプレーンテキストを含むテキストドキュメントを表します。 |
|
|  | [Md](#Md) | Markdown は、プレーンテキストエディタを使用して書式付きテキストを作成するための軽量マークアップ言語です。 |
|
|  | [Json](#Json) | JSON（JavaScript Object Notation）は、データを共有するためのオープン標準ファイル形式で、人間が読めるテキストを使用してデータを保存および転送します。 |
|
|  | [Mhtml](#Mhtml) | MIME による集約 HTML ドキュメントのカプセル化は、HTML コードとそれに付随するリソースを単一のコンピュータファイルに結合するために使用されるウェブページアーカイブ形式です。 |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help は、Microsoft の独自オンラインヘルプバイナリ形式で、HTML ページのコレクション、インデックス、その他のナビゲーションツールで構成されています。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAll()](#getAll--) | すべての [TextualFormats](../../com.groupdocs.editor.formats/textualformats) の列挙可能なコレクションを取得します。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 指定されたファイル拡張子を持つ、指定された型の [TextualFormats](../../com.groupdocs.editor.formats/textualformats) インスタンスを取得します。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | ファイル拡張子を表す文字列を [TextualFormats](../../com.groupdocs.editor.formats/textualformats) オブジェクトに変換します。 |
|
### Html {#Html}
```
public static final TextualFormats Html
```


HyperText Markup Language ドキュメント（HTML）は、ブラウザで表示されるウェブページ用の拡張子です。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


eXtensible Markup Language ドキュメント（XML）は、HTML に似ていますが、オブジェクトを定義するタグの使用方法が異なります。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


プレーンテキストドキュメント（TXT）は、行形式のプレーンテキストを含むテキストドキュメントを表します。
このファイル形式の詳細を見る
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown は、プレーンテキストエディタを使用して書式付きテキストを作成するための軽量マークアップ言語です。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON（JavaScript Object Notation）は、データを共有するためのオープン標準ファイル形式で、人間が読めるテキストを使用してデータを保存および転送します。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


MIME による集約 HTML ドキュメントのカプセル化は、HTML コードとそれに付随するリソースを単一のコンピュータファイルに結合するために使用されるウェブページアーカイブ形式です。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help は、Microsoft の独自オンラインヘルプバイナリ形式で、HTML ページのコレクション、インデックス、その他のナビゲーションツールで構成されています。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


すべての [TextualFormats](../../com.groupdocs.editor.formats/textualformats) の列挙可能なコレクションを取得します。
値: すべての [TextualFormats](../../com.groupdocs.editor.formats/textualformats) インスタンスを含む IEnumerable{TextualFormats}。


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


指定されたファイル拡張子を持つ、指定された型の [TextualFormats](../../com.groupdocs.editor.formats/textualformats) インスタンスを取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | ドキュメント形式のファイル拡張子です。 |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


ファイル拡張子を表す文字列を [TextualFormats](../../com.groupdocs.editor.formats/textualformats) オブジェクトに変換します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | 変換するファイル拡張子です。拡張子に複数のピリオドが含まれる場合、最後のピリオド以降の部分が使用されます。 |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

