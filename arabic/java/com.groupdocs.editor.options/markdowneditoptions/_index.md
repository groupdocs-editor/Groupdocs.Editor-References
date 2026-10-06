---
title: "MarkdownEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يسمح بتحديد خيارات مخصصة لتحرير المستندات بتنسيق Markdown."
type: docs
weight: 21
url: /ar/java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

يسمح بتحديد خيارات مخصصة لتحرير المستندات بتنسيق Markdown.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | ينشئ ويعيد نسخة جديدة من فئة MarkdownEditOptions، |
حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | يسمح بالتحكم في كيفية حفظ الصور عند تحويل مستند Markdown |
إلى Html.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | يسمح بالتحكم في كيفية حفظ الصور عند تحويل مستند Markdown |
إلى Html.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


ينشئ ويعيد نسخة جديدة من فئة MarkdownEditOptions،
حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


يسمح بالتحكم في كيفية حفظ الصور عند تحويل مستند Markdown
إلى Html.
القيمة: رد الاتصال لحفظ الصورة.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


يسمح بالتحكم في كيفية حفظ الصور عند تحويل مستند Markdown
إلى Html.
القيمة: رد الاتصال لحفظ الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

