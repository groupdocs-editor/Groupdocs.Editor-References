---
title: "GroupDocs.Editor"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "GroupDocs.Editor 名前空間は、追加のアプリケーションなしでサードパーティのフロントエンド WYSIWYG エディタを使用してドキュメントを編集するためのクラスを提供します。"
type: docs
weight: 10
url: /ja/net/groupdocs.editor/
---
GroupDocs.Editor 名前空間は、サードパーティのフロントエンド WYSIWYG エディタを使用して、追加のアプリケーションなしでドキュメントを編集するためのクラスを提供します。

## クラス

| クラス | 説明 |
| --- | --- |
| [EditableDocument](./editabledocument) | 編集前後のコンテンツを含む中間ドキュメント |
| [Editor](./editor) | 変換メソッドをカプセル化するメインクラス。Editor クラスは、すべてのサポート対象フォーマットのドキュメントの読み込み、編集、保存のメソッドを提供します。これは破棄可能なので、'using' ディレクティブを使用するか、'Dispose()' メソッド呼び出しでリソースを手動で破棄してください。ドキュメントの読み込みはコンストラクタを通じて行われます。ドキュメントの編集は 'Edit' メソッドで、編集後の結果ドキュメントへの保存は 'Save' メソッドで行います。 |
| [EncryptedException](./encryptedexception) | ユーザーが X509Certificates を使用して暗号化されたドキュメントを開こうとしたときにスローされる例外です。 |
| [FormFieldManager](./formfieldmanager) | レガシーフォームフィールドを使用してフォームを管理します。レガシーフォームフィールドは、以前のバージョンのワードプロセッサで利用可能だったフィールドタイプです。レガシーツールアイコンをクリックすると表示されるレガシーフォーム グループには、ドキュメントに挿入できるテキスト、チェックボックス、ドロップダウン、日付などの 3 種類のフォームフィールドが含まれます。詳細は [`FormFieldType`](../groupdocs.editor.words.fieldmanagement/formfieldtype) を参照してください。これらのフォームフィールドは、フォームのユーザーが適切と判断するタイプの情報を選択または入力できるようにします。 |
| [IncorrectPasswordException](./incorrectpasswordexception) | 指定されたパスワードが正しくないときにスローされる例外です。 |
| [InvalidFormatException](./invalidformatexception) | ユーザーが元のドキュメント形式と互換性のないフォーマット固有オプションを使用してドキュメントを開こうとしたときにスローされる例外です。 |
| [License](./license) | コンポーネントのライセンス付与のためのメソッドを提供します。ライセンスに関する詳細は[こちら](https://purchase.groupdocs.com/faqs/licensing)をご覧ください。 |
| [Metered](./metered) | [Metered](https://purchase.groupdocs.com/faqs/licensing/metered) ライセンスを適用するためのメソッドを提供します。 |
| [PasswordRequiredException](./passwordrequiredexception) | ユーザーがパスワード保護された暗号化ドキュメントを開こうとし、開くためのパスワードを提供しなかったときにスローされる例外です。 |

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
