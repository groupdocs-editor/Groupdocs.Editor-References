---
title: "MarkdownEditOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "允许指定用于编辑 Markdown 格式文档的自定义选项。"
type: docs
weight: 21
url: /zh/nodejs-java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

允许指定用于编辑 Markdown 格式文档的自定义选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | 创建并返回一个新的 MarkdownEditOptions 类实例， |
其中所有选项均设置为默认值
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | 允许控制在转换 Markdown 文档时图像的保存方式 |
为 Html。
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | 允许控制在转换 Markdown 文档时图像的保存方式 |
为 Html。
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


创建并返回一个新的 MarkdownEditOptions 类实例，
其中所有选项均设置为默认值


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


允许控制在转换 Markdown 文档时图像的保存方式
为 Html。
值：图像保存回调。


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


允许控制在转换 Markdown 文档时图像的保存方式
为 Html。
值：图像保存回调。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

