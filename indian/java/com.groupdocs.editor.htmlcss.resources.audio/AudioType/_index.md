---
title: "AudioType"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक समर्थित ऑडियो प्रकार फ़ॉर्मेट का प्रतिनिधित्व करता है"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

एक समर्थित ऑडियो प्रकार (फ़ॉर्मेट) को दर्शाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | इस ऑडियो फ़ॉर्मेट का औपचारिक नाम |
|
|  | [getFileExtension()](#getFileExtension--) | इस ऑडियो फ़ॉर्मेट के लिए फ़ाइलनाम एक्सटेंशन (डॉट कैरेक्टर के बिना) |
|
|  | [getMimeCode()](#getMimeCode--) | इस ऑडियो फ़ॉर्मेट के लिए MIME कोड |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "AudioType" इंस्टेंस के बराबर है या नहीं |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं, जो सम्भवतः एक अन्य "AudioType" इंस्टेंस है |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | जाँचता है कि दो "AudioType" मान बराबर हैं या नहीं |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | जाँचता है कि दो \"AudioType\" मान बराबर नहीं हैं |
|
|  | [hashCode()](#hashCode--) | एक हैश-कोड लौटाता है, जो इस विशिष्ट मान प्रकार के लिए एक स्थिर संख्या है |
|
|  | [getUndefined()](#getUndefined--) | विशेष मान, जो अपरिभाषित, अज्ञात या असमर्थित ऑडियो फ़ॉर्मेट को दर्शाता है |
|
|  | [getMp3()](#getMp3--) | MPEG-1 ऑडियो लेयर III ऑडियो फ़ॉर्मेट का प्रतिनिधित्व करता है |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | एक \"AudioType\" मान लौटाता है, जो निर्दिष्ट फ़ाइलनाम से निकाले गए फ़ाइलनाम एक्सटेंशन के समतुल्य है |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


इस ऑडियो फ़ॉर्मेट का औपचारिक नाम


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


इस ऑडियो फ़ॉर्मेट के लिए फ़ाइलनाम एक्सटेंशन (डॉट कैरेक्टर के बिना)


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


इस ऑडियो फ़ॉर्मेट के लिए MIME कोड


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "AudioType" इंस्टेंस के बराबर है या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | इसके साथ जाँचने के लिए अन्य AudioType इंस्टेंस |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं, जो सम्भवतः एक अन्य "AudioType" इंस्टेंस है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | संभवतः AudioType स्ट्रक्ट का अन्य इंस्टेंस, जिसे System.Object में बॉक्स किया गया था |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


जाँचता है कि दो "AudioType" मान बराबर हैं या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | जाँचने के लिए पहला AudioType |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | जाँचने के लिए दूसरा AudioType |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


जाँचता है कि दो \"AudioType\" मान बराबर नहीं हैं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | जाँचने के लिए पहला AudioType |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | जाँचने के लिए दूसरा AudioType |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### hashCode() {#hashCode--}
```
public int hashCode()
```


एक हैश-कोड लौटाता है, जो इस विशिष्ट मान प्रकार के लिए एक स्थिर संख्या है


**Returns:**
int - 4-बाइट साइन्ड इंटीजर, Undefined मान के लिए 0

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


विशेष मान, जो अपरिभाषित, अज्ञात या असमर्थित ऑडियो फ़ॉर्मेट को दर्शाता है


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


MPEG-1 ऑडियो लेयर III ऑडियो फ़ॉर्मेट का प्रतिनिधित्व करता है


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


एक \"AudioType\" मान लौटाता है, जो निर्दिष्ट फ़ाइलनाम से निकाले गए फ़ाइलनाम एक्सटेंशन के समतुल्य है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइलनाम | java.lang.String | मनमाना फ़ाइलनाम, यह सापेक्ष या पूर्ण पथ हो सकता है |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

