---
title: "XmlHighlightOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يحتوي على خيارات تسمح بتخصيص تمييز XML أثناء التحويل من XML إلى HTML"
type: docs
weight: 53
url: /ar/java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

يحتوي على خيارات تسمح بتخصيص تمييز XML أثناء تحويل XML إلى HTML.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | مسؤول عن تمثيل خط وسوم XML (الأقواس الزاوية مع أسماء الوسوم) |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | مسؤول عن تمثيل خط أسماء السمات |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | مسؤول عن تمثيل خط قيم السمات |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | مسؤول عن تمثيل خط نص داخل الوسم |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | مسؤول عن تمثيل خط تعليقات HTML (بما في ذلك زوج وسوم الفتح والإغلاق) |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | مسؤول عن تمثيل خط أقسام CDATA (بما في ذلك زوج وسوم الفتح والإغلاق) |
|
|  | [isDefault()](#isDefault--) | يحدد ما إذا كان كائن خيارات تمييز XML هذا يحتوي على إعدادات الخط الافتراضية |
|
|  | [resetToDefault()](#resetToDefault--) | يعيد تعيين إعدادات الخط الحالية إلى قيمها الافتراضية |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


مسؤول عن تمثيل خط وسوم XML (الأقواس الزاوية مع أسماء الوسوم)


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


مسؤول عن تمثيل خط نص داخل الوسم


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


مسؤول عن تمثيل خط تعليقات HTML (بما في ذلك زوج وسوم الفتح والإغلاق)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


مسؤول عن تمثيل خط أقسام CDATA (بما في ذلك زوج وسوم الفتح والإغلاق)


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


يعيد تعيين إعدادات الخط الحالية إلى قيمها الافتراضية


