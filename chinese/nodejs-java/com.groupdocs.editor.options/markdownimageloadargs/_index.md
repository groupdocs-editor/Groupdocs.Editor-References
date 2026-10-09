---
title: "MarkdownImageLoadArgs"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "提供 MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs 事件的数据。"
type: docs
weight: 22
url: /zh/nodejs-java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

提供以下数据

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

事件。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | 获取或设置将在 Markdown 文档中保持原样的文件名，该文件名将被 |
处理。
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | 获取或设置将在 Markdown 文档中保持原样的文件名，该文件名将被 |
处理。
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | 获取一个值，指示此图像是否具有绝对 URI 链接。 |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | 获取一个值，指示此图像是否具有绝对 URI 链接。 |
|
|  | [setData(byte[] data)](#setData-byte---) | 设置资源的用户提供数据，该数据将在以下情况下使用： |

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

|
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


获取或设置将在 Markdown 文档中保持原样的文件名，该文件名将被
处理。


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


获取或设置将在 Markdown 文档中保持原样的文件名，该文件名将被
处理。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


获取一个值，指示此图像是否具有绝对 URI 链接。
值： true 表示此图像具有绝对 URI 链接；否则为 false。


**Returns:**
布尔
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


获取一个值，指示此图像是否具有绝对 URI 链接。
值： true 表示此图像具有绝对 URI 链接；否则为 false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


设置资源的用户提供数据，该数据将在以下情况下使用：

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] |  |

