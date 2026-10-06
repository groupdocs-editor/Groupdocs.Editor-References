---
title: "WordProcessingProtection"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "HTML से उत्पन्न WordProcessing दस्तावेज़ के लिए दस्तावेज़ सुरक्षा विकल्पों को संलग्न करता है"
type: docs
weight: 46
url: /hi/java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

WordProcessing दस्तावेज़ के लिए दस्तावेज़ सुरक्षा विकल्पों को संलग्न करता है,
जो HTML से उत्पन्न होता है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | बिना पैरामीटर वाला कंस्ट्रक्टर - सभी पैरामीटर डिफ़ॉल्ट मान रखते हैं |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | क्लास इंस्टैंसिएशन के दौरान सभी पैरामीटर सेट करने की अनुमति देता है |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | दस्तावेज़ के सुरक्षा प्रकार को सेट करने की अनुमति देता है। |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | दस्तावेज़ के सुरक्षा प्रकार को सेट करने की अनुमति देता है। |
|
|  | [getPassword()](#getPassword--) | दस्तावेज़ को सुरक्षित करने के लिए पासवर्ड। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | दस्तावेज़ को सुरक्षित करने के लिए पासवर्ड। |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


बिना पैरामीटर वाला कंस्ट्रक्टर - सभी पैरामीटर डिफ़ॉल्ट मान रखते हैं


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


क्लास इंस्टैंसिएशन के दौरान सभी पैरामीटर सेट करने की अनुमति देता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | protectionType | int | दस्तावेज़ की सुरक्षा प्रकार सेट करें |
|
|  | पासवर्ड | java.lang.String | सुरक्षा पासवर्ड सेट करें |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


दस्तावेज़ का सुरक्षा प्रकार सेट करने की अनुमति देता है। डिफ़ॉल्ट रूप से इसे नहीं सेट किया गया है
दस्तावेज़ को बिल्कुल भी सुरक्षित नहीं करता।


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


दस्तावेज़ का सुरक्षा प्रकार सेट करने की अनुमति देता है। डिफ़ॉल्ट रूप से इसे नहीं सेट किया गया है
दस्तावेज़ को बिल्कुल भी सुरक्षित नहीं करता।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


दस्तावेज़ को सुरक्षित करने के लिए पासवर्ड। यदि null या खाली स्ट्रिंग है - तो
सुरक्षा दस्तावेज़ पर लागू नहीं होगी।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


दस्तावेज़ को सुरक्षित करने के लिए पासवर्ड। यदि null या खाली स्ट्रिंग है - तो
सुरक्षा दस्तावेज़ पर लागू नहीं होगी।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
