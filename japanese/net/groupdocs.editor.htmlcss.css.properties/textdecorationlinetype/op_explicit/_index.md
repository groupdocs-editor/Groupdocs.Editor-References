---
title: "op_Explicit"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "特定の 8 ビットバイトを対応する TextDecorationLineTypegroupdocs.editor.htmlcss.css.properties/textdecorationlinetype にキャストします。キャストが無効な場合は例外をスローします。"
type: docs
weight: 180
url: /ja/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit/
---
## explicit operator {#op_explicit_1}

特定のバイト（8ビットオクテット）を対応する[`TextDecorationLineType`](../../textdecorationlinetype)にキャストし、キャストが無効な場合は例外をスローします

```csharp
public static explicit operator TextDecorationLineType(byte octet)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| オクテット | バイト | 5ビットがゼロで、残りの3ビットがフラグを示す8ビットオクテット（ビットフィールド） |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 指定された*octet*の値が無効です |

### 参照

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

指定された[`TextDecorationLineType`](../../textdecorationlinetype)インスタンスを同等のオクテット（8ビットビットフィールド）にキャストします

```csharp
public static explicit operator byte(TextDecorationLineType input)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | TextDecorationLineType | キャストする[`TextDecorationLineType`](../../textdecorationlinetype)インスタンス |

### 参照

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
