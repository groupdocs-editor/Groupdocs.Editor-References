---
title: "AudioType"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "サポート可能なオーディオタイプ形式のひとつを表します。"
type: docs
weight: 320
url: /ja/net/groupdocs.editor.htmlcss.resources.audio/audiotype/
---
## AudioType structure

サポート可能なオーディオタイプ（フォーマット）を 1 つ表します

```csharp
public struct AudioType : IEquatable<AudioType>, IResourceType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Mp3](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mp3) { get; } | MPEG-1 Audio Layer III オーディオ形式を表します。 |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.audio/audiotype/undefined) { get; } | 未定義、未知、またはサポートされていないオーディオ形式を示す特別な値です。 |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/fileextension) { get; } | このオーディオ形式のファイル名拡張子（ドット文字なし）です。 |
| [FormalName](../../groupdocs.editor.htmlcss.resources.audio/audiotype/formalname) { get; } | このオーディオ形式の正式名称です。 |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mimecode) { get; } | このオーディオ形式のMIMEコード |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/parsefromfilenamewithextension)(string) | 指定されたファイル名から抽出されたファイル拡張子に相当する AudioType 値を返します |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals)(AudioType) | このインスタンスが指定された "AudioType" インスタンスと等しいかどうかを判断します |
| override [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals_1)(object) | このインスタンスが指定されたキャストされていないオブジェクト（おそらく別の "AudioType" インスタンス）と等しいかどうかを判断します |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/gethashcode)() | この特定の値型に対して一定の数値であるハッシュコードを返します |
| [operator ==](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_equality) | 2つの "AudioType" 値が等しいかどうかをチェックします |
| [operator !=](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_inequality) | 2つの "AudioType" 値が等しくないかどうかをチェックします |

### 参照

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
