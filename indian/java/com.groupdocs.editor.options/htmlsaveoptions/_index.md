---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "HTML फ़ॉर्मेट में इंस्टेंस को सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 19
url: /hi/java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

HTML फ़ॉर्मेट में [EditableDocument](../../com.groupdocs.editor/editabledocument) इंस्टेंस को सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | HTML मार्कअप में HTML टैग नाम कैसे प्रदर्शित होंगे, इसे नियंत्रित करता है: सभी लोअर केस (डिफ़ॉल्ट मान), सभी अपर केस, या पहला अक्षर अपर केस |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | HTML मार्कअप में HTML टैग नाम कैसे प्रदर्शित होंगे, इसे नियंत्रित करता है: सभी लोअर केस (डिफ़ॉल्ट मान), सभी अपर केस, या पहला अक्षर अपर केस |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | HTML तत्वों में एट्रिब्यूट मानों के चारों ओर कौन सा डिलिमिटर उपयोग होगा, इसे नियंत्रित करता है: सिंगल कोट (डिफ़ॉल्ट मान) या डबल कोट |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | HTML तत्वों में एट्रिब्यूट मानों के चारों ओर कौन सा डिलिमिटर उपयोग होगा, इसे नियंत्रित करता है: सिंगल कोट (डिफ़ॉल्ट मान) या डबल कोट |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | CSS स्टाइलशीट(स) को कहाँ संग्रहीत किया जाए, इसे नियंत्रित करता है: बाहरी संसाधन के रूप में ( |
false
), या उन्हें HTML मार्कअप में एम्बेड करें, HTML-\\>HEAD सेक्शन के STYLE तत्व के भीतर (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | CSS स्टाइलशीट(स) को कहाँ संग्रहीत किया जाए, इसे नियंत्रित करता है: बाहरी संसाधन के रूप में ( |
false
), या उन्हें HTML मार्कअप में एम्बेड करें, HTML-\\>HEAD सेक्शन के STYLE तत्व के भीतर (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | इंटरफ़ेस, जिसे अंतिम‑उपयोगकर्ता को सभी बाहरी HTML संसाधनों को सहेजने के लिए लागू करना आवश्यक है |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | इंटरफ़ेस, जिसे अंतिम‑उपयोगकर्ता को सभी बाहरी HTML संसाधनों को सहेजने के लिए लागू करना आवश्यक है |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


HTML मार्कअप में HTML टैग नाम कैसे प्रदर्शित होंगे, इसे नियंत्रित करता है: सभी लोअर केस (डिफ़ॉल्ट मान), सभी अपर केस, या पहला अक्षर अपर केस


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


HTML मार्कअप में HTML टैग नाम कैसे प्रदर्शित होंगे, इसे नियंत्रित करता है: सभी लोअर केस (डिफ़ॉल्ट मान), सभी अपर केस, या पहला अक्षर अपर केस


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


HTML तत्वों में एट्रिब्यूट मानों के चारों ओर कौन सा डिलिमिटर उपयोग होगा, इसे नियंत्रित करता है: सिंगल कोट (डिफ़ॉल्ट मान) या डबल कोट


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


HTML तत्वों में एट्रिब्यूट मानों के चारों ओर कौन सा डिलिमिटर उपयोग होगा, इसे नियंत्रित करता है: सिंगल कोट (डिफ़ॉल्ट मान) या डबल कोट


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


CSS स्टाइलशीट(स) को कहाँ संग्रहीत किया जाए, इसे नियंत्रित करता है: बाहरी संसाधन के रूप में (
false
), या उन्हें HTML मार्कअप में एम्बेड करें, HTML-\\>HEAD सेक्शन के STYLE तत्व के भीतर (
true
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


CSS स्टाइलशीट(स) को कहाँ संग्रहीत किया जाए, इसे नियंत्रित करता है: बाहरी संसाधन के रूप में (
false
), या उन्हें HTML मार्कअप में एम्बेड करें, HTML-\\>HEAD सेक्शन के STYLE तत्व के भीतर (
true
)


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


इंटरफ़ेस, जिसे अंतिम‑उपयोगकर्ता को सभी बाहरी HTML संसाधनों को सहेजने के लिए लागू करना आवश्यक है


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


इंटरफ़ेस, जिसे अंतिम‑उपयोगकर्ता को सभी बाहरी HTML संसाधनों को सहेजने के लिए लागू करना आवश्यक है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

