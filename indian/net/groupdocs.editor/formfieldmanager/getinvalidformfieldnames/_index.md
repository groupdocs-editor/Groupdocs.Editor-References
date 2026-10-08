---
title: "GetInvalidFormFieldNames"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "दस्तावेज़ से अमान्य फ़ॉर्म फ़ील्ड नामों का संग्रह प्राप्त करता है।"
type: docs
weight: 30
url: /hi/net/groupdocs.editor/formfieldmanager/getinvalidformfieldnames/
---
## FormFieldManager.GetInvalidFormFieldNames method

दस्तावेज़ से अमान्य फ़ॉर्म फ़ील्ड नामों का संग्रह प्राप्त करता है।

```csharp
public IEnumerable<InvalidFormField> GetInvalidFormFieldNames()
```

### रिटर्न मान

दस्तावेज़ में पाए गए अमान्य फ़ॉर्म फ़ील्ड्स के नामों का प्रतिनिधित्व करने वाली स्ट्रिंग्स का एक एनेमरेबल संग्रह।

### टिप्पणियाँ

`GetInvalidFormFieldNames` मेथड दस्तावेज़ की सामग्री को स्कैन करता है ताकि अमान्य नामों वाले फ़ॉर्म फ़ील्ड्स की पहचान की जा सके। यह उन अमान्य फ़ॉर्म फ़ील्ड्स के नामों वाली स्ट्रिंग्स का एक संग्रह लौटाता है। एक फ़ॉर्म फ़ील्ड को तब अमान्य माना जाता है जब वह अन्य फ़ॉर्म फ़ील्ड्स के साथ एक अद्वितीय पहचानकर्ता को दोहराता है और उसके साथ कोई अद्वितीय बुकमार्क नाम नहीं जुड़ा होता। ये बुकमार्क नाम प्रत्येक फ़ॉर्म फ़ील्ड के पहचानकर्ता के रूप में कार्य करते हैं। लौटाया गया संग्रह दस्तावेज़ में दिखाई देने के क्रम में फ़ॉर्म फ़ील्ड नामों को बनाए रखता है। यह मेथड फ़ॉर्म फ़ील्ड्स में नामकरण समस्याओं का पता लगाने और उनका विश्लेषण करने में उपयोगी है, जिन्हें संभवतः [`FixInvalidFormFieldNames`](../fixinvalidformfieldnames) मेथड का उपयोग करके संबोधित किया जा सकता है।

### संबंधित देखें

* class [InvalidFormField](../../../groupdocs.editor.words.fieldmanagement/invalidformfield)
* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
