---
title: "SlideNumber"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "संपादन के लिए खोलने योग्य स्लाइड नंबरों को निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 30
url: /hi/net/groupdocs.editor.options/presentationeditoptions/slidenumber/
---
## PresentationEditOptions.SlideNumber property

संपादन के लिए खोलने योग्य स्लाइड नंबर निर्दिष्ट करने की अनुमति देता है।

```csharp
public int SlideNumber { get; set; }
```

### टिप्पणियाँ

स्लाइड नंबर एक शून्य‑आधारित सूचकांक है जो प्रस्तुति से एक विशिष्ट स्लाइड को संपादन के लिए चुनने और निर्दिष्ट करने की अनुमति देता है। यदि 0 से कम हो तो पहली स्लाइड चयनित होगी (SlideNumber = 0 के समान)। यदि प्रस्तुति में सभी स्लाइडों की संख्या से अधिक हो तो अंतिम स्लाइड चयनित होगी। यदि इनपुट प्रस्तुति में केवल एक ही स्लाइड है, तो यह विकल्प अनदेखा किया जाएगा और वह एकल स्लाइड संपादित होगी। यदि छिपी स्लाइड को संपादन के लिए खोलने का प्रयास किया जाता है, जबकि [`ShowHiddenSlides`](../showhiddenslides) विकल्प 'false' पर सेट है, तो अपवाद फेंका जाएगा।

### संबंधित देखें

* class [PresentationEditOptions](../../presentationeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
