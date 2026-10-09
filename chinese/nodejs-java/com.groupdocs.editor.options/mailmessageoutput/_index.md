---
title: "MailMessageOutput"
second_title: "GroupDocs.Editor 用于 Node.js 通过 Java API 参考"
description: "控制邮件消息的哪些部分应传递给输出处理。"
type: docs
weight: 20
url: /zh/nodejs-java/com.groupdocs.editor.options/mailmessageoutput/
---
**Inheritance:**
java.lang.Object
```
public final class MailMessageOutput
```

控制邮件消息的哪些部分应传递给输出处理。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [None](#None) | 电子邮件的任何部分都将不被处理 |
|
|  | [Body](#Body) | 处理邮件正文 |
|
|  | [Subject](#Subject) | 处理邮件主题 |
|
|  | [Date](#Date) | 处理邮件投递的日期和时间 |
|
|  | [To](#To) | 处理邮件的所有收件人 |
|
|  | [Cc](#Cc) | 处理邮件的所有抄送收件人 |
|
|  | [Bcc](#Bcc) | 处理邮件的所有密送收件人 |
|
|  | [From](#From) | 处理邮件的发件人 |
|
|  | [Attachments](#Attachments) | 处理邮件的所有附件 |
|
|  | [Metadata](#Metadata) | 处理所有其他技术元数据（敏感度、优先级、编码、MIME、X-Mailer 等） |
|
|  | [Common](#Common) | 常规输出 - 包含所有主要元数据的正文 |
|
|  | [All](#All) | 完整输出 - 包含所有元数据的正文 |
|
### None {#None}
```
public static final int None
```


电子邮件的任何部分都将不被处理


### Body {#Body}
```
public static final int Body
```


处理邮件正文


### Subject {#Subject}
```
public static final int Subject
```


处理邮件主题


### Date {#Date}
```
public static final int Date
```


处理邮件投递的日期和时间


### To {#To}
```
public static final int To
```


处理邮件的所有收件人


### Cc {#Cc}
```
public static final int Cc
```


处理邮件的所有抄送收件人


### Bcc {#Bcc}
```
public static final int Bcc
```


处理邮件的所有密送收件人


### From {#From}
```
public static final int From
```


处理邮件的发件人


### Attachments {#Attachments}
```
public static final int Attachments
```


处理邮件的所有附件


### Metadata {#Metadata}
```
public static final int Metadata
```


处理所有其他技术元数据（敏感度、优先级、编码、MIME、X-Mailer 等）


### Common {#Common}
```
public static final int Common
```


常规输出 - 包含所有主要元数据的正文


### All {#All}
```
public static final int All
```


完整输出 - 包含所有元数据的正文


