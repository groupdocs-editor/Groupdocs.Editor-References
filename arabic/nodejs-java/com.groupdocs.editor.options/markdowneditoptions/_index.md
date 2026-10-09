---
title: "MarkdownEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لتحرير المستندات بصيغة Markdown."
type: docs
weight: 21
url: /ar/nodejs-java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

يسمح بتحديد خيارات مخصصة لتحرير المستندات بصيغة Markdown.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | ينشئ ويعيد مثيلاً جديدًا من فئة MarkdownEditOptions، |
حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | يسمح بالتحكم في كيفية حفظ الصور عند تحويل مستند Markdown |
إلى HTML.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | يسمح بالتحكم في كيفية حفظ الصور عند تحويل مستند Markdown |
إلى HTML.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


ينشئ ويعيد مثيلاً جديدًا من فئة MarkdownEditOptions،
حيث يتم تعيين جميع الخيارات إلى قيمها الافتراضية


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


يسمح بالتحكم في كيفية حفظ الصور عند تحويل مستند Markdown
إلى HTML.
القيمة: رد الاتصال لحفظ الصورة.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


يسمح بالتحكم في كيفية حفظ الصور عند تحويل مستند Markdown
إلى HTML.
القيمة: رد الاتصال لحفظ الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

