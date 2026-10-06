---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "DOCX, RTF, ODT आदि जैसे सभी समर्थित WordProcessing Words‑अनुपालन फ़ॉर्मेट के दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 44
url: /hi/java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

सभी समर्थित दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है
WordProcessing (Words-compliant) फ़ॉर्मेट जैसे DOC(X), RTF, ODT आदि।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | WordProcessingEditOptions का एक नया इंस्टेंस बनाता है और लौटाता है |
क्लास, जहाँ सभी विकल्प उनकी डिफ़ॉल्ट मानों पर सेट होते हैं
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | WordProcessingEditOptions का एक नया इंस्टेंस बनाता है और लौटाता है |
क्लास जिसमें निर्दिष्ट पेजिनेशन है और अन्य सभी विकल्प डिफ़ॉल्ट हैं
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | निर्दिष्ट करता है कि भाषा जानकारी HTML मार्कअप में निर्यात की जाती है या नहीं |
'lang' HTML एट्रिब्यूट्स के रूप में।
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | निर्दिष्ट करता है कि भाषा जानकारी HTML मार्कअप में निर्यात की जाती है या नहीं |
'lang' HTML एट्रिब्यूट्स के रूप में।
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि केवल फ़ॉन्ट संसाधन निकालें या नहीं |
जो दस्तावेज़ की पाठ्य सामग्री में उपयोग होते हैं।
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि केवल फ़ॉन्ट संसाधन निकालें या नहीं |
जो दस्तावेज़ की पाठ्य सामग्री में उपयोग होते हैं।
|
|  | [getFontExtraction()](#getFontExtraction--) | इनपुट में उपयोग होने वाले फ़ॉन्ट संसाधनों को निकालने के लिए ज़िम्मेदार |
WordProcessing दस्तावेज़।
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | इनपुट में उपयोग होने वाले फ़ॉन्ट संसाधनों को निकालने के लिए ज़िम्मेदार |
WordProcessing दस्तावेज़।
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | 'class' में रखे जाने वाले क्लास नाम को निर्दिष्ट करने की अनुमति देता है |
हर HTML एलिमेंट में एट्रिब्यूट्स, जो इनपुट में किसी फ़ील्ड का प्रतिनिधित्व करता है
WordProcessing दस्तावेज़।
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | 'class' में रखे जाने वाले क्लास नाम को निर्दिष्ट करने की अनुमति देता है |
हर HTML एलिमेंट में एट्रिब्यूट्स, जो इनपुट में किसी फ़ील्ड का प्रतिनिधित्व करता है
WordProcessing दस्तावेज़।
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | इनपुट WordProcessing दस्तावेज़ के स्टाइलिंग और फ़ॉर्मेटिंग डेटा को कहाँ संग्रहीत किया जाए, नियंत्रित करता है: बाहरी स्टाइलशीट में ( |
false
) या HTML मार्कअप में इनलाइन स्टाइल्स के रूप में (
true
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | इनपुट WordProcessing दस्तावेज़ के स्टाइलिंग और फ़ॉर्मेटिंग डेटा को कहाँ संग्रहीत किया जाए, नियंत्रित करता है: बाहरी स्टाइलशीट में ( |
false
) या HTML मार्कअप में इनलाइन स्टाइल्स के रूप में (
true
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


WordProcessingEditOptions का एक नया इंस्टेंस बनाता है और लौटाता है
क्लास, जहाँ सभी विकल्प उनकी डिफ़ॉल्ट मानों पर सेट होते हैं


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


WordProcessingEditOptions का एक नया इंस्टेंस बनाता है और लौटाता है
क्लास जिसमें निर्दिष्ट पेजिनेशन है और अन्य सभी विकल्प डिफ़ॉल्ट हैं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | enablePagination | boolean | पेजिनेशन फ़्लैग, जो पेज्ड मोड के लिए समायोजित HTML आउटपुट को सक्षम करता है |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। द्वारा
डिफ़ॉल्ट निष्क्रिय है (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। द्वारा
डिफ़ॉल्ट निष्क्रिय है (false).


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


निर्दिष्ट करता है कि भाषा जानकारी HTML मार्कअप में निर्यात की जाती है या नहीं
'lang' HTML एट्रिब्यूट्स के रूप में। यह विकल्प राउंडट्रिप के लिए उपयोगी हो सकता है
बहु-भाषा दस्तावेज़ों के रूपांतरण के लिए। डिफ़ॉल्ट रूप से यह अक्षम है
(false).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


निर्दिष्ट करता है कि भाषा जानकारी HTML मार्कअप में निर्यात की जाती है या नहीं
'lang' HTML एट्रिब्यूट्स के रूप में। यह विकल्प राउंडट्रिप के लिए उपयोगी हो सकता है
बहु-भाषा दस्तावेज़ों के रूपांतरण के लिए। डिफ़ॉल्ट रूप से यह अक्षम है
(false).


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि केवल फ़ॉन्ट संसाधन निकालें या नहीं
जो दस्तावेज़ की पाठ्य सामग्री में उपयोग होते हैं।
मान: true यदि केवल उन फ़ॉन्ट संसाधनों को निकालना आवश्यक है, जो दस्तावेज़ की पाठ्य सामग्री में उपयोग होते हैं; अन्यथा, false। डिफ़ॉल्ट मान false है।


*** ** * ** ***

WordProcessing दस्तावेज़ में उपयोग किए गए सभी फ़ॉन्ट 100% सीधे (किसी पाठ पर लागू) नहीं होते। ऐसी स्थिति हो सकती है जहाँ फ़ॉन्ट दस्तावेज़ में संदर्भित हो और एम्बेड भी हो, लेकिन किसी भी पाठ भाग पर लागू न हो। उदाहरण के लिए, कुछ फ़ॉन्ट किसी शैली से जुड़े हो सकते हैं, लेकिन वह शैली किसी भी पाठ भाग पर लागू नहीं होती। यह विकल्प ऐसे मामलों को कैसे प्रोसेस किया जाए, नियंत्रित करता है।

<br />



**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि केवल फ़ॉन्ट संसाधन निकालें या नहीं
जो दस्तावेज़ की पाठ्य सामग्री में उपयोग होते हैं।
मान: true यदि केवल उन फ़ॉन्ट संसाधनों को निकालना आवश्यक है, जो दस्तावेज़ की पाठ्य सामग्री में उपयोग होते हैं; अन्यथा, false। डिफ़ॉल्ट मान false है।


*** ** * ** ***

WordProcessing दस्तावेज़ में उपयोग किए गए सभी फ़ॉन्ट 100% सीधे (किसी पाठ पर लागू) नहीं होते। ऐसी स्थिति हो सकती है जहाँ फ़ॉन्ट दस्तावेज़ में संदर्भित हो और एम्बेड भी हो, लेकिन किसी भी पाठ भाग पर लागू न हो। उदाहरण के लिए, कुछ फ़ॉन्ट किसी शैली से जुड़े हो सकते हैं, लेकिन वह शैली किसी भी पाठ भाग पर लागू नहीं होती। यह विकल्प ऐसे मामलों को कैसे प्रोसेस किया जाए, नियंत्रित करता है।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


इनपुट में उपयोग होने वाले फ़ॉन्ट संसाधनों को निकालने के लिए ज़िम्मेदार
WordProcessing दस्तावेज़। डिफ़ॉल्ट रूप से कोई फ़ॉन्ट नहीं निकालता
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


इनपुट में उपयोग होने वाले फ़ॉन्ट संसाधनों को निकालने के लिए ज़िम्मेदार
WordProcessing दस्तावेज़। डिफ़ॉल्ट रूप से कोई फ़ॉन्ट नहीं निकालता
(NotExtract).


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


'class' में रखे जाने वाले क्लास नाम को निर्दिष्ट करने की अनुमति देता है
हर HTML एलिमेंट में एट्रिब्यूट्स, जो इनपुट में किसी फ़ील्ड का प्रतिनिधित्व करता है
WordProcessing दस्तावेज़। डिफ़ॉल्ट रूप से NULL है - 'class' एट्रिब्यूट्स नहीं हैं
लागू किया गया।


*** ** * ** ***

WordProcessing फ़ॉर्मेट परिवार के लगभग सभी फ़ॉर्मेट में फ़ील्ड्स \\u2014 विशिष्ट दस्तावेज़ इकाइयाँ, जो उपयोगकर्ताओं से इनपुट डेटा प्राप्त करने की अनुमति देती हैं, शामिल होते हैं। फ़ील्ड्स की एक विस्तृत विविधता है: टेक्स्ट-बॉक्स, चेकबॉक्स, कॉम्बो-बॉक्स, ड्रॉप‑डाउन सूची, बटन, तिथि/समय पिकर आदि। इन सभी को सबसे उपयुक्त HTML संरचनाओं और तत्वों में अनुवादित किया जाता है, और यदि इनपुट दस्तावेज़ में मौजूद हों तो दर्ज किए गए उपयोगकर्ता डेटा को संरक्षित किया जाता है। विशिष्ट उपयोग‑केस में पूरे दस्तावेज़ की सामग्री को संपादित करने के बजाय केवल क्लाइंट‑साइड पर दर्ज किया गया डेटा एकत्र करना आवश्यक होता है। ऐसे मामलों में क्लाइंट‑साइड पर उनके डेटा के साथ इनपुट नियंत्रणों को प्राप्त करने के लिए किसी न किसी तरीके से उन्हें पहचानना आवश्यक है। यह प्रॉपर्टी आपको एक क्लास नाम निर्दिष्ट करने की अनुमति देती है, जो HTML मार्कअप में प्रत्येक इनपुट नियंत्रण पर लागू होगा, ताकि क्लाइंट कोड HTML दस्तावेज़ संरचना को पार करके डेटा एकत्र कर सके।

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


'class' में रखे जाने वाले क्लास नाम को निर्दिष्ट करने की अनुमति देता है
हर HTML एलिमेंट में एट्रिब्यूट्स, जो इनपुट में किसी फ़ील्ड का प्रतिनिधित्व करता है
WordProcessing दस्तावेज़। डिफ़ॉल्ट रूप से NULL है - 'class' एट्रिब्यूट्स नहीं हैं
लागू किया गया।


*** ** * ** ***

WordProcessing फ़ॉर्मेट परिवार के लगभग सभी फ़ॉर्मेट में फ़ील्ड्स \\u2014 विशिष्ट दस्तावेज़ इकाइयाँ, जो उपयोगकर्ताओं से इनपुट डेटा प्राप्त करने की अनुमति देती हैं, शामिल होते हैं। फ़ील्ड्स की एक विस्तृत विविधता है: टेक्स्ट-बॉक्स, चेकबॉक्स, कॉम्बो-बॉक्स, ड्रॉप‑डाउन सूची, बटन, तिथि/समय पिकर आदि। इन सभी को सबसे उपयुक्त HTML संरचनाओं और तत्वों में अनुवादित किया जाता है, और यदि इनपुट दस्तावेज़ में मौजूद हों तो दर्ज किए गए उपयोगकर्ता डेटा को संरक्षित किया जाता है। विशिष्ट उपयोग‑केस में पूरे दस्तावेज़ की सामग्री को संपादित करने के बजाय केवल क्लाइंट‑साइड पर दर्ज किया गया डेटा एकत्र करना आवश्यक होता है। ऐसे मामलों में क्लाइंट‑साइड पर उनके डेटा के साथ इनपुट नियंत्रणों को प्राप्त करने के लिए किसी न किसी तरीके से उन्हें पहचानना आवश्यक है। यह प्रॉपर्टी आपको एक क्लास नाम निर्दिष्ट करने की अनुमति देती है, जो HTML मार्कअप में प्रत्येक इनपुट नियंत्रण पर लागू होगा, ताकि क्लाइंट कोड HTML दस्तावेज़ संरचना को पार करके डेटा एकत्र कर सके।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


इनपुट WordProcessing दस्तावेज़ के स्टाइलिंग और फ़ॉर्मेटिंग डेटा को कहाँ संग्रहीत किया जाए, नियंत्रित करता है: बाहरी स्टाइलशीट में (
false
) या HTML मार्कअप में इनलाइन स्टाइल्स के रूप में (
true
)। डिफ़ॉल्ट रूप से बाहरी शैलियों का उपयोग किया जाता है (
false
).


**Returns:**
boolean
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


इनपुट WordProcessing दस्तावेज़ के स्टाइलिंग और फ़ॉर्मेटिंग डेटा को कहाँ संग्रहीत किया जाए, नियंत्रित करता है: बाहरी स्टाइलशीट में (
false
) या HTML मार्कअप में इनलाइन स्टाइल्स के रूप में (
true
)। डिफ़ॉल्ट रूप से बाहरी शैलियों का उपयोग किया जाता है (
false
).


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

