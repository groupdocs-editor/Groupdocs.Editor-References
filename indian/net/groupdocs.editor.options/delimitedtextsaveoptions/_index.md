---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सेपरेटर डिलिमिटर का उपयोग करने वाले टेक्स्ट‑आधारित स्प्रेडशीट दस्तावेज़ CSV, टैब‑आधारित आदि को जनरेट और सेव करने के विकल्प सम्मिलित करता है"
type: docs
weight: 820
url: /hi/net/groupdocs.editor.options/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions class

टेक्स्ट-आधारित स्प्रेडशीट दस्तावेज़ (CSV, टैब-आधारित आदि) को जनरेट और सहेजने के विकल्प शामिल करता है, जो एक विभाजक (डिलिमिटर) का उपयोग करते हैं

```csharp
public sealed class DelimitedTextSaveOptions : ISaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor)() | यह पैरामीटर‑लेस कंस्ट्रक्टर DelimitedTextSaveOptions का नया इंस्टेंस बनाता है जिसमें सेमीकोलन (;) डिफ़ॉल्ट सेपरेटर होता है (फिर [`Separator`](./separator) प्रॉपर्टी के माध्यम से संशोधित किया जा सकता है) |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor_1)(string) | डिलिमिटेड टेक्स्ट के लिए अनिवार्य सेपरेटर (डिलिमिटर) के साथ विकल्प क्लास का इंस्टेंस बनाता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [Encoding](../../groupdocs.editor.options/delimitedtextsaveoptions/encoding) { get; set; } | टेक्स्ट‑आधारित स्प्रेडशीट दस्तावेज़ के लिए एन्कोडिंग सेट करने की अनुमति देता है। डिफ़ॉल्ट रूप से (और यदि निर्दिष्ट नहीं किया गया) UTF8 है। |
| [KeepSeparatorsForBlankRow](../../groupdocs.editor.options/delimitedtextsaveoptions/keepseparatorsforblankrow) { get; set; } | निर्देश करता है कि क्या खाली पंक्ति के लिए सेपरेटर आउटपुट किए जाने चाहिए। डिफ़ॉल्ट मान `false` है, जिसका अर्थ है कि खाली पंक्ति की सामग्री खाली रहेगी। |
| [Separator](../../groupdocs.editor.options/delimitedtextsaveoptions/separator) { get; set; } | टेक्स्ट‑आधारित स्प्रेडशीट दस्तावेज़ों के लिए स्ट्रिंग सेपरेटर (डिलिमिटर) निर्दिष्ट करने की अनुमति देता है |
| [TrimLeadingBlankRowAndColumn](../../groupdocs.editor.options/delimitedtextsaveoptions/trimleadingblankrowandcolumn) { get; set; } | निर्देश करता है कि क्या अग्रणी खाली पंक्तियों और कॉलमों को MS Excel की तरह ट्रिम किया जाना चाहिए |

### टिप्पणियाँ

https://en.wikipedia.org/wiki/Delimiter-separated_values

### संबंधित देखें

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
