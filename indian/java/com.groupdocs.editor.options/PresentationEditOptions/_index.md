---
title: "PresentationEditOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सभी समर्थित प्रेज़ेंटेशन (PowerPoint‑compatible) फ़ॉर्मैट वाले दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 32
url: /hi/java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

सभी समर्थित दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है
प्रेज़ेंटेशन (PowerPoint‑compatible) फ़ॉर्मैट

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | स्लाइड नंबर निर्दिष्ट करने की अनुमति देता है, जिन्हें संपादन के लिए खोला जाना चाहिए |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | स्लाइड नंबर निर्दिष्ट करने की अनुमति देता है, जिन्हें संपादन के लिए खोला जाना चाहिए |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्दिष्ट करता है कि छिपी स्लाइड्स को शामिल किया जाना चाहिए या नहीं। |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्दिष्ट करता है कि छिपी स्लाइड्स को शामिल किया जाना चाहिए या नहीं। |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


स्लाइड नंबर निर्दिष्ट करने की अनुमति देता है, जिन्हें संपादन के लिए खोला जाना चाहिए


*** ** * ** ***

स्लाइड नंबर एक शून्य‑आधारित सूचकांक है जो प्रस्तुति से एक विशिष्ट स्लाइड को संपादन के लिए निर्दिष्ट और चुनने की अनुमति देता है। यदि यह 0 से कम है, तो पहली स्लाइड चुनी जाएगी (SlideNumber = 0 के समान)। यदि यह प्रस्तुति में सभी स्लाइडों की संख्या से अधिक है, तो अंतिम स्लाइड चुनी जाएगी। यदि इनपुट प्रस्तुति में केवल एक ही स्लाइड है, तो यह विकल्प अनदेखा किया जाएगा, और उस एकल स्लाइड को संपादित किया जाएगा। यदि छिपी स्लाइड को संपादन के लिए खोलने का प्रयास किया जाता है, जबकि ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) विकल्प 'false' पर सेट है, तो अपवाद फेंका जाएगा।

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


स्लाइड नंबर निर्दिष्ट करने की अनुमति देता है, जिन्हें संपादन के लिए खोला जाना चाहिए


*** ** * ** ***

स्लाइड नंबर एक शून्य‑आधारित सूचकांक है जो प्रस्तुति से एक विशिष्ट स्लाइड को संपादन के लिए निर्दिष्ट और चुनने की अनुमति देता है। यदि यह 0 से कम है, तो पहली स्लाइड चुनी जाएगी (SlideNumber = 0 के समान)। यदि यह प्रस्तुति में सभी स्लाइडों की संख्या से अधिक है, तो अंतिम स्लाइड चुनी जाएगी। यदि इनपुट प्रस्तुति में केवल एक ही स्लाइड है, तो यह विकल्प अनदेखा किया जाएगा, और उस एकल स्लाइड को संपादित किया जाएगा। यदि छिपी स्लाइड को संपादन के लिए खोलने का प्रयास किया जाता है, जबकि ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) विकल्प 'false' पर सेट है, तो अपवाद फेंका जाएगा।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


निर्दिष्ट करता है कि छिपी स्लाइड्स को शामिल किया जाना चाहिए या नहीं। डिफ़ॉल्ट है
false - छिपी स्लाइड्स नहीं दिखायीँ जातीं और अपवाद फेंका जाएगा जबकि
उन्हें संपादित करने का प्रयास किया जाता है।


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


निर्दिष्ट करता है कि छिपी स्लाइड्स को शामिल किया जाना चाहिए या नहीं। डिफ़ॉल्ट है
false - छिपी स्लाइड्स नहीं दिखायीँ जातीं और अपवाद फेंका जाएगा जबकि
उन्हें संपादित करने का प्रयास किया जाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

