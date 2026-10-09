---
title: "FixedLayoutFormats"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "PDF と XPS を含む、固定レイアウト（別名固定ページ）形式をすべてカプセル化しますが、ラスタ画像は含まれません。"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

すべての固定レイアウト（"fixed-page" とも呼ばれる）形式をカプセル化します。これには PDF と XPS が含まれます（ラスタ画像は含まれません）

<br />

*** ** * ** ***

さまざまな文書閲覧または公開アプリケーションは、ユーザーが (Adobe Acrobat、XPS Viewer) で文書を開くことを許可し、時には (Adobe InDesign) で特定の形式の文書を編集できるようにします。これらのアプリケーションは通常、いわゆる "fixed-page" 形式の文書を生成します。この文書形式は、文書のコンテンツが各ページのどこに配置されているかを正確に記述します。内部的には、PDF または XPS 形式は各ページの記述と、ページ上のコンテンツのレイアウトを指定する描画指示を含みます。これは画像形式に似ており、コンテンツがラスタ形式またはベクトル形式のどちらで表示されるかを記述しています。

<br />


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書タイプです。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAll()](#getAll--) | すべての [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) の列挙可能なコレクションを取得します。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 指定されたファイル拡張子を持つ、指定された型の [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) インスタンスを取得します。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | ファイル拡張子を表す文字列を [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) オブジェクトに変換します。 |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書タイプです。このファイル形式の目的は、アプリケーションソフトウェア、ハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


すべての [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) の列挙可能なコレクションを取得します。
値: すべての [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) のインスタンスを含む IEnumerable{FixedLayoutFormats}。


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


指定されたファイル拡張子を持つ、指定された型の [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) インスタンスを取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | ドキュメント形式のファイル拡張子です。 |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


ファイル拡張子を表す文字列を [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) オブジェクトに変換します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | 変換するファイル拡張子です。拡張子に複数のピリオドが含まれる場合、最後のピリオド以降の部分が使用されます。 |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

