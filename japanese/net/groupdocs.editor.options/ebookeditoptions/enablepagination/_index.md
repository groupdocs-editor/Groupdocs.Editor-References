---
title: "EnablePagination"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "生成された HTML ドキュメントでページングを有効または無効にできます。デフォルトは false で無効になっています。"
type: docs
weight: 30
url: /ja/net/groupdocs.editor.options/ebookeditoptions/enablepagination/
---
## EbookEditOptions.EnablePagination property

結果の HTML ドキュメントでページングを有効または無効にできます。デフォルトでは無効 (`false`) です。

```csharp
public bool EnablePagination { get; set; }
```

### 備考

本質的に、ほとんどの e ブック形式は内部的に Office Open XML のようなフローフォーマットで、コンテンツは連続的で章に分割されますがページには分割されません。ただし、ページ番号、脚注、ヘッダー/フッターなどのページ固有情報を含みます。一部の e ブックリーダーはコンテンツをページに分割しますが、他の（特にモバイル）リーダーは分割しません。このオプションは、編集時に e ブックコンテンツを HTML/CSS でどのように表現するか、フローモード（`false`）またはページモード（`true`）で制御します。

### 参照

* class [EbookEditOptions](../../ebookeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
