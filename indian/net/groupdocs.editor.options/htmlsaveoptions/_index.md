---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "EditableDocument../groupdocs.editor/editabledocument इंस्टेंस को HTML फ़ॉर्मेट में सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 900
url: /hi/net/groupdocs.editor.options/htmlsaveoptions/
---
## HtmlSaveOptions class

[`EditableDocument`](../../groupdocs.editor/editabledocument) इंस्टेंस को HTML फ़ॉर्मेट में सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।

```csharp
public sealed class HtmlSaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions)() | डिफ़ॉल्ट कंस्ट्रक्टर। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AttributeValueDelimiter](../../groupdocs.editor.options/htmlsaveoptions/attributevaluedelimiter) { get; set; } | HTML तत्वों में एट्रिब्यूट मानों के चारों ओर कौन सा डिलिमिटर उपयोग किया जाएगा, नियंत्रित करता है: सिंगल कोट (डिफ़ॉल्ट) या डबल कोट। |
| [EmbedStylesheetsIntoMarkup](../../groupdocs.editor.options/htmlsaveoptions/embedstylesheetsintomarkup) { get; set; } | CSS स्टाइलशीट(s) को कहाँ संग्रहीत किया जाए, नियंत्रित करता है: बाहरी संसाधन (`false`) के रूप में, या HTML मार्कअप में, HTML-&gt;HEAD सेक्शन के STYLE तत्व के भीतर एम्बेड (`true`) किया जाए। |
| [HtmlTagCase](../../groupdocs.editor.options/htmlsaveoptions/htmltagcase) { get; set; } | HTML मार्कअप में HTML टैग नाम कैसे प्रदर्शित होंगे, नियंत्रित करता है: सभी लोअर केस (डिफ़ॉल्ट), सभी अपर केस, या पहला अक्षर अपर केस। |
| [SavingCallback](../../groupdocs.editor.options/htmlsaveoptions/savingcallback) { get; set; } | इंटरफ़ेस, जिसे अंतिम उपयोगकर्ता को सभी बाहरी HTML संसाधनों को सहेजने के लिए लागू करना **must** है। यह प्रॉपर्टी `null` नहीं होनी चाहिए, अन्यथा GroupDocs.Editor HTML फ़ॉर्मेट में [`EditableDocument`](../../groupdocs.editor/editabledocument) को सहेजते समय अपवाद फेंकेगा। |

### संबंधित देखें

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
