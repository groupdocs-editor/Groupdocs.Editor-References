---
title: "RecognizeLists"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "जब दस्तावेज़ सादे टेक्स्ट फ़ॉर्मेट से आयात किया जाता है, तो क्रमांकित सूची आइटम कैसे पहचाने जाएँ, इसे निर्दिष्ट करने की अनुमति देता है। डिफ़ॉल्ट मान true है।"
type: docs
weight: 60
url: /hi/net/groupdocs.editor.options/texteditoptions/recognizelists/
---
## TextEditOptions.RecognizeLists property

जब दस्तावेज़ सादे टेक्स्ट फ़ॉर्मेट से आयात किया जाता है, तो क्रमांकित सूची आइटम कैसे पहचाने जाएँ, इसे निर्दिष्ट करने की अनुमति देता है। डिफ़ॉल्ट मान true है।

```csharp
public bool RecognizeLists { get; set; }
```

### टिप्पणियाँ

यदि यह विकल्प false पर सेट किया जाता है, तो सूची पहचान एल्गोरिद्म सूची पैराग्राफ़ का पता लगाता है, जब सूची संख्याएँ डॉट, दायाँ कोष्ठक या बुलेट प्रतीकों (जैसे "•", "*", "-" या "o") में समाप्त होती हैं। यदि यह विकल्प true पर सेट किया जाता है, तो व्हाइटस्पेस भी सूची संख्या विभाजकों के रूप में उपयोग होते हैं: अरबी शैली की क्रमांकन (1., 1.1.2.) के लिए सूची पहचान एल्गोरिद्म व्हाइटस्पेस और डॉट (".") दोनों का उपयोग करता है।

### संबंधित देखें

* class [TextEditOptions](../../texteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
