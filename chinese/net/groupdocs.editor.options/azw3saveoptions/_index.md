---
title: Azw3SaveOptions
second_title: GroupDocs.Editor for .NET API 参考
description: 允许指定用于生成和保存 AZW3 电子书的自定义选项也称为 Kindle Format 8 KF8
type: docs
weight: 660
url: /zh/net/groupdocs.editor.options/azw3saveoptions/
---
## Azw3SaveOptions class

允许指定用于生成和保存 AZW3 电子书的自定义选项，也称为 Kindle Format 8 (KF8)

```csharp
public sealed class Azw3SaveOptions : ISaveOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Azw3SaveOptions](azw3saveoptions)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [SplitHeadingLevel](../../groupdocs.editor.options/azw3saveoptions/splitheadinglevel) { get; set; } | 指定是否将 AZW3 电子书的内容拆分为包，如果是，则指定拆分 AZW3 内容的最大标题级别。默认值为`2` 将其设置为`0`将禁用拆分，因此电子书的所有内容将合并到 AZW3. 内的单个包中 |

### 也可以看看

* interface [ISaveOptions](../isaveoptions)
* 命名空间 [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* 部件 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->