---
title: "TiffImage"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "TIFF टैग्ड इमेज फ़ाइल फ़ॉर्मेट में एक छवि का प्रतिनिधित्व करता है, साथ में इसकी मेटाडेटा और अतिरिक्त विधियाँ"
type: docs
weight: 550
url: /hi/net/groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
## TiffImage class

TIFF (Tagged Image File Format) फ़ॉर्मेट में एक छवि का प्रतिनिधित्व करता है, जिसमें उसका मेटाडाटा और अतिरिक्त मेथड्स होते हैं।

```csharp
public sealed class TiffImage : RasterImageResourceBase
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [TiffImage](tiffimage#constructor)(string, Stream) | सामग्री से नया GifImage इंस्टेंस बनाता है, जो बाइट स्ट्रीम के रूप में दर्शाया गया है, और निर्दिष्ट नाम के साथ |
| [TiffImage](tiffimage#constructor_1)(string, string) | सामग्री से नया TiffImage इंस्टेंस बनाता है, जो base64-एन्कोडेड स्ट्रिंग के रूप में दर्शाया गया है, और निर्दिष्ट नाम के साथ |

## गुण

| नाम | विवरण |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | इस छवि का अनुपात लौटाता है, जो चौड़ाई-से-ऊँचाई संबंध है |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | इस रास्टर छवि की सामग्री बाइट स्ट्रीम के रूप में लौटाता है |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | इस रास्टर छवि का सही फ़ाइलनाम लौटाता है, जो नाम और एक्सटेंशन से बना होता है। सिद्धांततः यह नाम से अलग हो सकता है। |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | निर्धारित करता है कि यह रास्टर छवि डिस्पोज़्ड है या नहीं |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | इस रास्टर छवि फ़ाइल की लंबाई बाइट्स में लौटाता है |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | इस रास्टर छवि के रैखिक आयाम (चौड़ाई और ऊँचाई) लौटाता है |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | इस रास्टर छवि का नाम लौटाता है। आमतौर पर इसमें फ़ाइलनाम एक्सटेंशन नहीं होता और सिद्धांततः यह फ़ाइलनाम से अलग हो सकता है। |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | इस रास्टर छवि की सामग्री बेस64-एन्कोडेड स्ट्रिंग के रूप में लौटाता है |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/type) { get; } | लौटाता है [`Tiff`](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | इस रास्टर छवि को डिस्पोज़ करता है, उसकी सामग्री को डिस्पोज़ करता है और अधिकांश मेथड्स और प्रॉपर्टीज़ को गैर-कार्यशील बनाता है |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | निर्दिष्ट रेफ़रेंस समानता के साथ इस इंस्टेंस की जाँच करता है। |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | इस रास्टर छवि को निर्दिष्ट फ़ाइल में सहेजता है |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid)(Stream) | जाँचता है कि निर्दिष्ट स्ट्रीम वैध TIFF छवि है |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid_1)(string) | जाँचता है कि निर्दिष्ट base64-एन्कोडेड स्ट्रिंग वैध TIFF छवि है |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | इवेंट, जो तब होता है जब यह रास्टर इमेज नष्ट किया जाता है। |

### टिप्पणियाँ

विवरण के लिए https://en.wikipedia.org/wiki/TIFF देखें। बहुत दुर्लभ मामलों में TIFF WordProcessing दस्तावेज़ों के भीतर मौजूद होता है।

### संबंधित देखें

* class [RasterImageResourceBase](../rasterimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
