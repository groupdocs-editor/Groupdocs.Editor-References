---
title: Dispose
second_title: GroupDocs.Editor for .NET API 参考
description: 处理此 Editor 实例以便它释放所有内部资源并变得不可用于进一步使用
type: docs
weight: 40
url: /zh/net/groupdocs.editor/editor/dispose/
---
## Editor.Dispose method

处理此 Editor 实例，以便它释放所有内部资源并变得不可用于进一步使用

```csharp
public void Dispose()
```

### 评论

调用此方法后，调用此实例的所有其他方法将抛出ObjectDisposedException.多次调用此方法是安全的——所有后续调用都将被忽略。

### 也可以看看

* class [Editor](../../editor)
* 命名空间 [GroupDocs.Editor](../../editor)
* 部件 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
