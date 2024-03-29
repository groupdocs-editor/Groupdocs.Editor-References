---
title: IImageResource
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: कस भ प्रकर रेखपुंज य वेक्टर के छव संसधन क प्रतनधत्व करत है
type: docs
weight: 480
url: /hi/net/groupdocs.editor.htmlcss.resources.images/iimageresource/
---
## IImageResource interface

किसी भी प्रकार, रेखापुंज या वेक्टर के छवि संसाधन का प्रतिनिधित्व करता है

```csharp
public interface IImageResource : IHtmlResource, IImage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/iimageresource/aspectratio) { get; } | लागू करने के प्रकार में किसी विशेष छवि के प्रकार की परवाह किए बिना एक पहलू अनुपात वापस करना चाहिए। दोनों वेक्टर और रास्टर छवियों की चौड़ाई और ऊंचाई के बीच आंतरिक पहलू अनुपात होता है। |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images/iimageresource/lineardimensions) { get; } | कार्यान्वयन प्रकार में छवि के रैखिक आयाम वापस करना चाहिए। रेखापुंज छवियों के लिए वे पिक्सेल में आंतरिक आयाम हैं। वेक्टर छवियां, समकक्ष में, कोई निश्चित आयाम नहीं हैं, लेकिन उनके मेटाडेटा में विभिन्न माप इकाइयों में कुछ बुनियादी आयाम हो सकते हैं। |
| [Type](../../groupdocs.editor.htmlcss.resources.images/iimageresource/type) { get; } | कार्यान्वयन प्रकार में विशिष्ट छवि प्रकार के उदाहरण के रूप में विशिष्ट छवि का एक प्रकार वापस करना चाहिए, जो सभी प्रकार-विशिष्ट जानकारी को समाहित करता है |

### टिप्पणियों

https://developer.mozilla.org/en-US/docs/Web/CSS/image

### यह सभी देखें

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IImage](../iimage)
* नाम स्थान [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* सभा [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
