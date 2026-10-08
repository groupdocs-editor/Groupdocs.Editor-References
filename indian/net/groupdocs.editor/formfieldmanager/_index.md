---
title: "FormFieldManager"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "Legacy फ़ॉर्म फ़ील्ड्स के साथ फ़ॉर्म प्रबंधित करें। Legacy फ़ॉर्म फ़ील्ड्स वे फ़ील्ड प्रकार हैं जो Word प्रोसेसिंग के पिछले संस्करणों में उपलब्ध थे। Legacy Tools आइकन पर क्लिक करने के बाद दिखाई देने वाला Legacy Forms समूह उन तीन प्रकार के फ़ॉर्म फ़ील्ड्स को शामिल करता है जिन्हें आप दस्तावेज़ में सम्मिलित कर सकते हैं: टेक्स्ट, चेक बॉक्स, ड्रॉपडाउन, तिथि आदि। अधिक देखें FormFieldType../groupdocs.editor.words.fieldmanagement/formfieldtype। इन प्रत्येक फ़ॉर्म फ़ील्ड्स से फ़ॉर्म उपयोगकर्ता को वह प्रकार की जानकारी चुनने या दर्ज करने की अनुमति मिलती है जिसे आप उपयुक्त मानते हैं।"
type: docs
weight: 40
url: /hi/net/groupdocs.editor/formfieldmanager/
---
## FormFieldManager class

Legacy फ़ॉर्म फ़ील्ड्स के साथ फ़ॉर्म प्रबंधित करें। Legacy फ़ॉर्म फ़ील्ड्स वे फ़ील्ड प्रकार हैं जो Word प्रोसेसिंग के पिछले संस्करणों में उपलब्ध थे। Legacy Tools आइकन पर क्लिक करने के बाद दिखाई देने वाला Legacy Forms समूह उन तीन प्रकार के फ़ॉर्म फ़ील्ड्स को शामिल करता है जिन्हें आप दस्तावेज़ में सम्मिलित कर सकते हैं: टेक्स्ट, चेक बॉक्स, ड्रॉप-डाउन, तिथि आदि, अधिक देखें [`FormFieldType`](../../groupdocs.editor.words.fieldmanagement/formfieldtype)। इन प्रत्येक फ़ॉर्म फ़ील्ड्स से फ़ॉर्म उपयोगकर्ता को वह प्रकार की जानकारी चुनने या दर्ज करने की अनुमति मिलती है जिसे आप उपयुक्त मानते हैं।

```csharp
public sealed class FormFieldManager
```

## गुण

| नाम | विवरण |
| --- | --- |
| [FormFieldCollection](../../groupdocs.editor/formfieldmanager/formfieldcollection) { get; } | दस्तावेज़ में फ़ॉर्म फ़ील्ड्स का संग्रह प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [FixInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/fixinvalidformfieldnames)(IEnumerable&lt;InvalidFormField&gt;) | निर्दिष्ट अपडेट लागू करके या स्वचालित रूप से अद्वितीय नाम उत्पन्न करके दस्तावेज़ में अमान्य फ़ॉर्म फ़ील्ड नामों को ठीक करता है। |
| [GetInvalidFormFieldNames](../../groupdocs.editor/formfieldmanager/getinvalidformfieldnames)() | दस्तावेज़ से अमान्य फ़ॉर्म फ़ील्ड नामों का संग्रह प्राप्त करता है। |
| [HasInvalidFormFields](../../groupdocs.editor/formfieldmanager/hasinvalidformfields)() | जाँचता है कि क्या दस्तावेज़ में कोई अमान्य फ़ॉर्म फ़ील्ड्स हैं। |
| [RemoveFormFields](../../groupdocs.editor/formfieldmanager/removeformfields)(IEnumerable&lt;IFormField&gt;) | दस्तावेज़ से कई फ़ॉर्म फ़ील्ड्स को हटाता है। |
| [RemoveFormFiled](../../groupdocs.editor/formfieldmanager/removeformfiled)(IFormField) | दस्तावेज़ से एक विशिष्ट फ़ॉर्म फ़ील्ड को हटाता है। |
| [UpdateFormFiled](../../groupdocs.editor/formfieldmanager/updateformfiled)(FormFieldCollection) | प्रदान किए गए फ़ॉर्म फ़ील्ड्स के संग्रह के आधार पर दस्तावेज़ में फ़ॉर्म फ़ील्ड्स को अपडेट करता है। |

### टिप्पणियाँ

यह [`FormFieldManager`](../formfieldmanager) क्लास दस्तावेज़ में फ़ॉर्म फ़ील्ड्स को संभालने के लिए कार्यक्षमता प्रदान करती है। यह उपयोगकर्ताओं को फ़ॉर्म फ़ील्ड्स को प्राप्त करने, अपडेट करने, ठीक करने, अमान्यता की जाँच करने और हटाने की अनुमति देती है।

### संबंधित देखें

* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
