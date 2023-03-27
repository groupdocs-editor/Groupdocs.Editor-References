---
title: TryParse
second_title: GroupDocs.Editor for .NET API リファレンス
description: 数値と単位名を含む指定された文字列を長さの値として解析しようとします
type: docs
weight: 270
url: /ja/net/groupdocs.editor.htmlcss.css.datatypes/length/tryparse/
---
## Length.TryParse method

数値と単位名を含む、指定された文字列を長さの値として解析しようとします

```csharp
public static bool TryParse(string input, out Length result)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| input | String | 解析する必要がある入力文字列 |
| result | Length& | 解析の結果を含む出力パラメーター。 解析が失敗した場合、デフォルトの長さ値 (単位のないゼロ) が含まれます。 |

### 戻り値

解析が成功した場合は true、失敗した場合は false

### 関連項目

* struct [Length](../../length)
* 名前空間 [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../length)
* 組み立て [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->