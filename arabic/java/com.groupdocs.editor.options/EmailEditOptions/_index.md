---
title: "EmailEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يسمح بتحديد خيارات مخصصة لتحرير المستندات في صيغ البريد الإلكتروني المختلفة"
type: docs
weight: 14
url: /ar/java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

يسمح بتحديد خيارات مخصصة لتحرير المستندات بصيغ البريد الإلكتروني (email) المختلفة

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | ينشئ مثيلًا جديدًا من الفئة [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions)، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | ينشئ مثيلًا جديدًا من الفئة [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) مع |
MailMessageOutput
معامل (#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput)
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | يسمح بالتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى مخرجات [EditableDocument](../../com.groupdocs.editor/editabledocument) ثم إلى HTML المُصدَّر |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | يسمح بالتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى مخرجات [EditableDocument](../../com.groupdocs.editor/editabledocument) ثم إلى HTML المُصدَّر |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


ينشئ مثيلًا جديدًا من الفئة [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions)، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


ينشئ مثيلًا جديدًا من الفئة [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) مع
MailMessageOutput
معامل (#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | mailMessageOutput | int | مخرج رسالة البريد، والذي يمكن أيضًا تحديده عبر الخاصية |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


يسمح بالتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى مخرجات [EditableDocument](../../com.groupdocs.editor/editabledocument) ثم إلى HTML المُصدَّر
القيمة: تعداد معلم يحدد أجزاء رسالة البريد التي يجب معالجتها. القيمة الافتراضية هي MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


يسمح بالتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى مخرجات [EditableDocument](../../com.groupdocs.editor/editabledocument) ثم إلى HTML المُصدَّر
القيمة: تعداد معلم يحدد أجزاء رسالة البريد التي يجب معالجتها. القيمة الافتراضية هي MailMessageOutput.All


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

