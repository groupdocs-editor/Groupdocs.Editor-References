---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "प्रेजेंटेशन PowerPoint संगत दस्तावेज़ों को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 1100
url: /hi/net/groupdocs.editor.options/presentationsaveoptions/
---
## PresentationSaveOptions class

प्रेजेंटेशन (PowerPoint-समर्थित) दस्तावेज़ों को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

```csharp
public sealed class PresentationSaveOptions : ISaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PresentationSaveOptions](presentationsaveoptions#constructor)() | यह पैरामीटररहित कंस्ट्रक्टर PresentationSaveOptions का नया इंस्टेंस PPTX आउटपुट फ़ॉर्मेट के साथ बनाता है (फिर इसे [`OutputFormat`](./outputformat) प्रॉपर्टी के माध्यम से संशोधित किया जा सकता है)। |
| [PresentationSaveOptions](presentationsaveoptions#constructor_1)(PresentationFormats) | निर्दिष्ट अनिवार्य प्रेजेंटेशन आउटपुट फ़ॉर्मेट के साथ PresentationSaveOptions का नया इंस्टेंस बनाता है, जबकि सभी अन्य पैरामीटर डिफ़ॉल्ट होते हैं। |

## गुण

| नाम | विवरण |
| --- | --- |
| [InsertAsNewSlide](../../groupdocs.editor.options/presentationsaveoptions/insertasnewslide) { get; set; } | बूलियन फ़्लैग, जो यह निर्दिष्ट करता है कि संपादित स्लाइड को मूल प्रेजेंटेशन में निर्दिष्ट स्थिति पर मौजूद स्लाइड को बदलना चाहिए या इसे मौजूदा स्लाइड और पिछले स्लाइड के बीच बिना उसकी सामग्री बदले सम्मिलित करना चाहिए, जहाँ स्थिति [`SlideNumber`](./slidenumber) प्रॉपर्टी द्वारा निर्दिष्ट होती है। डिफ़ॉल्ट रूप से `false` है — मौजूदा स्लाइड को बदला जाएगा। यह प्रॉपर्टी तब अनदेखी की जाती है जब [`SlideNumber`](./slidenumber) प्रॉपर्टी का मान `'0'` पर सेट किया जाता है। |
| [OutputFormat](../../groupdocs.editor.options/presentationsaveoptions/outputformat) { get; set; } | प्रेजेंटेशन फ़ॉर्मेट निर्दिष्ट करने की अनुमति देता है, जिसका उपयोग दस्तावेज़ को सहेजने के लिए किया जाएगा। |
| [Password](../../groupdocs.editor.options/presentationsaveoptions/password) { get; set; } | परिणामी प्रेजेंटेशन दस्तावेज़ को एन्कोड करने के लिए उपयोग किए जाने वाले पासवर्ड को निर्दिष्ट, संशोधित और प्राप्त करने की अनुमति देता है। डिफ़ॉल्ट रूप से NULL है - पासवर्ड सेट नहीं होगा। यदि पहले सेट किया गया हो तो पासवर्ड हटाने के लिए इसे NULL या खाली स्ट्रिंग पर सेट करें। |
| [SlideNumber](../../groupdocs.editor.options/presentationsaveoptions/slidenumber) { get; set; } | नए सिंगल-स्लाइड प्रेजेंटेशन (डिफ़ॉल्ट व्यवहार) बनाने के बजाय संपादित स्लाइड को मौजूदा प्रेजेंटेशन में सम्मिलित करने की अनुमति देता है। स्लाइड नंबर प्रेजेंटेशन में स्लाइड का 1-आधारित क्रमांक है, जो Editor क्लास में लोड किया गया है। यदि यह 0 (डिफ़ॉल्ट मान) है, तो नया प्रेजेंटेशन एकल संपादित स्लाइड के साथ बनाया जाएगा। यदि यह शून्य से बड़ा या छोटा है, और Editor क्लास में वैध प्रेजेंटेशन लोड है, तो इनपुट EditableDocument इंस्टेंस में संग्रहीत संपादित स्लाइड इस प्रेजेंटेशन में सम्मिलित की जाएगी। |
| [SlideNumbersToDelete](../../groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete) { get; set; } | संपादित स्लाइड को मौजूदा प्रेजेंटेशन में सम्मिलित करने की स्थिति में, सहेजते समय प्रेजेंटेशन से हटाए जाने वाले स्लाइडों के 1-आधारित क्रमांक वाली एरे निर्दिष्ट करने की अनुमति देता है। |

### टिप्पणियाँ

इस क्लास का इंस्टेंस कुछ प्रेजेंटेशन-विशिष्ट फ़ॉर्मेट के अंतिम दस्तावेज़ में संपादित प्रेजेंटेशन को सहेजने के लिए मेथड में पास किया जाना चाहिए। सभी अन्य पैरामीटर वैकल्पिक हैं और छोड़े जा सकते हैं, डिफ़ॉल्ट रूप से सहेजे जाने वाले प्रेजेंटेशन का फ़ॉर्मेट PPTX है, लेकिन इसे कंस्ट्रक्टर या प्रॉपर्टी के माध्यम से बदला जा सकता है।

### संबंधित देखें

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
