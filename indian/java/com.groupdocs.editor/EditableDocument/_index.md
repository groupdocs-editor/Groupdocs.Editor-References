---
title: "EditableDocument"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "मध्यवर्ती दस्तावेज़ जिसमें संपादन से पहले और बाद की सामग्री होती है"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

मध्यवर्ती दस्तावेज़, जिसमें संपादन से पहले और बाद की सामग्री होती है।


*** ** * ** ***

EditableDocument क्लास का उदाहरण Editor.edit() मेथड द्वारा उत्पन्न किया जा सकता है या उपयोगकर्ता स्वयं स्थैतिक फैक्ट्रीज़ का उपयोग करके बना सकता है। EditableDocument आंतरिक रूप से दस्तावेज़ को अपने बंद स्वरूप में संग्रहीत करता है, जो सभी आयात और निर्यात स्वरूपों (जिन्हें GroupDocs.Editor समर्थन करता है) के साथ संगत (परिवर्तनीय) है। किसी भी WYSIWYG क्लाइंट-साइड एडिटर (जैसे CKEditor या TinyMCE) में दस्तावेज़ को संपादन योग्य बनाने के लिए, EditableDocument HTML मार्कअप उत्पन्न करने और संसाधनों को बनाने के मेथड प्रदान करता है, जिन्हें उपयोगकर्ता स्वीकार कर सकता है।

<br />


## Fields

| Field | विवरण |
| --- | --- |
| [Disposed](#Disposed) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getImages()](#getImages--) | बाहरी इमेज संसाधनों (रास्टर इमेज) को प्राप्त करने की अनुमति देता है, जो उपयोग किए जाते हैं |
इस HTML दस्तावेज़ द्वारा
|
|  | [getFonts()](#getFonts--) | बाहरी फ़ॉन्ट संसाधनों को प्राप्त करने की अनुमति देता है, जो इस HTML द्वारा उपयोग किए जाते हैं |
दस्तावेज़
|
|  | [getCss()](#getCss--) | CSS संसाधनों की सूची लौटाता है |
|
|  | [getAudio()](#getAudio--) | ऑडियो संसाधनों की सूची लौटाता है |
|
|  | [getAllResources()](#getAllResources--) | सभी मौजूदा संसाधनों की सूची लौटाता है: सभी स्टाइलशीट्स, छवियाँ से |
HTML और सभी स्टाइलशीट्स, फ़ॉन्ट्स
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | निर्दिष्ट स्ट्रीम में इस सामग्री को लिखकर और निर्दिष्ट टेक्स्ट एन्कोडिंग के साथ, HTML दस्तावेज़ की संपूर्ण सामग्री को बाइट स्ट्रीम के रूप में लौटाता है |
|
|  | [getBodyContent()](#getBodyContent--) | HTML दस्तावेज़ का बॉडी लौटाता है (खुलने और बंद होने के बीच की सामग्री |
BODY टैग्स (इन टैग्स के बिना) को स्ट्रिंग के रूप में।
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | HTML दस्तावेज़ का बॉडी लौटाता है (खुलने और बंद होने के बीच की सामग्री |
BODY टैग्स (इन टैग्स के बिना) को स्ट्रिंग के रूप में, जहाँ बाहरी लिंक
संसाधनों में निर्दिष्ट उपसर्ग होता है।
|
|  | [getContent()](#getContent--) | HTML दस्तावेज़ की संपूर्ण सामग्री को स्ट्रिंग के रूप में लौटाता है। |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | HTML दस्तावेज़ की संपूर्ण सामग्री को स्ट्रिंग के रूप में लौटाता है, जहाँ लिंक |
बाहरी संसाधनों में निर्दिष्ट उपसर्ग होता है।
|
|  | [getCssContent()](#getCssContent--) | सभी बाहरी स्टाइलशीट्स की सामग्री को स्ट्रिंग्स की सूची के रूप में लौटाता है, जहाँ |
एक स्ट्रिंग एक स्टाइलशीट का प्रतिनिधित्व करती है।
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | सभी बाहरी स्टाइलशीट्स की सामग्री को स्ट्रिंग्स की सूची के रूप में लौटाता है, जहाँ |
एक स्ट्रिंग एक स्टाइलशीट का प्रतिनिधित्व करती है।
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | इस HTML दस्तावेज़ की सभी सामग्री को सभी संबंधित संसाधनों के साथ एक |
एकल स्ट्रिंग के रूप में, जहाँ सभी संसाधन HTML के भीतर एम्बेड किए जाते हैं
मार्कअप को base64-एन्कोडेड रूप में।
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | निर्दिष्ट पथ पर इस HTML दस्तावेज़ को फ़ाइल में सहेजता है, जहाँ HTML मार्कअप |
सहेजा जाएगा, और संसाधनों वाले साथ के फ़ोल्डर में।
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | निर्दिष्ट पथ पर इस HTML दस्तावेज़ को फ़ाइल में सहेजता है, जहाँ HTML मार्कअप |
सहेजा जाएगा, और साथ के फ़ोल्डर में, जो
निर्दिष्ट पथ पर स्थित है।
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | स्थैतिक फ़ैक्टरी, जो EditableDocument का एक उदाहरण बनाती है |
निर्दिष्ट HTML मार्कअप और संबंधित लिंक्ड संसाधनों के सेट से
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | स्थैतिक फ़ैक्टरी, जो निर्दिष्ट HTML मार्कअप और संसाधनों से, जो पूर्ण पथ द्वारा निर्दिष्ट फ़ोल्डर में स्थित हैं, एक EditableDocument का उदाहरण बनाती है |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | स्थैतिक फ़ैक्टरी, जो एक HTML से EditableDocument का उदाहरण बनाती है |
फ़ाइल, जो स्वयं *.html फ़ाइल के पथ और एक फ़ोल्डर द्वारा निर्दिष्ट होती है
लिंक्ड संसाधनों के साथ
|
|  | [dispose()](#dispose--) | इस Editable दस्तावेज़ उदाहरण को नष्ट करता है, उसकी सामग्री को नष्ट करते हुए और |
जिससे उसकी विधियाँ और गुण काम करना बंद कर देते हैं
|
|  | [isDisposed()](#isDisposed--) | निर्धारित करता है कि यह Editable दस्तावेज़ पहले ही नष्ट किया गया है (true) या |
नहीं (false)
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


बाहरी इमेज संसाधनों (रास्टर इमेज) को प्राप्त करने की अनुमति देता है, जो उपयोग किए जाते हैं
इस HTML दस्तावेज़ द्वारा


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


बाहरी फ़ॉन्ट संसाधनों को प्राप्त करने की अनुमति देता है, जो इस HTML द्वारा उपयोग किए जाते हैं
दस्तावेज़


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


CSS संसाधनों की सूची लौटाता है


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


ऑडियो संसाधनों की सूची लौटाता है


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


सभी मौजूदा संसाधनों की सूची लौटाता है: सभी स्टाइलशीट्स, छवियाँ से
HTML और सभी स्टाइलशीट्स, फ़ॉन्ट्स


*** ** * ** ***

यह प्रॉपर्टी 'Images', 'Fonts' और 'Css' प्रॉपर्टियों का संयोजित परिणाम लौटाती है

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


निर्दिष्ट स्ट्रीम में इस सामग्री को लिखकर और निर्दिष्ट टेक्स्ट एन्कोडिंग के साथ, HTML दस्तावेज़ की संपूर्ण सामग्री को बाइट स्ट्रीम के रूप में लौटाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | स्टोरेज | java.io.OutputStream | नॉन-नल बाइट स्ट्रीम, जो लिखने का समर्थन करती है |
|
|  | एन्कोडिंग | java.nio.charset.Charset | नॉन-नल टेक्स्ट एन्कोडिंग, जिसे निर्दिष्ट स्टोरेज में टेक्स्ट सामग्री लिखते समय लागू किया जाना चाहिए |


TStream
: java.io.InputStream का कोई भी कार्यान्वयन
|

**Returns:**
java.io.OutputStream - निर्दिष्ट स्टोरेज का उदाहरण

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


HTML दस्तावेज़ का बॉडी लौटाता है (खुलने और बंद होने के बीच की सामग्री
BODY टैग्स (इन टैग्स के बिना) को स्ट्रिंग के रूप में।


**Returns:**
java.lang.String - स्ट्रिंग, जिसमें HTML दस्तावेज़ का बॉडी शामिल है


*** ** * ** ***

WYSIWYG एडिटर्स दस्तावेज़ के बॉडी के साथ काम करते हैं और HEAD ब्लॉक से उसकी मेटा जानकारी को सही ढंग से प्रोसेस नहीं कर पाते हैं। यह मेथड ऐसे मामलों के लिए डिज़ाइन किया गया है। यह ओवरलोड बाहरी संसाधन अनुरोधों के लिए URIs को समायोजित करने की अनुमति नहीं देता।

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


HTML दस्तावेज़ का बॉडी लौटाता है (खुलने और बंद होने के बीच की सामग्री
BODY टैग्स (इन टैग्स के बिना) को स्ट्रिंग के रूप में, जहाँ बाहरी लिंक
संसाधनों में निर्दिष्ट उपसर्ग होता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | इस पैरामीटर के माध्यम से आप एक प्रीफ़िक्स निर्दिष्ट कर सकते हैं, जो सभी बाहरी छवियों के लिंक में IMG तत्वों में जोड़े जाएंगे, जो परिणामी HTML स्ट्रिंग में मौजूद होंगे। यदि NULL या खाली है, तो प्रीफ़िक्स नहीं जोड़े जाएंगे। |


*** ** * ** ***

WYSIWYG एडिटर्स दस्तावेज़ के बॉडी के साथ काम करते हैं और HEAD ब्लॉक से उसकी मेटा जानकारी को सही ढंग से प्रोसेस नहीं कर पाते हैं। यह मेथड ऐसे मामलों के लिए डिज़ाइन किया गया है। यह ओवरलोड बाहरी संसाधन अनुरोधों के लिए URIs को समायोजित करने की अनुमति देता है।

<br />

|

**Returns:**
java.lang.String - String, जो HTML दस्तावेज़ के बॉडी को लिंक के साथ रखता है, बाहरी छवियों के अनुसार समायोजित किया गया है

### getContent() {#getContent--}
```
public String getContent()
```


HTML दस्तावेज़ की संपूर्ण सामग्री को स्ट्रिंग के रूप में लौटाता है।


**Returns:**
java.lang.String - String, जो HTML दस्तावेज़ की सामग्री रखता है

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


HTML दस्तावेज़ की संपूर्ण सामग्री को स्ट्रिंग के रूप में लौटाता है, जहाँ लिंक
बाहरी संसाधनों में निर्दिष्ट उपसर्ग होता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | इस पैरामीटर के माध्यम से आप एक प्रीफ़िक्स निर्दिष्ट कर सकते हैं, जो सभी बाहरी छवियों के लिंक में IMG तत्वों में जोड़े जाएंगे, जो परिणामी HTML स्ट्रिंग में मौजूद होंगे। यदि NULL या खाली है, तो प्रीफ़िक्स नहीं जोड़े जाएंगे। |
|
|  | externalCssTemplate | java.lang.String | इस पैरामीटर का उपयोग करके आप एक उपसर्ग निर्दिष्ट कर सकते हैं, जो सभी बाहरी स्टाइलशीट्स के लिंक में LINK तत्वों में जोड़े जाएंगे, जो परिणामी HTML स्ट्रिंग में उपस्थित होंगे। यदि NULL या खाली है, तो उपसर्ग नहीं जोड़े जाएंगे। |
|

**Returns:**
java.lang.String - String, जो लिंक के साथ HTML दस्तावेज़ की सामग्री रखता है, बाहरी संसाधनों के अनुसार समायोजित किया गया है

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


सभी बाहरी स्टाइलशीट्स की सामग्री को स्ट्रिंग्स की सूची के रूप में लौटाता है, जहाँ
एक स्ट्रिंग एक स्टाइलशीट का प्रतिनिधित्व करती है। यदि कोई नहीं है तो खाली सूची लौटाता है,
इस दस्तावेज़ के लिए CSS।


**Returns:**
java.util.List<java.lang.String> - स्ट्रिंग्स की एक सूची, जहाँ प्रत्येक स्ट्रिंग एक CSS दस्तावेज़ की सामग्री रखती है

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


सभी बाहरी स्टाइलशीट्स की सामग्री को स्ट्रिंग्स की सूची के रूप में लौटाता है, जहाँ
एक स्ट्रिंग एक स्टाइलशीट का प्रतिनिधित्व करती है। निर्दिष्ट उपसर्ग लागू किया जाएगा,
प्रत्येक परिणामी स्टाइलशीट में बाहरी संसाधन के प्रत्येक लिंक पर।
यदि इस दस्तावेज़ के लिए कोई CSS नहीं है तो खाली सूची लौटाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | इस पैरामीटर का उपयोग करके आप एक उपसर्ग निर्दिष्ट कर सकते हैं, जो सभी बाहरी छवियों के लिंक में जोड़ा जाएगा, जो परिणामी CSS स्ट्रिंग्स में CSS घोषणाओं में उपस्थित होंगे। यदि NULL या खाली है, तो उपसर्ग नहीं जोड़े जाएंगे। |
|
|  | externalFontsPrefix | java.lang.String | इस पैरामीटर का उपयोग करके आप एक उपसर्ग निर्दिष्ट कर सकते हैं, जो सभी बाहरी फ़ॉन्ट्स के लिंक में जोड़ा जाएगा, |
|

**Returns:**
java.util.List<java.lang.String> - स्ट्रिंग्स की एक सूची, जहाँ प्रत्येक स्ट्रिंग एक CSS दस्तावेज़ की सामग्री रखती है

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


इस HTML दस्तावेज़ की सभी सामग्री को सभी संबंधित संसाधनों के साथ एक
एकल स्ट्रिंग के रूप में, जहाँ सभी संसाधन HTML के भीतर एम्बेड किए जाते हैं
मार्कअप को base64-एन्कोडेड रूप में।


**Returns:**
java.lang.String - String, जो किसी भी स्थिति में NULL या खाली नहीं है

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


निर्दिष्ट पथ पर इस HTML दस्तावेज़ को फ़ाइल में सहेजता है, जहाँ HTML मार्कअप
सहेजा जाएगा, और संसाधनों वाले साथ के फ़ोल्डर में।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | फ़ाइल का पूर्ण पथ, जहाँ HTML मार्कअप संग्रहीत किया जाएगा। यदि फ़ाइल मौजूद है तो इसे बनाया या अधिलेखित किया जाएगा। संबंधित संसाधन फ़ोल्डर उसी फ़ोल्डर में बनाया जाएगा, जहाँ HTML फ़ाइल मौजूद है। |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


निर्दिष्ट पथ पर इस HTML दस्तावेज़ को फ़ाइल में सहेजता है, जहाँ HTML मार्कअप
सहेजा जाएगा, और साथ के फ़ोल्डर में, जो
निर्दिष्ट पथ पर स्थित है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | फ़ाइल का पूर्ण पथ, जहाँ HTML मार्कअप संग्रहीत किया जाएगा। यह NULL या खाली नहीं हो सकता। यदि फ़ाइल मौजूद है तो इसे बनाया या अधिलेखित किया जाएगा। |
|
|  | resourcesFolderPath | java.lang.String | साथी फ़ोल्डर का पूर्ण पथ, जहाँ सभी संबंधित संसाधन संग्रहीत किए जाएंगे। यदि NULL या खाली है, तो फ़ोल्डर उसी निर्देशिका में स्वचालित रूप से बनाया जाएगा, जहाँ \*.html फ़ाइल है। यदि निर्दिष्ट किया गया है और मौजूद नहीं है, तो इसे बनाया जाएगा। |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


स्थैतिक फ़ैक्टरी, जो EditableDocument का एक उदाहरण बनाती है
निर्दिष्ट HTML मार्कअप और संबंधित लिंक्ड संसाधनों के सेट से


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, जिसमें कच्चा HTML मार्कअप होता है, जिसे पार्स किया जाना चाहिए। यह NULL, खाली या अमान्य नहीं हो सकता। |
|
|  | संसाधन | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | HTML-डॉक्यूमेंट में उपयोग किए जाने वाले सभी संसाधनों (छवियां, स्टाइलशीट्स, फ़ॉन्ट्स) का संग्रह, जो newHtmlContent पैरामीटर में निर्दिष्ट है। यह अनुपस्थित हो सकता है (NULL या खाली संग्रह)। |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


स्थैतिक फ़ैक्टरी, जो निर्दिष्ट HTML मार्कअप और संसाधनों से, जो पूर्ण पथ द्वारा निर्दिष्ट फ़ोल्डर में स्थित हैं, एक EditableDocument का उदाहरण बनाती है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, जिसमें कच्चा HTML मार्कअप होता है, जिसे पार्स किया जाना चाहिए। यह NULL, खाली या अमान्य नहीं हो सकता। |
|
|  | resourceFolderPath | java.lang.String | संसाधनों वाले फ़ोल्डर का अनिवार्य पथ। इस फ़ोल्डर में स्थित सभी स्टाइलशीट्स का उपयोग किया जाएगा। यह NULL या खाली स्ट्रिंग नहीं हो सकता, और यह फ़ोल्डर मौजूद होना चाहिए। |

<br />

*** ** * ** ***

यह स्थैतिक फ़ैक्टरी तब उपयोगी होती है जब HTML डॉक्यूमेंट की सामग्री स्ट्रिंग के रूप में प्रस्तुत की जाती है, लेकिन सभी संसाधन किसी फ़ोल्डर में स्थित होते हैं, और अक्सर HTML मार्कअप में इन संसाधनों के लिंक अमान्य या अनुपस्थित होते हैं। इस मेथड को कॉल करने पर यह निर्दिष्ट फ़ोल्डर को स्कैन करता है और स्वचालित रूप से पाए गए सभी स्टाइलशीट्स को डॉक्यूमेंट पर लागू करता है। विभिन्न HTML एडिटर्स से सामग्री प्राप्त करते समय यह मेथड बहुत उपयोगी है, जहाँ अक्सर डॉक्यूमेंट मेटाडेटा आदि काट दिया जाता है।

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


स्थैतिक फ़ैक्टरी, जो एक HTML से EditableDocument का उदाहरण बनाती है
फ़ाइल, जो स्वयं *.html फ़ाइल के पथ और एक फ़ोल्डर द्वारा निर्दिष्ट होती है
लिंक्ड संसाधनों के साथ


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | String, जो HTML फ़ाइल का पूर्ण पथ रखता है। यह null नहीं हो सकता, वैध फ़ाइल पथ होना चाहिए, और फ़ाइल स्वयं मौजूद होनी चाहिए। |
|
|  | resourceFolderPath | java.lang.String | HTML संसाधनों वाले फ़ोल्डर का वैकल्पिक पथ। यदि NULL है, अमान्य है या ऐसा फ़ोल्डर मौजूद नहीं है, तो एडिटर स्वयं HTML मार्कअप का विश्लेषण करके इस फ़ोल्डर को खोजने की कोशिश करेगा। |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


इस Editable दस्तावेज़ उदाहरण को नष्ट करता है, उसकी सामग्री को नष्ट करते हुए और
जिससे उसकी विधियाँ और गुण काम करना बंद कर देते हैं


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


निर्धारित करता है कि यह Editable दस्तावेज़ पहले ही नष्ट किया गया है (true) या
नहीं (false)


**Returns:**
boolean
