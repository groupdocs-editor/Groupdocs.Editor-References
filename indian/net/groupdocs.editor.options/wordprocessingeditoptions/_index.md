---
title: WordProcessingEditOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: डओस एक्स आरटएफ ओडट आद जैसे सभ समर्थत वर्डप्रसेसंग वर्ड्सकंप्लयंट प्ररूपं के दस्तवेज़ं के संपदन के लए कस्टम वकल्प नर्दष्ट करने क अनुमत देत है
type: docs
weight: 1200
url: /hi/net/groupdocs.editor.options/wordprocessingeditoptions/
---
## WordProcessingEditOptions class

डीओसी (एक्स), आरटीएफ, ओडीटी आदि जैसे सभी समर्थित वर्डप्रोसेसिंग (वर्ड्स-कंप्लायंट) प्रारूपों के दस्तावेज़ों के संपादन के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।

```csharp
public class WordProcessingEditOptions : IEditOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor)() | WordProcessingEditOptions वर्ग का एक नया उदाहरण बनाता है और लौटाता है, जहाँ सभी विकल्प उनके डिफ़ॉल्ट मान पर सेट होते हैं |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor_1)(bool) | निर्दिष्ट पेजिनेशन के साथ WordProcessingEditOptions वर्ग का एक नया उदाहरण बनाता है और लौटाता है और अन्य सभी विकल्पों को डिफ़ॉल्ट करता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/wordprocessingeditoptions/enablelanguageinformation) { get; set; } | निर्दिष्ट करता है कि भाषा की जानकारी HTML मार्कअप को 'लैंग' HTML विशेषताओं के रूप में निर्यात की जाती है या नहीं। यह विकल्प बहु-भाषा दस्तावेज़ों के राउंडट्रिप रूपांतरण के लिए उपयोगी हो सकता है। डिफ़ॉल्ट रूप से यह अक्षम (झूठा) है। |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingeditoptions/enablepagination) { get; set; } | परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। डिफ़ॉल्ट रूप से अक्षम (झूठा) है। |
| [ExtractOnlyUsedFont](../../groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont) { get; set; } | एक मान प्राप्त या सेट करता है जो इंगित करता है कि दस्तावेज़ की टेक्स्ट सामग्री में उपयोग किए जाने वाले फ़ॉन्ट संसाधनों को ही निकालें। |
| [FontExtraction](../../groupdocs.editor.options/wordprocessingeditoptions/fontextraction) { get; set; } | फ़ॉन्ट संसाधनों को निकालने के लिए जिम्मेदार है, जिनका उपयोग इनपुट वर्डप्रोसेसिंग दस्तावेज़ में किया जाता है। डिफ़ॉल्ट रूप से कोई फ़ॉन्ट नहीं निकालता (NotExtract). |
| [InputControlsClassName](../../groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname) { get; set; } | एक वर्ग नाम निर्दिष्ट करने की अनुमति देता है, जिसे प्रत्येक HTML तत्व में 'वर्ग' विशेषताओं में रखा जाएगा, जो इनपुट वर्डप्रोसेसिंग दस्तावेज़ में कुछ फ़ील्ड का प्रतिनिधित्व करता है। डिफ़ॉल्ट रूप से NULL है - 'वर्ग' विशेषताएँ लागू नहीं होती हैं। |

### यह सभी देखें

* interface [IEditOptions](../ieditoptions)
* नाम स्थान [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* सभा [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->