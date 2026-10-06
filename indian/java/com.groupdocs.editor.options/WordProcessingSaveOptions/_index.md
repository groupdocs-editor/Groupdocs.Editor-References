---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "संपादित होने के बाद WordProcessing-अनुरूप दस्तावेज़ों को जेनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 48
url: /hi/java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

जेनरेट करने और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।
संपादित होने के बाद WordProcessing-अनुरूप दस्तावेज़।


*** ** * ** ***

WordProcessingSaveOptions उन स्थितियों में लागू होता है जब EditableDocument क्लास का एक इंस्टेंस मौजूद हो, जिसमें संपादित दस्तावेज़ सामग्री हो, और इस सामग्री को WordProcessing फ़ॉर्मैट के नए दस्तावेज़ में सहेजना आवश्यक हो।

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | यह पैरामीटरलेस कंस्ट्रक्टर WordProcessingSaveOptions का नया इंस्टेंस DOCX आउटपुट फ़ॉर्मैट के साथ बनाता है (इसे बाद में के माध्यम से संशोधित किया जा सकता है। |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) property)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | निर्दिष्ट के साथ WordProcessingSaveOptions का एक नया उदाहरण बनाता है |
अनिवार्य WordProcessing आउटपुट फ़ॉर्मेट, जबकि सभी अन्य पैरामीटर हैं
डिफ़ॉल्ट
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है, जिसका उपयोग दस्तावेज़ को सहेजने के लिए किया जाएगा |
दस्तावेज़।
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है, जिसका उपयोग दस्तावेज़ को सहेजने के लिए किया जाएगा |
दस्तावेज़।
|
|  | [getPassword()](#getPassword--) | पासवर्ड को निर्दिष्ट, संशोधित, प्राप्त या हटाने की अनुमति देता है, जो होगा |
उत्पन्न WordProcessing दस्तावेज़ को एन्कोड करने के लिए उपयोग किया जाता है।
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | पासवर्ड को निर्दिष्ट, संशोधित, प्राप्त या हटाने की अनुमति देता है, जो होगा |
उत्पन्न WordProcessing दस्तावेज़ को एन्कोड करने के लिए उपयोग किया जाता है।
|
|  | [getOutputFormat()](#getOutputFormat--) | WordProcessing फ़ॉर्मेट को निर्दिष्ट करने की अनुमति देता है, जिसका उपयोग सहेजने के लिए किया जाएगा |
दस्तावेज़
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | WordProcessing फ़ॉर्मेट को निर्दिष्ट करने की अनुमति देता है, जिसका उपयोग सहेजने के लिए किया जाएगा |
दस्तावेज़
|
|  | [getLocale()](#getLocale--) | WordProcessing के लिए डिफ़ॉल्ट लोकेल (भाषा) को ओवरराइड सेट करने की अनुमति देता है |
दस्तावेज़, जो इसके निर्माण के दौरान लागू होगा।
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | WordProcessing के लिए डिफ़ॉल्ट लोकेल (भाषा) को ओवरराइड सेट करने की अनुमति देता है |
दस्तावेज़, जो इसके निर्माण के दौरान लागू होगा।
|
|  | [getLocaleBi()](#getLocaleBi--) | WordProcessing दस्तावेज़ के लिए लोकेल (भाषा) को ओवरराइड सेट करने की अनुमति देता है |
RTL (right-to-left) टेक्स्ट के लिए, जो इसके
निर्माण के दौरान लागू होगा।
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | WordProcessing दस्तावेज़ के लिए लोकेल (भाषा) को ओवरराइड सेट करने की अनुमति देता है |
RTL (right-to-left) टेक्स्ट के लिए, जो इसके
निर्माण के दौरान लागू होगा।
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | WordProcessing दस्तावेज़ के लिए लोकेल (भाषा) को ओवरराइड करने की अनुमति देता है |
East-Asian टेक्स्ट के लिए, जो इसके निर्माण के दौरान लागू होगा।
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | WordProcessing दस्तावेज़ के लिए लोकेल (भाषा) को ओवरराइड करने की अनुमति देता है |
East-Asian टेक्स्ट के लिए, जो इसके निर्माण के दौरान लागू होगा।
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | दस्तावेज़ जनरेशन से मेमोरी ऑप्टिमाइज़ेशन तंत्र को सक्षम करता है |
HTML, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है।
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | दस्तावेज़ जनरेशन से मेमोरी ऑप्टिमाइज़ेशन तंत्र को सक्षम करता है |
HTML, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है।
|
|  | [getProtection()](#getProtection--) | दस्तावेज़ सुरक्षा विकल्पों को नियंत्रित और लागू करने की अनुमति देता है |
किसी भी फ़ॉर्मेट के WordProcessing दस्तावेज़ के लिए, जो दस्तावेज़
सुरक्षा।
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | दस्तावेज़ सुरक्षा विकल्पों को नियंत्रित और लागू करने की अनुमति देता है |
किसी भी फ़ॉर्मेट के WordProcessing दस्तावेज़ के लिए, जो दस्तावेज़
सुरक्षा।
|
|  | [getFontEmbedding()](#getFontEmbedding--) | आउटपुट WordProcessing में फ़ॉन्ट संसाधनों को एम्बेड करने के लिए जिम्मेदार |
दस्तावेज़।
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | आउटपुट WordProcessing में फ़ॉन्ट संसाधनों को एम्बेड करने के लिए जिम्मेदार |
दस्तावेज़।
|
|  | [deepClone()](#deepClone--) | इस उदाहरण की पूरी कॉपी बनाता और लौटाता है |
WordProcessingSaveOptions क्लास
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


यह पैरामीटरलेस कंस्ट्रक्टर WordProcessingSaveOptions का नया इंस्टेंस DOCX आउटपुट फ़ॉर्मैट के साथ बनाता है (इसे बाद में के माध्यम से संशोधित किया जा सकता है।
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) property)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


निर्दिष्ट के साथ WordProcessingSaveOptions का एक नया उदाहरण बनाता है
अनिवार्य WordProcessing आउटपुट फ़ॉर्मेट, जबकि सभी अन्य पैरामीटर हैं
डिफ़ॉल्ट


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | अनिवार्य आउटपुट फ़ॉर्मेट, जिसमें WordProcessing दस्तावेज़ को सहेजा जाना चाहिए |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है, जिसका उपयोग दस्तावेज़ को सहेजने के लिए किया जाएगा
दस्तावेज़। यदि मूल दस्तावेज़ पेजिनेशन में खोला और संपादित किया गया था
मोड, इस विकल्प को भी सक्षम किया जाना चाहिए। डिफ़ॉल्ट रूप से यह अक्षम है।


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है, जिसका उपयोग दस्तावेज़ को सहेजने के लिए किया जाएगा
दस्तावेज़। यदि मूल दस्तावेज़ पेजिनेशन में खोला और संपादित किया गया था
मोड, इस विकल्प को भी सक्षम किया जाना चाहिए। डिफ़ॉल्ट रूप से यह अक्षम है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


पासवर्ड को निर्दिष्ट, संशोधित, प्राप्त या हटाने की अनुमति देता है, जो होगा
उत्पन्न WordProcessing दस्तावेज़ को एन्कोड करने के लिए उपयोग किया जाता है। NULL या
पासवर्ड हटाने (साफ़ करने) के लिए खाली स्ट्रिंग।


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


पासवर्ड को निर्दिष्ट, संशोधित, प्राप्त या हटाने की अनुमति देता है, जो होगा
उत्पन्न WordProcessing दस्तावेज़ को एन्कोड करने के लिए उपयोग किया जाता है। NULL या
पासवर्ड हटाने (साफ़ करने) के लिए खाली स्ट्रिंग।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


WordProcessing फ़ॉर्मेट को निर्दिष्ट करने की अनुमति देता है, जिसका उपयोग सहेजने के लिए किया जाएगा
दस्तावेज़


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


WordProcessing फ़ॉर्मेट को निर्दिष्ट करने की अनुमति देता है, जिसका उपयोग सहेजने के लिए किया जाएगा
दस्तावेज़


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


WordProcessing के लिए डिफ़ॉल्ट लोकेल (भाषा) को ओवरराइड सेट करने की अनुमति देता है
दस्तावेज़, जो इसके निर्माण के दौरान लागू किया जाएगा। जब नहीं है
निर्दिष्ट (डिफ़ॉल्ट मान), MS Word (या अन्य प्रोग्राम) पता लगाएगा (या
चुनेगा) दस्तावेज़ का लोकेल उसके अपने सेटिंग्स या अन्य
कारकों के अनुसार।


*** ** * ** ***

यह विकल्प निर्दिष्ट लोकेल को दस्तावेज़ के समग्र पाठ पर बलपूर्वक लागू करता है। इसे उपयोग न करें यदि दस्तावेज़ में विभिन्न भागों का पाठ है, जो विभिन्न भाषाओं में लिखा गया है।

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


WordProcessing के लिए डिफ़ॉल्ट लोकेल (भाषा) को ओवरराइड सेट करने की अनुमति देता है
दस्तावेज़, जो इसके निर्माण के दौरान लागू किया जाएगा। जब नहीं है
निर्दिष्ट (डिफ़ॉल्ट मान), MS Word (या अन्य प्रोग्राम) पता लगाएगा (या
चुनेगा) दस्तावेज़ का लोकेल उसके अपने सेटिंग्स या अन्य
कारकों के अनुसार।

*** ** * ** ***


यह विकल्प निर्दिष्ट लोकेल को समग्र पाठ पर बलपूर्वक लागू करता है
दस्तावेज़ में। इसे उपयोग न करें यदि दस्तावेज़ में विभिन्न भागों का
पाठ है, जो विभिन्न भाषाओं में लिखा गया है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


WordProcessing दस्तावेज़ के लिए लोकेल (भाषा) को ओवरराइड सेट करने की अनुमति देता है
RTL (right-to-left) टेक्स्ट के लिए, जो इसके
सृजन। जब निर्दिष्ट नहीं है (डिफ़ॉल्ट मान), MS Word (या अन्य
प्रोग्राम) दस्तावेज़ के RTL लोकेल को उसके अनुसार पता लगाएगा (या चुनेगा) उसके
अपने सेटिंग्स या अन्य कारकों के अनुसार।

*** ** * ** ***


यह विकल्प निर्दिष्ट लोकेल को समग्र RTL पाठ पर बलपूर्वक लागू करता है
दस्तावेज़ में। इसे उपयोग न करें यदि दस्तावेज़ में विभिन्न भागों का
पाठ है, जो विभिन्न भाषाओं में लिखा गया है।


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


WordProcessing दस्तावेज़ के लिए लोकेल (भाषा) को ओवरराइड सेट करने की अनुमति देता है
RTL (right-to-left) टेक्स्ट के लिए, जो इसके
सृजन। जब निर्दिष्ट नहीं है (डिफ़ॉल्ट मान), MS Word (या अन्य
प्रोग्राम) दस्तावेज़ के RTL लोकेल को उसके अनुसार पता लगाएगा (या चुनेगा) उसके
अपने सेटिंग्स या अन्य कारकों के अनुसार।

*** ** * ** ***


यह विकल्प निर्दिष्ट लोकेल को समग्र RTL पाठ पर बलपूर्वक लागू करता है
दस्तावेज़ में। इसे उपयोग न करें यदि दस्तावेज़ में विभिन्न भागों का
पाठ है, जो विभिन्न भाषाओं में लिखा गया है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


WordProcessing दस्तावेज़ के लिए लोकेल (भाषा) को ओवरराइड करने की अनुमति देता है
East-Asian पाठ के लिए, जो इसके निर्माण के दौरान लागू होगा। जब
निर्दिष्ट नहीं है (डिफ़ॉल्ट मान), MS Word (या अन्य प्रोग्राम) पता लगाएगा
(या चुने) दस्तावेज़ का East-Asian लोकेल उसके अपने सेटिंग्स के अनुसार
या अन्य कारकों के अनुसार।

*** ** * ** ***


यह विकल्प निर्दिष्ट लोकेल को समग्र रूप से लागू करता है
दस्तावेज़ में East-Asian पाठ। इसे उपयोग न करें यदि दस्तावेज़ में है
विभिन्न भागों का पाठ, जो विभिन्न पर लिखा गया है
भाषाओं।


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


WordProcessing दस्तावेज़ के लिए लोकेल (भाषा) को ओवरराइड करने की अनुमति देता है
East-Asian पाठ के लिए, जो इसके निर्माण के दौरान लागू होगा। जब
निर्दिष्ट नहीं है (डिफ़ॉल्ट मान), MS Word (या अन्य प्रोग्राम) पता लगाएगा
(या चुने) दस्तावेज़ का East-Asian लोकेल उसके अपने सेटिंग्स के अनुसार
या अन्य कारकों के अनुसार।

*** ** * ** ***


यह विकल्प निर्दिष्ट लोकेल को समग्र रूप से लागू करता है
दस्तावेज़ में East-Asian पाठ। इसे उपयोग न करें यदि दस्तावेज़ में है
विभिन्न भागों का पाठ, जो विभिन्न पर लिखा गया है
भाषाओं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


दस्तावेज़ जनरेशन से मेमोरी ऑप्टिमाइज़ेशन तंत्र को सक्षम करता है
HTML, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है।
इस विकल्प को true सेट करने से मेमोरी की खपत में काफी कमी आ सकती है
बड़े दस्तावेज़ उत्पन्न करते समय धीमी सहेजने की गति के बदले।
डिफ़ॉल्ट false है (बेहतर के लिए मेमोरी अनुकूलन अक्षम किया गया है
प्रदर्शन)।


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


दस्तावेज़ जनरेशन से मेमोरी ऑप्टिमाइज़ेशन तंत्र को सक्षम करता है
HTML, जो मेमोरी उपयोग को कम करने की कीमत पर प्रदर्शन को घटाता है।
इस विकल्प को true सेट करने से मेमोरी की खपत में काफी कमी आ सकती है
बड़े दस्तावेज़ उत्पन्न करते समय धीमी सहेजने की गति के बदले।
डिफ़ॉल्ट false है (बेहतर के लिए मेमोरी अनुकूलन अक्षम किया गया है
प्रदर्शन)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


दस्तावेज़ सुरक्षा विकल्पों को नियंत्रित और लागू करने की अनुमति देता है
किसी भी फ़ॉर्मेट के WordProcessing दस्तावेज़ के लिए, जो दस्तावेज़
सुरक्षा। डिफ़ॉल्ट रूप से NULL है - दस्तावेज़ सुरक्षा उपयोग नहीं की जाएगी।


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


दस्तावेज़ सुरक्षा विकल्पों को नियंत्रित और लागू करने की अनुमति देता है
किसी भी फ़ॉर्मेट के WordProcessing दस्तावेज़ के लिए, जो दस्तावेज़
सुरक्षा। डिफ़ॉल्ट रूप से NULL है - दस्तावेज़ सुरक्षा उपयोग नहीं की जाएगी।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


आउटपुट WordProcessing में फ़ॉन्ट संसाधनों को एम्बेड करने के लिए जिम्मेदार
दस्तावेज़। डिफ़ॉल्ट रूप से कोई फ़ॉन्ट एम्बेड नहीं करता (NotEmbed)।


**Returns:**
int - 
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


आउटपुट WordProcessing में फ़ॉन्ट संसाधनों को एम्बेड करने के लिए जिम्मेदार
दस्तावेज़। डिफ़ॉल्ट रूप से कोई फ़ॉन्ट एम्बेड नहीं करता (NotEmbed)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


इस उदाहरण की पूरी कॉपी बनाता और लौटाता है
WordProcessingSaveOptions क्लास


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance

