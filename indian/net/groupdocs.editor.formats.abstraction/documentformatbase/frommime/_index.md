---
title: "FromMime"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट प्रकार T का वह इंस्टेंस प्राप्त करता है जिसका निर्दिष्ट MIME प्रकार है।"
type: docs
weight: 60
url: /hi/net/groupdocs.editor.formats.abstraction/documentformatbase/frommime/
---
## DocumentFormatBase.FromMime&lt;T&gt; method

निर्दिष्ट प्रकार *T* की एक इंस्टेंस प्राप्त करता है जिसका निर्दिष्ट MIME प्रकार है।

```csharp
public static T FromMime<T>(string mime)
    where T : DocumentFormatBase
```

| Parameter | विवरण |
| --- | --- |
| T | डॉक्यूमेंट फ़ॉर्मेट का प्रकार। |
| mime | डॉक्यूमेंट फ़ॉर्मेट का MIME प्रकार। |

### रिटर्न मान

निर्दिष्ट प्रकार *T* का वह इंस्टेंस जिसमें निर्दिष्ट MIME प्रकार है।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| InvalidOperationException | जब कोई मिलते-जुलते डॉक्यूमेंट फ़ॉर्मेट नहीं मिलता तो फेंका जाता है। |

### संबंधित देखें

* class [DocumentFormatBase](../../documentformatbase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
