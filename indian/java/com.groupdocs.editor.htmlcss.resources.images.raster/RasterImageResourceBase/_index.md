---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "किसी भी समर्थित रास्टर छवि के लिए बेस क्लास जिसमें स्थिर नाम, आयाम, अनुपात, प्रकार, आकार और सामग्री हो।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

किसी भी समर्थित रास्टर छवि के लिए बेस क्लास जिसमें स्थिर नाम, आयाम, पहलू
अनुपात, प्रकार, आकार, और सामग्री।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## Fields

| Field | विवरण |
| --- | --- |
| [Disposed](#Disposed) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getName()](#getName--) | इस रास्टर छवि का नाम लौटाता है। |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | इस रास्टर छवि का सही फ़ाइलनाम लौटाता है, जो नाम और |
एक्सटेंशन।
|
|  | [getLinearDimensions()](#getLinearDimensions--) | इस रास्टर छवि के रैखिक आयाम (चौड़ाई और ऊँचाई) लौटाता है |
|
|  | [getAspectRatio()](#getAspectRatio--) | इस छवि का अनुपात चौड़ाई-से-ऊँचाई संबंध के रूप में लौटाता है |
|
|  | [getLength()](#getLength--) | इस रास्टर छवि फ़ाइल की लंबाई बाइट्स में लौटाता है |
|
|  | [getByteContent()](#getByteContent--) | इस रास्टर छवि की सामग्री को बाइट स्ट्रीम के रूप में लौटाता है |
|
|  | [getTextContent()](#getTextContent--) | इस रास्टर छवि की सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में लौटाता है |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | इस रास्टर छवि को निर्दिष्ट फ़ाइल में सहेजता है |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | इस इंस्टेंस को निर्दिष्ट के साथ रेफ़रेंस समानता पर जाँचता है। |
|
|  | [dispose()](#dispose--) | इस रास्टर छवि को डिस्पोज़ करता है, उसकी सामग्री को डिस्पोज़ करता है और अधिकांश मेथड्स को |
और प्रॉपर्टीज़ काम नहीं कर रही हैं
|
|  | [isDisposed()](#isDisposed--) | निर्धारित करता है कि यह रास्टर इमेज डिस्पोज़्ड है या नहीं |
|
|  | [getType()](#getType--) | इम्प्लीमेंटेशन में प्रकार को रास्टर के प्रकार के बारे में जानकारी लौटानी चाहिए |
इमेज
|
### RasterImageResourceBase() {#RasterImageResourceBase--}
```
public RasterImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


इस रास्टर इमेज का नाम लौटाता है। आमतौर पर इसमें फ़ाइलनाम नहीं होता
एक्सटेंशन और सैद्धांतिक रूप से फ़ाइलनाम से अलग हो सकता है।


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


इस रास्टर छवि का सही फ़ाइलनाम लौटाता है, जो नाम और
एक्सटेंशन। सैद्धांतिक रूप से नाम से अलग हो सकता है।


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


इस रास्टर छवि के रैखिक आयाम (चौड़ाई और ऊँचाई) लौटाता है


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


इस छवि का अनुपात चौड़ाई-से-ऊँचाई संबंध के रूप में लौटाता है


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


इस रास्टर छवि फ़ाइल की लंबाई बाइट्स में लौटाता है


**Returns:**
int - 
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


इस रास्टर छवि की सामग्री को बाइट स्ट्रीम के रूप में लौटाता है


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


इस रास्टर छवि की सामग्री को base64-एन्कोडेड स्ट्रिंग के रूप में लौटाता है


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


इस रास्टर छवि को निर्दिष्ट फ़ाइल में सहेजता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | फ़ाइल का पूर्ण पथ, जिसे बनाया या पुनः लिखा जाएगा। |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


इस इंस्टेंस को निर्दिष्ट के साथ रेफ़रेंस समानता पर जाँचता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | अन्य IHtmlResource इनहेरिटर |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### dispose() {#dispose--}
```
public final void dispose()
```


इस रास्टर छवि को डिस्पोज़ करता है, उसकी सामग्री को डिस्पोज़ करता है और अधिकांश मेथड्स को
और प्रॉपर्टीज़ काम नहीं कर रही हैं


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


निर्धारित करता है कि यह रास्टर इमेज डिस्पोज़्ड है या नहीं


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


इम्प्लीमेंटेशन में प्रकार को रास्टर के प्रकार के बारे में जानकारी लौटानी चाहिए
इमेज


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
