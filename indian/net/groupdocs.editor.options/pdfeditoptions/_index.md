---
title: "PdfEditOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "PDF दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 1050
url: /hi/net/groupdocs.editor.options/pdfeditoptions/
---
## PdfEditOptions class

PDF दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

```csharp
public sealed class PdfEditOptions : FixedLayoutEditOptionsBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PdfEditOptions](pdfeditoptions#constructor)() | PdfEditOptions क्लास का एक नया उदाहरण बनाता और लौटाता है, जहाँ सभी विकल्प डिफ़ॉल्ट मानों पर सेट होते हैं। |
| [PdfEditOptions](pdfeditoptions#constructor_1)(bool) | निर्दिष्ट पेजिनेशन के साथ PdfEditOptions क्लास का एक नया उदाहरण बनाता और लौटाता है, जबकि अन्य सभी विकल्प डिफ़ॉल्ट रहते हैं। |

## गुण

| नाम | विवरण |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम (true) या अक्षम (false) करने की अनुमति देता है। डिफ़ॉल्ट रूप से अक्षम (false) है। |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | प्रोसेस करने के लिए पेज रेंज सेट करने की अनुमति देता है। डिफ़ॉल्ट रूप से फिक्स्ड‑लेआउट दस्तावेज़ के सभी पेज प्रोसेस किए जाते हैं। |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | इनपुट फिक्स्ड‑लेआउट दस्तावेज़ को परिणामी HTML में बदलते समय छवियों को छोड़ना चाहिए या नहीं, यह दर्शाने वाला फ़्लैग प्राप्त या सेट करता है। डिफ़ॉल्ट false है - छवियों को संरक्षित रखा जाता है। |

### संबंधित देखें

* class [FixedLayoutEditOptionsBase](../fixedlayouteditoptionsbase)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
