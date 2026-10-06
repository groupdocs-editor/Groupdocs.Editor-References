---
title: "PageRange"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक पेज रेंज को संलग्न करता है जिसमें खुले या बंद सीमाएँ हो सकती हैं।"
type: docs
weight: 27
url: /hi/java/com.groupdocs.editor.options/pagerange/
---
**Inheritance:**
java.lang.Object
```
public class PageRange
```

एक पेज रेंज को संलग्न करता है, जिसमें खुले या बंद सीमाएँ हो सकती हैं। डिफ़ॉल्ट रूप से यह "पूर्णतः खुला" होता है - यह सभी मौजूदा पृष्ठों को शामिल करता है। पेज क्रमांक 1 से शुरू होता है, 0 से नहीं।

<br />

*** ** * ** ***

एक अपरिवर्तनीय स्ट्रक्ट, जो एक पेज रेंज को संलग्न करता है, जो किसी विशिष्ट दस्तावेज़ से संबंधित नहीं है, और किसी भी दस्तावेज़ के लिए पेज रेंज का प्रतिनिधित्व कर सकता है।

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PageRange()](#PageRange--) |  |
## Fields

| Field | विवरण |
| --- | --- |
|  | [AllPages](#AllPages) | किसी दस्तावेज़ के सभी मौजूदा पृष्ठों का प्रतिनिधित्व करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getStartNumber()](#getStartNumber--) | समावेशी प्रारंभ पेज संख्या, जिससे यह पेज रेंज शुरू होती है। |
|
|  | [getEndNumber()](#getEndNumber--) | विशिष्ट समाप्ति पेज संख्या, जिसके तक यह पेज रेंज जारी रहती है और जहाँ यह विशेष रूप से समाप्त होती है। |
|
|  | [getCount()](#getCount--) | रेंज के भीतर पृष्ठों की संख्या। |
|
|  | [isDefault()](#isDefault--) | यह दर्शाता है कि क्या यह इंस्टेंस डिफ़ॉल्ट "पूर्णतः खुला" पेज रेंज का प्रतिनिधित्व करता है, अर्थात्। |
|
|  | [equals(PageRange other)](#equals-com.groupdocs.editor.options.PageRange-) | पता लगाता है कि यह PageRange इंस्टेंस निर्दिष्ट के बराबर है या नहीं। |
|
|  | [fromBeginningWithCount(int pageCount)](#fromBeginningWithCount-int-) | एक पेज रेंज बनाता है, जो पहले पेज से शुरू होती है और निर्दिष्ट संख्या के पृष्ठों को शामिल करती है। |
|
|  | [fromStartPageTillEnd(int startPageNumber)](#fromStartPageTillEnd-int-) | एक पेज रेंज बनाता है, जो निर्दिष्ट पेज संख्या से शुरू होती है और दस्तावेज़ के अंत तक जारी रहती है। |
|
|  | [fromStartPageWithCount(int startPageNumber, int pageCount)](#fromStartPageWithCount-int-int-) | एक पेज रेंज बनाता है, जो निर्दिष्ट पेज संख्या से शुरू होती है और निर्दिष्ट संख्या के पृष्ठों को शामिल करती है, या अनिश्चित पेज गिनती (अंत तक)। |
|
|  | [fromStartPageTillEndPage(int startPageNumber, int endPageNumber)](#fromStartPageTillEndPage-int-int-) | एक पेज रेंज बनाता है, जो निर्दिष्ट पेज संख्या (समावेशी) से शुरू होती है और निर्दिष्ट पेज संख्या (विशिष्ट) तक जारी रहती है। |
|
### PageRange() {#PageRange--}
```
public PageRange()
```


### AllPages {#AllPages}
```
public static final PageRange AllPages
```


किसी दस्तावेज़ के सभी मौजूदा पृष्ठों का प्रतिनिधित्व करता है। डिफ़ॉल्ट मान।


### getStartNumber() {#getStartNumber--}
```
public final int getStartNumber()
```


समावेशी प्रारंभ पेज संख्या, जिससे यह पेज रेंज शुरू होती है। यदि 1 - पेज रेंज दस्तावेज़ के पहले पेज से शुरू होती है।


**Returns:**
int
### getEndNumber() {#getEndNumber--}
```
public final int getEndNumber()
```


विशिष्ट समाप्ति पेज संख्या, जिसके तक यह पेज रेंज जारी रहती है और जहाँ यह विशेष रूप से समाप्त होती है। यदि 0 - पेज रेंज दस्तावेज़ के अंत तक फैली रहती है।


**Returns:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


रेंज के भीतर पृष्ठों की संख्या। यदि 0 - पेज रेंज दस्तावेज़ के अंत तक फैली रहती है, चाहे उसमें कितने भी पृष्ठ हों।


**Returns:**
int
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


यह दर्शाता है कि क्या यह इंस्टेंस डिफ़ॉल्ट "पूर्णतः खुला" पेज रेंज का प्रतिनिधित्व करता है, अर्थात् यह दस्तावेज़ के सभी पृष्ठों को शामिल करता है।


**Returns:**
boolean
### equals(PageRange other) {#equals-com.groupdocs.editor.options.PageRange-}
```
public final boolean equals(PageRange other)
```


पता लगाता है कि यह PageRange इंस्टेंस निर्दिष्ट के बराबर है या नहीं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [PageRange](../../com.groupdocs.editor.options/pagerange) | समानता जाँचने के लिए अन्य PageRange इंस्टेंस। |
|

**Returns:**
बूलियन - true यदि समान हैं; false यदि असमान हैं।

### fromBeginningWithCount(int pageCount) {#fromBeginningWithCount-int-}
```
public static PageRange fromBeginningWithCount(int pageCount)
```


एक पेज रेंज बनाता है, जो पहले पेज से शुरू होती है और निर्दिष्ट संख्या के पृष्ठों को शामिल करती है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | pageCount | int | पृष्ठों की संख्या, शून्य से सख्ती से बड़ी होनी चाहिए |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEnd(int startPageNumber) {#fromStartPageTillEnd-int-}
```
public static PageRange fromStartPageTillEnd(int startPageNumber)
```


एक पेज रेंज बनाता है, जो निर्दिष्ट पेज संख्या से शुरू होती है और दस्तावेज़ के अंत तक जारी रहती है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | startPageNumber | int | पृष्ठ संख्या, जिससे पृष्ठ सीमा शुरू होती है, समावेशी रूप से। पृष्ठ संख्याएँ 1-आधारित हैं, इसलिए शून्य से सख्ती से बड़ी होनी चाहिए |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageWithCount(int startPageNumber, int pageCount) {#fromStartPageWithCount-int-int-}
```
public static PageRange fromStartPageWithCount(int startPageNumber, int pageCount)
```


एक पेज रेंज बनाता है, जो निर्दिष्ट पेज संख्या से शुरू होती है और निर्दिष्ट संख्या के पृष्ठों को शामिल करती है, या अनिश्चित पेज गिनती (अंत तक)।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | startPageNumber | int | पृष्ठ संख्या, जिससे पृष्ठ सीमा शुरू होती है, समावेशी रूप से। पृष्ठ संख्याएँ 1-आधारित हैं, इसलिए शून्य से सख्ती से बड़ी होनी चाहिए |
|
|  | pageCount | int | पृष्ठों की संख्या, शून्य से सख्ती से बड़ी होनी चाहिए। यदि शून्य है - इसका मतलब है दस्तावेज़ के अंत तक सभी पृष्ठ |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - New PageRange instance

### fromStartPageTillEndPage(int startPageNumber, int endPageNumber) {#fromStartPageTillEndPage-int-int-}
```
public static PageRange fromStartPageTillEndPage(int startPageNumber, int endPageNumber)
```


एक पेज रेंज बनाता है, जो निर्दिष्ट पेज संख्या (समावेशी) से शुरू होती है और निर्दिष्ट पेज संख्या (विशिष्ट) तक जारी रहती है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | startPageNumber | int | पृष्ठ संख्या, जिससे पृष्ठ सीमा शुरू होती है, समावेशी रूप से। पृष्ठ संख्याएँ 1-आधारित हैं, इसलिए शून्य से सख्ती से बड़ी होनी चाहिए |
|
|  | endPageNumber | int | पृष्ठ संख्या, जिसके तक पृष्ठ सीमा जारी रहती है, केवलात्मक रूप से। पृष्ठ संख्याएँ 1-आधारित हैं, इसलिए शून्य से सख्ती से बड़ी होनी चाहिए, और साथ ही startPageNumber से सख्ती से बड़ी होनी चाहिए |
|

**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange) - 
