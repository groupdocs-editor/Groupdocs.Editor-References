---
title: "SavingCallback"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "इंटरफ़ेस जिसे अंतिम उपयोगकर्ता को सभी बाहरी HTML संसाधनों को सहेजने के लिए लागू करना आवश्यक है। इस प्रॉपर्टी का मान null नहीं होना चाहिए, अन्यथा GroupDocs.Editor HTML फ़ॉर्मेट में EditableDocumentgroupdocs.editor/editabledocument को सहेजते समय अपवाद फेंकेगा।"
type: docs
weight: 50
url: /hi/net/groupdocs.editor.options/htmlsaveoptions/savingcallback/
---
## HtmlSaveOptions.SavingCallback property

इंटरफ़ेस, जिसे अंतिम‑उपयोगकर्ता को सभी बाहरी HTML संसाधनों को सहेजने के लिए लागू करना आवश्यक है। यह प्रॉपर्टी **must** `null` नहीं होना चाहिए, अन्यथा GroupDocs.Editor [`EditableDocument`](../../../groupdocs.editor/editabledocument) को HTML फ़ॉर्मेट में सहेजते समय अपवाद फेंकेगा।

```csharp
public IHtmlSavingCallback SavingCallback { get; set; }
```

### टिप्पणियाँ

यदि [`EmbedStylesheetsIntoMarkup`](../embedstylesheetsintomarkup) प्रॉपर्टी का मान `true` पर सेट किया जाता है, तो सभी स्टाइलशीट्स HTML मार्कअप में एम्बेड हो जाएँगी और इसलिए उन्हें इस सहेजने वाले कॉलबैक को पास नहीं किया जाएगा।

### संबंधित देखें

* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
