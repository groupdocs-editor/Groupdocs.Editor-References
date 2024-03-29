---
title: EnablePagination
second_title: GroupDocs.Editor for .NET API リファレンス
description: 結果の HTML ドキュメントでページネーションを有効または無効にできますデフォルトでは無効になっています 間違い.
type: docs
weight: 30
url: /ja/net/groupdocs.editor.options/ebookeditoptions/enablepagination/
---
## EbookEditOptions.EnablePagination property

結果の HTML ドキュメントでページネーションを有効または無効にできます。デフォルトでは無効になっています (`間違い`).

```csharp
public bool EnablePagination { get; set; }
```

### 備考

本質的に、ほとんどの電子書籍形式は内部的に Office Open XML のようなフロー形式であり、コンテンツはしっかりしていて、ページではなく章に分割されています。ただし、ページ番号、脚注、ヘッダー/フッターなどのページ固有の情報が含まれています。一部の電子書籍リーダーは、電子書籍コンテンツをページに分割しますが、他のもの (特にモバイル) はそうしません。このオプションを使用すると、編集中に電子書籍のコンテンツを HTML/CSS でどのように表現するかを制御できます — フロート (`間違い`) またはページ (`真実`） 意見。

### 関連項目

* class [EbookEditOptions](../../ebookeditoptions)
* 名前空間 [GroupDocs.Editor.Options](../../ebookeditoptions)
* 組み立て [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
