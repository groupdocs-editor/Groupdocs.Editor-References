---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "निर्दिष्ट प्रकार के संशोधन से आउटपुट स्प्रेडशीट दस्तावेज़ में एक कार्यपत्र को निर्दिष्ट पासवर्ड के साथ सुरक्षित करने की अनुमति देने वाले कार्यपत्र सुरक्षा विकल्पों को समाहित करता है।"
type: docs
weight: 49
url: /hi/java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

कार्यपत्र सुरक्षा विकल्पों को समाहित करता है, जो एक कार्यपत्र को सुरक्षित करने की अनुमति देते हैं।
आउटपुट स्प्रेडशीट दस्तावेज़ में निर्दिष्ट प्रकार के संशोधन से एक
निर्दिष्ट पासवर्ड।


*** ** * ** ***

XLSX जैसे अधिकांश स्प्रेडशीट फ़ॉर्मेट पासवर्ड के साथ संपादन से कार्यपत्र को सुरक्षित करने की अनुमति देते हैं। यह क्लास ऐसी सुरक्षा को सक्षम करने और इसके विकल्प निर्दिष्ट करने की अनुमति देती है।

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | डिफ़ॉल्ट पैरामीटरों के साथ नया इंस्टेंस बनाता है। |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | निर्दिष्ट कार्यपत्र सुरक्षा प्रकार के साथ नया इंस्टेंस बनाता है और |
पासवर्ड
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | कार्यपत्र सुरक्षा का प्रकार निर्दिष्ट करने की अनुमति देता है। |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | कार्यपत्र सुरक्षा का प्रकार निर्दिष्ट करने की अनुमति देता है। |
|
|  | [getPassword()](#getPassword--) | पासवर्ड, जो कार्यपत्र को सुरक्षित करने के लिए उपयोग किया जाता है। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | पासवर्ड, जो कार्यपत्र को सुरक्षित करने के लिए उपयोग किया जाता है। |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


डिफ़ॉल्ट पैरामीटरों के साथ नया इंस्टेंस बनाता है। यदि संशोधित नहीं किया गया और पास किया गया
SpreadsheetSaveOptions को, तो कोई कार्यपत्र सुरक्षा लागू नहीं होगी


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


निर्दिष्ट कार्यपत्र सुरक्षा प्रकार के साथ नया इंस्टेंस बनाता है और
पासवर्ड


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | protectionType | int | कार्यपत्र सुरक्षा का प्रकार |
|
|  | पासवर्ड | java.lang.String | पासवर्ड, जो सुरक्षा को लॉक करता है |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


कार्यपत्र सुरक्षा का प्रकार निर्दिष्ट करने की अनुमति देता है। डिफ़ॉल्ट रूप से यह 'None' है -
सुरक्षा लागू नहीं होती।


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


कार्यपत्र सुरक्षा का प्रकार निर्दिष्ट करने की अनुमति देता है। डिफ़ॉल्ट रूप से यह 'None' है -
सुरक्षा लागू नहीं होती।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


पासवर्ड, जो कार्यपत्र को सुरक्षित करने के लिए उपयोग किया जाता है। यदि NULL या खाली
स्ट्रिंग है, तो सुरक्षा लागू नहीं होगी।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


पासवर्ड, जो कार्यपत्र को सुरक्षित करने के लिए उपयोग किया जाता है। यदि NULL या खाली
स्ट्रिंग है, तो सुरक्षा लागू नहीं होगी।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

