---
title: "EmailSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات البريد الإلكتروني."
type: docs
weight: 15
url: /ar/nodejs-java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات البريد الإلكتروني (email).

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | يُنشئ مثيلاً جديدًا من الفئة [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions)، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | يُنشئ مثيلاً جديدًا من الفئة [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) مع |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) المعامل
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | يسمح بالتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى مستند البريد الإلكتروني الناتج، والذي سيتم إنشاؤه وحفظه باستخدام طريقة [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-). |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | يسمح بالتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى مستند البريد الإلكتروني الناتج، والذي سيتم إنشاؤه وحفظه باستخدام طريقة [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-). |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


يُنشئ مثيلاً جديدًا من الفئة [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions)، حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


يُنشئ مثيلاً جديدًا من الفئة [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) مع
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


يسمح بالتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى مستند البريد الإلكتروني الناتج، والذي سيتم إنشاؤه وحفظه باستخدام طريقة [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-).
القيمة: تعداد معلم يحدد أجزاء رسالة البريد التي يجب معالجتها. القيمة الافتراضية هي MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


يسمح بالتحكم في أي أجزاء من رسالة البريد يجب تسليمها إلى مستند البريد الإلكتروني الناتج، والذي سيتم إنشاؤه وحفظه باستخدام طريقة [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-).
القيمة: تعداد معلم يحدد أجزاء رسالة البريد التي يجب معالجتها. القيمة الافتراضية هي MailMessageOutput.All


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

