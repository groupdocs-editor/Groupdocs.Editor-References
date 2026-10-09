---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "包含可在将 XML 文档呈现为 HTML 时调整其格式的选项"
type: docs
weight: 52
url: /zh/nodejs-java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

包含允许在 XML 文档呈现为 HTML 时调整其格式的选项。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | 启用后，每个 XML 元素中的每一对属性-值都将放在新行上。 |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | 启用后，每个 XML 元素中的每一对属性-值都将放在新行上。 |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | 启用后，叶子文本节点（XML 元素内部的文本内容且没有子节点）将以更大的左缩进在新行上呈现。 |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | 启用后，叶子文本节点（XML 元素内部的文本内容且没有子节点）将以更大的左缩进在新行上呈现。 |
|
|  | [getLeftIndent()](#getLeftIndent--) | 允许为每个新行的左缩进指定偏移量。 |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 允许为每个新行的左缩进指定偏移量。 |
|
|  | [isDefault()](#isDefault--) | 指示此 XML 格式化选项实例是否具有默认值 |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


启用后，每个 XML 元素中的每一对属性-值都将放在新行上。
默认情况下为 false（已禁用）\\u2014 所有属性-值对放在同一行。


**Returns:**
布尔
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


启用后，每个 XML 元素中的每一对属性-值都将放在新行上。
默认情况下为 false（已禁用）\\u2014 所有属性-值对放在同一行。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


启用后，叶子文本节点（XML 元素内部的文本内容且没有子节点）将以更大的左缩进在新行上呈现。
默认情况下为 false（已禁用）\\u2014 叶子文本节点与其父节点位于同一行，且没有新的缩进。


**Returns:**
布尔
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


启用后，叶子文本节点（XML 元素内部的文本内容且没有子节点）将以更大的左缩进在新行上呈现。
默认情况下为 false（已禁用）\\u2014 叶子文本节点与其父节点位于同一行，且没有新的缩进。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


允许为每个新行的左缩进指定偏移量。不能是无单位的非零值。默认值为 10pt。


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


允许为每个新行的左缩进指定偏移量。不能是无单位的非零值。默认值为 10pt。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


指示此 XML 格式化选项实例是否具有默认值


**Returns:**
布尔
