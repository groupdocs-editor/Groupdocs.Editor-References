---
title: PdfSaveOptions
second_title: GroupDocs.Editor for .NET API 参考
description: 允许指定用于生成和保存 PDF便携式文档格式文档的自定义选项
type: docs
weight: 1060
url: /zh/net/groupdocs.editor.options/pdfsaveoptions/
---
## PdfSaveOptions class

允许指定用于生成和保存 PDF（便携式文档格式）文档的自定义选项

```csharp
public sealed class PdfSaveOptions : ISaveOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Compliance](../../groupdocs.editor.options/pdfsaveoptions/compliance) { get; set; } | 指定输出文档的 PDF 标准合规级别。默认为 PdfCompliance.Pdf17. |
| [FontEmbedding](../../groupdocs.editor.options/pdfsaveoptions/fontembedding) { get; set; } | 负责将原始文档中使用的字体资源嵌入到生成的 PDF 文档中。默认情况下不嵌入任何字体 (NotEmbed). |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/pdfsaveoptions/optimizememoryusage) { get; set; } | 在从 HTML 生成文档期间启用内存优化机制，这会以减少内存使用为代价降低性能。 将此选项设置为 true 可以显着减少内存消耗，同时以较慢的保存时间为代价生成大型文档。 默认值为 false （为了更好的性能禁用了内存优化）。 |
| [Password](../../groupdocs.editor.options/pdfsaveoptions/password) { get; set; } | 密码，将作为用户密码应用于生成的 PDF 文档，打开时需要。 如果为 NULL 或为空，则不会将密码应用于文档。否则，文档将使用 RC4（密钥长度为 128 位）加密。 默认为 NULL — 不应用密码。 |

### 也可以看看

* interface [ISaveOptions](../isaveoptions)
* 命名空间 [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* 部件 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
