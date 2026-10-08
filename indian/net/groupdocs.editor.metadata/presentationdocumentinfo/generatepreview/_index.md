---
title: "GeneratePreview"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "चयनित स्लाइड का पूर्वावलोकन SVG छवि के रूप में बनाता और लौटाता है।"
type: docs
weight: 50
url: /hi/net/groupdocs.editor.metadata/presentationdocumentinfo/generatepreview/
---
## PresentationDocumentInfo.GeneratePreview method

चयनित स्लाइड का पूर्वावलोकन SVG छवि के रूप में बनाता और लौटाता है।

```csharp
public SvgImage GeneratePreview(int slideIndex)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| slideIndex | Int32 | वांछित स्लाइड का 0‑आधारित सूचकांक। 0 से कम नहीं हो सकता, इस प्रस्तुति में स्लाइडों की संख्या से अधिक नहीं हो सकता। |

### रिटर्न मान

SVG इमेज को गैर‑null उदाहरण के रूप में [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage) क्लास की।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | निर्दिष्ट *slideIndex* 0 से कम या इस प्रस्तुति में स्लाइडों की संख्या से अधिक है। |

### संबंधित देखें

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [PresentationDocumentInfo](../../presentationdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
