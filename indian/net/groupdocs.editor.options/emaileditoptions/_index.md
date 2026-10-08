---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "विभिन्न इलेक्ट्रॉनिक मेल फ़ॉर्मेट में दस्तावेज़ संपादन के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 850
url: /hi/net/groupdocs.editor.options/emaileditoptions/
---
## EmailEditOptions class

विभिन्न इलेक्ट्रॉनिक मेल (email) फॉर्मेट्स में दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

```csharp
public sealed class EmailEditOptions : IEditOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [EmailEditOptions](emaileditoptions#constructor)() | एक नई [`EmailEditOptions`](../emaileditoptions) क्लास का इंस्टेंस इनिशियलाइज़ करता है, जहाँ सभी विकल्प डिफ़ॉल्ट मानों पर सेट होते हैं |
| [EmailEditOptions](emaileditoptions#constructor_1)(MailMessageOutput) | एक नई [`EmailEditOptions`](../emaileditoptions) क्लास का इंस्टेंस [`MailMessageOutput`](./mailmessageoutput) पैरामीटर के साथ इनिशियलाइज़ करता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [MailMessageOutput](../../groupdocs.editor.options/emaileditoptions/mailmessageoutput) { get; set; } | मेल संदेश के किन भागों को आउटपुट [`EditableDocument`](../../groupdocs.editor/editabledocument) में डिलिवर किया जाना चाहिए और फिर उत्पन्न HTML में, इसे नियंत्रित करने की अनुमति देता है। |

### संबंधित देखें

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
