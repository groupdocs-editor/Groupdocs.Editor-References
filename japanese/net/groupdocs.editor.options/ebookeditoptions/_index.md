---
title: EbookEditOptions
second_title: GroupDocs.Editor for .NET API リファレンス
description: サポートされているすべての形式の電子書籍ドキュメントを編集するためのカスタム オプションを指定および調整できます ePubMOBIおよび AZW3.
type: docs
weight: 840
url: /ja/net/groupdocs.editor.options/ebookeditoptions/
---
## EbookEditOptions class

サポートされているすべての形式の電子書籍ドキュメントを編集するためのカスタム オプションを指定および調整できます: ePub、MOBI、および AZW3.

```csharp
public sealed class EbookEditOptions : IEditOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [EbookEditOptions](ebookeditoptions#constructor)() | の新しいインスタンスを初期化します[`EbookEditOptions`](../ebookeditoptions)すべてのオプションがデフォルト値に設定されているクラス |
| [EbookEditOptions](ebookeditoptions#constructor_1)(bool) | の新しいインスタンスを初期化します[`EbookEditOptions`](../ebookeditoptions)ページネーションを指定したクラス mode |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/ebookeditoptions/enablelanguageinformation) { get; set; } | 言語情報を「lang」HTML 属性の形式で HTML マークアップにエクスポートするかどうかを指定します。 このオプションは、多言語ドキュメントのラウンドトリップ変換に役立ちます。デフォルトでは無効になっています (`間違い`). |
| [EnablePagination](../../groupdocs.editor.options/ebookeditoptions/enablepagination) { get; set; } | 結果の HTML ドキュメントでページネーションを有効または無効にできます。デフォルトでは無効になっています (`間違い`). |

### 備考

サポートされている電子書籍形式:

1. [ePub](https://docs.fileformat.com/ebook/epub/) （電子出版）
2. [モビ](https://docs.fileformat.com/ebook/mobi/) (モビポケット)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/)(Kindleフォーマット8t)

### 関連項目

* interface [IEditOptions](../ieditoptions)
* 名前空間 [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* 組み立て [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
