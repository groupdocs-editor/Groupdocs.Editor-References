---
title: "GetDocumentInfo"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "इस Editor इंस्टेंस में लोड किए गए दस्तावेज़ के मेटाडाटा को लौटाता है"
type: docs
weight: 70
url: /hi/net/groupdocs.editor/editor/getdocumentinfo/
---
## Editor.GetDocumentInfo method

उस दस्तावेज़ के मेटाडेटा को लौटाता है, जो इस 'Editor' इंस्टेंस में लोड किया गया था।

```csharp
public IDocumentInfo GetDocumentInfo(string password)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| password | String | उपयोगकर्ता दस्तावेज़ के लिए पासवर्ड निर्दिष्ट कर सकता है, यदि यह दस्तावेज़ पासवर्ड से एन्क्रिप्टेड है। यह NULL या खाली स्ट्रिंग हो सकता है, जो अनुपस्थित पासवर्ड के बराबर है। उन दस्तावेज़ फ़ॉर्मेट्स के लिए, जिनमें पासवर्ड सुरक्षा सुविधा नहीं है, यह तर्क अनदेखा किया जाएगा। यदि दस्तावेज़ एन्क्रिप्टेड है, और इस पैरामीटर में पासवर्ड निर्दिष्ट नहीं किया गया है, लेकिन इसे लोड विकल्पों में इस [`Editor`](../../editor) इंस्टेंस को बनाते समय पहले निर्दिष्ट किया गया था, तो इसका उपयोग किया जाएगा। |

### रिटर्न मान

फ़ॉर्मेट-विशिष्ट इनहेरिटर [`IDocumentInfo`](../../../groupdocs.editor.metadata/idocumentinfo) इंटरफ़ेस का, जो पहचाने गए फ़ॉर्मेट को फ़ॉर्मेट-विशिष्ट मेटाडाटा के साथ दर्शाता है, या NULL, यदि दस्तावेज़ को समर्थित के रूप में पहचाना नहीं गया या वह भ्रष्ट है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ObjectDisposedException | जब Editor इंस्टेंस पहले ही डिस्पोज़ हो चुका हो और "GetDocumentInfo" को बुलाया जाए तो फेंका जाता है। |
| [PasswordRequiredException](../../passwordrequiredexception) | जब लोड किया गया दस्तावेज़ पासवर्ड-प्रोटेक्टेड हो, लेकिन पासवर्ड पैरामीटर "*password*" में और निर्माण के दौरान लोडिंग विकल्पों में निर्दिष्ट नहीं किया गया हो तो फेंका जाता है। |
| [IncorrectPasswordException](../../incorrectpasswordexception) | जब लोड किया गया दस्तावेज़ पासवर्ड-प्रोटेक्टेड हो, पासवर्ड निर्दिष्ट किया गया हो, लेकिन वह गलत हो तो फेंका जाता है। |
| InvalidOperationException | जब अज्ञात प्रकृति की अप्रत्याशित त्रुटि हुई हो तो फेंका जाता है। |

### टिप्पणियाँ

GetDocumentInfo मेथड उपयोगी है जब यह स्पष्ट न हो कि इनपुट दस्तावेज़ किस फ़ॉर्मेट का है, क्या वह पासवर्ड-प्रोटेक्टेड है और/या उसमें कितने पृष्ठ/वर्कशीट/स्लाइड हैं। इस मेटाडाटा के आधार पर, जो GetDocumentInfo द्वारा लौटाया जाता है, मुख्य प्रोसेसिंग पाइपलाइन के लिए लोड और एडिट विकल्पों को सही ढंग से समायोजित करना संभव है।

GetDocumentInfo मेथड हमेशा पूर्ण डेटा लौटाता है, यह ट्रायल मोड से प्रभावित नहीं होता, इसका उपयोग उपभोग किए गए बाइट्स या क्रेडिट्स को घटाता नहीं है।

**Learn more**

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Extracting+document+metainfo)

### संबंधित देखें

* interface [IDocumentInfo](../../../groupdocs.editor.metadata/idocumentinfo)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
