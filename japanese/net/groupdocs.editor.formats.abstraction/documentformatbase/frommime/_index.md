---
title: "FromMime"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "指定された MIME タイプを持つ、指定された型 T のインスタンスを取得します。"
type: docs
weight: 60
url: /ja/net/groupdocs.editor.formats.abstraction/documentformatbase/frommime/
---
## DocumentFormatBase.FromMime&lt;T&gt; method

指定された MIME タイプを持つ、指定された型 *T* のインスタンスを取得します。

```csharp
public static T FromMime<T>(string mime)
    where T : DocumentFormatBase
```

| パラメーター | 説明 |
| --- | --- |
| T | ドキュメント形式の型です。 |
| mime | ドキュメント形式の MIME タイプです。 |

### 戻り値

指定された MIME タイプを持つ、指定された型 *T* のインスタンスです。

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | 一致するドキュメント形式が見つからない場合にスローされます。 |

### 参照

* class [DocumentFormatBase](../../documentformatbase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
