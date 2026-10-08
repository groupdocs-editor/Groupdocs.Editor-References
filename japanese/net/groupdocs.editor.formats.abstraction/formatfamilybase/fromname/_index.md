---
title: "FromName"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された名前を持つ、指定された型 T のインスタンスを取得します。"
type: docs
weight: 60
url: /ja/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromname/
---
## FormatFamilyBase.FromName&lt;T&gt; method

指定された名前を持つ、指定された型 *T* のインスタンスを取得します。

```csharp
public static T FromName<T>(string name)
    where T : FormatFamilyBase
```

| パラメーター | 説明 |
| --- | --- |
| T | フォーマットファミリーの型です。 |
| 名前 | フォーマット ファミリの名前。 |

### 戻り値

指定された型 *T* のインスタンスで、指定された名前を持つ。

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | 一致するフォーマットファミリーが見つからない場合にスローされます。 |

### 参照

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
