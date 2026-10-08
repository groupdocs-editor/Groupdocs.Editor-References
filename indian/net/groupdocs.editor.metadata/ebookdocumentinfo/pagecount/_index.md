---
title: "PageCount"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "MOBI या AZW3 के मामले में पृष्ठों की संख्या या ePub के मामले में अध्यायों की संख्या लौटाता है।"
type: docs
weight: 30
url: /hi/net/groupdocs.editor.metadata/ebookdocumentinfo/pagecount/
---
## EbookDocumentInfo.PageCount property

MOBI या AZW3 के मामले में पृष्ठों की संख्या या ePub के मामले में अध्यायों की संख्या लौटाता है।

```csharp
public int PageCount { get; }
```

### टिप्पणियाँ

e-Book दस्तावेज़ आमतौर पर स्थिर पृष्ठ नहीं रखते और इसलिए पृष्ठ गणना नहीं होती। ePub के मामले में अध्यायों की संख्या गणना करना संभव है। हालांकि, MOBI और AZW3 फॉर्मेट में भी कोई अध्याय नहीं होते, इसलिए यह संख्या मानक पृष्ठ आकार A4 पोर्ट्रेट अभिविन्यास में सेट से गणना की जाती है।

### संबंधित देखें

* struct [EbookDocumentInfo](../../ebookdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
