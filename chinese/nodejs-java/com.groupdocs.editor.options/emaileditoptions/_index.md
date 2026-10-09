---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "允许为不同电子邮件格式的文档编辑指定自定义选项"
type: docs
weight: 14
url: /zh/nodejs-java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

允许指定用于编辑不同电子邮件（email）格式文档的自定义选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | 初始化 [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) 类的新实例，所有选项均设置为默认值 |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | 使用以下参数初始化 [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) 类的新实例 |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) 参数
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | 允许控制邮件消息的哪些部分应输出到 [EditableDocument](../../com.groupdocs.editor/editabledocument)，然后生成 HTML |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | 允许控制邮件消息的哪些部分应输出到 [EditableDocument](../../com.groupdocs.editor/editabledocument)，然后生成 HTML |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


初始化 [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) 类的新实例，所有选项均设置为默认值


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


使用以下参数初始化 [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) 类的新实例
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) 参数


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | mailMessageOutput | int | 邮件消息输出，也可以通过属性指定 |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


允许控制邮件消息的哪些部分应输出到 [EditableDocument](../../com.groupdocs.editor/editabledocument)，然后生成 HTML
值：标记枚举，用于控制应处理的邮件消息部分。默认值为 MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


允许控制邮件消息的哪些部分应输出到 [EditableDocument](../../com.groupdocs.editor/editabledocument)，然后生成 HTML
值：标记枚举，用于控制应处理的邮件消息部分。默认值为 MailMessageOutput.All


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

