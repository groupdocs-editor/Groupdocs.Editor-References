---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "XPS XML पेपर स्पेसिफिकेशन्स दस्तावेज़ों को जेनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 1300
url: /hi/net/groupdocs.editor.options/xpssaveoptions/
---
## XpsSaveOptions class

XPS (XML Paper Specifications) दस्तावेज़ उत्पन्न करने और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

```csharp
public sealed class XpsSaveOptions : ISaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/xpssaveoptions/optimizememoryusage) { get; set; } | HTML से दस्तावेज़ जनरेट करने के दौरान मेमोरी ऑप्टिमाइज़ेशन मैकेनिज़्म सक्षम करता है, जो मेमोरी उपयोग कम करने की कीमत पर प्रदर्शन को घटाता है। इस विकल्प को true सेट करने से बड़े दस्तावेज़ जनरेट करते समय मेमोरी खपत में काफी कमी आ सकती है, लेकिन सहेजने के समय धीमा हो जाता है। डिफ़ॉल्ट रूप से false है (बेहतर प्रदर्शन के लिए मेमोरी ऑप्टिमाइज़ेशन अक्षम है)। |

### टिप्पणियाँ

एक XPS फ़ाइल पेज लेआउट फ़ाइलों को दर्शाती है जो माइक्रोसॉफ्ट द्वारा बनाई गई XML पेपर स्पेसिफिकेशन्स पर आधारित होती हैं। इसे EMF फ़ाइल फ़ॉर्मेट के विकल्प के रूप में विकसित किया गया था और यह PDF फ़ाइल फ़ॉर्मेट के समान है, लेकिन दस्तावेज़ के लेआउट, रूप-रंग और प्रिंटिंग जानकारी में XML का उपयोग करता है।

### संबंधित देखें

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
