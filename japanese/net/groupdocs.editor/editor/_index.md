---
title: "Editor"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "変換メソッドをカプセル化したメインクラスです。Editor クラスは、すべてのサポート対象フォーマットのドキュメントの読み込み、編集、保存のメソッドを提供します。破棄可能なオブジェクトなので、using ディレクティブを使用するか、Dispose メソッド呼び出しでリソースを手動で破棄してください。ドキュメントの読み込みはコンストラクタを通じて行われます。ドキュメントの編集は Edit メソッドで、編集後の結果ドキュメントへの保存は Save メソッドで行います。"
type: docs
weight: 20
url: /ja/net/groupdocs.editor/editor/
---
## Editor class

変換メソッドをカプセル化するメインクラス。Editor クラスは、すべてのサポート対象フォーマットのドキュメントの読み込み、編集、保存のメソッドを提供します。これは破棄可能なので、'using' ディレクティブを使用するか、'Dispose()' メソッド呼び出しでリソースを手動で破棄してください。ドキュメントの読み込みはコンストラクタを通じて行われます。ドキュメントの編集は 'Edit' メソッドで、編集後の結果ドキュメントへの保存は 'Save' メソッドで行います。

```csharp
public sealed class Editor : IAuxDisposable
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Editor](editor#constructor)(DocumentFormatBase) | [`Editor`](../editor) クラスの新しいインスタンスを初期化し、指定されたフォーマットに基づく新しい空のドキュメントを作成します。 |
| [Editor](editor#constructor_1)(Stream) | 指定された入力ドキュメント（ストリームとして）で新しい Editor インスタンスを初期化します。 |
| [Editor](editor#constructor_3)(string) | 指定された入力ドキュメント（完全なファイルパスとして）とEditor設定で新しいEditorインスタンスを初期化します |
| [Editor](editor#constructor_2)(Stream, ILoadOptions) | 指定された入力ドキュメント（ストリームとして）とそのロードオプションで新しいEditorインスタンスを初期化します。 |
| [Editor](editor#constructor_4)(string, ILoadOptions) | 指定された入力ドキュメント（完全なファイルパスとして）とそのロードオプションで新しいEditorインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FormFieldManager](../../groupdocs.editor/editor/formfieldmanager) { get; } | ドキュメント内のフォームフィールドを管理する機能へのアクセスを提供します。 |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | このEditorインスタンスが既に破棄されていて使用できないか（true）、まだ破棄されておらずアクティブであるか（false）を示します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | このEditorインスタンスを破棄し、すべての内部リソースを解放して以後使用できなくなります。 |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | デフォルトオプションを使用して以前に読み込まれたドキュメントを編集用に開き、'[`EditableDocument`](../editabledocument)' クラスのインスタンスを生成して返します。このインスタンスは、HTMLマークアップと関連リソースを生成するメソッドを含みます。 |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | 指定されたフォーマット固有のオプションを使用して以前に読み込まれたドキュメントを編集用に開き、'[`EditableDocument`](../editabledocument)' クラスのインスタンスを生成して返します。このインスタンスは、HTMLマークアップと関連リソースを生成するメソッドを含みます。 |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | この'Editor'インスタンスに読み込まれたドキュメントに関するメタデータを返します。 |
| [Save](../../groupdocs.editor/editor/save#save)(Stream) | 現在のドキュメント内容を指定された出力ストリームに保存します。 |
| [Save](../../groupdocs.editor/editor/save#save_3)(EditableDocument, string) | 指定された編集済みドキュメント（'[`EditableDocument`](../editabledocument)' のインスタンスとして表現）を、ファイル名拡張子から決定される形式の結果ドキュメントに変換し、指定されたファイルパスでファイルに内容を保存します。 |
| [Save](../../groupdocs.editor/editor/save#save_1)(Stream, WordProcessingSaveOptions) | 変更後の元ドキュメント（例：[`FormFieldManager`](./formfieldmanager)）を、指定された形式の結果ドキュメントに変換し、提供されたストリームに内容を保存します。 |
| [Save](../../groupdocs.editor/editor/save#save_2)(EditableDocument, Stream, ISaveOptions) | 指定された編集済みドキュメント（'[`EditableDocument`](../editabledocument)' のインスタンスとして表現）を、指定された形式の結果ドキュメントに変換し、指定されたストリームに内容を保存します。 |
| [Save](../../groupdocs.editor/editor/save#save_4)(EditableDocument, string, ISaveOptions) | 指定された編集済みドキュメント（'[`EditableDocument`](../editabledocument)' のインスタンスとして表現）を、指定された形式の結果ドキュメントに変換し、指定されたファイルパスでファイルに内容を保存します。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | このEditorインスタンスが破棄され、すべての内部リソースが解放されたときに発生するイベント |

### 備考

EditorクラスはGroupDocs.Editorのエントリーポイントかつルートオブジェクトとみなすべきです。すべての操作はこのクラスを使用して実行されます。Editorクラスを使用した完全なドキュメント編集パイプラインの典型的な使用方法は以下の通りです：

1. コンストラクタを通じてドキュメントをEditorインスタンスにロードします。
2. オプションで、[`GetDocumentInfo`](./getdocumentinfo) メソッドを使用してドキュメントタイプを検出します。
3. [`Edit`](./edit) メソッドを呼び出し、[`EditableDocument`](../editabledocument) クラスのインスタンスを取得してドキュメントを編集用に開きます。
4. 任意のWYSIWYG HTMLエディタを使用してクライアント側でドキュメント内容を編集します。
5. 編集されたドキュメント内容から新しい[`EditableDocument`](../editabledocument) のインスタンスを作成します。
6. [`Save`](./save) メソッドを呼び出して、編集されたドキュメントを任意の出力形式で保存します。
7. 'using' 演算子または手動でEditorクラスのインスタンスを破棄します。

### 参照

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
