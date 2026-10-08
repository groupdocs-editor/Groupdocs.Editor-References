---
title: "ExportImagesAsBase64"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट करता है कि छवियों को आउटपुट फ़ाइल में Base64 फ़ॉर्मेट में सहेजा जाए या नहीं। डिफ़ॉल्ट false है।"
type: docs
weight: 20
url: /hi/net/groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64/
---
## MarkdownSaveOptions.ExportImagesAsBase64 property

निर्धारित करता है कि छवियों को आउटपुट फ़ाइल में Base64 फ़ॉर्मेट में सहेजा जाए या नहीं। डिफ़ॉल्ट `false` है।

```csharp
public bool ExportImagesAsBase64 { get; set; }
```

### टिप्पणियाँ

जब यह प्रॉपर्टी `true` पर सेट की जाती है, तो इमेज डेटा सीधे इमेज एलिमेंट्स ![]() में निर्यात हो जाता है और अलग फ़ाइलें नहीं बनतीं। यह प्रॉपर्टी, यदि `true` पर सेट की गई है, तो [`ImagesFolder`](../imagesfolder) प्रॉपर्टी से अधिक प्राथमिकता रखती है।

### संबंधित देखें

* class [MarkdownSaveOptions](../../markdownsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
