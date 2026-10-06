---
title: "InvalidImageFormatException"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "जब किसी सामग्री को खोलने, लोड करने, सहेजने या प्रोसेस करने की कोशिश की जाती है, जो संभवतः एक इमेज (रास्टर या वेक्टर) है, लेकिन वास्तव में वह अप्रत्याशित प्रकार की इमेज है या बिल्कुल इमेज नहीं है, तब फेंकी जाने वाली अपवाद।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

जब खोलने, लोड करने, सहेजने या प्रोसेस करने की कोशिश की जाती है, तब फेंकी जाने वाली अपवाद।
किसी तरह किसी सामग्री, जो संभवतः एक इमेज (रास्टर या वेक्टर) है,
लेकिन वास्तव में वह अप्रत्याशित प्रकार की इमेज है या बिल्कुल इमेज नहीं है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | निर्दिष्ट त्रुटि संदेश के साथ InvalidImageFormatException का नया उदाहरण बनाता है |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | निर्दिष्ट त्रुटि संदेश और innerException के संदर्भ के साथ InvalidImageFormatException का नया उदाहरण बनाता है |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


निर्दिष्ट त्रुटि संदेश के साथ InvalidImageFormatException का नया उदाहरण बनाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | पाठ संदेश, जो त्रुटि का वर्णन करता है, null या खाली हो सकता है |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


निर्दिष्ट त्रुटि संदेश और innerException के संदर्भ के साथ InvalidImageFormatException का नया उदाहरण बनाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | पाठ संदेश, जो त्रुटि का वर्णन करता है, null या खाली हो सकता है |
|
|  | innerException | java.lang.RuntimeException | वर्तमान अपवाद का कारण बनने वाली अपवाद, या यदि कोई inner exception निर्दिष्ट नहीं किया गया हो तो null संदर्भ। |
|

