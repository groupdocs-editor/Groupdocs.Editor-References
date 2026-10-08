---
title: "पासवर्ड"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "प्रेजेंटेशन दस्तावेज़ को खोलने के लिए उपयोग किया जाने वाला पासवर्ड निर्दिष्ट करने, संशोधित करने और प्राप्त करने की अनुमति देता है यदि वह एन्कोडेड हो। पासवर्ड हटाने के लिए NULL या खाली स्ट्रिंग सेट करें।"
type: docs
weight: 20
url: /hi/net/groupdocs.editor.options/presentationloadoptions/password/
---
## PresentationLoadOptions.Password property

यदि एन्कोडेड हो तो Presentation दस्तावेज़ खोलने के लिए उपयोग किए जाने वाले पासवर्ड को निर्दिष्ट, संशोधित और प्राप्त करने की अनुमति देता है। पासवर्ड हटाने के लिए NULL या खाली स्ट्रिंग सेट करें।

```csharp
public string Password { get; set; }
```

### टिप्पणियाँ

डिफ़ॉल्ट रूप से इस प्रॉपर्टी का मान NULL है — पासवर्ड सेट नहीं है। यदि इनपुट प्रेजेंटेशन दस्तावेज़ पासवर्ड-संरक्षित है, तो पासवर्ड अनिवार्य है और यदि पासवर्ड निर्दिष्ट नहीं किया गया या अमान्य है तो अपवाद फेंका जाएगा। यदि इनपुट प्रेजेंटेशन दस्तावेज़ पासवर्ड-संरक्षित नहीं है, लेकिन पासवर्ड सेट किया गया है, तो उसे अनदेखा किया जाएगा।

### संबंधित देखें

* class [PresentationLoadOptions](../../presentationloadoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
