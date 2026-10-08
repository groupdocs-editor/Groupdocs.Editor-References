---
title: "EmailFormats"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "すべてのメール形式をカプセル化します。次のファイルタイプが含まれます Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml。"
type: docs
weight: 90
url: /ja/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

すべてのメール形式をカプセル化します。次のファイルタイプが含まれます: [`Tnef`](./tnef)、[`Eml`](./eml)、[`Emlx`](./emlx)、[`Msg`](./msg)、[`Html`](./html)、[`Mhtml`](./mhtml)。

```csharp
public class EmailFormats : DocumentFormatBase
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | ドキュメント形式のファイル拡張子を取得します。 |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | ドキュメント形式が属するフォーマットファミリーを取得します。 |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | フォーマットファミリーの一意の識別子を取得します。 |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | ドキュメント形式の MIME タイプを取得します。 |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | フォーマットファミリーの名前を取得します。 |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | すべての[`EmailFormats`](../emailformats)の列挙可能なコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | 指定されたファイル拡張子を持つ、指定されたタイプ[`EmailFormats`](../emailformats)のインスタンスを取得します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | このインスタンスが指定された [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスと等しいかどうかを判断します。 |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | このインスタンスが指定された [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) インスタンスと等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | このインスタンスが指定された [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) インスタンスと等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 現在のオブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | ファイル拡張子を表す文字列を[`EmailFormats`](../emailformats)オブジェクトに変換します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | EMLファイル形式は、Outlookやその他の関連アプリケーションで保存されたメールメッセージを表します。このファイル形式の詳細は[here](https://docs.fileformat.com/email/eml/)でご覧ください。 |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | EMLXファイル形式はAppleによって実装・開発されました。Apple MailアプリケーションはメールのエクスポートにEMLX形式を使用します。このファイル形式の詳細は[here](https://docs.fileformat.com/email/emlx/)でご覧ください。 |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML形式のメールです。 |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Internet Calendaring and Scheduling Core Object Specification (iCalendar)は、カレンダーイベントやスケジュールの交換・配布のためのインターネット標準 (RFC 2445) です。このファイル形式の詳細は[here](https://docs.fileformat.com/email/ics/)でご覧ください。 |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBoxファイル形式は、電子メールメッセージのコレクションを格納するコンテナを表す汎用的な用語です。このファイル形式の詳細は[here](https://docs.fileformat.com/email/mbox/)でご覧ください。 |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTMLは「MIME encapsulation of aggregate HTML documents」の頭字語です。 |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSGはMicrosoft OutlookおよびExchangeでメールメッセージ、連絡先、予定、その他のタスクを保存するために使用されるファイル形式です。このファイル形式の詳細は[here](https://docs.fileformat.com/email/msg/)でご覧ください。 |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | .oft拡張子のファイルは、Microsoft Outlookで作成されたテンプレートファイルです。このファイル形式の詳細は[here](https://docs.fileformat.com/email/oft/)でご覧ください。 |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | オフラインストレージテーブル (OST) ファイルは、Microsoft Outlookを使用してExchangeサーバーに登録した際に、ローカルマシン上でオフラインモードのユーザーメールボックスデータを表します。このファイル形式の詳細は[here](https://docs.fileformat.com/email/ost/)でご覧ください。 |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | .pst拡張子のファイルは、Outlook Personal Storage Files（個人ストレージテーブルとも呼ばれる）を表し、さまざまなユーザー情報を保存します。このファイル形式の詳細は[here](https://docs.fileformat.com/email/pst/)でご覧ください。 |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) は、Messaging Application Programming Interface (MAPI) に基づいてメール添付ファイルをカプセル化する Microsoft の独自フォーマットです。このファイル形式の詳細は[こちら](https://docs.fileformat.com/email/tnef/)をご覧ください。 |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF（Virtual Card Format）または vCard は、連絡先情報を保存するデジタルファイル形式です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/email/vcf/)をご覧ください。 |

### 備考

メール形式の詳細は[こちら](https://docs.fileformat.com/email/)をご覧ください。

### 参照

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
