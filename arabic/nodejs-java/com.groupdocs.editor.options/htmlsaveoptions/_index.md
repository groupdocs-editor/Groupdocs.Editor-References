---
title: "HtmlSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لحفظ الكائن إلى صيغة HTML"
type: docs
weight: 19
url: /ar/nodejs-java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

يسمح بتحديد خيارات مخصصة لحفظ الكائن [EditableDocument](../../com.groupdocs.editor/editabledocument) إلى صيغة HTML

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | يتحكم في كيفية ظهور أسماء وسوم HTML في ترميز HTML: جميعها بأحرف صغيرة (القيمة الافتراضية)، جميعها بأحرف كبيرة، أو الحرف الأول كبير |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | يتحكم في كيفية ظهور أسماء وسوم HTML في ترميز HTML: جميعها بأحرف صغيرة (القيمة الافتراضية)، جميعها بأحرف كبيرة، أو الحرف الأول كبير |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | يتحكم في الفاصل الذي سيُستخدم حول قيم السمات في عناصر HTML: علامة اقتباس مفردة (القيمة الافتراضية) أو علامة اقتباس مزدوجة |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | يتحكم في الفاصل الذي سيُستخدم حول قيم السمات في عناصر HTML: علامة اقتباس مفردة (القيمة الافتراضية) أو علامة اقتباس مزدوجة |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | يتحكم في مكان تخزين أوراق الأنماط CSS: كموارد خارجية ( |
false
)، أو تضمينها في ترميز HTML، داخل عنصر STYLE في قسم HTML-\>HEAD (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | يتحكم في مكان تخزين أوراق الأنماط CSS: كموارد خارجية ( |
false
)، أو تضمينها في ترميز HTML، داخل عنصر STYLE في قسم HTML-\>HEAD (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | الواجهة التي يجب أن ينفذها المستخدم النهائي لحفظ جميع موارد HTML الخارجية |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | الواجهة التي يجب أن ينفذها المستخدم النهائي لحفظ جميع موارد HTML الخارجية |
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
| قيمة | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


يتحكم في الفاصل الذي سيُستخدم حول قيم السمات في عناصر HTML: علامة اقتباس مفردة (القيمة الافتراضية) أو علامة اقتباس مزدوجة


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


يتحكم في الفاصل الذي سيُستخدم حول قيم السمات في عناصر HTML: علامة اقتباس مفردة (القيمة الافتراضية) أو علامة اقتباس مزدوجة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


يتحكم في مكان تخزين أوراق الأنماط CSS: كموارد خارجية (
false
)، أو تضمينها في ترميز HTML، داخل عنصر STYLE في قسم HTML-\>HEAD (
true
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


يتحكم في مكان تخزين أوراق الأنماط CSS: كموارد خارجية (
false
)، أو تضمينها في ترميز HTML، داخل عنصر STYLE في قسم HTML-\>HEAD (
true
)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


الواجهة التي يجب أن ينفذها المستخدم النهائي لحفظ جميع موارد HTML الخارجية


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


الواجهة التي يجب أن ينفذها المستخدم النهائي لحفظ جميع موارد HTML الخارجية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

