---
title: SplitHeadingLevel
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: नर्दष्ट करत है क क्य AZW3 ईपुस्तक क समग्र क पैकेजं पर वभजत करन है और यद हँ त शर्षकं क अधकतम स्तर जस पर AZW3 क समग्र क वभजत करन है डफ़ल्ट मन है2 . इसे सेट करन0वभजन क अक्षम कर देग इसलए ईपुस्तक क सभ समग्र क AZW3. के अंदर एक पैकेज में शमल कय जएग
type: docs
weight: 20
url: /hi/net/groupdocs.editor.options/azw3saveoptions/splitheadinglevel/
---
## Azw3SaveOptions.SplitHeadingLevel property

निर्दिष्ट करता है कि क्या AZW3 ई-पुस्तक की सामग्री को पैकेजों पर विभाजित करना है और यदि हाँ, तो शीर्षकों का अधिकतम स्तर जिस पर AZW3 की सामग्री को विभाजित करना है। डिफ़ॉल्ट मान है`2` . इसे सेट करना`0`विभाजन को अक्षम कर देगा, इसलिए ई-पुस्तक की सभी सामग्री को AZW3. के अंदर एक पैकेज में शामिल किया जाएगा

```csharp
public int SplitHeadingLevel { get; set; }
```

### टिप्पणियों

कुछ मामलों में ई-पुस्तक की सामग्री को आउटपुट AZW3 फ़ाइल के अंदर स्थित कई छोटे पैकेजों में विभाजित करना बेहतर होता है। यह गुण नियंत्रित करता है कि क्या ऐसा पृथक्करण किया जाना चाहिए और यदि हाँ, तो कैसे।

जब यह संपत्ति 1 से 9 के मान पर सेट होती है, तो दस्तावेज़ का उपयोग करके स्वरूपित पैराग्राफ में विभाजित हो जाएगा**शीर्षक 1** ,**शीर्षक 2** ,**शीर्षक 3** आदि शैलियों को निर्दिष्ट शीर्ष स्तर तक।

डिफ़ॉल्ट रूप से (का मान`2` ), केवल**शीर्षक 1** और**शीर्षक 2** पैराग्राफ दस्तावेज़ को विभाजित करने का कारण बनते हैं। इस गुण को शून्य पर सेट करने से दस्तावेज़ शीर्षक अनुच्छेदों में विभाजित नहीं होगा।

### यह सभी देखें

* class [Azw3SaveOptions](../../azw3saveoptions)
* नाम स्थान [GroupDocs.Editor.Options](../../azw3saveoptions)
* सभा [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
