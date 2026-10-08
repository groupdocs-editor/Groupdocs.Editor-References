---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "区切り文字を使用するテキストベースのスプレッドシートドキュメント（CSV、タブ区切りなど）を生成および保存するためのオプションを含みます"
type: docs
weight: 820
url: /ja/net/groupdocs.editor.options/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions class

区切り文字（デリミタ）を使用するテキストベースのスプレッドシートドキュメント（CSV、タブ区切りなど）を生成および保存するためのオプションを含みます

```csharp
public sealed class DelimitedTextSaveOptions : ISaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor)() | このパラメータなしコンストラクタは、デフォルトのセミコロン (;) 区切り文字で DelimitedTextSaveOptions の新しいインスタンスを作成します（その後、[`Separator`](./separator) プロパティで変更可能です） |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor_1)(string) | 必須の区切り文字（デリミタ）を指定して、区切りテキスト用オプションクラスのインスタンスを作成します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Encoding](../../groupdocs.editor.options/delimitedtextsaveoptions/encoding) { get; set; } | テキストベースのスプレッドシートドキュメントのエンコーディングを設定できます。デフォルト（指定しない場合）は UTF8 です。 |
| [KeepSeparatorsForBlankRow](../../groupdocs.editor.options/delimitedtextsaveoptions/keepseparatorsforblankrow) { get; set; } | 空行に区切り文字を出力するかどうかを示します。デフォルト値は `false` で、空行の内容は空になります。 |
| [Separator](../../groupdocs.editor.options/delimitedtextsaveoptions/separator) { get; set; } | テキストベースのスプレッドシートドキュメント用に文字列区切り文字（デリミタ）を指定できます |
| [TrimLeadingBlankRowAndColumn](../../groupdocs.editor.options/delimitedtextsaveoptions/trimleadingblankrowandcolumn) { get; set; } | MS Excel が行うように、先頭の空白行や列をトリムするかどうかを示します |

### 備考

https://en.wikipedia.org/wiki/Delimiter-separated_values

### 参照

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
