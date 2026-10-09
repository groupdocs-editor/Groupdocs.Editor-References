---
title: "EmailEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لتحرير المستندات في صيغ البريد الإلكتروني المختلفة"
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

يسمح بتحديد خيارات مخصصة لتحرير المستندات بصيغ البريد الإلكتروني المختلفة (email).

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | يُنشئ مثيلًا جديدًا من الفئة [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions)، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | يُنشئ مثيلًا جديدًا من الفئة [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) باستخدام |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) المعامل
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | يسمح بالتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى [EditableDocument](../../com.groupdocs.editor/editabledocument) الناتج ثم إلى HTML المُصدر |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | يسمح بالتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى [EditableDocument](../../com.groupdocs.editor/editabledocument) الناتج ثم إلى HTML المُصدر |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


يُنشئ مثيلًا جديدًا من الفئة [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions)، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


يُنشئ مثيلًا جديدًا من الفئة [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) باستخدام
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) المعامل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | mailMessageOutput | int | إخراج رسالة البريد، والذي يمكن أيضًا تحديده عبر الخاصية |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


يسمح بالتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى [EditableDocument](../../com.groupdocs.editor/editabledocument) الناتج ثم إلى HTML المُصدر
القيمة: تعداد معلم يحدد أجزاء رسالة البريد التي يجب معالجتها. القيمة الافتراضية هي MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


يسمح بالتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى [EditableDocument](../../com.groupdocs.editor/editabledocument) الناتج ثم إلى HTML المُصدر
القيمة: تعداد معلم يحدد أجزاء رسالة البريد التي يجب معالجتها. القيمة الافتراضية هي MailMessageOutput.All


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

