---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "すべてのサポート対象フォーマット（ePub、MOBI、AZW3）で Ebook ドキュメントを編集するためのカスタムオプションを指定および調整できます。"
type: docs
weight: 830
url: /ja/net/groupdocs.editor.options/ebookeditoptions/
---
## EbookEditOptions class

すべてのサポート対象フォーマット（ePub、MOBI、AZW3）で電子書籍ドキュメントを編集するためのカスタムオプションを指定および調整できます。

```csharp
public sealed class EbookEditOptions : IEditOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [EbookEditOptions](ebookeditoptions#constructor)() | すべてのオプションがデフォルト値に設定された [`EbookEditOptions`](../ebookeditoptions) クラスの新しいインスタンスを初期化します。 |
| [EbookEditOptions](ebookeditoptions#constructor_1)(bool) | 指定されたページングモードで [`EbookEditOptions`](../ebookeditoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/ebookeditoptions/enablelanguageinformation) { get; set; } | 言語情報を 'lang' HTML 属性の形で HTML マークアップにエクスポートするかどうかを指定します。このオプションは多言語ドキュメントの往復変換に役立つ場合があります。デフォルトでは無効 (`false`) です。 |
| [EnablePagination](../../groupdocs.editor.options/ebookeditoptions/enablepagination) { get; set; } | 結果の HTML ドキュメントでページングを有効または無効にできます。デフォルトでは無効 (`false`) です。 |

### 備考

サポートされている e-Book 形式：

1. [ePub](https://docs.fileformat.com/ebook/epub/)（Electronic Publication）
2. [MOBI](https://docs.fileformat.com/ebook/mobi/)（MobiPocket）
3. [AZW3](https://docs.fileformat.com/ebook/azw3/)（Kindle Format 8t）

### 参照

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
