---
title: "ExportCidUrls"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट करता है कि क्या CID ContentID URLs का उपयोग करके MHTML दस्तावेज़ों में शामिल संसाधन (छवियां, फ़ॉन्ट, CSS) को संदर्भित किया जाए। डिफ़ॉल्ट मान false है।"
type: docs
weight: 20
url: /hi/net/groupdocs.editor.options/mhtmlsaveoptions/exportcidurls/
---
## MhtmlSaveOptions.ExportCidUrls property

निर्दिष्ट करता है कि क्या MHTML दस्तावेज़ों में शामिल संसाधनों (छवियां, फ़ॉन्ट, CSS) को संदर्भित करने के लिए CID (Content-ID) URLs का उपयोग किया जाए। डिफ़ॉल्ट मान `false` है।

```csharp
public bool ExportCidUrls { get; set; }
```

### टिप्पणियाँ

डिफ़ॉल्ट रूप से, MHTML दस्तावेज़ों में संसाधनों को फ़ाइल नाम (उदाहरण के लिए, "image.png") द्वारा संदर्भित किया जाता है, जो MIME भागों के "Content-Location" हेडर से मेल खाते हैं। यह विकल्प एक वैकल्पिक विधि सक्षम करता है, जिसमें संसाधन फ़ाइलों के संदर्भ को CID (Content-ID) URLs के रूप में लिखा जाता है (उदाहरण के लिए, "cid:image.png") और यह "Content-ID" हेडर से मेल खाता है।

सिद्धांत में, दोनों संदर्भ विधियों में कोई अंतर नहीं होना चाहिए और दोनों में से कोई भी किसी भी ब्राउज़र या मेल एजेंट में ठीक काम करना चाहिए। व्यवहार में, कुछ एजेंट फ़ाइल नाम द्वारा संसाधनों को प्राप्त करने में विफल होते हैं। यदि आपका ब्राउज़र या मेल एजेंट MTHML दस्तावेज़ में शामिल संसाधनों को लोड करने से इनकार करता है (छवियां नहीं दिखाता या CSS शैली नहीं लोड करता), तो दस्तावेज़ को CID URLs के साथ निर्यात करने का प्रयास करें।

### संबंधित देखें

* class [MhtmlSaveOptions](../../mhtmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
