---
title: "FontType"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "एक समर्थित फ़ॉन्ट प्रकार को दर्शाता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

एक समर्थित फ़ॉन्ट प्रकार को दर्शाता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FontType()](#FontType--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | विशेष मान, जो अपरिभाषित, अज्ञात या असमर्थित फ़ॉन्ट को दर्शाता है |
संसाधन
|
|  | [getWoff()](#getWoff--) | WOFF (Web Open Font Format) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है |
|
|  | [getWoff2()](#getWoff2--) | WOFF2 (Web Open Font Format version 2) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है |
|
|  | [getTtf()](#getTtf--) | TTF (TrueType Font) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है |
|
|  | [getOtf()](#getOtf--) | OTF (OpenType Font) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है |
|
|  | [getTtc()](#getTtc--) | TrueType Collection (TTC) फ़ॉन्ट का प्रतिनिधित्व करता है |
|
|  | [getEot()](#getEot--) | EOT (Embedded OpenType) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है |
|
|  | [getCssName()](#getCssName--) | इस फ़ॉन्ट प्रकार का CSS-संगत नाम लौटाता है, जो इस में उपयोग किया जाता है |
|
|  | [getFormalName()](#getFormalName--) | इस फ़ॉन्ट प्रकार का औपचारिक नाम लौटाता है |
|
|  | [getFileExtension()](#getFileExtension--) | इस फ़ॉन्ट प्रकार के लिए फ़ाइलनाम विस्तार (बिंदु अक्षर के बिना) |
|
|  | [getFontFormat()](#getFontFormat--) | @font-face फ़ॉर्मेट के लिए फ़ॉन्ट फ़ॉर्मेट |
|
|  | [getMimeCode()](#getMimeCode--) | किसी विशिष्ट फ़ॉन्ट प्रकार का MIME कोड |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | FontType मान लौटाता है, जो निर्दिष्ट CSS-संगत के बराबर है |
फ़ॉन्ट प्रकार का नाम
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | FontType मान लौटाता है, जो फ़ाइलनाम विस्तार के बराबर है, जो |
निर्दिष्ट फ़ाइलनाम से निकाला गया है
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | FontType मान लौटाता है, जो निर्दिष्ट MIME-कोड के बराबर है |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | निर्दिष्ट सेट से पहला फ़ॉन्ट प्रकार लौटाता है, जो "Undefined" नहीं है |
मान, या अन्यथा "Undefined" फ़ॉन्ट प्रकार (जब सभी आइटम हैं
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "FontType" के बराबर है या नहीं |
उदाहरण
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि यह उदाहरण निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं, |
जो संभवतः एक अन्य "FontType" इंस्टेंस है
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | जाँचता है कि दो "FontType" मान बराबर हैं या नहीं |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | जाँचता है कि दो "FontType" मान बराबर नहीं हैं |
|
|  | [hashCode()](#hashCode--) | एक हैश-कोड लौटाता है, जो इस विशिष्ट मान के लिए एक स्थिर संख्या है |
प्रकार
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


विशेष मान, जो अपरिभाषित, अज्ञात या असमर्थित फ़ॉन्ट को दर्शाता है
संसाधन


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


WOFF (Web Open Font Format) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


WOFF2 (Web Open Font Format version 2) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


TTF (TrueType Font) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


OTF (OpenType Font) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


TrueType Collection (TTC) फ़ॉन्ट का प्रतिनिधित्व करता है


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


EOT (Embedded OpenType) फ़ॉन्ट प्रकार का प्रतिनिधित्व करता है


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


इस फ़ॉन्ट प्रकार का CSS-संगत नाम लौटाता है, जो इस में उपयोग किया जाता है


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


इस फ़ॉन्ट प्रकार का औपचारिक नाम लौटाता है


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


इस फ़ॉन्ट प्रकार के लिए फ़ाइलनाम विस्तार (बिंदु अक्षर के बिना)


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


@font-face फ़ॉर्मेट के लिए फ़ॉन्ट फ़ॉर्मेट


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


किसी विशिष्ट फ़ॉन्ट प्रकार का MIME कोड


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


FontType मान लौटाता है, जो निर्दिष्ट CSS-संगत के बराबर है
फ़ॉन्ट प्रकार का नाम


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | फ़ॉन्ट प्रकार का CSS-संगत नाम |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


FontType मान लौटाता है, जो फ़ाइलनाम विस्तार के बराबर है, जो
निर्दिष्ट फ़ाइलनाम से निकाला गया है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ाइलनाम | java.lang.String | फ़ाइलनाम विस्तार के साथ, यह पूर्ण नाम भी हो सकता है |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


FontType मान लौटाता है, जो निर्दिष्ट MIME-कोड के बराबर है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | mimeCode | java.lang.String | MIME-कोड |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


निर्दिष्ट सेट से पहला फ़ॉन्ट प्रकार लौटाता है, जो "Undefined" नहीं है
मान, या अन्यथा "Undefined" फ़ॉन्ट प्रकार (जब सभी आइटम हैं
"Undefined")


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | एक या अधिक FontType मान, NULL या खाली संग्रह की अनुमति नहीं है |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


निर्धारित करता है कि यह इंस्टेंस निर्दिष्ट "FontType" के बराबर है या नहीं
उदाहरण


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | इसके साथ जाँचने के लिए अन्य FontType इंस्टेंस |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि यह उदाहरण निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है या नहीं,
जो संभवतः एक अन्य "FontType" इंस्टेंस है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | obj | java.lang.Object | अन्य इंस्टेंस संभवतः FontType स्ट्रक्ट का, जिसे System.Object में बॉक्स किया गया था |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


जाँचता है कि दो "FontType" मान बराबर हैं या नहीं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | जाँचने के लिए पहला FontType |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | जाँचने के लिए दूसरा FontType |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


जाँचता है कि दो "FontType" मान बराबर नहीं हैं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | जाँचने के लिए पहला FontType |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | जाँचने के लिए दूसरा FontType |
|

**Returns:**
boolean - यदि बराबर हों तो True, यदि असमान हों तो false

### hashCode() {#hashCode--}
```
public int hashCode()
```


एक हैश-कोड लौटाता है, जो इस विशिष्ट मान के लिए एक स्थिर संख्या है
प्रकार


**Returns:**
int - 4-बाइट साइन्ड इंटीजर, Undefined मान के लिए 0

