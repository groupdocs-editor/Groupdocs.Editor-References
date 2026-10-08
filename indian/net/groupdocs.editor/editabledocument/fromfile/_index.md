---
title: "FromFile"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "स्थैतिक फ़ैक्ट्री जो एक HTML फ़ाइल से EditableDocument का इंस्टेंस बनाती है, जिसे .html फ़ाइल के पथ और लिंक्ड संसाधनों वाले फ़ोल्डर द्वारा निर्दिष्ट किया गया है"
type: docs
weight: 10
url: /hi/net/groupdocs.editor/editabledocument/fromfile/
---
## EditableDocument.FromFile method

स्थैतिक फ़ैक्टरी, जो *.html फ़ाइल के पथ और लिंक्ड संसाधनों वाले फ़ोल्डर द्वारा निर्दिष्ट HTML फ़ाइल से EditableDocument की एक इंस्टेंस बनाती है

```csharp
public static EditableDocument FromFile(string htmlFilePath, string resourceFolderPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| htmlFilePath | String | स्ट्रिंग, जिसमें HTML फ़ाइल का पूर्ण पथ होता है। यह null नहीं हो सकता, वैध फ़ाइल पथ होना चाहिए, और फ़ाइल स्वयं मौजूद होनी चाहिए। |
| resourceFolderPath | String | HTML संसाधनों वाले फ़ोल्डर का वैकल्पिक पथ। यदि NULL है, अमान्य है या ऐसा फ़ोल्डर मौजूद नहीं है, तो एडिटर स्वयं इस फ़ोल्डर को खोजने का प्रयास करेगा, HTML मार्कअप का विश्लेषण करके |

### रिटर्न मान

EditableDocument का नया गैर-NULL उदाहरण

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | HTML फ़ाइल पथ, और/या संसाधन फ़ोल्डर पथ अमान्य है/हैं |
| FileNotFoundException | निर्दिष्ट HTML फ़ाइल नहीं मिली |

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
