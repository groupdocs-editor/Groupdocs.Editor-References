---
title: "EbookSaveOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "サポートされているすべての e-Book 形式（ePub、MOBI、AZW3）でドキュメントを生成および保存するためのカスタムオプションを指定できます。"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

すべてのサポート可能な電子書籍形式（ePub、MOBI、AZW3）でドキュメントを生成および保存するためのカスタムオプションを指定できます。

<br />

*** ** * ** ***

サポートされている電子書籍形式：

1. [ePub](../https://docs.fileformat.com/ebook/epub/)（電子出版）
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/)（MobiPocket）
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/)（Kindle Format 8t）

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | このパラメータなしコンストラクタは、ePub 出力形式で EbookSaveOptions の新しいインスタンスを作成します（その後、次を通じて変更可能です |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) プロパティ)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | 指定された必須 e-Book 出力形式で [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) の新しいインスタンスを作成し、他のすべてのパラメータはデフォルトのままにします |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | e-Book ファイルを分割する見出しの最大レベルを指定します。 |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | e-Book ファイルを分割する見出しの最大レベルを指定します。 |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | 結果ファイルに組み込みおよびカスタムのドキュメント プロパティをエクスポートするかどうかを指定します。 |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | 結果ファイルに組み込みおよびカスタムのドキュメント プロパティをエクスポートするかどうかを指定します。 |
|
|  | [getOutputFormat()](#getOutputFormat--) | 結果の e-Book ファイルの形式を指定します：IDPF ePub、MOBI、または AZW3。 |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | 結果の e-Book ファイルの形式を指定します：IDPF ePub、MOBI、または AZW3。 |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


このパラメータなしコンストラクタは、ePub 出力形式で EbookSaveOptions の新しいインスタンスを作成します（その後、次を通じて変更可能です
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) プロパティ)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


指定された必須 e-Book 出力形式で [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) の新しいインスタンスを作成し、他のすべてのパラメータはデフォルトのままにします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | 必須の出力形式で、e-Book を保存する形式 |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


e-Book ファイルを分割する見出しの最大レベルを指定します。デフォルト値は
2
.
これを設定すると
0
分割が無効になり、e-Book のすべてのコンテンツが結果ファイル内の単一パッケージに組み込まれます。

<br />

*** ** * ** ***

このプロパティが 1 から 9 の値に設定されている場合、文書は次の書式が適用された段落で分割されます

**Heading 1**
,
**Heading 2**
,
**Heading 3**
等のスタイルが指定された見出しレベルまで適用されます。

デフォルトでは、のみ
**Heading 1**
および
**Heading 2**
段落が文書の分割を引き起こします。
このプロパティをゼロ（またはゼロ未満）に設定すると、見出し段落で文書がまったく分割されなくなります。

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


e-Book ファイルを分割する見出しの最大レベルを指定します。デフォルト値は
2
.
これを設定すると
0
分割が無効になり、e-Book のすべてのコンテンツが結果ファイル内の単一パッケージに組み込まれます。

<br />

*** ** * ** ***

このプロパティが 1 から 9 の値に設定されている場合、文書は次の書式が適用された段落で分割されます

**Heading 1**
,
**Heading 2**
,
**Heading 3**
等のスタイルが指定された見出しレベルまで適用されます。

デフォルトでは、のみ
**Heading 1**
および
**Heading 2**
段落が文書の分割を引き起こします。
このプロパティをゼロ（またはゼロ未満）に設定すると、見出し段落で文書がまったく分割されなくなります。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


結果ファイルに組み込みおよびカスタムのドキュメント プロパティをエクスポートするかどうかを指定します。
デフォルト値は
false
.


**Returns:**
ブール
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


結果ファイルに組み込みおよびカスタムのドキュメント プロパティをエクスポートするかどうかを指定します。
デフォルト値は
false
.


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


結果の e-Book ファイルの形式を指定します：IDPF ePub、MOBI、または AZW3。


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


結果の e-Book ファイルの形式を指定します：IDPF ePub、MOBI、または AZW3。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

