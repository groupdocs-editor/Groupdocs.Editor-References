---
title: "FromMarkupAndResourceFolder"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "स्थैतिक फ़ैक्ट्री जो निर्दिष्ट HTML मार्कअप और पूर्ण पथ द्वारा निर्दिष्ट फ़ोल्डर में स्थित संसाधनों से EditableDocument का एक उदाहरण बनाती है"
type: docs
weight: 30
url: /hi/net/groupdocs.editor/editabledocument/frommarkupandresourcefolder/
---
## EditableDocument.FromMarkupAndResourceFolder method

स्थैतिक फ़ैक्टरी, जो पूर्ण पथ द्वारा निर्दिष्ट फ़ोल्डर में स्थित संसाधनों और निर्दिष्ट HTML मार्कअप से EditableDocument की एक इंस्टेंस बनाती है

```csharp
public static EditableDocument FromMarkupAndResourceFolder(string newHtmlContent, 
    string resourceFolderPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| newHtmlContent | String | String, जिसमें कच्चा HTML मार्कअप होता है, जिसे पार्स किया जाना चाहिए। NULL, खाली या अमान्य नहीं हो सकता। |
| resourceFolderPath | String | संसाधनों वाले फ़ोल्डर का अनिवार्य पथ। इस फ़ोल्डर में स्थित सभी स्टाइलशीट्स का उपयोग किया जाएगा। NULL या खाली स्ट्रिंग नहीं होनी चाहिए, और यह फ़ोल्डर मौजूद होना चाहिए। |

### रिटर्न मान

EditableDocument का नया गैर-NULL उदाहरण

### टिप्पणियाँ

यह स्थैतिक फ़ैक्ट्री तब उपयोगी होती है जब HTML दस्तावेज़ की सामग्री स्ट्रिंग के रूप में प्रस्तुत की गई हो, लेकिन सभी संसाधन किसी फ़ोल्डर में स्थित हों, और अक्सर HTML मार्कअप में इन संसाधनों के लिंक अमान्य या अनुपस्थित होते हैं। इस विधि को बुलाते समय यह निर्दिष्ट फ़ोल्डर को स्कैन करती है और स्वचालित रूप से पाए गए सभी स्टाइलशीट्स को दस्तावेज़ पर लागू करती है। विभिन्न HTML संपादकों से सामग्री प्राप्त करते समय यह विधि बहुत उपयोगी होती है, जहाँ आमतौर पर दस्तावेज़ मेटाडेटा आदि काट दिया जाता है।

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
