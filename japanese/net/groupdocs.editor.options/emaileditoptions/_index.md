---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "さまざまな電子メール形式のドキュメント編集用にカスタムオプションを指定できます"
type: docs
weight: 850
url: /ja/net/groupdocs.editor.options/emaileditoptions/
---
## EmailEditOptions class

さまざまな電子メール（email）フォーマットのドキュメントを編集するためのカスタムオプションを指定できます。

```csharp
public sealed class EmailEditOptions : IEditOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [EmailEditOptions](emaileditoptions#constructor)() | [`EmailEditOptions`](../emaileditoptions) クラスの新しいインスタンスを初期化し、すべてのオプションがデフォルト値に設定されます |
| [EmailEditOptions](emaileditoptions#constructor_1)(MailMessageOutput) | [`EmailEditOptions`](../emaileditoptions) クラスの新しいインスタンスを、[`MailMessageOutput`](./mailmessageoutput) パラメータで初期化します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [MailMessageOutput](../../groupdocs.editor.options/emaileditoptions/mailmessageoutput) { get; set; } | メールメッセージのどの部分を出力の [`EditableDocument`](../../groupdocs.editor/editabledocument) に渡し、さらに生成された HTML にするかを制御できます |

### 参照

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
