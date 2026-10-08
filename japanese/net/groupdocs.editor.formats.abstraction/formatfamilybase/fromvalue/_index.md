---
title: "FromValue"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された識別子を持つ、指定された型 T のインスタンスを取得します。"
type: docs
weight: 70
url: /ja/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue/
---
## FormatFamilyBase.FromValue&lt;T&gt; method

指定された識別子を持つ、指定された型 *T* のインスタンスを取得します。

```csharp
public static T FromValue<T>(int value)
    where T : FormatFamilyBase
```

| パラメーター | 説明 |
| --- | --- |
| T | フォーマットファミリーの型です。 |
| value | フォーマットファミリーの識別子です。 |

### 戻り値

指定された識別子を持つ、指定された型 *T* のインスタンスです。

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | 一致するフォーマットファミリーが見つからない場合にスローされます。 |

### 参照

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
