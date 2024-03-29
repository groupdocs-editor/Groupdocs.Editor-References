---
title: DelimitedTextSaveOptions
second_title: GroupDocs.Editor for .NET API リファレンス
description: セパレーター delimiter を使用するテキストベースのスプレッドシート ドキュメント CSVタブベースなど を生成および保存するためのオプションが含まれています
type: docs
weight: 830
url: /ja/net/groupdocs.editor.options/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions class

セパレーター (delimiter) を使用するテキストベースのスプレッドシート ドキュメント (CSV、タブベースなど) を生成および保存するためのオプションが含まれています

```csharp
public sealed class DelimitedTextSaveOptions : ISaveOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions)(string) | 必須の区切り文字 (delimiter) で区切られたテキストのオプション クラスのインスタンスを作成します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Encoding](../../groupdocs.editor.options/delimitedtextsaveoptions/encoding) { get; set; } | テキストベースのスプレッドシート ドキュメントのエンコーディングを設定できます。デフォルトでは (および指定されていない場合)、UTF8. です。 |
| [KeepSeparatorsForBlankRow](../../groupdocs.editor.options/delimitedtextsaveoptions/keepseparatorsforblankrow) { get; set; } | 空白行にセパレータを出力するかどうかを示します。デフォルト値は`間違い`これは、空白行のコンテンツが空になることを意味します. |
| [Separator](../../groupdocs.editor.options/delimitedtextsaveoptions/separator) { get; set; } | テキストベースのスプレッドシート ドキュメントの文字列セパレータ (区切り文字) を指定できます |
| [TrimLeadingBlankRowAndColumn](../../groupdocs.editor.options/delimitedtextsaveoptions/trimleadingblankrowandcolumn) { get; set; } | MS Excel のように先頭の空白の行と列をトリミングする必要があるかどうかを示します |

### 備考

https://en.wikipedia.org/wiki/Delimiter-separated_values

### 関連項目

* interface [ISaveOptions](../isaveoptions)
* 名前空間 [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* 組み立て [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
