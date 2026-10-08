---
title: "Mp3Audio"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "मनचाहे फ़ॉर्मेट के एक ऑडियो संसाधन का प्रतिनिधित्व करता है"
type: docs
weight: 330
url: /hi/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
## Mp3Audio class

मनचाहे फ़ॉर्मेट के एक ऑडियो संसाधन का प्रतिनिधित्व करता है

```csharp
public sealed class Mp3Audio : IEquatable<Mp3Audio>, IHtmlResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Mp3Audio](mp3audio)(string, Stream) | MP3 सामग्री, जो बाइट स्ट्रीम के रूप में दर्शाई गई है, से नया Mp3Audio क्लास बनाता है, और निर्दिष्ट नाम के साथ |

## गुण

| नाम | विवरण |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/bytecontent) { get; } | इस फ़ॉन्ट की सामग्री बाइट स्ट्रीम के रूप में लौटाता है |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/filenamewithextension) { get; } | इस MP3 सामग्री का सही फ़ाइलनाम लौटाता है, जो नाम और एक्सटेंशन से बना होता है। सिद्धांततः यह नाम से भिन्न हो सकता है। |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isdisposed) { get; } | निर्धारित करता है कि यह MP3 सामग्री डिस्पोज़ है या नहीं |
| [Name](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/name) { get; } | इस MP3 सामग्री का नाम लौटाता है। आमतौर पर इसमें फ़ाइलनाम एक्सटेंशन नहीं होता और सिद्धांततः यह फ़ाइलनाम से भिन्न हो सकता है। |
| [TextContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/textcontent) { get; } | इस MP3 संसाधन की सामग्री बेस64-एन्कोडेड स्ट्रिंग के रूप में लौटाता है। यह मान पहली बार कॉल करने के बाद कैश किया जाता है। |
| [Type](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/type) { get; } | AudioType.Mp3 लौटाता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/dispose)() | इस MP3 संसाधन को डिस्पोज़ करता है, उसकी सामग्री को डिस्पोज़ करता है और अधिकांश मेथड्स और प्रॉपर्टीज़ को गैर-कार्यशील बना देता है |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals_1)(IHtmlResource) | निर्दिष्ट HTML संसाधन के साथ इस उदाहरण की संदर्भ समानता की जाँच करता है |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals)(Mp3Audio) | निर्दिष्ट फ़ॉन्ट संसाधन के साथ इस उदाहरण की संदर्भ समानता की जाँच करता है |
| [Save](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/save)(string) | इस MP3 संसाधन को निर्दिष्ट फ़ाइल में सहेजता है |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isvalid)(Stream) | जाँचता है कि निर्दिष्ट स्ट्रीम वैध MP3 सामग्री है या नहीं |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/disposed) | इवेंट, जो तब होता है जब यह MP3 सामग्री नष्ट की जाती है |

### संबंधित देखें

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
