---
title: "SlideNumbersToDelete"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक एरे निर्दिष्ट करने की अनुमति देता है जिसमें 1based स्लाइड नंबर होते हैं, जिन्हें प्रस्तुति को सहेजते समय हटाया जाना चाहिए, यदि संपादित स्लाइड मौजूदा प्रस्तुति में सम्मिलित की गई हो।"
type: docs
weight: 60
url: /hi/net/groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete/
---
## PresentationSaveOptions.SlideNumbersToDelete property

संपादित स्लाइड को मौजूदा प्रेजेंटेशन में सम्मिलित करने की स्थिति में, सहेजते समय प्रेजेंटेशन से हटाए जाने वाले स्लाइडों के 1-आधारित क्रमांक वाली एरे निर्दिष्ट करने की अनुमति देता है।

```csharp
public int[] SlideNumbersToDelete { get; set; }
```

### टिप्पणियाँ

जब संपादित स्लाइड को नई सिंगल-स्लाइड प्रस्तुति (डिफ़ॉल्ट व्यवहार) के रूप में नहीं, बल्कि मौजूदा प्रस्तुति में ([`SlideNumber`](../slidenumber) प्रॉपर्टी का उपयोग करके) सहेजा जाता है, तो इस एरे में उनके नंबर निर्दिष्ट करके इस प्रस्तुति की कुछ विशिष्ट स्लाइडों को हटाना भी संभव है।

डिफ़ॉल्ट रूप से यह एरे `null` है — कोई स्लाइड हटाई नहीं जाएगी। हालांकि, जब यह एरे non-null और non-empty हो, और इसमें कम से कम एक वैध स्लाइड नंबर हो, तो संपादित स्लाइड की सामग्री के साथ आउटपुट Presentation दस्तावेज़ उत्पन्न होने के बाद, निर्दिष्ट नंबर वाली स्लाइडें प्रस्तुति से उस समय हटाई जाएंगी जब उसकी सामग्री को आउटपुट स्ट्रीम या फ़ाइल में लिखा जाएगा।

इस एरे में स्लाइड नंबर 1-आधारित हैं, 0-आधारित नहीं, अमान्य नंबर (1 से कम या कुल स्लाइडों की संख्या से अधिक) को नजरअंदाज किया जाएगा।

### संबंधित देखें

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
