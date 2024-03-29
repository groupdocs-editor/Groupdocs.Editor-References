---
title: FromMarkup
second_title: GroupDocs.Editor for .NET API 参考
description: 静态工厂它根据指定的 HTML 标记和一组相应的链接资源创建 EditableDocument 实例
type: docs
weight: 20
url: /zh/net/groupdocs.editor/editabledocument/frommarkup/
---
## EditableDocument.FromMarkup method

静态工厂，它根据指定的 HTML 标记和一组相应的链接资源创建 EditableDocument 实例

```csharp
public static EditableDocument FromMarkup(string newHtmlContent, 
    IEnumerable<IHtmlResource> resources)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newHtmlContent | String | 字符串，包含应解析的原始 HTML 标记。不能为 NULL、空或无效。 |
| resources | IEnumerable`1 | 在 HTML 文档中使用的所有资源（图像、样式表、字体）的集合，在中指定*newHtmlContent*范围。可能不存在（NULL 或空集合）。 |

### 返回值

EditableDocument 的新非空实例

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 带有输入原始 HTML 标记的字符串不能为 null 或为空 |

### 也可以看看

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* class [EditableDocument](../../editabledocument)
* 命名空间 [GroupDocs.Editor](../../editabledocument)
* 部件 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
