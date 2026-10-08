---
title: "EditableDocument"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "संपादन से पहले और बाद की सामग्री को शामिल करने वाला मध्यवर्ती दस्तावेज़"
type: docs
weight: 10
url: /hi/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

मध्यवर्ती दस्तावेज़, जिसमें संपादन से पहले और बाद की सामग्री होती है

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | सभी मौजूदा संसाधनों की सूची लौटाता है: सभी स्टाइलशीट्स, HTML से छवियाँ और सभी स्टाइलशीट्स, फ़ॉन्ट्स, ऑडियो |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | ऑडियो संसाधनों की सूची लौटाता है |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | इस HTML दस्तावेज़ द्वारा उपयोग किए जाने वाले स्टाइलशीट (CSS) संसाधनों (बाहरी और एम्बेडेड, लेकिन इनलाइन नहीं) को प्राप्त करने की अनुमति देता है |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | इस HTML दस्तावेज़ द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट संसाधनों को प्राप्त करने की अनुमति देता है |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | इस HTML दस्तावेज़ द्वारा उपयोग किए जाने वाले बाहरी छवि संसाधनों (रास्टर और वेक्टर छवियाँ) को प्राप्त करने की अनुमति देता है |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | निर्धारित करता है कि यह Editable दस्तावेज़ पहले ही डिस्पोज़ हो चुका है (true) या नहीं (false) |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | स्थैतिक फ़ैक्टरी, जो *.html फ़ाइल के पथ और लिंक्ड संसाधनों वाले फ़ोल्डर द्वारा निर्दिष्ट HTML फ़ाइल से EditableDocument की एक इंस्टेंस बनाती है |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup)(string) | स्थैतिक फ़ैक्टरी, जो निर्दिष्ट HTML मार्कअप से [`EditableDocument`](../editabledocument) की एक इंस्टेंस बनाती है |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup_1)(string, IEnumerable&lt;IHtmlResource&gt;) | स्थैतिक फ़ैक्टरी, जो निर्दिष्ट HTML मार्कअप और संबंधित लिंक्ड संसाधनों के सेट से EditableDocument की एक इंस्टेंस बनाती है |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | स्थैतिक फ़ैक्टरी, जो पूर्ण पथ द्वारा निर्दिष्ट फ़ोल्डर में स्थित संसाधनों और निर्दिष्ट HTML मार्कअप से EditableDocument की एक इंस्टेंस बनाती है |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | इस Editable दस्तावेज़ इंस्टेंस को डिस्पोज़ करता है, उसकी सामग्री को डिस्पोज़ करता है और उसकी मेथड्स और प्रॉपर्टीज़ को निष्क्रिय कर देता है |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | HTML दस्तावेज़ के बॉडी को (ओपनिंग और क्लोज़िंग BODY टैग्स के बीच की आंतरिक सामग्री, टैग्स के बिना) स्ट्रिंग के रूप में लौटाता है। |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | HTML दस्तावेज़ के बॉडी को (ओपनिंग और क्लोज़िंग BODY टैग्स के बीच की आंतरिक सामग्री, टैग्स के बिना) स्ट्रिंग के रूप में लौटाता है, जहाँ बाहरी संसाधनों के लिंक निर्दिष्ट टेम्प्लेट के साथ प्लेसहोल्डर्स शामिल करते हैं। |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | HTML दस्तावेज़ की संपूर्ण सामग्री को स्ट्रिंग के रूप में लौटाता है। |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | HTML दस्तावेज़ की संपूर्ण सामग्री को स्ट्रिंग के रूप में लौटाता है, जहाँ बाहरी संसाधनों के लिंक निर्दिष्ट टेम्प्लेट के साथ प्लेसहोल्डर्स शामिल करते हैं। |
| [GetContent&lt;TStream&gt;](../../groupdocs.editor/editabledocument/getcontent#getcontent_2)(TStream, Encoding) | निर्दिष्ट टेक्स्ट एन्कोडिंग के साथ निर्दिष्ट स्ट्रीम में इस सामग्री को लिखकर HTML दस्तावेज़ की संपूर्ण सामग्री को बाइट स्ट्रीम के रूप में लौटाता है |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | सभी बाहरी स्टाइलशीट्स की सामग्री को स्ट्रिंग्स की सूची के रूप में लौटाता है, जहाँ प्रत्येक स्ट्रिंग एक स्टाइलशीट का प्रतिनिधित्व करती है। यदि इस दस्तावेज़ के लिए कोई CSS नहीं है तो खाली सूची लौटाता है। |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | सभी बाहरी स्टाइलशीट्स की सामग्री को स्ट्रिंग्स की सूची के रूप में लौटाता है, जहाँ प्रत्येक स्ट्रिंग एक स्टाइलशीट का प्रतिनिधित्व करती है। निर्दिष्ट प्रीफ़िक्स प्रत्येक परिणामी स्टाइलशीट में बाहरी संसाधन के हर लिंक पर लागू किया जाएगा। यदि इस दस्तावेज़ के लिए कोई CSS नहीं है तो खाली सूची लौटाता है। |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | इस HTML दस्तावेज़ की सभी सामग्री को सभी संबंधित संसाधनों के साथ एकल स्ट्रिंग के रूप में लौटाता है, जहाँ सभी संसाधन HTML मार्कअप के भीतर बेस64-एन्कोडेड रूप में एम्बेडेड होते हैं। |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string) | निर्दिष्ट पथ पर फ़ाइल में इस HTML दस्तावेज़ को सहेजता है, जहाँ HTML मार्कअप संग्रहीत होगा, और संबंधित संसाधनों वाले फ़ोल्डर में भी। |
| [Save](../../groupdocs.editor/editabledocument/save#save_2)(string, string) | निर्दिष्ट पथ पर फ़ाइल में इस HTML दस्तावेज़ को सहेजता है, जहाँ HTML मार्कअप संग्रहीत होगा, और निर्दिष्ट पथ पर स्थित संबंधित संसाधनों वाले फ़ोल्डर में भी। |
| [Save](../../groupdocs.editor/editabledocument/save#save)(TextWriter, HtmlSaveOptions) | इस [`EditableDocument`](../editabledocument) की सामग्री को निर्दिष्ट टेक्स्ट राइटर में HTML दस्तावेज़ के रूप में सहेजता है, जबकि दूसरा विकल्प पैरामीटर सहेजने की प्रक्रिया को अनुकूलित करने और संसाधन सहेजने के कॉलबैक को निर्दिष्ट करने की अनुमति देता है |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | इवेंट, जो इस Editable दस्तावेज़ को नष्ट करने के बाद, नष्ट करने की प्रक्रिया समाप्त होते ही होता है |

### टिप्पणियाँ

`EditableDocument` क्लास का इंस्टेंस '[`Edit`](../editor/edit)' मेथड द्वारा बनाया जा सकता है या उपयोगकर्ता स्वयं स्थैतिक फ़ैक्टरीज़ का उपयोग करके बना सकता है। `EditableDocument` आंतरिक रूप से दस्तावेज़ को अपने बंद फ़ॉर्मेट में संग्रहीत करता है, जो सभी आयात और निर्यात फ़ॉर्मेट्स के साथ संगत (परिवर्तनीय) है, जिन्हें GroupDocs.Editor समर्थन करता है। किसी भी WYSIWYG क्लाइंट-साइड एडिटर (जैसे CKEditor या TinyMCE) में दस्तावेज़ को संपादन योग्य बनाने के लिए, `EditableDocument` HTML मार्कअप उत्पन्न करने और संसाधनों को बनाने के लिए मेथड्स प्रदान करता है, जिन्हें उपयोगकर्ता स्वीकार कर सकता है।

### संबंधित देखें

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
