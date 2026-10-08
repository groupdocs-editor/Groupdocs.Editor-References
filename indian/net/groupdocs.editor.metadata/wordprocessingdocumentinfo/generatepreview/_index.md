---
title: "GeneratePreview"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "चयनित पृष्ठ का पूर्वावलोकन SVG छवि के रूप में उत्पन्न करता है और लौटाता है"
type: docs
weight: 60
url: /hi/net/groupdocs.editor.metadata/wordprocessingdocumentinfo/generatepreview/
---
## WordProcessingDocumentInfo.GeneratePreview method

चयनित पृष्ठ का पूर्वावलोकन SVG छवि के रूप में उत्पन्न करता है और लौटाता है

```csharp
public SvgImage GeneratePreview(int pageIndex)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| pageIndex | Int32 | वांछित पृष्ठ का 0‑आधारित सूचकांक। 0 से कम नहीं हो सकता, इस WordProcessing दस्तावेज़ में पृष्ठों की संख्या से अधिक नहीं हो सकता। |

### रिटर्न मान

SVG इमेज को गैर‑null उदाहरण के रूप में [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage) क्लास की।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | निर्दिष्ट *pageIndex* 0 से कम या इस WordProcessing दस्तावेज़ में पृष्ठों की संख्या से अधिक है। |

### संबंधित देखें

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [WordProcessingDocumentInfo](../../wordprocessingdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
