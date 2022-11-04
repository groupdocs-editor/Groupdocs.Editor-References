---
title: IDocumentInfo
second_title: GroupDocs.Editor for .NET API 参考
description: 所有文件元数据包装器的通用接口
type: docs
weight: 590
url: /zh/net/groupdocs.editor.metadata/idocumentinfo/
---
## IDocumentInfo interface

所有文件元数据包装器的通用接口

```csharp
public interface IDocumentInfo
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/idocumentinfo/format) { get; } | 在实现类型中应该返回一个文档格式作为一个类型的单个值，它代表一个格式系列并继承自 IDocumentFormat 接口 |
| [IsEncrypted](../../groupdocs.editor.metadata/idocumentinfo/isencrypted) { get; } | 表示特定文件是否加密并需要密码才能打开。对于无法加密的文档类型（如所有基于文本的），应始终返回“false”。 |
| [PageCount](../../groupdocs.editor.metadata/idocumentinfo/pagecount) { get; } | 在实现类型时应返回页数或其他类似格式相关实体（选项卡、幻灯片等）的计数（数量）。 对于那些没有类似内容的系列类型（如纯文本文档或 XML）应返回1. |
| [Size](../../groupdocs.editor.metadata/idocumentinfo/size) { get; } | 以字节为单位的文档大小 |

### 也可以看看

* 命名空间 [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* 部件 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->