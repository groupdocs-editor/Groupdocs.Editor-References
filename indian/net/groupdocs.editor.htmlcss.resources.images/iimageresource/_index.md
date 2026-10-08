---
title: "IImageResource"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "किसी भी प्रकार की इमेज रिसोर्स का प्रतिनिधित्व करता है, चाहे वह रास्टर हो या वेक्टर।"
type: docs
weight: 470
url: /hi/net/groupdocs.editor.htmlcss.resources.images/iimageresource/
---
## IImageResource interface

किसी भी प्रकार की इमेज रिसोर्स का प्रतिनिधित्व करता है, रास्टर या वेक्टर।

```csharp
public interface IImageResource : IHtmlResource, IImage
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/iimageresource/aspectratio) { get; } | इम्प्लीमेंटेशन में प्रकार को किसी भी इमेज का पहलू अनुपात लौटाना चाहिए, चाहे उसका प्रकार कुछ भी हो। वेक्टर और रास्टर दोनों इमेजों की चौड़ाई और ऊँचाई के बीच अंतर्निहित पहलू अनुपात होता है। |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images/iimageresource/lineardimensions) { get; } | इम्प्लीमेंटेशन में प्रकार को इमेज के रैखिक आयाम लौटाने चाहिए। रास्टर इमेजों के लिए ये पिक्सेल में अंतर्निहित आयाम होते हैं। वेक्टर इमेजों के पास निश्चित आयाम नहीं होते, लेकिन उनके मेटाडेटा में विभिन्न माप इकाइयों में कुछ बुनियादी आयाम शामिल हो सकते हैं। |
| [Type](../../groupdocs.editor.htmlcss.resources.images/iimageresource/type) { get; } | इम्प्लीमेंटेशन में प्रकार को विशिष्ट इमेज का प्रकार, एक विशिष्ट ImageType के उदाहरण के रूप में लौटाना चाहिए, जो सभी प्रकार-विशिष्ट जानकारी को समेटे हुए है। |

### टिप्पणियाँ

https://developer.mozilla.org/en-US/docs/Web/CSS/image

### संबंधित देखें

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IImage](../iimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
