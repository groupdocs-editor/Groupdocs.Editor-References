---
title: "SplitHeadingLevel"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "eBook फ़ाइल को विभाजित करने के लिए अधिकतम हेडिंग स्तर निर्दिष्ट करता है। डिफ़ॉल्ट मान 2 है। इसे 0 पर सेट करने से विभाजन निष्क्रिय हो जाएगा, जिससे eBook की सभी सामग्री एक ही पैकेज में परिणामी फ़ाइल के अंदर सम्मिलित हो जाएगी।"
type: docs
weight: 40
url: /hi/net/groupdocs.editor.options/ebooksaveoptions/splitheadinglevel/
---
## EbookSaveOptions.SplitHeadingLevel property

e-Book फ़ाइल को विभाजित करने के लिए शीर्षकों के अधिकतम स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान `2` है। इसे `0` पर सेट करने से विभाजन निष्क्रिय हो जाएगा, इसलिए e-Book की सभी सामग्री एक ही पैकेज में सम्मिलित हो जाएगी जो परिणामस्वरूप फ़ाइल में होगी।

```csharp
public int SplitHeadingLevel { get; set; }
```

### टिप्पणियाँ

जब इस प्रॉपर्टी को 1 से 9 के मान पर सेट किया जाता है, तो दस्तावेज़ उन पैराग्राफ़ों पर विभाजित हो जाएगा जो **Heading 1**, **Heading 2**, **Heading 3** आदि शैलियों का उपयोग करते हैं, निर्दिष्ट हेडिंग स्तर तक।

डिफ़ॉल्ट रूप में, केवल **Heading 1** और **Heading 2** पैराग्राफ़ दस्तावेज़ को विभाजित करते हैं। इस प्रॉपर्टी को शून्य (या शून्य से कम) पर सेट करने से दस्तावेज़ हेडिंग पैराग्राफ़ों पर बिल्कुल भी विभाजित नहीं होगा।

### संबंधित देखें

* class [EbookSaveOptions](../../ebooksaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
