---
title: "ExtractOnlyUsedFont"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "ドキュメントのテキストコンテンツで使用されているフォントリソースのみを抽出するかどうかを示す値を取得または設定します。"
type: docs
weight: 40
url: /ja/net/groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont/
---
## WordProcessingEditOptions.ExtractOnlyUsedFont property

ドキュメントのテキストコンテンツで使用されているフォントリソースのみを抽出するかどうかを示す値を取得または設定します。

```csharp
public bool ExtractOnlyUsedFont { get; set; }
```

### Property Value

`true` は、ドキュメントのテキスト内容で使用されているフォントリソースのみを抽出する必要がある場合を示します。そうでない場合は `false`。デフォルト値は `false` です。

### 備考

WordProcessing ドキュメントで使用されているすべてのフォントが 100% 直接（テキストに適用）されているわけではありません。フォントがドキュメント内で参照され、埋め込まれていても、テキストのどの部分にも適用されていない状況があり得ます。たとえば、あるフォントがスタイルに付随していても、そのスタイルがテキストのいずれの部分にも適用されていない場合があります。このオプションは、そのようなケースをどのように処理するかを制御します。

### 参照

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
