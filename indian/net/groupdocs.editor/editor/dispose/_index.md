---
title: "नष्ट करें"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "Editor के इस इंस्टेंस को नष्ट करता है ताकि यह सभी आंतरिक संसाधनों को मुक्त कर दे और आगे के उपयोग के लिए अनुपलब्ध हो जाए।"
type: docs
weight: 50
url: /hi/net/groupdocs.editor/editor/dispose/
---
## Editor.Dispose method

Editor के इस इंस्टेंस को डिस्पोज़ करता है, जिससे यह सभी आंतरिक संसाधनों को मुक्त कर देता है और आगे के उपयोग के लिए अनुपलब्ध हो जाता है।

```csharp
public void Dispose()
```

### टिप्पणियाँ

इस मेथड को बुलाने के बाद, इस इंस्टेंस के सभी अन्य मेथड्स को कॉल करने पर ObjectDisposedException उत्पन्न होगा। इस मेथड को कई बार कॉल करना सुरक्षित है — सभी बाद के कॉलों को अनदेखा किया जाएगा।

### संबंधित देखें

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
