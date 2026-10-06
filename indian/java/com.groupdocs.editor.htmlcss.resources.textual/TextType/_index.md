---
title: "TextType"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक समर्थित पाठ्य संसाधन प्रकार का प्रतिनिधित्व करता है"
type: docs
weight: 12
url: /hi/java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

एक समर्थित पाठ्य संसाधन प्रकार का प्रतिनिधित्व करता है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [TextType()](#TextType--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | विशेष मान, जो अपरिभाषित, अज्ञात या असमर्थित पाठ को दर्शाता है |
संसाधन
|
|  | [getCss()](#getCss--) | पाठ संसाधन का CSS प्रकार |
|
|  | [getXml()](#getXml--) | पाठ संसाधन का XML प्रकार |
|
|  | [getFormalName()](#getFormalName--) | इस पाठ संसाधन प्रकार का औपचारिक नाम लौटाता है |
|
|  | [getFileExtension()](#getFileExtension--) | किसी विशेष पाठ का फ़ाइल एक्सटेंशन (प्रारंभिक बिंदु अक्षर के बिना) |
संसाधन
|
|  | [getMimeCode()](#getMimeCode--) | किसी विशेष पाठ संसाधन प्रकार का MIME कोड |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | निर्धारित करता है कि यह उदाहरण निर्दिष्ट \"TextType\" के बराबर है या नहीं |
उदाहरण
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि यह उदाहरण निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं, |
जो सम्भवतः एक अन्य \"TextType\" उदाहरण है
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | परिभाषित करता है कि दो विशिष्ट \"TextType\" उदाहरण बराबर हैं या नहीं |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | परिभाषित करता है कि दो विशिष्ट \"TextType\" उदाहरण असमान हैं या नहीं |
|
|  | [hashCode()](#hashCode--) | एक हैश-कोड लौटाता है, जो इस विशिष्ट मान के लिए एक स्थिर संख्या है |
प्रकार
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | TextType मान लौटाता है, जो फ़ाइलनाम एक्सटेंशन के बराबर है, जिसे निर्दिष्ट फ़ाइलनाम से एक्सटेंशन के साथ या शुद्ध एक्सटेंशन से निकाला गया है |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


विशेष मान, जो अपरिभाषित, अज्ञात या असमर्थित पाठ को दर्शाता है
संसाधन


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


पाठ संसाधन का CSS प्रकार


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


पाठ संसाधन का XML प्रकार


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


इस पाठ संसाधन प्रकार का औपचारिक नाम लौटाता है


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


किसी विशेष पाठ का फ़ाइल एक्सटेंशन (प्रारंभिक बिंदु अक्षर के बिना)
संसाधन


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


किसी विशेष पाठ संसाधन प्रकार का MIME कोड


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


निर्धारित करता है कि यह उदाहरण निर्दिष्ट \"TextType\" के बराबर है या नहीं
उदाहरण


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | अन्य TextType उदाहरण, जिसे समानता पर इस के साथ तुलना किया जाना चाहिए |
|

**Returns:**
बूलियन - यदि बराबर हों तो true लौटाता है या यदि असमान हों तो false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि यह उदाहरण निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं,
जो सम्भवतः एक अन्य \"TextType\" उदाहरण है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | अन्य TextType उदाहरण, जो ऑब्जेक्ट में बॉक्स किया गया है |
|

**Returns:**
बूलियन - यदि बराबर हों तो true लौटाता है या यदि असमान हों तो false

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


परिभाषित करता है कि दो विशिष्ट \"TextType\" उदाहरण बराबर हैं या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | पहला TextType उदाहरण |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | दूसरा TextType उदाहरण |
|

**Returns:**
बूलियन - यदि बराबर हों तो true लौटाता है या यदि असमान हों तो false

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


परिभाषित करता है कि दो विशिष्ट \"TextType\" उदाहरण असमान हैं या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | पहला TextType उदाहरण |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | दूसरा TextType उदाहरण |
|

**Returns:**
बूलियन - यदि असमान हों तो true लौटाता है या यदि बराबर हों तो false

### hashCode() {#hashCode--}
```
public int hashCode()
```


एक हैश-कोड लौटाता है, जो इस विशिष्ट मान के लिए एक स्थिर संख्या है
प्रकार


**Returns:**
int - साइन्ड 4-बाइट पूर्णांक संख्या। यदि इस उदाहरण का डिफ़ॉल्ट मान है तो 0 लौटाता है।

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


TextType मान लौटाता है, जो फ़ाइलनाम एक्सटेंशन के बराबर है, जिसे निर्दिष्ट फ़ाइलनाम से एक्सटेंशन के साथ या शुद्ध एक्सटेंशन से निकाला गया है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइलनाम | java.lang.String | फ़ाइलनाम एक्सटेंशन के साथ, यह सापेक्ष या निरपेक्ष पथ हो सकता है, या स्वयं शुद्ध एक्सटेंशन हो सकता है |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure

