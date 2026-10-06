---
title: "PdfLoadOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "包含用于将 PDF 文档加载到 Editor 类中的选项。"
type: docs
weight: 30
url: /zh/java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

包含用于将 PDF 文档加载到 Editor 类中的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 允许指定、修改和获取密码，该密码将在打开已加密的 PDF 文档时使用。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 允许指定、修改和获取密码，该密码将在打开已加密的 PDF 文档时使用。 |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


允许指定、修改和获取密码，该密码将在打开已加密的 PDF 文档时使用。
设置为 NULL 或空字符串以不使用密码（默认值）。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


允许指定、修改和获取密码，该密码将在打开已加密的 PDF 文档时使用。
设置为 NULL 或空字符串以不使用密码（默认值）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

