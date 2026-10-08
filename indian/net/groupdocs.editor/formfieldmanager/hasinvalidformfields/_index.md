---
title: "HasInvalidFormFields"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "जाँचता है कि क्या दस्तावेज़ में कोई अमान्य फ़ॉर्म फ़ील्ड्स हैं।"
type: docs
weight: 40
url: /hi/net/groupdocs.editor/formfieldmanager/hasinvalidformfields/
---
## FormFieldManager.HasInvalidFormFields method

जाँचता है कि क्या दस्तावेज़ में कोई अमान्य फ़ॉर्म फ़ील्ड्स हैं।

```csharp
public bool HasInvalidFormFields()
```

### रिटर्न मान

`true` यदि दस्तावेज़ में एक या अधिक अमान्य फ़ॉर्म फ़ील्ड्स हैं; अन्यथा, `false`।

### टिप्पणियाँ

`HasInvalidFormFields` मेथड दस्तावेज़ की सामग्री को स्कैन करता है ताकि यह निर्धारित किया जा सके कि इसमें कोई भी फ़ॉर्म फ़ील्ड्स हैं जिनके नाम अमान्य हैं या नहीं। एक फ़ॉर्म फ़ील्ड को तब अमान्य माना जाता है जब वह अन्य फ़ॉर्म फ़ील्ड्स के साथ एक अद्वितीय पहचानकर्ता को दोहराता है और उसके साथ कोई अद्वितीय बुकमार्क नाम नहीं जुड़ा होता। ये बुकमार्क नाम प्रत्येक फ़ॉर्म फ़ील्ड के पहचानकर्ता के रूप में कार्य करते हैं। यह मेथड जल्दी से यह जांचने में उपयोगी है कि क्या दस्तावेज़ को आगे निरीक्षण और फ़ॉर्म फ़ील्ड नामों के संभावित सुधार की आवश्यकता है। ; ; ;

### संबंधित देखें

* class [FormFieldManager](../../formfieldmanager)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
