---
title: "HtmlSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يسمح بتحديد خيارات مخصصة لحفظ المثيل إلى تنسيق HTML"
type: docs
weight: 19
url: /ar/java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

يسمح بتحديد خيارات مخصصة لحفظ المثيل [EditableDocument](../../com.groupdocs.editor/editabledocument) إلى تنسيق HTML

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | يتحكم في كيفية ظهور أسماء وسوم HTML في ترميز HTML: جميعها بأحرف صغيرة (القيمة الافتراضية)، جميعها بأحرف كبيرة، أو الحرف الأول كبير |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | يتحكم في كيفية ظهور أسماء وسوم HTML في ترميز HTML: جميعها بأحرف صغيرة (القيمة الافتراضية)، جميعها بأحرف كبيرة، أو الحرف الأول كبير |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | يتحكم في أي فاصل حول قيم السمات في عناصر HTML سيتم استخدامه: علامة اقتباس مفردة (القيمة الافتراضية) أو علامة اقتباس مزدوجة |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | يتحكم في أي فاصل حول قيم السمات في عناصر HTML سيتم استخدامه: علامة اقتباس مفردة (القيمة الافتراضية) أو علامة اقتباس مزدوجة |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | يتحكم في مكان تخزين ملفات CSS (stylesheets): كموارد خارجية ( |
false
), أو تضمينها في ترميز HTML، داخل عنصر STYLE في قسم HTML-\>HEAD (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | يتحكم في مكان تخزين ملفات CSS (stylesheets): كموارد خارجية ( |
false
), أو تضمينها في ترميز HTML، داخل عنصر STYLE في قسم HTML-\>HEAD (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | واجهة يجب أن ينفذها المستخدم النهائي لحفظ جميع موارد HTML الخارجية |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | واجهة يجب أن ينفذها المستخدم النهائي لحفظ جميع موارد HTML الخارجية |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


يتحكم في كيفية ظهور أسماء وسوم HTML في ترميز HTML: جميعها بأحرف صغيرة (القيمة الافتراضية)، جميعها بأحرف كبيرة، أو الحرف الأول كبير


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


يتحكم في كيفية ظهور أسماء وسوم HTML في ترميز HTML: جميعها بأحرف صغيرة (القيمة الافتراضية)، جميعها بأحرف كبيرة، أو الحرف الأول كبير


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


يتحكم في أي فاصل حول قيم السمات في عناصر HTML سيتم استخدامه: علامة اقتباس مفردة (القيمة الافتراضية) أو علامة اقتباس مزدوجة


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


يتحكم في أي فاصل حول قيم السمات في عناصر HTML سيتم استخدامه: علامة اقتباس مفردة (القيمة الافتراضية) أو علامة اقتباس مزدوجة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


يتحكم في مكان تخزين ملفات CSS (stylesheets): كموارد خارجية (
false
), أو تضمينها في ترميز HTML، داخل عنصر STYLE في قسم HTML-\>HEAD (
true
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


يتحكم في مكان تخزين ملفات CSS (stylesheets): كموارد خارجية (
false
), أو تضمينها في ترميز HTML، داخل عنصر STYLE في قسم HTML-\>HEAD (
true
)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


واجهة يجب أن ينفذها المستخدم النهائي لحفظ جميع موارد HTML الخارجية


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


واجهة يجب أن ينفذها المستخدم النهائي لحفظ جميع موارد HTML الخارجية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

