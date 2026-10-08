---
title: "Dispose"
second_title: "GroupDocs.Editor for .NET API リファレンス"
description: "Editor のこのインスタンスを破棄し、すべての内部リソースを解放して以後使用できなくします。"
type: docs
weight: 50
url: /ja/net/groupdocs.editor/editor/dispose/
---
## Editor.Dispose method

このEditorインスタンスを破棄し、すべての内部リソースを解放して以後使用できなくなります。

```csharp
public void Dispose()
```

### 備考

このメソッドが呼び出された後、このインスタンスの他のすべてのメソッドを呼び出すと ObjectDisposedException がスローされます。このメソッドは複数回呼び出しても安全で、以降の呼び出しはすべて無視されます。

### 参照

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.editor.dll 用に生成されました -->
