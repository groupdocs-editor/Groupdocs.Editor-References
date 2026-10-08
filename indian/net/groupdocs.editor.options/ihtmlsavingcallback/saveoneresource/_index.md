---
title: "SaveOneResource"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "इंस्टेंस मेथड जो Savegroupdocs.editor/editabledocument/save मेथड कॉल के दौरान ट्रिगर होता है और जिसे अंतिम उपयोगकर्ता को प्रदान किए गए HTML संसाधन को प्राप्त करने और सहेजने के लिए लागू करना आवश्यक है, तथा इस संसाधन के लिए एक लिंक वापस कॉलर को लौटाना होता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.editor.options/ihtmlsavingcallback/saveoneresource/
---
## IHtmlSavingCallback.SaveOneResource method

इंस्टेंस मेथड, जो [`Save`](../../../groupdocs.editor/editabledocument/save) मेथड कॉल के दौरान ट्रिगर होता है और जिसे अंतिम‑उपयोगकर्ता को प्रदान किए गए HTML संसाधन को प्राप्त करने और सहेजने के लिए लागू करना आवश्यक है, तथा इस संसाधन के लिए एक लिंक वापस कॉलर को लौटाना होता है।

```csharp
public string SaveOneResource(IHtmlResource resource)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| संसाधन | IHtmlResource | किसी भी प्रकार का HTML संसाधन (छवियाँ और फ़ॉन्ट्स, संभवतः स्टाइलशीट्स यदि वे HTML मार्कअप में एम्बेड नहीं हैं), जिसे GroupDocs.Editor इस इंटरफ़ेस की उपयोगकर्ता‑परिभाषित इम्प्लीमेंटेशन को पास करता है, उपयोगकर्ता द्वारा प्राप्त किया जाता है, और उपयोगकर्ता इसे सहेजने, भेजने, परिवर्तित करने आदि जैसी आवश्यक प्रक्रियाएँ कर सकता है। GroupDocs.Editor इस मेथड को कभी भी `null` HTML संसाधन नहीं पास करेगा। |

### रिटर्न मान

*resource* पैरामीटर में प्राप्त संसाधन का एक लिंक (संदर्भ), जिसे उपयोगकर्ता को GroupDocs.Editor को प्रदान करना आवश्यक है, ताकि GroupDocs.Editor इस लिंक को HTML मार्कअप में रखेगा।

### टिप्पणियाँ

GroupDocs.Editor अपेक्षा करता है कि इस मेथड की उपयोगकर्ता‑परिभाषित इम्प्लीमेंटेशन निष्पादन के दौरान अपवाद न फेंके। हालांकि, जब अपवाद होते हैं, तो GroupDocs.Editor HTML मार्कअप में [`FilenameWithExtension`](../../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) प्रॉपर्टी का मान लिखेगा।

### संबंधित देखें

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
