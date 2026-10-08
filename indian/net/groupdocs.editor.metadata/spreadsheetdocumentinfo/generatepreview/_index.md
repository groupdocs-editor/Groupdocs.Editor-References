---
title: "GeneratePreview"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "चयनित वर्कशीट का पूर्वावलोकन SVG छवि के रूप में उत्पन्न करता है और लौटाता है"
type: docs
weight: 60
url: /hi/net/groupdocs.editor.metadata/spreadsheetdocumentinfo/generatepreview/
---
## SpreadsheetDocumentInfo.GeneratePreview method

चयनित वर्कशीट का पूर्वावलोकन SVG छवि के रूप में उत्पन्न करता है और लौटाता है

```csharp
public SvgImage GeneratePreview(int worksheetIndex)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| worksheetIndex | Int32 | वांछित वर्कशीट का 0‑आधारित सूचकांक। 0 से कम नहीं हो सकता, इस स्प्रेडशीट में वर्कशीटों की संख्या से अधिक नहीं हो सकता। |

### रिटर्न मान

SVG इमेज को गैर‑null उदाहरण के रूप में [`SvgImage`](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage) क्लास की।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentOutOfRangeException | निर्दिष्ट *worksheetIndex* 0 से कम या इस स्प्रेडशीट में वर्कशीटों की संख्या से अधिक है। |

### संबंधित देखें

* class [SvgImage](../../../groupdocs.editor.htmlcss.resources.images.vector/svgimage)
* struct [SpreadsheetDocumentInfo](../../spreadsheetdocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
