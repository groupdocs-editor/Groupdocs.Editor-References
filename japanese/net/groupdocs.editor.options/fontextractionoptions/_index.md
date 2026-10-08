---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "フォント抽出オプションは、どのフォントを抽出し、どこから抽出するかを制御します。"
type: docs
weight: 890
url: /ja/net/groupdocs.editor.options/fontextractionoptions/
---
## FontExtractionOptions enumeration

フォント抽出オプションは、どのフォントを抽出し、どこから抽出するかを制御します。

```csharp
public enum FontExtractionOptions
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| NotExtract | `0` | ドキュメントやシステムからフォントリソースを抽出しません。デフォルト値です。 |
| ExtractAllEmbedded | `1` | 入力 Word ドキュメントに埋め込まれたすべてのフォントリソースを抽出します。カスタムかシステムかに関わらず抽出します。 |
| ExtractEmbeddedWithoutSystem | `2` | カスタム（システムではない）埋め込みフォントリソースのみを抽出します |
| ExtractAll | `3` | 入力 WordProcessing ドキュメントで使用されているすべてのフォント（システムフォントを含む）を抽出しようとします |

### 参照

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
