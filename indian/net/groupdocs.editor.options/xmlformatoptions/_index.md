---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "XML दस्तावेज़ को HTML के रूप में प्रस्तुत करने पर उसके फ़ॉर्मेटिंग को समायोजित करने के विकल्प शामिल हैं"
type: docs
weight: 1280
url: /hi/net/groupdocs.editor.options/xmlformatoptions/
---
## XmlFormatOptions class

जब XML दस्तावेज़ को HTML के रूप में प्रस्तुत किया जाता है, तो उसके फ़ॉर्मेटिंग को समायोजित करने के विकल्प शामिल करता है

```csharp
public sealed class XmlFormatOptions : IEditOptions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [EachAttributeFromNewline](../../groupdocs.editor.options/xmlformatoptions/eachattributefromnewline) { get; set; } | सक्षम होने पर, प्रत्येक XML तत्व में प्रत्येक गुण‑मान जोड़ी नई पंक्ति में रखी जाएगी। डिफ़ॉल्ट रूप से यह फ़ॉल्स (असक्षम) है — सभी गुण‑मान जोड़े एक ही पंक्ति में रखे जाते हैं। |
| [IsDefault](../../groupdocs.editor.options/xmlformatoptions/isdefault) { get; } | यह दर्शाता है कि इस XML फ़ॉर्मेटिंग विकल्प के उदाहरण में डिफ़ॉल्ट मान है या नहीं |
| [LeafTextNodesOnNewline](../../groupdocs.editor.options/xmlformatoptions/leaftextnodesonnewline) { get; set; } | सक्षम होने पर, लीफ़ टेक्स्ट नोड्स (XML तत्वों के भीतर का पाठ्य सामग्री, जिसके कोई चाइल्ड नहीं होते) नई पंक्ति में बड़े बाएँ इंडेंट के साथ प्रदर्शित होंगे। डिफ़ॉल्ट रूप से यह फ़ॉल्स (असक्षम) है — लीफ़ टेक्स्ट नोड्स अपने पैरेंट के समान पंक्ति में रखे जाते हैं, बिना नए इंडेंट के। |
| [LeftIndent](../../groupdocs.editor.options/xmlformatoptions/leftindent) { get; set; } | प्रत्येक नई पंक्ति के बाएँ इंडेंट के लिए ऑफ़सेट निर्दिष्ट करने की अनुमति देता है। यह शून्य‑रहित इकाई‑रहित मान नहीं हो सकता। डिफ़ॉल्ट रूप से यह 10pt है। |

### संबंधित देखें

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
