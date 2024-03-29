---
title: FromStartPageTillEndPage
second_title: GroupDocs.Editor for .NET API 参考
description: 创建一个页面范围从指定的页码包括开始一直持续到指定的页码不包括
type: docs
weight: 40
url: /zh/net/groupdocs.editor.options/pagerange/fromstartpagetillendpage/
---
## PageRange.FromStartPageTillEndPage method

创建一个页面范围，从指定的页码（包括）开始，一直持续到指定的页码（不包括）

```csharp
public static PageRange FromStartPageTillEndPage(ushort startPageNumber, ushort endPageNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startPageNumber | UInt16 | 页码，页面范围从其开始，包括在内。页码从 1 开始，因此必须严格大于零 |
| endPageNumber | UInt16 | 页码，直到页面范围继续，独占。页码从 1 开始，因此必须严格大于零，也必须严格大于*startPageNumber* |

### 也可以看看

* struct [PageRange](../../pagerange)
* 命名空间 [GroupDocs.Editor.Options](../../pagerange)
* 部件 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
