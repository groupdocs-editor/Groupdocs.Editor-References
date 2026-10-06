---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "包含用于加载 WordProcessing（Word 兼容）文档的选项，如 DOCX、RTF、ODT 等。"
type: docs
weight: 45
url: /zh/java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

包含用于加载 WordProcessing（Word 兼容）文档的选项，如
DOC(X)、RTF、ODT 等到 Editor 类中

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 允许指定、修改并获取将用于 |
打开 WordProcessing 文档（如果已编码）。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 允许指定、修改并获取将用于 |
打开 WordProcessing 文档（如果已编码）。
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


允许指定、修改并获取将用于
打开 WordProcessing 文档（如果已编码）。设置为 NULL 或空。
字符串，以便不使用密码（默认值）。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


允许指定、修改并获取将用于
打开 WordProcessing 文档（如果已编码）。设置为 NULL 或空。
字符串，以便不使用密码（默认值）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

