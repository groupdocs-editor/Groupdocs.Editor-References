---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "समग्र HTML दस्तावेज़ों की MHTML MIME संलग्नक को उत्पन्न करने और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 1020
url: /hi/net/groupdocs.editor.options/mhtmlsaveoptions/
---
## MhtmlSaveOptions class

MHTML (MIME एन्कैप्सुलेशन ऑफ एग्रीगेट HTML डॉक्यूमेंट्स) दस्तावेज़ों को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

```csharp
public sealed class MhtmlSaveOptions : ISaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MhtmlSaveOptions](mhtmlsaveoptions)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [ExportCidUrls](../../groupdocs.editor.options/mhtmlsaveoptions/exportcidurls) { get; set; } | निर्दिष्ट करता है कि क्या MHTML दस्तावेज़ों में शामिल संसाधनों (छवियां, फ़ॉन्ट, CSS) को संदर्भित करने के लिए CID (Content-ID) URLs का उपयोग किया जाए। डिफ़ॉल्ट मान `false` है। |
| [ExportDocumentProperties](../../groupdocs.editor.options/mhtmlsaveoptions/exportdocumentproperties) { get; set; } | निर्दिष्ट करता है कि क्या अंतर्निहित और कस्टम दस्तावेज़ गुणों को MHTML में निर्यात किया जाए। डिफ़ॉल्ट मान `false` है। |
| [ExportLanguageInformation](../../groupdocs.editor.options/mhtmlsaveoptions/exportlanguageinformation) { get; set; } | निर्दिष्ट करता है कि क्या भाषा जानकारी को MHTML में निर्यात किया जाए। डिफ़ॉल्ट मान `false` है। |

### संबंधित देखें

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
