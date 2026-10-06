---
title: "FixedLayoutEditOptionsBase"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "PDF और XPS जैसे फिक्स्ड-लेआउट फ़ॉर्मेट्स के सभी दस्तावेज़ों के विकल्पों के लिए बेस एब्स्ट्रैक्ट क्लास।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

PDF और XPS जैसे फिक्स्ड-लेआउट फ़ॉर्मेट्स के सभी दस्तावेज़ों के विकल्पों के लिए बेस एब्स्ट्रैक्ट क्लास।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | इनपुट फिक्स्ड-लेआउट दस्तावेज़ को परिणामी HTML में परिवर्तित करते समय छवियों को छोड़ना है या नहीं, यह दर्शाने वाला फ़्लैग प्राप्त करता है या सेट करता है। |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | इनपुट फिक्स्ड-लेआउट दस्तावेज़ को परिणामी HTML में परिवर्तित करते समय छवियों को छोड़ना है या नहीं, यह दर्शाने वाला फ़्लैग प्राप्त करता है या सेट करता है। |
|
|  | [getPages()](#getPages--) | प्रोसेस करने के लिए पेज रेंज सेट करने की अनुमति देता है। |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | प्रोसेस करने के लिए पेज रेंज सेट करने की अनुमति देता है। |
|
|  | [getEnablePagination()](#getEnablePagination--) | परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम (true) या अक्षम (false) करने की अनुमति देता है। |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम (true) या अक्षम (false) करने की अनुमति देता है। |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


इनपुट फिक्स्ड-लेआउट दस्तावेज़ को परिणामी HTML में परिवर्तित करते समय छवियों को छोड़ना है या नहीं, यह दर्शाने वाला फ़्लैग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट रूप से false है — छवियों को संरक्षित किया जाता है।


**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


इनपुट फिक्स्ड-लेआउट दस्तावेज़ को परिणामी HTML में परिवर्तित करते समय छवियों को छोड़ना है या नहीं, यह दर्शाने वाला फ़्लैग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट रूप से false है — छवियों को संरक्षित किया जाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


प्रोसेस करने के लिए पेज रेंज सेट करने की अनुमति देता है। डिफ़ॉल्ट रूप से फिक्स्ड-लेआउट दस्तावेज़ के सभी पेज प्रोसेस किए जाते हैं।


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


प्रोसेस करने के लिए पेज रेंज सेट करने की अनुमति देता है। डिफ़ॉल्ट रूप से फिक्स्ड-लेआउट दस्तावेज़ के सभी पेज प्रोसेस किए जाते हैं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम (true) या अक्षम (false) करने की अनुमति देता है। डिफ़ॉल्ट रूप से यह अक्षम (false) है।

<br />

*** ** * ** ***

फ़िक्स्ड-लेआउट फ़ॉर्मैट दस्तावेज़ (विशेष रूप से PDF और XPS) मूल रूप से सख्ती से पेज्ड होते हैं, उनका कंटेंट एक स्थिर लेआउट रखता है और पेजों में विभाजित होता है। लेकिन परिणामी संपादन योग्य HTML को या तो पेजलेस या पेजिनल दृश्य में प्रस्तुत किया जा सकता है।

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम (true) या अक्षम (false) करने की अनुमति देता है। डिफ़ॉल्ट रूप से यह अक्षम (false) है।

<br />

*** ** * ** ***

फ़िक्स्ड-लेआउट फ़ॉर्मैट दस्तावेज़ (विशेष रूप से PDF और XPS) मूल रूप से सख्ती से पेज्ड होते हैं, उनका कंटेंट एक स्थिर लेआउट रखता है और पेजों में विभाजित होता है। लेकिन परिणामी संपादन योग्य HTML को या तो पेजलेस या पेजिनल दृश्य में प्रस्तुत किया जा सकता है।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

