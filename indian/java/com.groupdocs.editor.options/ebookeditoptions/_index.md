---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सभी समर्थित फ़ॉर्मेट ePub, MOBI और AZW3 में ई-बुक दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने और समायोजित करने की अनुमति देता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

सभी समर्थित फ़ॉर्मेट्स (ePub, MOBI, और AZW3) में ई-बुक दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट और समायोजित करने की अनुमति देता है।

<br />

*** ** * ** ***

समर्थित ई-बुक फ़ॉर्मैट:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (इलेक्ट्रॉनिक प्रकाशन)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle फ़ॉर्मैट 8t)

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | एक नया इंस्टेंस इनिशियलाइज़ करता है [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) क्लास का, जहाँ सभी विकल्प उनके डिफ़ॉल्ट मानों पर सेट होते हैं |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | निर्दिष्ट पेजिनेशन मोड के साथ [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | निर्दिष्ट करता है कि क्या भाषा जानकारी को HTML मार्कअप में 'lang' HTML एट्रिब्यूट्स के रूप में निर्यात किया जाता है। |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | निर्दिष्ट करता है कि क्या भाषा जानकारी को HTML मार्कअप में 'lang' HTML एट्रिब्यूट्स के रूप में निर्यात किया जाता है। |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


एक नया इंस्टेंस इनिशियलाइज़ करता है [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) क्लास का, जहाँ सभी विकल्प उनके डिफ़ॉल्ट मानों पर सेट होते हैं


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


निर्दिष्ट पेजिनेशन मोड के साथ [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | enablePagination | boolean | परिणामी HTML दस्तावेज़ में ई-बुक सामग्री की पेजिनेशन को सक्षम (true) या अक्षम (false) करता है। डिफ़ॉल्ट रूप से अक्षम (false) है। |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। डिफ़ॉल्ट रूप से अक्षम (
false
).

<br />

*** ** * ** ***

मूल रूप में अधिकांश ई-बुक फ़ॉर्मेट आंतरिक रूप से Office Open XML जैसी फ्लो फ़ॉर्मेट होते हैं, जहाँ सामग्री एक ठोस रूप में होती है और अध्यायों में विभाजित होती है, लेकिन पृष्ठों में नहीं। हालांकि, इसमें पृष्ठ-विशिष्ट जानकारी जैसे पृष्ठ संख्या, फुटनोट, हेडर/फ़ूटर आदि शामिल होते हैं। कुछ ई-बुक रीडर ई-बुक सामग्री को पृष्ठों में विभाजित करते हैं, जबकि अन्य (विशेषकर मोबाइल) \\u2014 नहीं। यह विकल्प संपादन के दौरान ई-बुक सामग्री को HTML/CSS में कैसे प्रदर्शित किया जाए, इसे नियंत्रित करने की अनुमति देता है \\u2014 फ्लोट (false) या पेज्ड (true) दृश्य में।

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। डिफ़ॉल्ट रूप से अक्षम (
false
).

<br />

*** ** * ** ***

मूल रूप में अधिकांश ई-बुक फ़ॉर्मेट आंतरिक रूप से Office Open XML जैसी फ्लो फ़ॉर्मेट होते हैं, जहाँ सामग्री एक ठोस रूप में होती है और अध्यायों में विभाजित होती है, लेकिन पृष्ठों में नहीं। हालांकि, इसमें पृष्ठ-विशिष्ट जानकारी जैसे पृष्ठ संख्या, फुटनोट, हेडर/फ़ूटर आदि शामिल होते हैं। कुछ ई-बुक रीडर ई-बुक सामग्री को पृष्ठों में विभाजित करते हैं, जबकि अन्य (विशेषकर मोबाइल) \\u2014 नहीं। यह विकल्प संपादन के दौरान ई-बुक सामग्री को HTML/CSS में कैसे प्रदर्शित किया जाए, इसे नियंत्रित करने की अनुमति देता है \\u2014 फ्लोट (false) या पेज्ड (true) दृश्य में।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


निर्दिष्ट करता है कि क्या भाषा जानकारी को HTML मार्कअप में 'lang' HTML एट्रिब्यूट्स के रूप में निर्यात किया जाता है।
यह विकल्प बहु-भाषी दस्तावेज़ों के राउंडट्रिप रूपांतरण के लिए उपयोगी हो सकता है। डिफ़ॉल्ट रूप से यह अक्षम है (
false
).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


निर्दिष्ट करता है कि क्या भाषा जानकारी को HTML मार्कअप में 'lang' HTML एट्रिब्यूट्स के रूप में निर्यात किया जाता है।
यह विकल्प बहु-भाषी दस्तावेज़ों के राउंडट्रिप रूपांतरण के लिए उपयोगी हो सकता है। डिफ़ॉल्ट रूप से यह अक्षम है (
false
).


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

