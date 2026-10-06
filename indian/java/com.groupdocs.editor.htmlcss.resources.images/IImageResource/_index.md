---
title: "IImageResource"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "किसी भी प्रकार (रेस्टर या वेक्टर) की छवि संसाधन का प्रतिनिधित्व करता है"
type: docs
weight: 13
url: /hi/java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

किसी भी प्रकार के इमेज संसाधन, रास्टर या वेक्टर को दर्शाता है।


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getType()](#getType--) | कार्यान्वयन में प्रकार को एक विशिष्ट छवि का प्रकार लौटाना चाहिए एक |
विशिष्ट ImageType का उदाहरण, जो सभी प्रकार-विशिष्ट जानकारी को संलग्न करता है
|
|  | [getAspectRatio()](#getAspectRatio--) | कार्यान्वयन में प्रकार को किसी विशेष छवि का अनुपात (aspect ratio) लौटाना चाहिए |
उसके प्रकार की परवाह किए बिना।
|
|  | [getLinearDimensions()](#getLinearDimensions--) | कार्यान्वयन में प्रकार को छवि के रैखिक आयाम लौटाने चाहिए। |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


कार्यान्वयन में प्रकार को एक विशिष्ट छवि का प्रकार लौटाना चाहिए एक
विशिष्ट ImageType का उदाहरण, जो सभी प्रकार-विशिष्ट जानकारी को संलग्न करता है


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


कार्यान्वयन में प्रकार को किसी विशेष छवि का अनुपात (aspect ratio) लौटाना चाहिए
उसके प्रकार की परवाह किए बिना। दोनों वेक्टर और रेस्टर छवियों में अंतर्निहित
चौड़ाई और ऊँचाई के बीच अनुपात (aspect ratio)।


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


कार्यान्वयन में प्रकार को छवि के रैखिक आयाम लौटाने चाहिए। के लिए
रेस्टर छवियों में वे पिक्सेल में अंतर्निहित आयाम होते हैं। वेक्टर छवियों में, इन
विपरीत, कोई निश्चित आयाम नहीं होते, लेकिन उनका मेटाडाटा शामिल कर सकता है
विभिन्न माप इकाइयों में कुछ बुनियादी आयाम।


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
