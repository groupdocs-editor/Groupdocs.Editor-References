---
title: "EBookFormats"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "すべての eBook 形式をカプセル化します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

すべての電子書籍形式をカプセル化します。以下のファイルタイプが含まれます：
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
Mobi 形式の詳細は[こちら](../https://docs.fileformat.com/ebook/mobi/)、ePub 形式の詳細は[こちら](../https://docs.fileformat.com/ebook/epub/)です。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI は MobiPocket Reader 用に開発された形式の名称です。 |
|
|  | [Epub](#Epub) | Electronic Publication (IDPF ePub) 形式は、出版社と読者向けに標準的なデジタル出版形式を提供する電子書籍ファイル形式です。 |
|
|  | [Azw3](#Azw3) | AZW3 は Kindle Format 8 (KF8) とも呼ばれ、Amazon Kindle デバイス向けに開発された AZW 電子書籍デジタルファイル形式の改良版です。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAll()](#getAll--) | すべての [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) の列挙可能なコレクションを取得します。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 指定されたファイル拡張子を持つ、指定されたタイプの [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) インスタンスを取得します。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | ファイル拡張子を表す文字列を [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) オブジェクトに変換します。 |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI は MobiPocket Reader 用に開発された形式の名称です。別名は PRC、AZW です。
現在、Amazon によってやや異なる DRM スキームで使用され、AZW と呼ばれています。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


Electronic Publication (IDPF ePub) 形式は、出版社と読者向けに標準的なデジタル出版形式を提供する電子書籍ファイル形式です。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3 は Kindle Format 8 (KF8) とも呼ばれ、Amazon Kindle デバイス向けに開発された AZW 電子書籍デジタルファイル形式の改良版です。
この形式は古い AZW ファイルの拡張版です。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


すべての [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) の列挙可能なコレクションを取得します。
値: すべての [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) インスタンスを含む IEnumerable{EBookFormats}。


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


指定されたファイル拡張子を持つ、指定されたタイプの [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) インスタンスを取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | ドキュメント形式のファイル拡張子です。 |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


ファイル拡張子を表す文字列を [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) オブジェクトに変換します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | 変換するファイル拡張子です。拡張子に複数のピリオドが含まれる場合、最後のピリオド以降の部分が使用されます。 |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

