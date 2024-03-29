---
title: ToStringSpecified
second_title: GroupDocs.Editor for .NET API 参考
description: 以指定单位类型返回此长度的字符串表示形式数值将根据单位类型的变化进行转换
type: docs
weight: 250
url: /zh/net/groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified/
---
## Length.ToStringSpecified method

以指定单位类型返回此长度的字符串表示形式。数值将根据单位类型的变化进行转换。

```csharp
public string ToStringSpecified(Unit unit)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| unit | Unit | 指定单位，此实例在序列化为字符串之前应转换为该单位。 应该有效。不能没有单位。 |

### 返回值

字符串表示

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| InvalidEnumArgumentException | 值未定义 |
| ArgumentOutOfRangeException | 禁止使用无单位值 |

### 也可以看看

* enum [Unit](../../length.unit)
* struct [Length](../../length)
* 命名空间 [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../length)
* 部件 [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
