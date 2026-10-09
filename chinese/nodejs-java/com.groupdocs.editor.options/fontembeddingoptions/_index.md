---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "字体嵌入选项控制哪些字体资源应嵌入到输出的 WordProcessing 文档中"
type: docs
weight: 17
url: /zh/nodejs-java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

字体嵌入选项控制哪些字体资源应嵌入到
输出的 WordProcessing 文档


*** ** * ** ***

字体嵌入选项在文档保存期间（从中间的 EditableDocument 转换为输出的 WordProcessing 格式）应用，此枚举作为属性包含在 WordProcessingSaveOptions 中，使用时应从该属性获取

<br />


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | 不要嵌入任何字体资源，无论是来自 EditableDocument 还是来自 |
系统。
|
|  | [EmbedAll](#EmbedAll) | 分析来自输入 EditableDocument 的文档内容，查找所有使用的字体 |
并将它们嵌入到输出的 WordProcessing 文档中。
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | 等同于 [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll)，但排除这些字体， |
这些字体被操作系统视为系统字体
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


不要嵌入任何字体资源，无论是来自 EditableDocument 还是来自
系统。默认值。


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


分析来自输入 EditableDocument 的文档内容，查找所有使用的字体
并将它们嵌入到输出的 WordProcessing 文档中。首先
GroupDocs.Editor 从 EditableDocument 中的字体资源获取字体。
如果这些字体不足或缺失，则 GroupDocs.Editor 将获取字体
来自操作系统。


*** ** * ** ***

首先，GroupDocs.Editor 分析 EditableDocument 的内容并形成所有使用字体的列表。然后在 EditableDocument 的字体资源中搜索这些字体。如果 EditableDocument 包含一些未在文档内容中使用的字体资源，则这些资源将被忽略。如果文档内容中使用的某些字体在 EditableDocument 中没有对应的字体资源，GroupDocs.Editor 将尝试在操作系统中查找它们。此选项类似于 Microsoft Word 2007 及更高版本中\"Embed fonts in the file\"选项且所有子选项均关闭的情况。

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


等同于 [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll)，但排除这些字体，
这些字体被操作系统视为系统字体


*** ** * ** ***

MS Windows 有系统字体的概念，这些是 Windows 本身最基本且常用的字体。使用此选项时，GroupDocs.Editor 的行为类似于 [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll) 情况，但最终会审查获取的字体集合并排除那些被操作系统视为系统字体的字体。此选项类似于 Microsoft Word 2007 及更高版本中的\"Embed fonts in the file\" + \"Do not embed common system fonts\"选项。

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
