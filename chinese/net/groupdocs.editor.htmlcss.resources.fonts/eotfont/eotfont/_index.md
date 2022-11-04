---
title: EotFont
second_title: GroupDocs.Editor for .NET API 参考
description: 从内容创建新的 EotFont 类表示为 base64 编码的字符串并具有指定的名称
type: docs
weight: 10
url: /zh/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/eotfont/
---
## EotFont(string, string) {#constructor_1}

从内容创建新的 EotFont 类，表示为 base64 编码的字符串，并具有指定的名称

```csharp
public EotFont(string name, string contentInBase64)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | String | EOT 字体的名称。不能为 null、空或空格。 |
| contentInBase64 | String | 内容为 base64 编码的字符串。不能为 null、空或空格。 如果不是 EOT 内容，会抛出异常。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 也可以看看

* class [EotFont](../../eotfont)
* 命名空间 [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../eotfont)
* 部件 [GroupDocs.Editor](../../../)

---

## EotFont(string, Stream) {#constructor}

从内容创建新的 EotFont 类，表示为字节流，并具有指定的名称

```csharp
public EotFont(string name, Stream binaryContent)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | String | EOT 字体的名称。不能为 null、空或空格。 |
| binaryContent | Stream | 内容为字节流。阅读从原始位置开始。不能为空。 应该是可读和可搜索的。如果此实例将被释放，则此流也将被释放。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### 也可以看看

* class [EotFont](../../eotfont)
* 命名空间 [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../eotfont)
* 部件 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->