---
title: "XmlFormatOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يحتوي على خيارات تسمح بضبط تنسيق مستند XML عندما يُمثَّل كـ HTML"
type: docs
weight: 52
url: /ar/java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

يحتوي على خيارات تسمح بضبط تنسيق مستند XML عندما يُعرض كـ HTML.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | عند التفعيل، سيتم وضع كل زوج من السمة والقيمة في كل عنصر XML على سطر جديد. |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | عند التفعيل، سيتم وضع كل زوج من السمة والقيمة في كل عنصر XML على سطر جديد. |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | عند التفعيل، سيتم عرض عقد النص الورقية (المحتوى النصي داخل عناصر XML التي لا تحتوي على أبناء) على سطر جديد مع مسافة بادئة يسرى أكبر. |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | عند التفعيل، سيتم عرض عقد النص الورقية (المحتوى النصي داخل عناصر XML التي لا تحتوي على أبناء) على سطر جديد مع مسافة بادئة يسرى أكبر. |
|
|  | [getLeftIndent()](#getLeftIndent--) | يسمح بتحديد إزاحة للمسافة البادئة اليسرى لكل سطر جديد. |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | يسمح بتحديد إزاحة للمسافة البادئة اليسرى لكل سطر جديد. |
|
|  | [isDefault()](#isDefault--) | يشير إلى ما إذا كان هذا المثال من خيارات تنسيق XML يحتوي على قيمة افتراضية |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


عند التفعيل، سيتم وضع كل زوج من السمة والقيمة في كل عنصر XML على سطر جديد.
بشكل افتراضي يكون false (معطل) \\u2014 جميع أزواج السمة والقيمة توضع في سطر واحد.


**Returns:**
boolean
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


عند التفعيل، سيتم وضع كل زوج من السمة والقيمة في كل عنصر XML على سطر جديد.
بشكل افتراضي يكون false (معطل) \\u2014 جميع أزواج السمة والقيمة توضع في سطر واحد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


عند التفعيل، سيتم عرض عقد النص الورقية (المحتوى النصي داخل عناصر XML التي لا تحتوي على أبناء) على سطر جديد مع مسافة بادئة يسرى أكبر.
بشكل افتراضي يكون false (معطل) \\u2014 تُوضع عقد النص الورقية على نفس سطر أصولها، دون مسافة بادئة جديدة.


**Returns:**
boolean
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


عند التفعيل، سيتم عرض عقد النص الورقية (المحتوى النصي داخل عناصر XML التي لا تحتوي على أبناء) على سطر جديد مع مسافة بادئة يسرى أكبر.
بشكل افتراضي يكون false (معطل) \\u2014 تُوضع عقد النص الورقية على نفس سطر أصولها، دون مسافة بادئة جديدة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


يسمح بتحديد إزاحة للمسافة البادئة اليسرى لكل سطر جديد. لا يمكن أن تكون قيمة غير صفرية بدون وحدة. بشكل افتراضي تكون 10pt


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


يسمح بتحديد إزاحة للمسافة البادئة اليسرى لكل سطر جديد. لا يمكن أن تكون قيمة غير صفرية بدون وحدة. بشكل افتراضي تكون 10pt


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


يشير إلى ما إذا كان هذا المثال من خيارات تنسيق XML يحتوي على قيمة افتراضية


**Returns:**
boolean
