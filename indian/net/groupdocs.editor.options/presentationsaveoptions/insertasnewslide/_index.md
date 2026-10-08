---
title: "InsertAsNewSlide"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक बूलियन फ़्लैग जो यह निर्दिष्ट करता है कि संपादित स्लाइड को मूल प्रस्तुति में मौजूदा स्लाइड को निर्दिष्ट स्थिति पर SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber प्रॉपर्टी द्वारा बदलना चाहिए या इसे मौजूदा स्लाइड और पिछले स्लाइड के बीच बिना उसकी सामग्री बदले इंजेक्ट करना चाहिए। डिफ़ॉल्ट रूप से यह false है, मौजूदा स्लाइड को बदल दिया जाएगा। यदि SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber प्रॉपर्टी का मान 0 पर सेट है तो यह प्रॉपर्टी अनदेखी की जाएगी।"
type: docs
weight: 20
url: /hi/net/groupdocs.editor.options/presentationsaveoptions/insertasnewslide/
---
## PresentationSaveOptions.InsertAsNewSlide property

एक बूलियन फ़्लैग, जो यह निर्दिष्ट करता है कि संपादित स्लाइड को मूल प्रस्तुति में मौजूदा स्लाइड को उस स्थिति पर, जो [`SlideNumber`](../slidenumber) प्रॉपर्टी द्वारा निर्दिष्ट है, बदलना चाहिए या इसे मौजूदा स्लाइड और पिछले स्लाइड के बीच उसकी सामग्री को बदले बिना इंजेक्ट करना चाहिए। डिफ़ॉल्ट रूप से यह `false` है — मौजूदा स्लाइड को बदल दिया जाएगा। यदि [`SlideNumber`](../slidenumber) प्रॉपर्टी का मान '0' पर सेट है तो यह प्रॉपर्टी अनदेखी की जाएगी।

```csharp
public bool InsertAsNewSlide { get; set; }
```

### टिप्पणियाँ

डिफ़ॉल्ट रूप से स्लाइड को बदल दिया जाता है। इसका मतलब है कि यदि दी गई प्रस्तुति में 5 स्लाइडें हैं, और [`SlideNumber`](../slidenumber)=4 है, तो 4थी स्लाइड को नई संपादित स्लाइड से बदल दिया जाएगा, जबकि प्रस्तुति में कुल स्लाइडों की संख्या (5) अपरिवर्तित रहेगी। हालांकि, यदि इस प्रॉपर्टी का मान true पर सेट किया जाता है, तो नई संपादित स्लाइड को 4थी स्लाइड के रूप में इंजेक्ट किया जाएगा, और सभी बाद की स्लाइडें अंत की ओर शिफ्ट हो जाएँगी: "पुरानी" 4थी स्लाइड 5वीं बन जाएगी, और 5वीं 6वीं बन जाएगी, और प्रस्तुति में कुल स्लाइडों की संख्या एक से बढ़कर 6 हो जाएगी।

### संबंधित देखें

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
