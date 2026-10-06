---
title: "EmailFormats"
second_title: "GroupDocs.Editor for Java API 参考"
description: "封装所有电子邮件格式。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

封装所有电子邮件格式。包括以下文件类型：
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

了解更多关于电子邮件格式的信息，请点击[此处](../https://docs.fileformat.com/email/)。

<br />


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Tnef](#Tnef) | 传输中立封装格式（TNEF）是微软的专有格式，用于基于消息应用程序编程接口（MAPI）封装电子邮件附件。 |
|
|  | [Eml](#Eml) | EML 文件格式表示使用 Outlook 及其他相关应用程序保存的电子邮件消息。 |
|
|  | [Emlx](#Emlx) | EMLX 文件格式由 Apple 实现和开发。 |
|
|  | [Msg](#Msg) | MSG 是 Microsoft Outlook 和 Exchange 用于存储电子邮件、联系人、约会或其他任务的文件格式。 |
|
|  | [Html](#Html) | HTML 格式的电子邮件。 |
|
|  | [Mhtml](#Mhtml) | MHTML，是 “MIME encapsulation of aggregate HTML documents” 的缩写。 |
|
|  | [Ics](#Ics) | 互联网日历和调度核心对象规范（iCalendar）是一项互联网标准（RFC 2445），用于交换和部署日历事件及调度。 |
|
|  | [Vcf](#Vcf) | VCF（虚拟名片格式）或 vCard 是用于存储联系信息的数字文件格式。 |
|
|  | [Pst](#Pst) | .pst 扩展名的文件代表 Outlook 个人存储文件（亦称个人存储表），用于存储各种用户信息。 |
|
|  | [Mbox](#Mbox) | MBox 文件格式是一个通用术语，表示用于收集电子邮件的容器。 |
|
|  | [Oft](#Oft) | .oft 扩展名的文件是使用 Microsoft Outlook 创建的模板文件。 |
|
|  | [Ost](#Ost) | 离线存储表（OST）文件表示 user\\u2019s 在本地机器上离线模式下的邮箱数据，该数据在使用 Microsoft Outlook 注册 Exchange Server 时生成。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getAll()](#getAll--) | 获取所有 [EmailFormats](../../com.groupdocs.editor.formats/emailformats) 的可枚举集合。 |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 检索具有指定文件扩展名的指定类型 [EmailFormats](../../com.groupdocs.editor.formats/emailformats) 实例。 |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | 将表示文件扩展名的字符串转换为 [EmailFormats](../../com.groupdocs.editor.formats/emailformats) 对象。 |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


传输中立封装格式（TNEF）是微软的专有格式，用于基于消息应用程序编程接口（MAPI）封装电子邮件附件。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


EML 文件格式表示使用 Outlook 及其他相关应用程序保存的电子邮件消息。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


EMLX 文件格式由 Apple 实现和开发。Apple Mail 应用程序使用 EMLX 文件格式导出电子邮件。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG 是 Microsoft Outlook 和 Exchange 用于存储电子邮件、联系人、约会或其他任务的文件格式。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


HTML 格式的电子邮件。


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML，是 “MIME encapsulation of aggregate HTML documents” 的缩写。


### Ics {#Ics}
```
public static final EmailFormats Ics
```


互联网日历和调度核心对象规范（iCalendar）是一项互联网标准（RFC 2445），用于交换和部署日历事件及调度。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF（虚拟名片格式）或 vCard 是用于存储联系信息的数字文件格式。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


.pst 扩展名的文件代表 Outlook 个人存储文件（亦称个人存储表），用于存储各种用户信息。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


MBox 文件格式是一个通用术语，表示用于收集电子邮件的容器。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


.oft 扩展名的文件是使用 Microsoft Outlook 创建的模板文件。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


离线存储表（OST）文件表示 user\\u2019s 在本地机器上离线模式下的邮箱数据，该数据在使用 Microsoft Outlook 注册 Exchange Server 时生成。
了解更多关于此文件格式的信息
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


获取所有 [EmailFormats](../../com.groupdocs.editor.formats/emailformats) 的可枚举集合。
值：包含所有 [EmailFormats](../../com.groupdocs.editor.formats/emailformats) 实例的 IEnumerable{EmailFormats}。


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


检索具有指定文件扩展名的指定类型 [EmailFormats](../../com.groupdocs.editor.formats/emailformats) 实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 文档格式的文件扩展名。 |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


将表示文件扩展名的字符串转换为 [EmailFormats](../../com.groupdocs.editor.formats/emailformats) 对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 扩展名 | java.lang.String | 要转换的文件扩展名。如果扩展名包含多个句点，则使用最后一个句点之后的部分。 |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

