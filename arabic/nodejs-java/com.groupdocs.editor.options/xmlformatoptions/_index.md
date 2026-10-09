---
title: "XmlFormatOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يحتوي على خيارات تسمح بضبط تنسيق مستند XML عندما يتم تمثيله كـ HTML"
type: docs
weight: 52
url: /ar/nodejs-java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

يتضمن خيارات تسمح بضبط تنسيق مستند XML عندما يُعرض كـ HTML.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | عند التمكين، سيتم وضع كل زوج من السمة والقيمة في كل عنصر XML على سطر جديد. |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | عند التمكين، سيتم وضع كل زوج من السمة والقيمة في كل عنصر XML على سطر جديد. |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | عند التمكين، سيتم عرض عقد النص الورقية (المحتوى النصي داخل عناصر XML التي لا تحتوي على أبناء) على سطر جديد مع مسافة بادئة يسرى أكبر. |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | عند التمكين، سيتم عرض عقد النص الورقية (المحتوى النصي داخل عناصر XML التي لا تحتوي على أبناء) على سطر جديد مع مسافة بادئة يسرى أكبر. |
|
|  | [getLeftIndent()](#getLeftIndent--) | يسمح بتحديد إزاحة للمسافة البادئة اليسرى لكل سطر جديد. |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | يسمح بتحديد إزاحة للمسافة البادئة اليسرى لكل سطر جديد. |
|
|  | [isDefault()](#isDefault--) | يشير إلى ما إذا كان لهذا الكائن من خيارات تنسيق XML قيمة افتراضية |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


عند التمكين، سيتم وضع كل زوج من السمة والقيمة في كل عنصر XML على سطر جديد.
بشكل افتراضي تكون false (معطلة) \\u2014 جميع أزواج السمة-القيمة توضع في سطر واحد.


**Returns:**
boolean
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


عند التمكين، سيتم وضع كل زوج من السمة والقيمة في كل عنصر XML على سطر جديد.
بشكل افتراضي تكون false (معطلة) \\u2014 جميع أزواج السمة-القيمة توضع في سطر واحد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


عند التمكين، سيتم عرض عقد النص الورقية (المحتوى النصي داخل عناصر XML التي لا تحتوي على أبناء) على سطر جديد مع مسافة بادئة يسرى أكبر.
بشكل افتراضي تكون false (معطلة) \\u2014 تُوضع عقد النص الورقية على نفس سطر الوالدين دون مسافة بادئة جديدة.


**Returns:**
boolean
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


عند التمكين، سيتم عرض عقد النص الورقية (المحتوى النصي داخل عناصر XML التي لا تحتوي على أبناء) على سطر جديد مع مسافة بادئة يسرى أكبر.
بشكل افتراضي تكون false (معطلة) \\u2014 تُوضع عقد النص الورقية على نفس سطر الوالدين دون مسافة بادئة جديدة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

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


يشير إلى ما إذا كان لهذا الكائن من خيارات تنسيق XML قيمة افتراضية


**Returns:**
boolean
