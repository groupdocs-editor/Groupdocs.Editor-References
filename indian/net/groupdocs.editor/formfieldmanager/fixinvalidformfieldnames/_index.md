---
title: "FixInvalidFormFieldNames"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट अपडेट लागू करके या स्वचालित रूप से अद्वितीय नाम उत्पन्न करके दस्तावेज़ में अमान्य फ़ॉर्म फ़ील्ड नामों को ठीक करता है।"
type: docs
weight: 20
url: /hi/net/groupdocs.editor/formfieldmanager/fixinvalidformfieldnames/
---
## FormFieldManager.FixInvalidFormFieldNames method

निर्दिष्ट अपडेट लागू करके या स्वचालित रूप से अद्वितीय नाम उत्पन्न करके दस्तावेज़ में अमान्य फ़ॉर्म फ़ील्ड नामों को ठीक करता है।

```csharp
public void FixInvalidFormFieldNames(IEnumerable<InvalidFormField> updateInvalidFormFieldNames)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| updateInvalidFormFieldNames | IEnumerable`1 | अमान्य फ़ॉर्म फ़ील्ड नामों के लिए अपडेट्स का एक संग्रह। प्रत्येक अपडेट में फ़ॉर्म फ़ील्ड का मूल नाम और उसका संबंधित नया नाम शामिल होता है। यदि खाली छोड़ दिया जाए, तो अमान्य फ़ॉर्म फ़ील्ड नामों को स्वचालित रूप से अद्वितीय बनाने के लिए पुनःनामित किया जाएगा। |

### टिप्पणियाँ

`FixInvalidFormFieldNames` मेथड दस्तावेज़ के फ़ॉर्म फ़ील्ड्स में नामकरण टकराव या असंगतियों को *updateInvalidFormFieldNames* संग्रह में निर्दिष्ट अपडेट्स लागू करके, या यदि संग्रह खाली है तो स्वचालित रूप से अद्वितीय नाम उत्पन्न करके हल करता है। यह मेथड तब उपयोगी होता है जब कुछ फ़ॉर्म फ़ील्ड नाम अमान्य या दस्तावेज़ के अन्य तत्वों के साथ टकराव में हों, और सही कार्यक्षमता सुनिश्चित करने के लिए उन्हें सुधारा जाना आवश्यक हो। ; ;

### संबंधित देखें

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
