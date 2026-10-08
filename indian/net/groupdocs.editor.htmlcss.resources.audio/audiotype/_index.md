---
title: "AudioType"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "एक समर्थित ऑडियो प्रकार फ़ॉर्मेट का प्रतिनिधित्व करता है"
type: docs
weight: 320
url: /hi/net/groupdocs.editor.htmlcss.resources.audio/audiotype/
---
## AudioType structure

समर्थित ऑडियो प्रकार (फ़ॉर्मेट) का प्रतिनिधित्व करता है

```csharp
public struct AudioType : IEquatable<AudioType>, IResourceType
```

## गुण

| नाम | विवरण |
| --- | --- |
| static [Mp3](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mp3) { get; } | MPEG-1 ऑडियो लेयर III ऑडियो फ़ॉर्मेट का प्रतिनिधित्व करता है |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.audio/audiotype/undefined) { get; } | विशेष मान, जो अपरिभाषित, अज्ञात या असमर्थित ऑडियो फ़ॉर्मेट को दर्शाता है |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/fileextension) { get; } | इस ऑडियो फ़ॉर्मेट के लिए फ़ाइलनाम एक्सटेंशन (डॉट अक्षर के बिना) |
| [FormalName](../../groupdocs.editor.htmlcss.resources.audio/audiotype/formalname) { get; } | इस ऑडियो फ़ॉर्मेट का औपचारिक नाम |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mimecode) { get; } | इस ऑडियो फ़ॉर्मेट के लिए MIME कोड |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/parsefromfilenamewithextension)(string) | AudioType मान लौटाता है, जो फ़ाइलनाम एक्सटेंशन के बराबर है, जो निर्दिष्ट फ़ाइलनाम से निकाला गया है |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals)(AudioType) | निर्धारित करता है कि यह उदाहरण निर्दिष्ट "AudioType" उदाहरण के बराबर है या नहीं |
| override [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals_1)(object) | निर्धारित करता है कि यह उदाहरण निर्दिष्ट अनकास्टेड ऑब्जेक्ट के बराबर है, जो संभवतः एक अन्य "AudioType" उदाहरण है या नहीं |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/gethashcode)() | हैश-कोड लौटाता है, जो इस विशिष्ट मान प्रकार के लिए एक स्थिर संख्या है |
| [operator ==](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_equality) | जाँचता है कि दो "AudioType" मान बराबर हैं या नहीं |
| [operator !=](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_inequality) | जाँचता है कि दो "AudioType" मान असमान हैं या नहीं |

### संबंधित देखें

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
