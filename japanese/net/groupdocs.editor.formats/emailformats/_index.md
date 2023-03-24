---
title: EmailFormats
second_title: GroupDocs.Editor for .NET API リファレンス
description: すべての電子メール形式をカプセル化します次のファイル タイプが含まれます Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml.
type: docs
weight: 60
url: /ja/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

すべての電子メール形式をカプセル化します。次のファイル タイプが含まれます: [`Tnef`](./tnef) , [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Html`](./html) , [`Mhtml`](./mhtml).

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | 型の実装では、形式のファイル拡張子を返す必要があります (先頭のドット文字なし)。 |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | 実装タイプでは、指定された format の MIME コードを返す必要があります |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | 型の実装では、完全な正式な形式 name を返す必要があります |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | のインスタンスを返します[`EmailFormats`](../emailformats)指定されたファイル拡張子に関連付けられた構造体、または拡張子を適切に解析できない場合は例外をスローします |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | このインスタンスが他の指定された電子メール インスタンスと等しいかどうかを判断します |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | このインスタンスが他の指定された IDocumentFormat と等しいかどうかを判断します instance |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | このインスタンスが、おそらくボックス化された Email である他の指定されたオブジェクトと等しいかどうかを判断します |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | このインスタンスに対して不変のハッシュコードを返します |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | このフォーマットのフォーマット名を返します |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | equality で指定された 2 つの Email インスタンスをチェックします |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | inequality で指定された 2 つの Email インスタンスをチェックします |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | EML ファイル形式は、Outlook およびその他の関連アプリケーションを使用して保存された電子メール メッセージを表します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | EMLX ファイル形式は、Apple によって実装および開発されています。 Apple Mail アプリケーションは、電子メールのエクスポートに EMLX ファイル形式を使用します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML 形式のメール。 |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Internet Calendaring and Scheduling Core Object Specification (iCalendar) は、カレンダー イベントとスケジューリングを交換および展開するためのインターネット標準 (RFC 2445) です。 このファイル形式の詳細[ここ](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBox ファイル形式は、電子メール メッセージのコレクションのコンテナーを表す一般的な用語です。 このファイル形式の詳細[ここ](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML、「集約 HTML ドキュメントの MIME カプセル化」の頭文字 |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG は、Microsoft Outlook および Exchange で電子メール メッセージ、連絡先、予定、またはその他のタスクを保存するために使用されるファイル形式です。 このファイル形式の詳細[ここ](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | 拡張子が .oft のファイルは、Microsoft Outlook を使用して作成されたテンプレート ファイルです。 このファイル形式の詳細[ここ](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | オフライン ストレージ テーブル (OST) ファイルは、Microsoft Outlook を使用して Exchange Server に登録したときに、ローカル マシン上のオフライン モードでユーザーのメールボックス データを表します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/email/ost/). |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | 拡張子が .pst のファイルは、さまざまなユーザー情報を格納する Outlook 個人用記憶域ファイル (個人用記憶域テーブルとも呼ばれます) を表します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/email/pst/). |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) は、Messaging Application Programming Interface (MAPI) に基づいて電子メールの添付ファイルをカプセル化するための Microsoft 独自のフォーマットです。 このファイル形式の詳細[ここ](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) または vCard は、連絡先情報を保存するためのデジタル ファイル形式です。 このファイル形式の詳細[ここ](https://docs.fileformat.com/email/vcf/). |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | 内部クラスを返します。これは、既存のすべての電子メール形式で列挙可能な可能性を提供します |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | 電子メール タイプの「foreach」機能を有効にする IEnumerable ジェネリック インターフェイスを実装します |

### 備考

メール形式の詳細[ここ](https://docs.fileformat.com/email/).

### 関連項目

* interface [IDocumentFormat](../idocumentformat)
* 名前空間 [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* 組み立て [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
