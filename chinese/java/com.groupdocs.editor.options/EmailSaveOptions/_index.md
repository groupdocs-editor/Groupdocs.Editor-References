---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor for Java API 参考"
description: "允许指定用于生成和保存电子邮件文档的自定义选项"
type: docs
weight: 15
url: /zh/java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

允许指定用于生成和保存电子邮件（email）文档的自定义选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | 初始化一个新的 [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) 类实例，所有选项均设置为默认值 |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | 使用以下方式初始化一个新的 [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) 类实例，带有 |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) 参数
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | 允许控制邮件消息的哪些部分应传递到输出的电子邮件文档，该文档将使用 [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) 方法生成并保存 |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | 允许控制邮件消息的哪些部分应传递到输出的电子邮件文档，该文档将使用 [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) 方法生成并保存 |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


初始化一个新的 [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) 类实例，所有选项均设置为默认值


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


使用以下方式初始化一个新的 [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) 类实例，带有
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


允许控制邮件消息的哪些部分应传递到输出的电子邮件文档，该文档将使用 [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) 方法生成并保存
值：标记枚举，控制应处理的邮件消息部分。默认值为 MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


允许控制邮件消息的哪些部分应传递到输出的电子邮件文档，该文档将使用 [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) 方法生成并保存
值：标记枚举，控制应处理的邮件消息部分。默认值为 MailMessageOutput.All


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

