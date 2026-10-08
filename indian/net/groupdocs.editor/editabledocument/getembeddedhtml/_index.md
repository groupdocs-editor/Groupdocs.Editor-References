---
title: "GetEmbeddedHtml"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "इस HTML दस्तावेज़ की सभी सामग्री को सभी संबंधित संसाधनों के साथ एकल स्ट्रिंग के रूप में लौटाता है, जहाँ सभी संसाधन HTML मार्कअप के भीतर base64encoded रूप में एम्बेडेड होते हैं।"
type: docs
weight: 150
url: /hi/net/groupdocs.editor/editabledocument/getembeddedhtml/
---
## EditableDocument.GetEmbeddedHtml method

इस HTML दस्तावेज़ की सभी सामग्री को सभी संबंधित संसाधनों के साथ एकल स्ट्रिंग के रूप में लौटाता है, जहाँ सभी संसाधन HTML मार्कअप के भीतर बेस64-एन्कोडेड रूप में एम्बेडेड होते हैं।

```csharp
public string GetEmbeddedHtml()
```

### रिटर्न मान

स्ट्रिंग, जो किसी भी स्थिति में NULL या खाली नहीं है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ObjectDisposedException | यह EditableDocument उदाहरण पहले ही नष्ट कर दिया गया था |

### टिप्पणियाँ

यह विधि इस EditableDocument को HTML में परिवर्तित करती है और इसे एकल स्ट्रिंग में क्रमबद्ध करती है, जहाँ सभी संसाधन स्ट्रिंग में HTML मार्कअप के साथ एम्बेड होते हैं:

* All images from HTML-&gt;BODY are converted to base64 format and are located in the IMG 'src' attribute
* All stylesheets are stored in the STYLE elements inside HTML-&gt;HEAD sections
* All images from stylesheets are converted to base64 format and located in the appropriate CSS declarations
* All fonts from stylesheets are converted to base64 format and located in the appropriate @font-face at-rules

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
