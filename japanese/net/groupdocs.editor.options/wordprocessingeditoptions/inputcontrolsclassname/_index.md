---
title: "InputControlsClassName"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "入力 WordProcessing ドキュメント内のフィールドを表すすべての HTML 要素の class 属性に設定されるクラス名を指定できるようにします。デフォルトでは NULL で、class 属性は適用されません。"
type: docs
weight: 60
url: /ja/net/groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname/
---
## WordProcessingEditOptions.InputControlsClassName property

入力の WordProcessing ドキュメントのフィールドを表すすべての HTML 要素の 'class' 属性に設定されるクラス名を指定できるようにします。デフォルトは NULL で、'class' 属性は適用されません。

```csharp
public string InputControlsClassName { get; set; }
```

### 備考

WordProcessing 系列のほぼすべてのフォーマットはフィールドを含んでいます—ユーザーから入力データを取得できる特定のドキュメントエンティティです。テキストボックス、チェックボックス、コンボボックス、ドロップダウンリスト、ボタン、日付/時刻ピッカーなど、さまざまなフィールドが存在します。これらはすべて、入力ドキュメントに存在する場合は入力されたユーザーデータを保持したまま、最適な HTML 構造や要素に変換されます。特定のユースケースでは、ドキュメント全体を編集するのではなく、クライアント側で入力データだけを収集することが求められます。そのためには、クライアント側でデータとともに取得できるように入力コントロールを何らかの方法で識別する必要があります。このプロパティは、HTML マークアップ内のすべての入力コントロールに適用されるクラス名を指定できるようにし、クライアントコードが HTML ドキュメント構造を走査してデータを収集できるようにします。

### 参照

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
