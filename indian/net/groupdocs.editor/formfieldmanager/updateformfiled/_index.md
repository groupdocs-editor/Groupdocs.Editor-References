---
title: "UpdateFormFiled"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "प्रदान किए गए फ़ॉर्म फ़ील्ड्स के संग्रह के आधार पर दस्तावेज़ में फ़ॉर्म फ़ील्ड्स को अपडेट करता है।"
type: docs
weight: 70
url: /hi/net/groupdocs.editor/formfieldmanager/updateformfiled/
---
## FormFieldManager.UpdateFormFiled method

प्रदान किए गए फ़ॉर्म फ़ील्ड्स के संग्रह के आधार पर दस्तावेज़ में फ़ॉर्म फ़ील्ड्स को अपडेट करता है।

```csharp
public void UpdateFormFiled(FormFieldCollection formFieldCollection)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| formFieldCollection | FormFieldCollection | दस्तावेज़ पर लागू करने के लिए अपडेट्स वाले फ़ॉर्म फ़ील्ड्स का संग्रह। |

### टिप्पणियाँ

`UpdateFormFiled` मेथड दस्तावेज़ में फ़ॉर्म फ़ील्ड्स को प्रदान की गई *formFieldCollection* के आधार पर अपडेट करता है। संग्रह में प्रत्येक फ़ॉर्म फ़ील्ड दस्तावेज़ में एक फ़ॉर्म फ़ील्ड के अनुरूप होता है, और संग्रह में निर्दिष्ट अपडेट्स उसी अनुसार लागू होते हैं। यह मेथड दस्तावेज़ और बाहरी स्रोत, जैसे उपयोगकर्ता इंटरफ़ेस या डेटाबेस, के बीच फ़ॉर्म फ़ील्ड डेटा को सिंक्रनाइज़ करने में उपयोगी है।

### संबंधित देखें

* class [FormFieldCollection](../../../groupdocs.editor.words.fieldmanagement/formfieldcollection)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
