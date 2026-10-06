---
title: "XmlHighlightOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "XML‑से‑HTML रूपांतरण के दौरान XML हाइलाइटिंग को अनुकूलित करने के विकल्प शामिल करता है"
type: docs
weight: 53
url: /hi/java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

XML से HTML रूपांतरण के दौरान XML हाइलाइटिंग को अनुकूलित करने की अनुमति देने वाले विकल्प शामिल हैं।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | XML टैग (टैग नामों के साथ एंगल ब्रैकेट) के फ़ॉन्ट को प्रदर्शित करने के लिए जिम्मेदार |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | एट्रिब्यूट नामों के फ़ॉन्ट को प्रदर्शित करने के लिए जिम्मेदार |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | एट्रिब्यूट मानों के फ़ॉन्ट को प्रदर्शित करने के लिए जिम्मेदार |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | इनर‑टैग टेक्स्ट के फ़ॉन्ट को प्रदर्शित करने के लिए जिम्मेदार |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | HTML टिप्पणी (खोलने और बंद करने वाले टैग की जोड़ी सहित) के फ़ॉन्ट को प्रदर्शित करने के लिए जिम्मेदार |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | CDATA सेक्शन (खोलने और बंद करने वाले टैग की जोड़ी सहित) के फ़ॉन्ट को प्रदर्शित करने के लिए जिम्मेदार |
|
|  | [isDefault()](#isDefault--) | निर्धारित करता है कि इस XML हाइलाइट विकल्प ऑब्जेक्ट में डिफ़ॉल्ट फ़ॉन्ट सेटिंग्स हैं या नहीं |
|
|  | [resetToDefault()](#resetToDefault--) | वर्तमान फ़ॉन्ट सेटिंग्स को उनके डिफ़ॉल्ट मानों पर रीसेट करता है |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


XML टैग (टैग नामों के साथ एंगल ब्रैकेट) के फ़ॉन्ट को प्रदर्शित करने के लिए जिम्मेदार


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


एट्रिब्यूट नामों के फ़ॉन्ट को प्रदर्शित करने के लिए जिम्मेदार


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


एट्रिब्यूट मानों के फ़ॉन्ट को प्रदर्शित करने के लिए जिम्मेदार


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


इनर‑टैग टेक्स्ट के फ़ॉन्ट को प्रदर्शित करने के लिए जिम्मेदार


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


HTML टिप्पणी (खोलने और बंद करने वाले टैग की जोड़ी सहित) के फ़ॉन्ट को प्रदर्शित करने के लिए जिम्मेदार


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


CDATA सेक्शन (खोलने और बंद करने वाले टैग की जोड़ी सहित) के फ़ॉन्ट को प्रदर्शित करने के लिए जिम्मेदार


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


निर्धारित करता है कि इस XML हाइलाइट विकल्प ऑब्जेक्ट में डिफ़ॉल्ट फ़ॉन्ट सेटिंग्स हैं या नहीं


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


वर्तमान फ़ॉन्ट सेटिंग्स को उनके डिफ़ॉल्ट मानों पर रीसेट करता है


