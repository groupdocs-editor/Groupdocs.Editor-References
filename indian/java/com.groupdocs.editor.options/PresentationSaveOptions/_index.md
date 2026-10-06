---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "Presentation PowerPoint-संगत दस्तावेज़ों को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 34
url: /hi/java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Presentation को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।
(PowerPoint-संगत) दस्तावेज़

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | यह पैरामीटररहित कंस्ट्रक्टर PPTX आउटपुट फ़ॉर्मेट के साथ PresentationSaveOptions का नया इंस्टेंस बनाता है (फिर इसे के माध्यम से संशोधित किया जा सकता है |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | निर्दिष्ट के साथ PresentationSaveOptions का नया इंस्टेंस बनाता है |
अनिवार्य Presentation आउटपुट फ़ॉर्मेट, जबकि सभी अन्य पैरामीटर हैं
डिफ़ॉल्ट
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getPassword()](#getPassword--) | पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा। |
परिणामी Presentation दस्तावेज़ को एन्कोड करना।
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | परिणामी Presentation दस्तावेज़ को एन्कोड करने के लिए उपयोग किए जाने वाले पासवर्ड को निर्दिष्ट, संशोधित और प्राप्त करने की अनुमति देता है। |
|
|  | [getSlideNumber()](#getSlideNumber--) | नए सिंगल‑स्लाइड प्रेजेंटेशन बनाने के बजाय मौजूदा प्रेजेंटेशन में संपादित स्लाइड डालने की अनुमति देता है (डिफ़ॉल्ट व्यवहार)। |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | नए सिंगल‑स्लाइड प्रेजेंटेशन बनाने के बजाय मौजूदा प्रेजेंटेशन में संपादित स्लाइड डालने की अनुमति देता है (डिफ़ॉल्ट व्यवहार)। |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | बूलियन फ़्लैग, जो यह निर्दिष्ट करता है कि संपादित स्लाइड को मूल प्रेजेंटेशन में निर्दिष्ट स्थिति पर मौजूदा स्लाइड को बदलना चाहिए या नहीं, |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) प्रॉपर्टी, या इसे मौजूदा स्लाइड और पिछले स्लाइड के बीच डाला जाना चाहिए, बिना उसकी सामग्री को बदले।
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | बूलियन फ़्लैग, जो यह निर्दिष्ट करता है कि संपादित स्लाइड को मूल प्रेजेंटेशन में निर्दिष्ट स्थिति पर मौजूदा स्लाइड को बदलना चाहिए या नहीं, |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) प्रॉपर्टी, या इसे मौजूदा स्लाइड और पिछले स्लाइड के बीच डाला जाना चाहिए, बिना उसकी सामग्री को बदले।
|
|  | [getOutputFormat()](#getOutputFormat--) | दस्तावेज़ को सहेजने के लिए उपयोग किए जाने वाले Presentation फ़ॉर्मेट को निर्दिष्ट करने की अनुमति देता है |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | दस्तावेज़ को सहेजने के लिए उपयोग किए जाने वाले Presentation फ़ॉर्मेट को निर्दिष्ट करने की अनुमति देता है |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | संपादित स्लाइड को मौजूदा प्रेजेंटेशन में डालने की स्थिति में, सहेजते समय प्रेजेंटेशन से हटाए जाने वाले स्लाइडों के 1-आधारित नंबरों की एक एरे निर्दिष्ट करने की अनुमति देता है। |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | संपादित स्लाइड को मौजूदा प्रेजेंटेशन में डालने की स्थिति में, सहेजते समय प्रेजेंटेशन से हटाए जाने वाले स्लाइडों के 1-आधारित नंबरों की एक एरे निर्दिष्ट करने की अनुमति देता है। |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


यह पैरामीटररहित कंस्ट्रक्टर PPTX आउटपुट फ़ॉर्मेट के साथ PresentationSaveOptions का नया इंस्टेंस बनाता है (फिर इसे के माध्यम से संशोधित किया जा सकता है
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


निर्दिष्ट के साथ PresentationSaveOptions का नया इंस्टेंस बनाता है
अनिवार्य Presentation आउटपुट फ़ॉर्मेट, जबकि सभी अन्य पैरामीटर हैं
डिफ़ॉल्ट


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | अनिवार्य आउटपुट फ़ॉर्मेट, जिसमें Presentation दस्तावेज़ को सहेजा जाना चाहिए |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है, जो उपयोग किया जाएगा।
परिणामी Presentation दस्तावेज़ को एन्कोड करना। डिफ़ॉल्ट रूप से यह NULL है -
पासवर्ड सेट नहीं किया जाएगा। हटाने के लिए इसे NULL या खाली स्ट्रिंग सेट करें।
पासवर्ड, यदि पहले सेट किया गया था।


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


परिणामी Presentation दस्तावेज़ को एन्कोड करने के लिए उपयोग किए जाने वाले पासवर्ड को निर्दिष्ट, संशोधित और प्राप्त करने की अनुमति देता है।
डिफ़ॉल्ट रूप से NULL है - पासवर्ड सेट नहीं होगा। पासवर्ड को हटाने के लिए NULL या खाली स्ट्रिंग सेट करें, यदि वह पहले सेट किया गया था।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


नए सिंगल‑स्लाइड प्रेजेंटेशन बनाने के बजाय मौजूदा प्रेजेंटेशन में संपादित स्लाइड डालने की अनुमति देता है (डिफ़ॉल्ट व्यवहार)।
Slide number प्रस्तुति में स्लाइड का 1-आधारित क्रमांक है, जो Editor class में लोड किया गया है। यदि यह 0 (डिफ़ॉल्ट मान) है, तो नई प्रस्तुति एकल संपादित स्लाइड के साथ बनाई जाएगी। यदि यह शून्य से बड़ा या छोटा है, और Editor class में वैध प्रस्तुति लोड है, तो इनपुट EditableDocument इंस्टेंस में संग्रहीत संपादित स्लाइड इस प्रस्तुति में सम्मिलित की जाएगी।

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


नए सिंगल‑स्लाइड प्रेजेंटेशन बनाने के बजाय मौजूदा प्रेजेंटेशन में संपादित स्लाइड डालने की अनुमति देता है (डिफ़ॉल्ट व्यवहार)।
Slide number प्रस्तुति में स्लाइड का 1-आधारित क्रमांक है, जो Editor class में लोड किया गया है। यदि यह 0 (डिफ़ॉल्ट मान) है, तो नई प्रस्तुति एकल संपादित स्लाइड के साथ बनाई जाएगी। यदि यह शून्य से बड़ा या छोटा है, और Editor class में वैध प्रस्तुति लोड है, तो इनपुट EditableDocument इंस्टेंस में संग्रहीत संपादित स्लाइड इस प्रस्तुति में सम्मिलित की जाएगी।

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


बूलियन फ़्लैग, जो यह निर्दिष्ट करता है कि संपादित स्लाइड को मूल प्रेजेंटेशन में निर्दिष्ट स्थिति पर मौजूदा स्लाइड को बदलना चाहिए या नहीं,
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) प्रॉपर्टी, या इसे मौजूदा स्लाइड और पिछले स्लाइड के बीच डाला जाना चाहिए, बिना उसकी सामग्री को बदले।
डिफ़ॉल्ट रूप से false \\u2014 मौजूदा स्लाइड को प्रतिस्थापित किया जाएगा। यह प्रॉपर्टी तब अनदेखी की जाती है, यदि मान का
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) प्रॉपर्टी '0' पर सेट है।

<br />

*** ** * ** ***

डिफ़ॉल्ट रूप से स्लाइड को प्रतिस्थापित किया जाता है। इसका अर्थ है कि यदि दी गई प्रस्तुति में 5 स्लाइड हैं, और SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4 है, तो 4वीं स्लाइड को नई संपादित स्लाइड से प्रतिस्थापित किया जाएगा, जबकि प्रस्तुति में कुल स्लाइडों की संख्या (5) अपरिवर्तित रहेगी। हालांकि, यदि इस प्रॉपर्टी का मान *true* पर सेट किया जाता है, तो नई संपादित स्लाइड को 4वीं स्लाइड के रूप में डाला जाएगा, और सभी बाद की स्लाइडें अंत की ओर शिफ्ट हो जाएँगी: "old" 4वीं स्लाइड 5वीं बन जाएगी, और 5वीं 6वीं बन जाएगी, और प्रस्तुति में कुल स्लाइडों की संख्या एक से बढ़कर 6 हो जाएगी।

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


बूलियन फ़्लैग, जो यह निर्दिष्ट करता है कि संपादित स्लाइड को मूल प्रेजेंटेशन में निर्दिष्ट स्थिति पर मौजूदा स्लाइड को बदलना चाहिए या नहीं,
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) प्रॉपर्टी, या इसे मौजूदा स्लाइड और पिछले स्लाइड के बीच डाला जाना चाहिए, बिना उसकी सामग्री को बदले।
डिफ़ॉल्ट रूप से false \\u2014 मौजूदा स्लाइड को प्रतिस्थापित किया जाएगा। यह प्रॉपर्टी तब अनदेखी की जाती है, यदि मान का
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) प्रॉपर्टी '0' पर सेट है।

<br />

*** ** * ** ***

डिफ़ॉल्ट रूप से स्लाइड को प्रतिस्थापित किया जाता है। इसका अर्थ है कि यदि दी गई प्रस्तुति में 5 स्लाइड हैं, और SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4 है, तो 4वीं स्लाइड को नई संपादित स्लाइड से प्रतिस्थापित किया जाएगा, जबकि प्रस्तुति में कुल स्लाइडों की संख्या (5) अपरिवर्तित रहेगी। हालांकि, यदि इस प्रॉपर्टी का मान *true* पर सेट किया जाता है, तो नई संपादित स्लाइड को 4वीं स्लाइड के रूप में डाला जाएगा, और सभी बाद की स्लाइडें अंत की ओर शिफ्ट हो जाएँगी: "old" 4वीं स्लाइड 5वीं बन जाएगी, और 5वीं 6वीं बन जाएगी, और प्रस्तुति में कुल स्लाइडों की संख्या एक से बढ़कर 6 हो जाएगी।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


दस्तावेज़ को सहेजने के लिए उपयोग किए जाने वाले Presentation फ़ॉर्मेट को निर्दिष्ट करने की अनुमति देता है

<br />

*** ** * ** ***

आउटपुट फ़ॉर्मेट आमतौर पर इस क्लास के कंस्ट्रक्टर में सेट किया जाता है, क्योंकि यह अनिवार्य है। यह प्रॉपर्टी बाद में आउटपुट फ़ॉर्मेट प्राप्त करने या संशोधित करने की अनुमति देती है, जब [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) क्लास का इंस्टेंस पहले ही बना हो।

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


दस्तावेज़ को सहेजने के लिए उपयोग किए जाने वाले Presentation फ़ॉर्मेट को निर्दिष्ट करने की अनुमति देता है

<br />

*** ** * ** ***

आउटपुट फ़ॉर्मेट आमतौर पर इस क्लास के कंस्ट्रक्टर में सेट किया जाता है, क्योंकि यह अनिवार्य है। यह प्रॉपर्टी बाद में आउटपुट फ़ॉर्मेट प्राप्त करने या संशोधित करने की अनुमति देती है, जब [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) क्लास का इंस्टेंस पहले ही बना हो।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


सहेजते समय प्रस्तुति से हटाई जाने वाली स्लाइडों के 1-आधारित क्रमांक वाली एक एरे निर्दिष्ट करने की अनुमति देता है, जब संपादित स्लाइड मौजूदा प्रस्तुति में डाली जाती है। जब संपादित स्लाइड को नई एकल-स्लाइड प्रस्तुति (डिफ़ॉल्ट व्यवहार) के रूप में नहीं, बल्कि मौजूदा प्रस्तुति में ( #getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int) का उपयोग करके) सहेजा जाता है, तो इस एरे में उनके क्रमांक निर्दिष्ट करके इस प्रस्तुति की कुछ विशेष स्लाइडों को हटाना भी संभव है। डिफ़ॉल्ट रूप से यह एरे null है \\u2014 कोई स्लाइड हटाई नहीं जाएगी। हालांकि, जब यह एरे non-null और non-empty हो, और इसमें कम से कम एक वैध स्लाइड क्रमांक हो, तो संपादित स्लाइड की सामग्री के साथ आउटपुट Presentation दस्तावेज़ उत्पन्न होने के बाद, निर्दिष्ट क्रमांक वाली स्लाइडें प्रस्तुति से हटाई जाएँगी, ठीक आउटपुट स्ट्रीम या फ़ाइल में लिखने से पहले। इस एरे में स्लाइड क्रमांक 1-आधारित हैं, 0-आधारित नहीं। अमान्य क्रमांक (1 से कम या कुल स्लाइडों की संख्या से अधिक) को अनदेखा किया जाएगा।


**Returns:**
int[] - हटाने के लिए 1-आधारित स्लाइड क्रमांक की एरे, या यदि कुछ नहीं हटाना है तो null।

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


सहेजते समय प्रस्तुति से हटाई जाने वाली स्लाइडों के 1-आधारित क्रमांक वाली एरे निर्दिष्ट करने की अनुमति देता है, जब संपादित स्लाइड मौजूदा प्रस्तुति में डाली जाती है। इस एरे में स्लाइड क्रमांक 1-आधारित हैं। अमान्य क्रमांक को अनदेखा किया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | मान | int[] | हटाने के लिए 1-आधारित स्लाइड क्रमांक की एरे (null या खाली हो सकती है)। |
|

