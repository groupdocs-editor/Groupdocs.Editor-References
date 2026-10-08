---
title: "IAuxDisposable"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "標準の IDisposable インターフェイスを拡張し、オブジェクトの現在の状態を取得し、破棄イベントに登録できるようにします。"
type: docs
weight: 420
url: /ja/net/groupdocs.editor.htmlcss.resources/iauxdisposable/
---
## IAuxDisposable interface

標準の IDisposable インターフェイスを拡張し、オブジェクトの現在の状態を取得し、disposing イベントを購読できるようにします

```csharp
public interface IAuxDisposable : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources/iauxdisposable/isdisposed) { get; } | リソースが閉じているかどうかを判断します（true が閉じている、false が開いている）。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources/iauxdisposable/disposed) | オブジェクトが破棄されたときに発生します。 |

### 参照

* namespace [GroupDocs.Editor.HtmlCss.Resources](../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
