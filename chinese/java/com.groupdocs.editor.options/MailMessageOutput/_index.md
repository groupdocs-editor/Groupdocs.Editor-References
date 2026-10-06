---
title: "MailMessageOutput"
second_title: "GroupDocs.Editor for Java API 参考"
description: "控制邮件消息的哪些部分应传递到输出处理。"
type: docs
weight: 20
url: /zh/java/com.groupdocs.editor.options/mailmessageoutput/
---
**Inheritance:**
java.lang.Object
```
public final class MailMessageOutput
```

控制邮件消息的哪些部分应传递到输出处理。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [None](#None) | 不会处理任何电子邮件消息部分 |
|
|  | [Body](#Body) | 处理邮件消息的正文 |
|
|  | [Subject](#Subject) | 处理邮件消息的主题 |
|
|  | [Date](#Date) | 处理邮件消息的发送日期和时间 |
|
|  | [To](#To) | 处理邮件消息的所有收件人 |
|
|  | [Cc](#Cc) | 处理邮件消息的所有抄送收件人 |
|
|  | [Bcc](#Bcc) | 处理邮件消息的所有密送收件人 |
|
|  | [From](#From) | 处理邮件消息的发件人 |
|
|  | [Attachments](#Attachments) | 处理邮件消息的所有附件 |
|
|  | [Metadata](#Metadata) | 处理所有其他技术元数据（敏感度、优先级、编码、MIME、X-Mailer 等） |
|
|  | [Common](#Common) | 通用输出 - 包含所有主要元数据的正文 |
|
|  | [All](#All) | 完整输出 - 包含所有元数据的正文 |
|
### None {#None}
```
public static final int None
```


不会处理任何电子邮件消息部分


### Body {#Body}
```
public static final int Body
```


处理邮件消息的正文


### Subject {#Subject}
```
public static final int Subject
```


处理邮件消息的主题


### Date {#Date}
```
public static final int Date
```


处理邮件消息的发送日期和时间


### To {#To}
```
public static final int To
```


处理邮件消息的所有收件人


### Cc {#Cc}
```
public static final int Cc
```


处理邮件消息的所有抄送收件人


### Bcc {#Bcc}
```
public static final int Bcc
```


处理邮件消息的所有密送收件人


### From {#From}
```
public static final int From
```


处理邮件消息的发件人


### Attachments {#Attachments}
```
public static final int Attachments
```


处理邮件消息的所有附件


### Metadata {#Metadata}
```
public static final int Metadata
```


处理所有其他技术元数据（敏感度、优先级、编码、MIME、X-Mailer 等）


### Common {#Common}
```
public static final int Common
```


通用输出 - 包含所有主要元数据的正文


### All {#All}
```
public static final int All
```


完整输出 - 包含所有元数据的正文


