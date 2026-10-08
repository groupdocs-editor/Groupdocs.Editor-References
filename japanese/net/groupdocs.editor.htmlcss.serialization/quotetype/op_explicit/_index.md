---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された QuoteTypegroupdocs.editor.htmlcss.serialization/quotetype インスタンスを Char にキャストします"
type: docs
weight: 100
url: /ja/net/groupdocs.editor.htmlcss.serialization/quotetype/op_explicit/
---
## explicit operator {#op_explicit}

指定された [`QuoteType`](../../quotetype) インスタンスを Char にキャストします

```csharp
public static explicit operator char(QuoteType quote)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| クオート | QuoteType | キャスト対象の Quote 型インスタンス |

### 参照

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit_1}

特定の Char を対応する [`QuoteType`](../../quotetype) にキャストし、キャストが無効な場合は例外をスローします

```csharp
public static explicit operator QuoteType(char character)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 文字 | Char | シングルクオート (U+0027 APOSTROPHE) またはダブルクオート (U+0022 QUOTATION MARK) 文字です。その他の文字が指定された場合は例外がスローされます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 指定された Char は引用符でもアポストロフィでもありません |

### 参照

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
