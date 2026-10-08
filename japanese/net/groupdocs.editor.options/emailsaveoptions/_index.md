---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "電子メール文書の生成および保存のためのカスタムオプションを指定できるようにします。"
type: docs
weight: 860
url: /ja/net/groupdocs.editor.options/emailsaveoptions/
---
## EmailSaveOptions class

電子メール（email）ドキュメントを生成および保存するためのカスタムオプションを指定できます。

```csharp
public sealed class EmailSaveOptions : ISaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [EmailSaveOptions](emailsaveoptions#constructor)() | すべてのオプションがデフォルト値に設定された、[`EmailSaveOptions`](../emailsaveoptions) クラスの新しいインスタンスを初期化します。 |
| [EmailSaveOptions](emailsaveoptions#constructor_1)(MailMessageOutput) | `[`MailMessageOutput`](./mailmessageoutput)` パラメータを使用して、[`EmailSaveOptions`](../emailsaveoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [MailMessageOutput](../../groupdocs.editor.options/emailsaveoptions/mailmessageoutput) { get; set; } | `[`Save`](../../groupdocs.editor/editor/save)` メソッドで生成および保存される出力メール文書に、メールメッセージのどの部分を含めるかを制御できるようにします。 |

### 参照

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
