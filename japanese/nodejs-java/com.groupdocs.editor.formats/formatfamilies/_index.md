---
title: "FormatFamilies"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "システムで利用可能なさまざまなフォーマットファミリーを表します。"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

システムで利用可能なさまざまなフォーマットファミリーを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [EBook](#EBook) | eBook フォーマットファミリーを表します。 |
|
|  | [Email](#Email) | Email フォーマットファミリーを表します。 |
|
|  | [FixedLayout](#FixedLayout) | Fixed Layout フォーマットファミリーを表します。 |
|
|  | [Presentation](#Presentation) | Presentation フォーマットファミリーを表します。 |
|
|  | [Spreadsheet](#Spreadsheet) | Spreadsheet フォーマットファミリーを表します。 |
|
|  | [Textual](#Textual) | Textual フォーマットファミリーを表します。 |
|
|  | [WordProcessing](#WordProcessing) | Word Processing フォーマットファミリーを表します。 |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


eBook フォーマットファミリーを表します。
Mobi フォーマットの詳細を見る
[here](../https://docs.fileformat.com/ebook/mobi/)
,
AZW3 フォーマットについて
[here](../https://docs.fileformat.com/ebook/azw3/)
,
および ePub フォーマットについて
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


Email フォーマットファミリーを表します。
メール形式について詳しく学ぶ
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


Fixed Layout フォーマットファミリーを表します。
さまざまな文書閲覧または公開アプリケーションは、ユーザーが (Adobe Acrobat、XPS Viewer) で開くことを許可し、場合によっては (Adobe InDesign) で特定のフォーマットの文書を編集できるようにします。
These applications typically produce so-called \u201cfixed-page\u201d format documents.
Such a document format describes precisely where a document\u2019s content is placed on every page.
内部的に、PDF または XPS フォーマットは、各ページの説明と、ページ上のコンテンツのレイアウトを指定する描画指示を含んでいます。
これは画像フォーマットに似ており、コンテンツがラスタ形式またはベクトル形式のどちらで表示されるかを記述します。


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


Presentation フォーマットファミリーを表します。
プレゼンテーション形式について詳しく学ぶ
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


Spreadsheet フォーマットファミリーを表します。
バイナリ、XML、テキストのすべてのスプレッドシートフォーマット（CSV、TSV、セミコロン区切りなどの区切り文字ベースのテキスト形式は除く）で、ワークブックを保存できます。


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


Textual フォーマットファミリーを表します。
マークアップ（XML、HTML）やその他を含む、すべてのテキスト（テキストベース）形式をカプセル化します。


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


Word Processing フォーマットファミリーを表します。
ワードプロセッシングフォーマットについて詳しく学ぶ
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

MIME コードは次のリソースから取得されます: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />



