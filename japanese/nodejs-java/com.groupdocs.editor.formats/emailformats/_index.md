---
title: "EmailFormats"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "すべてのメール形式をカプセル化します。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

すべてのメール形式をカプセル化します。以下のファイルタイプが含まれます：
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

メール形式の詳細は[こちら](../https://docs.fileformat.com/email/)です。

<br />


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Tnef](#Tnef) | Transport Neutral Encapsulation Format (TNEF) は、Messaging Application Programming Interface (MAPI) に基づくメール添付ファイルをカプセル化する Microsoft の独自形式です。 |
|
|  | [Eml](#Eml) | EML ファイル形式は、Outlook やその他の関連アプリケーションで保存されたメールメッセージを表します。 |
|
|  | [Emlx](#Emlx) | EMLX ファイル形式は Apple によって実装・開発されています。 |
|
|  | [Msg](#Msg) | MSG は Microsoft Outlook と Exchange がメールメッセージ、連絡先、予定、その他のタスクを保存するために使用するファイル形式です。 |
|
|  | [Html](#Html) | HTML 形式のメールです。 |
|
|  | [Mhtml](#Mhtml) | MHTML は "MIME encapsulation of aggregate HTML documents" の頭字語です。 |
|
|  | [Ics](#Ics) | インターネットカレンダーおよびスケジューリングコアオブジェクト仕様 (iCalendar) は、カレンダーイベントとスケジューリングの交換および展開のためのインターネット標準 (RFC 2445) です。 |
|
|  | [Vcf](#Vcf) | VCF（Virtual Card Format）または vCard は、連絡先情報を保存するためのデジタルファイル形式です。 |
|
|  | [Pst](#Pst) | .pst 拡張子のファイルは、Outlook Personal Storage Files（別名 Personal Storage Table）を表し、さまざまなユーザー情報を保存します。 |
|
|  | [Mbox](#Mbox) | MBox ファイル形式は、電子メールメッセージのコレクションを格納するコンテナを表す汎用的な用語です。 |
|
|  | [Oft](#Oft) | .oft 拡張子のファイルは、Microsoft Outlook を使用して作成されるテンプレートファイルです。 |
|
|  | [Ost](#Ost) | Offline Storage Table (OST) ファイルは、Microsoft Outlook を使用して Exchange Server に登録した際、ローカルマシン上でオフラインモードのユーザーのメールボックスデータを表します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAll()](#getAll--) | すべての [EmailFormats](../../com.groupdocs.editor.formats/emailformats) の列挙可能なコレクションを取得します。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 指定されたファイル拡張子を持つ、指定されたタイプの [EmailFormats](../../com.groupdocs.editor.formats/emailformats) インスタンスを取得します。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | ファイル拡張子を表す文字列を [EmailFormats](../../com.groupdocs.editor.formats/emailformats) オブジェクトに変換します。 |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format (TNEF) は、Messaging Application Programming Interface (MAPI) に基づくメール添付ファイルをカプセル化する Microsoft の独自形式です。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


EML ファイル形式は、Outlook やその他の関連アプリケーションで保存されたメールメッセージを表します。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


EMLX ファイル形式は Apple によって実装・開発されました。Apple Mail アプリケーションはメールのエクスポートに EMLX ファイル形式を使用します。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG は Microsoft Outlook と Exchange がメールメッセージ、連絡先、予定、その他のタスクを保存するために使用するファイル形式です。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


HTML 形式のメールです。


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML は "MIME encapsulation of aggregate HTML documents" の頭字語です。


### Ics {#Ics}
```
public static final EmailFormats Ics
```


インターネットカレンダーおよびスケジューリングコアオブジェクト仕様 (iCalendar) は、カレンダーイベントとスケジューリングの交換および展開のためのインターネット標準 (RFC 2445) です。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF（Virtual Card Format）または vCard は、連絡先情報を保存するためのデジタルファイル形式です。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


.pst 拡張子のファイルは、Outlook Personal Storage Files（別名 Personal Storage Table）を表し、さまざまなユーザー情報を保存します。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


MBox ファイル形式は、電子メールメッセージのコレクションを格納するコンテナを表す汎用的な用語です。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


.oft 拡張子のファイルは、Microsoft Outlook を使用して作成されるテンプレートファイルです。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


Offline Storage Table (OST) ファイルは、Microsoft Outlook を使用して Exchange Server に登録した際、ローカルマシン上でオフラインモードのユーザーのメールボックスデータを表します。
このファイル形式の詳細を見る
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


すべての [EmailFormats](../../com.groupdocs.editor.formats/emailformats) の列挙可能なコレクションを取得します。
値: すべての [EmailFormats](../../com.groupdocs.editor.formats/emailformats) インスタンスを含む IEnumerable{EmailFormats}。


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


指定されたファイル拡張子を持つ、指定されたタイプの [EmailFormats](../../com.groupdocs.editor.formats/emailformats) インスタンスを取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | ドキュメント形式のファイル拡張子です。 |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


ファイル拡張子を表す文字列を [EmailFormats](../../com.groupdocs.editor.formats/emailformats) オブジェクトに変換します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 拡張子 | java.lang.String | 変換するファイル拡張子です。拡張子に複数のピリオドが含まれる場合、最後のピリオド以降の部分が使用されます。 |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

