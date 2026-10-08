---
title: "Locale"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "WordProcessing दस्तावेज़ के लिए डिफ़ॉल्ट लोकैल भाषा को ओवरराइड करने की अनुमति देता है, जो निर्माण के दौरान लागू होगी। जब निर्दिष्ट नहीं किया जाता है, तो डिफ़ॉल्ट मान MS Word या अन्य प्रोग्राम अपने सेटिंग्स या अन्य कारकों के अनुसार दस्तावेज़ का लोकैल पता लगाएगा या चुनेगा।"
type: docs
weight: 40
url: /hi/net/groupdocs.editor.options/wordprocessingsaveoptions/locale/
---
## WordProcessingSaveOptions.Locale property

WordProcessing दस्तावेज़ के लिए डिफ़ॉल्ट लोकेल (भाषा) को ओवरराइड सेट करने की अनुमति देता है, जो निर्माण के दौरान लागू होगा। जब निर्दिष्ट नहीं किया जाता (डिफ़ॉल्ट मान), तो MS Word (या अन्य प्रोग्राम) अपने सेटिंग्स या अन्य कारकों के अनुसार दस्तावेज़ का लोकेल पहचान (या चुन) लेगा।

```csharp
public CultureInfo Locale { get; set; }
```

### टिप्पणियाँ

यह विकल्प निर्दिष्ट लोकैल को दस्तावेज़ के समग्र टेक्स्ट पर बलपूर्वक लागू करता है। यदि दस्तावेज़ में विभिन्न भाषाओं में लिखे विभिन्न भाग हैं, तो इसका उपयोग न करें।

### संबंधित देखें

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
