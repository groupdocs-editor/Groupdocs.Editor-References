---
title: EditableDocument
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: इंटरमडएट दस्तवेज़ जसमें संपदन से पहले और बद में समग्र शमल है
type: docs
weight: 10
url: /hi/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

इंटरमीडिएट दस्तावेज़, जिसमें संपादन से पहले और बाद में सामग्री शामिल है

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | सभी मौजूदा संसाधनों की सूची लौटाता है: सभी स्टाइलशीट, HTML से छवियां और सभी स्टाइलशीट, फ़ॉन्ट, ऑडियो |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | ऑडियो संसाधनों की सूची लौटाता है |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | CSS संसाधनों की सूची लौटाता है |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | बाहरी फ़ॉन्ट संसाधनों को प्राप्त करने की अनुमति देता है, जिनका उपयोग इस HTML दस्तावेज़ द्वारा किया जाता है |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | बाह्य छवि संसाधनों (रेखापुंज और सदिश छवियों) को प्राप्त करने की अनुमति देता है, जिनका उपयोग इस HTML दस्तावेज़ द्वारा किया जाता है |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | यह निर्धारित करता है कि यह संपादन योग्य दस्तावेज़ पहले ही निपटाया गया था (सत्य) या नहीं (झूठा) |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | स्टेटिक फ़ैक्टरी, जो एक HTML फ़ाइल से संपादन योग्य दस्तावेज़ का एक उदाहरण बनाता है, जो कि *.html फ़ाइल के पथ और लिंक किए गए संसाधनों के साथ एक फ़ोल्डर द्वारा निर्दिष्ट किया गया है |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup)(string, IEnumerable&lt;IHtmlResource&gt;) | स्टेटिक फ़ैक्टरी, जो निर्दिष्ट HTML मार्कअप से संपादन योग्य दस्तावेज़ का एक उदाहरण और संबंधित लिंक किए गए संसाधनों का एक सेट बनाता है |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | स्टेटिक फ़ैक्टरी, जो एक निर्दिष्ट HTML मार्कअप और फ़ोल्डर में स्थित संसाधनों से संपादन योग्य दस्तावेज़ का एक उदाहरण बनाता है, पूर्ण पथ द्वारा निर्दिष्ट |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | इस संपादन योग्य दस्तावेज़ उदाहरण का निपटान करता है, इसकी सामग्री का निपटान करता है और इसकी विधियों और गुणों को गैर-कार्यशील बनाता है |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | एक स्ट्रिंग के रूप में HTML दस्तावेज़ (इन टैग के बिना BODY टैग खोलने और बंद करने के बीच की आंतरिक सामग्री) का एक निकाय लौटाता है। |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | एक स्ट्रिंग के रूप में HTML दस्तावेज़ (इन टैग के बिना BODY टैग खोलने और बंद करने के बीच की आंतरिक सामग्री) का एक भाग लौटाता है, जहां बाहरी संसाधनों के लिंक में निर्दिष्ट उपसर्ग होता है। |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | HTML दस्तावेज़ की संपूर्ण सामग्री को एक स्ट्रिंग के रूप में लौटाता है. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | HTML दस्तावेज़ की समग्र सामग्री को एक स्ट्रिंग के रूप में लौटाता है, जहां बाहरी संसाधनों के लिंक में निर्दिष्ट उपसर्ग होता है। |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | स्ट्रिंग की सूची के रूप में सभी बाहरी स्टाइलशीट की सामग्री लौटाता है, जहां एक स्ट्रिंग एक स्टाइलशीट का प्रतिनिधित्व करती है। खाली सूची लौटाता है, अगर इस दस्तावेज़ के लिए कोई सीएसएस नहीं है। |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | स्ट्रिंग की सूची के रूप में सभी बाहरी स्टाइलशीट की सामग्री लौटाता है, जहां एक स्ट्रिंग एक स्टाइलशीट का प्रतिनिधित्व करती है। प्रत्येक परिणामी स्टाइलशीट में बाहरी संसाधन के प्रत्येक लिंक पर निर्दिष्ट उपसर्ग लागू किया जाएगा। खाली सूची देता है, अगर इसके लिए कोई सीएसएस नहीं है दस्तावेज़. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | इस HTML दस्तावेज़ की सभी सामग्री को एक स्ट्रिंग के रूप में सभी संबंधित संसाधनों के साथ लौटाता है, जहाँ सभी संसाधन HTML मार्कअप के अंदर बेस64-एन्कोडेड रूप में एम्बेड किए गए हैं। |
| [Save](../../groupdocs.editor/editabledocument/save#save)(string) | इस HTML दस्तावेज़ को निर्दिष्ट पथ पर फ़ाइल में सहेजता है, जहाँ HTML मार्कअप संग्रहीत किया जाएगा, और संसाधनों के साथ फ़ोल्डर में। |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string, string) | इस HTML दस्तावेज़ को निर्दिष्ट पथ पर फ़ाइल में सहेजता है, जहाँ HTML मार्कअप संग्रहीत किया जाएगा, और संसाधनों के साथ फ़ोल्डर में, जो निर्दिष्ट पथ पर स्थित है। |

## आयोजन

| नाम | विवरण |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | घटना, जो तब होती है जब इस संपादन योग्य दस्तावेज़ का निपटारा किया जाता है, निपटान प्रक्रिया समाप्त करने के ठीक बाद |

### टिप्पणियों

संपादन योग्य दस्तावेज़ वर्ग का उदाहरण 'द्वारा निर्मित किया जा सकता है[`Edit`](../editor/edit) विधि या स्थिर कारखानों का उपयोग करके उपयोगकर्ता द्वारा स्वयं बनाया गया। संपादन योग्य दस्तावेज़ आंतरिक रूप से दस्तावेज़ को अपने स्वयं के बंद प्रारूप में संग्रहीत करता है, जो सभी आयात और निर्यात प्रारूपों के साथ संगत (परिवर्तनीय) है, जो कि GroupDocs.Editor का समर्थन करता है। किसी भी WYSIWYG क्लाइंट-साइड संपादक (जैसे CKEditor या TinyMCE) में दस्तावेज़ को संपादन योग्य बनाने के लिए, संपादन योग्य दस्तावेज़ HTML मार्कअप उत्पन्न करने और संसाधन तैयार करने के तरीके प्रदान करता है, जिसे उपयोगकर्ता द्वारा स्वीकार किया जा सकता है।

### यह सभी देखें

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* नाम स्थान [GroupDocs.Editor](../../groupdocs.editor)
* सभा [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
