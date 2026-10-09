---
title: "XmlHighlightOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يحتوي على خيارات تسمح بتخصيص تمييز XML أثناء تحويل XML إلى HTML"
type: docs
weight: 53
url: /ar/nodejs-java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

يتضمن خيارات تسمح بتخصيص تمييز XML أثناء تحويل XML إلى HTML.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | مسؤول عن تمثيل خط علامات XML (الأقواس الزاوية مع أسماء العلامات) |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | مسؤول عن تمثيل خط أسماء السمات |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | مسؤول عن تمثيل خط قيم السمات |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | مسؤول عن تمثيل خط النص داخل العلامة |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | مسؤول عن تمثيل خط تعليقات HTML (بما في ذلك زوج العلامات الافتتاحية والختامية) |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | مسؤول عن تمثيل خط أقسام CDATA (بما في ذلك زوج العلامات الافتتاحية والختامية) |
|
|  | [isDefault()](#isDefault--) | يحدد ما إذا كان كائن خيارات تمييز XML هذا يحتوي على إعدادات الخط الافتراضية |
|
|  | [resetToDefault()](#resetToDefault--) | يعيد ضبط إعدادات الخط الحالية إلى القيم الافتراضية |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


مسؤول عن تمثيل خط علامات XML (الأقواس الزاوية مع أسماء العلامات)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


مسؤول عن تمثيل خط أسماء السمات


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


مسؤول عن تمثيل خط قيم السمات


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


مسؤول عن تمثيل خط النص داخل العلامة


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


مسؤول عن تمثيل خط تعليقات HTML (بما في ذلك زوج العلامات الافتتاحية والختامية)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


مسؤول عن تمثيل خط أقسام CDATA (بما في ذلك زوج العلامات الافتتاحية والختامية)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


يحدد ما إذا كان كائن خيارات تمييز XML هذا يحتوي على إعدادات الخط الافتراضية


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


يعيد ضبط إعدادات الخط الحالية إلى القيم الافتراضية


