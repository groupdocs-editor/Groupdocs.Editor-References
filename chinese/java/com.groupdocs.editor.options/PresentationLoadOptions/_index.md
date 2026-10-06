---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "允许指定用于加载所有受支持的 Presentation 格式（如 PPTX、PPTM、PPSX 等）文档的自定义选项。"
type: docs
weight: 33
url: /zh/java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

允许指定用于加载所有受支持的文档的自定义选项
Presentation 格式，如 PPT(X)、PPTM、PPS(X) 等。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 允许指定、修改并获取将用于 |
打开 Presentation 文档的密码（如果已加密）。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 允许指定、修改并获取将用于 |
打开 Presentation 文档的密码（如果已加密）。
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


允许指定、修改并获取将用于
打开 Presentation 文档的密码（如果已加密）。将其设置为 NULL 或空字符串
字符串以移除密码。


*** ** * ** ***

默认情况下，此属性为 NULL — 表示未设置密码。如果输入的 Presentation 文档受密码保护，则密码是必需的；如果未指定密码或密码无效，将抛出异常。如果输入的 Presentation 文档未受密码保护，但设置了密码，则该密码将被忽略。

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


允许指定、修改并获取将用于
打开 Presentation 文档的密码（如果已加密）。将其设置为 NULL 或空字符串
字符串以移除密码。


*** ** * ** ***

默认情况下，此属性为 NULL — 表示未设置密码。如果输入的 Presentation 文档受密码保护，则密码是必需的；如果未指定密码或密码无效，将抛出异常。如果输入的 Presentation 文档未受密码保护，但设置了密码，则该密码将被忽略。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

