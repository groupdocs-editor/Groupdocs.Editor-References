---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "允许为加载所有支持的 Presentation 格式（如 PPTX、PPTM、PPSX 等）的文档指定自定义选项。"
type: docs
weight: 33
url: /zh/nodejs-java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

允许为加载所有支持的文档指定自定义选项
Presentation 格式，如 PPT(X)、PPTM、PPS(X) 等。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 允许指定、修改和获取密码，该密码将用于 |
打开 Presentation 文档（如果已编码）。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 允许指定、修改和获取密码，该密码将用于 |
打开 Presentation 文档（如果已编码）。
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


允许指定、修改和获取密码，该密码将用于
打开 Presentation 文档（如果已编码）。设置为 NULL 或空值
字符串，用于移除密码。


*** ** * ** ***

默认情况下，此属性的值为 NULL \u2014 未设置密码。如果输入的 Presentation 文档受密码保护，则密码是必需的；如果未指定密码或密码无效，将抛出异常。如果输入的 Presentation 文档未受密码保护，但设置了密码，则会被忽略。

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


允许指定、修改和获取密码，该密码将用于
打开 Presentation 文档（如果已编码）。设置为 NULL 或空值
字符串，用于移除密码。


*** ** * ** ***

默认情况下，此属性的值为 NULL \u2014 未设置密码。如果输入的 Presentation 文档受密码保护，则密码是必需的；如果未指定密码或密码无效，将抛出异常。如果输入的 Presentation 文档未受密码保护，但设置了密码，则会被忽略。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

