---
title: "EnablePagination"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। डिफ़ॉल्ट रूप में अक्षम (false) है।"
type: docs
weight: 30
url: /hi/net/groupdocs.editor.options/ebookeditoptions/enablepagination/
---
## EbookEditOptions.EnablePagination property

परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। डिफ़ॉल्ट रूप से यह अक्षम (`false`) है।

```csharp
public bool EnablePagination { get; set; }
```

### टिप्पणियाँ

मूल रूप से अधिकांश ई-बुक फ़ॉर्मेट आंतरिक रूप से एक फ्लो फ़ॉर्मेट होते हैं जैसे Office Open XML, जहाँ सामग्री एक सतत प्रवाह में होती है और अध्यायों में विभाजित होती है लेकिन पृष्ठों में नहीं। हालांकि, इसमें पृष्ठ‑विशिष्ट जानकारी जैसे पृष्ठ संख्या, फुटनोट, हेडर/फ़ूटर आदि शामिल होते हैं। कुछ ई‑बुक रीडर ई‑बुक सामग्री को पृष्ठों में विभाजित करते हैं, जबकि अन्य (विशेषकर मोबाइल) नहीं करते। यह विकल्प नियंत्रित करता है कि संपादन के दौरान ई‑बुक सामग्री को HTML/CSS में कैसे दर्शाया जाए — फ्लोट (`false`) या पेज्ड (`true`) दृश्य में।

### संबंधित देखें

* class [EbookEditOptions](../../ebookeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
