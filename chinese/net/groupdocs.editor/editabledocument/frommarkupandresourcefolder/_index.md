---
title: FromMarkupAndResourceFolder
second_title: GroupDocs.Editor for .NET API 参考
description: 静态工厂从指定的 HTML 标记和资源创建 EditableDocument 的实例该资源位于文件夹中由完整路径指定
type: docs
weight: 30
url: /zh/net/groupdocs.editor/editabledocument/frommarkupandresourcefolder/
---
## EditableDocument.FromMarkupAndResourceFolder method

静态工厂，从指定的 HTML 标记和资源创建 EditableDocument 的实例，该资源位于文件夹中，由完整路径指定

```csharp
public static EditableDocument FromMarkupAndResourceFolder(string newHtmlContent, 
    string resourceFolderPath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newHtmlContent | String | 字符串，包含应解析的原始 HTML 标记。不能为 NULL、空或无效。 |
| resourceFolderPath | String | 包含资源的文件夹的强制路径。将使用位于此文件夹中的所有样式表。不能为 NULL 或空字符串，并且该文件夹应该存在。 |

### 返回值

EditableDocument 的新非空实例

### 评论

当 HTML 文档的内容以字符串形式呈现时，此静态工厂很有用，但所有资源都位于某个文件夹中，并且 HTML 标记中指向这些资源的链接通常无效且不存在。调用此方法时，它会扫描指定文件夹并自动将所有找到的样式表应用于文档。这种方法在从不同的 HTML 编辑器获取内容时非常有用，通常会切断文档元数据等。

### 也可以看看

* class [EditableDocument](../../editabledocument)
* 命名空间 [GroupDocs.Editor](../../editabledocument)
* 部件 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
