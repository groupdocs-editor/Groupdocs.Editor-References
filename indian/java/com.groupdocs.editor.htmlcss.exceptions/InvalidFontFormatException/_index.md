---
title: "InvalidFontFormatException"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "जब किसी सामग्री को खोलने, लोड करने, सहेजने या प्रोसेस करने की कोशिश की जाती है, जो संभवतः समर्थित ज्ञात फ़ॉर्मेट का फ़ॉन्ट है, लेकिन वास्तव में वह असमर्थित या अप्रत्याशित फ़ॉर्मेट का फ़ॉन्ट है या बिल्कुल फ़ॉन्ट नहीं है, तब फेंकी जाने वाली अपवाद।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

यह अपवाद तब फेंका जाता है जब किसी सामग्री को खोलने, लोड करने, सहेजने या किसी अन्य तरीके से प्रोसेस करने का प्रयास किया जाता है, जो संभवतः समर्थित (ज्ञात) फ़ॉर्मेट का फ़ॉन्ट माना जाता है, लेकिन वास्तव में वह असमर्थित या अप्रत्याशित फ़ॉर्मेट का फ़ॉन्ट है या बिल्कुल भी फ़ॉन्ट नहीं है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | निर्दिष्ट त्रुटि संदेश के साथ नया उदाहरण बनाता है |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | @see \"InvalidFontFormatException\" के साथ निर्दिष्ट त्रुटि संदेश और इस अपवाद का कारण बनने वाले inner exception के संदर्भ के साथ नया उदाहरण बनाता है |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


निर्दिष्ट त्रुटि संदेश के साथ नया उदाहरण बनाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | पाठ संदेश, जो त्रुटि का वर्णन करता है, null या खाली हो सकता है |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


@see \"InvalidFontFormatException\" के साथ निर्दिष्ट त्रुटि संदेश और इस अपवाद का कारण बनने वाले inner exception के संदर्भ के साथ नया उदाहरण बनाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | पाठ संदेश, जो त्रुटि का वर्णन करता है, null या खाली हो सकता है |
|
|  | innerException | java.lang.RuntimeException | वर्तमान अपवाद का कारण बनने वाली अपवाद, या यदि कोई inner exception निर्दिष्ट नहीं किया गया हो तो null संदर्भ। |
|

