---
title: "TryParse"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट स्ट्रिंग को लंबाई मान के रूप में पार्स करने का प्रयास करता है, जिसमें उसका संख्यात्मक मान और इकाई का नाम शामिल है।"
type: docs
weight: 280
url: /hi/net/groupdocs.editor.htmlcss.css.datatypes/length/tryparse/
---
## Length.TryParse method

निर्दिष्ट स्ट्रिंग को Length मान के रूप में पार्स करने का प्रयास करता है, जिसमें उसका संख्यात्मक मान और इकाई नाम शामिल है।

```csharp
public static bool TryParse(string input, out Length result)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| इनपुट | String | इनपुट स्ट्रिंग, जिसे पार्स किया जाना चाहिए |
| परिणाम | Length& | आउटपुट पैरामीटर, जिसमें पार्सिंग का परिणाम होता है। यदि पार्सिंग असफल होती है, तो इसमें डिफ़ॉल्ट लंबाई मान होता है — एक इकाई रहित शून्य। |

### रिटर्न मान

यदि पार्सिंग सफल हो तो true, यदि असफल हो तो false

### संबंधित देखें

* struct [Length](../../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
