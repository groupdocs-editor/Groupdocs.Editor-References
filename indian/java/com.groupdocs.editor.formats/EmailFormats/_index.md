---
title: "EmailFormats"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सभी ईमेल फ़ॉर्मेट को संलग्न करता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

सभी ईमेल फ़ॉर्मेट को संलग्न करता है। निम्नलिखित फ़ाइल प्रकार शामिल हैं:
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

ईमेल फ़ॉर्मेट के बारे में अधिक जानें [यहाँ](../https://docs.fileformat.com/email/).

<br />


## Fields

| Field | विवरण |
| --- | --- |
|  | [Tnef](#Tnef) | Transport Neutral Encapsulation Format (TNEF) Microsoft का स्वामित्व वाला फ़ॉर्मेट है, जो मैसेजिंग एप्लिकेशन प्रोग्रामिंग इंटरफ़ेस (MAPI) पर आधारित ईमेल अटैचमेंट को संलग्न करने के लिए उपयोग किया जाता है। |
|
|  | [Eml](#Eml) | EML फ़ाइल प्रारूप Outlook और अन्य संबंधित अनुप्रयोगों का उपयोग करके सहेजे गए ईमेल संदेशों का प्रतिनिधित्व करता है। |
|
|  | [Emlx](#Emlx) | EMLX फ़ाइल प्रारूप Apple द्वारा लागू और विकसित किया गया है। |
|
|  | [Msg](#Msg) | MSG वह फ़ाइल प्रारूप है जिसका उपयोग Microsoft Outlook और Exchange द्वारा ईमेल संदेश, संपर्क, नियुक्ति या अन्य कार्यों को संग्रहीत करने के लिए किया जाता है। |
|
|  | [Html](#Html) | HTML स्वरूपित ईमेल। |
|
|  | [Mhtml](#Mhtml) | MHTML, "MIME encapsulation of aggregate HTML documents" का संक्षिप्त रूप है। |
|
|  | [Ics](#Ics) | इंटरनेट कैलेंडरिंग और शेड्यूलिंग कोर ऑब्जेक्ट स्पेसिफिकेशन (iCalendar) एक इंटरनेट मानक (RFC 2445) है जो कैलेंडर इवेंट्स और शेड्यूलिंग के आदान‑प्रदान और तैनाती के लिए उपयोग किया जाता है। |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) या vCard संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल प्रारूप है। |
|
|  | [Pst](#Pst) | .pst एक्सटेंशन वाली फ़ाइलें Outlook पर्सनल स्टोरेज फ़ाइलें (जिसे पर्सनल स्टोरेज टेबल भी कहा जाता है) का प्रतिनिधित्व करती हैं जो उपयोगकर्ता की विभिन्न जानकारी संग्रहीत करती हैं। |
|
|  | [Mbox](#Mbox) | MBox फ़ाइल प्रारूप एक सामान्य शब्द है जो इलेक्ट्रॉनिक मेल संदेशों के संग्रह के लिए कंटेनर का प्रतिनिधित्व करता है। |
|
|  | [Oft](#Oft) | .oft एक्सटेंशन वाली फ़ाइलें टेम्प्लेट फ़ाइलें हैं जो Microsoft Outlook का उपयोग करके बनाई जाती हैं। |
|
|  | [Ost](#Ost) | ऑफ़लाइन स्टोरेज टेबल (OST) फ़ाइल उपयोगकर्ता के मेलबॉक्स डेटा को ऑफ़लाइन मोड में स्थानीय मशीन पर, Microsoft Outlook का उपयोग करके Exchange Server के साथ पंजीकरण के बाद दर्शाती है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getAll()](#getAll--) | सभी [EmailFormats](../../com.groupdocs.editor.formats/emailformats) की एक गणनीय संग्रह प्राप्त करता है। |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार के [EmailFormats](../../com.groupdocs.editor.formats/emailformats) का एक उदाहरण पुनः प्राप्त करता है। |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [EmailFormats](../../com.groupdocs.editor.formats/emailformats) ऑब्जेक्ट में परिवर्तित करता है। |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Transport Neutral Encapsulation Format (TNEF) Microsoft का स्वामित्व वाला फ़ॉर्मेट है, जो मैसेजिंग एप्लिकेशन प्रोग्रामिंग इंटरफ़ेस (MAPI) पर आधारित ईमेल अटैचमेंट को संलग्न करने के लिए उपयोग किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


EML फ़ाइल प्रारूप Outlook और अन्य संबंधित अनुप्रयोगों का उपयोग करके सहेजे गए ईमेल संदेशों का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


EMLX फ़ाइल प्रारूप Apple द्वारा लागू और विकसित किया गया है। Apple Mail एप्लिकेशन ईमेल निर्यात करने के लिए EMLX फ़ाइल प्रारूप का उपयोग करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


MSG वह फ़ाइल प्रारूप है जिसका उपयोग Microsoft Outlook और Exchange द्वारा ईमेल संदेश, संपर्क, नियुक्ति या अन्य कार्यों को संग्रहीत करने के लिए किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


HTML स्वरूपित ईमेल।


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML, "MIME encapsulation of aggregate HTML documents" का संक्षिप्त रूप है।


### Ics {#Ics}
```
public static final EmailFormats Ics
```


इंटरनेट कैलेंडरिंग और शेड्यूलिंग कोर ऑब्जेक्ट स्पेसिफिकेशन (iCalendar) एक इंटरनेट मानक (RFC 2445) है जो कैलेंडर इवेंट्स और शेड्यूलिंग के आदान‑प्रदान और तैनाती के लिए उपयोग किया जाता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (Virtual Card Format) या vCard संपर्क जानकारी संग्रहीत करने के लिए एक डिजिटल फ़ाइल प्रारूप है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


.pst एक्सटेंशन वाली फ़ाइलें Outlook पर्सनल स्टोरेज फ़ाइलें (जिसे पर्सनल स्टोरेज टेबल भी कहा जाता है) का प्रतिनिधित्व करती हैं जो उपयोगकर्ता की विभिन्न जानकारी संग्रहीत करती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


MBox फ़ाइल प्रारूप एक सामान्य शब्द है जो इलेक्ट्रॉनिक मेल संदेशों के संग्रह के लिए कंटेनर का प्रतिनिधित्व करता है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


.oft एक्सटेंशन वाली फ़ाइलें टेम्प्लेट फ़ाइलें हैं जो Microsoft Outlook का उपयोग करके बनाई जाती हैं।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


ऑफ़लाइन स्टोरेज टेबल (OST) फ़ाइल उपयोगकर्ता के मेलबॉक्स डेटा को ऑफ़लाइन मोड में स्थानीय मशीन पर, Microsoft Outlook का उपयोग करके Exchange Server के साथ पंजीकरण के बाद दर्शाती है।
इस फ़ाइल फ़ॉर्मेट के बारे में अधिक जानें
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


सभी [EmailFormats](../../com.groupdocs.editor.formats/emailformats) की एक गणनीय संग्रह प्राप्त करता है।
मान: एक IEnumerable{EmailFormats} जिसमें सभी [EmailFormats](../../com.groupdocs.editor.formats/emailformats) के उदाहरण शामिल हैं।


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


निर्दिष्ट फ़ाइल एक्सटेंशन वाले निर्दिष्ट प्रकार के [EmailFormats](../../com.groupdocs.editor.formats/emailformats) का एक उदाहरण पुनः प्राप्त करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | एक्सटेंशन | java.lang.String | दस्तावेज़ फ़ॉर्मेट का फ़ाइल एक्सटेंशन। |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


फ़ाइल एक्सटेंशन का प्रतिनिधित्व करने वाली स्ट्रिंग को एक [EmailFormats](../../com.groupdocs.editor.formats/emailformats) ऑब्जेक्ट में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | एक्सटेंशन | java.lang.String | परिवर्तित करने के लिए फ़ाइल एक्सटेंशन। यदि एक्सटेंशन में कई बिंदु हों, तो अंतिम बिंदु के बाद का भाग उपयोग किया जाता है। |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

