---
title: "ResourceTypeDetector"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "संसाधन प्रकार और फ़ॉर्मेट का पता लगाने के लिए उपयोगी स्थैतिक मेथड्स"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

संसाधन प्रकारों (फ़ॉर्मेट) का पता लगाने के लिए उपयोगी स्थैतिक मेथड्स।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | निर्दिष्ट फ़ाइलनाम से प्रकार का पता लगाता है और एक इंस्टेंस लौटाता है |
संबंधित IResourceType
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | इनपुट स्ट्रीम का विश्लेषण करने का प्रयास करता है और समर्थित HTML में से एक बनाता है |
उससे संसाधन, निर्दिष्ट अनुमानित प्रकार को ध्यान में रखते हुए, यदि यह
null नहीं है
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


निर्दिष्ट फ़ाइलनाम से प्रकार का पता लगाता है और एक इंस्टेंस लौटाता है
संबंधित IResourceType


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइलनाम | java.lang.String | इनपुट फ़ाइलनाम, जिससे यह मेथड परिणामी IResourceType इम्प्लीमेंटेशन निकालने का प्रयास करेगा |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


इनपुट स्ट्रीम का विश्लेषण करने का प्रयास करता है और समर्थित HTML में से एक बनाता है
उससे संसाधन, निर्दिष्ट अनुमानित प्रकार को ध्यान में रखते हुए, यदि यह
null नहीं है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | इनपुट स्ट्रीम, जिसमें संभवतः एक HTML संसाधन होता है। यदि अमान्य है, तो एक अपवाद फेंका जाएगा। |
|
|  | नाम | java.lang.String | संसाधन नाम, जिसका उपयोग सफल होने पर निर्मित और लौटाए गए संसाधन के लिए किया जाएगा। NULL, खाली या व्हाइटस्पेस नहीं हो सकता। |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | इनपुट HTML संसाधन का अनुमानित फ़ॉर्मेट, जो सर्वोत्तम प्रदर्शन प्राप्त करने में उपयोगी है। यदि पूरी तरह अज्ञात हो, तो NULL मान का उपयोग करें। यह गलत भी हो सकता है, जिससे प्रदर्शन और बिगड़ जाएगा। |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

