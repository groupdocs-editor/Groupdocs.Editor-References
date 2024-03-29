---
title: Edit
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: नर्दष्ट प्ररूपवशष्ट वकल्पं क उपयग करके संपदन के लए पहले से लड कए गए दस्तवेज़ क खलत है और क एक उदहरण देत हैEditableDocumentgroupdocs.editor/editabledocument वर्ग जसमें बदले में HTML मर्कअप और संबद्ध संसधनं के उत्पदन के तरके शमल हैं
type: docs
weight: 50
url: /hi/net/groupdocs.editor/editor/edit/
---
## Edit(IEditOptions) {#edit_1}

निर्दिष्ट प्रारूप-विशिष्ट विकल्पों का उपयोग करके संपादन के लिए पहले से लोड किए गए दस्तावेज़ को खोलता है और 'का एक उदाहरण देता है[`EditableDocument`](../../editabledocument) वर्ग, जिसमें, बदले में, HTML मार्कअप और संबद्ध संसाधनों के उत्पादन के तरीके शामिल हैं।

```csharp
public EditableDocument Edit(IEditOptions editOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| editOptions | IEditOptions | प्रारूप-विशिष्ट दस्तावेज़ विकल्प, जो रूपांतरण प्रक्रिया को ट्यून-अप करने की अनुमति देता है। NULL हो सकता है — उस स्थिति में GroupDocs.Editor पहले से लोड किए गए दस्तावेज़ के प्रारूप का पता लगाता है और इस प्रारूप के लिए डिफ़ॉल्ट विकल्प लागू करता है। पहले से लागू लोड विकल्पों के साथ विरोध नहीं करना चाहिए। |

### प्रतिलाभ की मात्रा

का उदाहरण[`EditableDocument`](../../editabledocument) वर्ग, जो अपने सभी संसाधनों के साथ मध्यवर्ती प्रारूप में समग्र इनपुट दस्तावेज़ को समाहित करता है। यह विधि, यदि सफलतापूर्वक समाप्त हो जाती है, तो कभी भी NULL नहीं लौटती है।

### टिप्पणियों

जब इनपुट मूल दस्तावेज़ को कंस्ट्रक्टर के माध्यम से 'संपादक' उदाहरण में लोड किया जाता है, तो यह विधि दस्तावेज़ को मध्यवर्ती प्रारूप में परिवर्तित करके संपादन के लिए खोलने की अनुमति देती है, जो 'संपादन योग्य दस्तावेज़' वर्ग के उदाहरण के भीतर होता है। '[`EditableDocument`](../../editabledocument) इस पद्धति से लौटाया गया, इसमें सभी आवश्यक कॉन्फ़िगरेशन में HTML मार्कअप और संबंधित संसाधनों (जैसे चित्र, फ़ॉन्ट और स्टाइलशीट) के उत्पादन के लिए सभी आवश्यक तरीके और गुण शामिल हैं, ताकि बाद में उन्हें किसी भी WYSIWYG HTML-संपादक में पास किया जा सके। यह अधिभार संपादन विकल्प प्राप्त करता है, जो पारिवारिक स्वरूपों के लिए विशिष्ट हैं। **और अधिक जानें**

* GroupDocs का उपयोग करके दस्तावेज़ संपादित करने के बारे में अधिक। संपादक: [GroupDocs.Editor का उपयोग करके दस्तावेज़ को कैसे संपादित करें](https://docs.groupdocs.com/display/editornet/Edit+document)

### यह सभी देखें

* class [EditableDocument](../../editabledocument)
* interface [IEditOptions](../../../groupdocs.editor.options/ieditoptions)
* class [Editor](../../editor)
* नाम स्थान [GroupDocs.Editor](../../editor)
* सभा [GroupDocs.Editor](../../../)

---

## Edit() {#edit}

पहले लोड किए गए दस्तावेज़ को डिफ़ॉल्ट विकल्पों का उपयोग करके संपादित करने के लिए खोलता है और 'का एक उदाहरण देता है[`EditableDocument`](../../editabledocument) वर्ग, जिसमें, बदले में, HTML मार्कअप और संबद्ध संसाधनों के उत्पादन के तरीके शामिल हैं।

```csharp
public EditableDocument Edit()
```

### प्रतिलाभ की मात्रा

का उदाहरण[`EditableDocument`](../../editabledocument) वर्ग, जो अपने सभी संसाधनों के साथ मध्यवर्ती प्रारूप में समग्र इनपुट दस्तावेज़ को समाहित करता है। यह विधि, यदि सफलतापूर्वक समाप्त हो जाती है, तो कभी भी NULL नहीं लौटती है।

### टिप्पणियों

जब इनपुट मूल दस्तावेज़ को कंस्ट्रक्टर के माध्यम से 'संपादक' उदाहरण में लोड किया जाता है, तो यह विधि दस्तावेज़ को मध्यवर्ती प्रारूप में परिवर्तित करके संपादन के लिए खोलने की अनुमति देती है, जो 'के उदाहरण के भीतर समझाया जाता है।[`EditableDocument`](../../editabledocument) कक्षा। '[`EditableDocument`](../../editabledocument) इस पद्धति से लौटाया गया, इसमें सभी आवश्यक कॉन्फ़िगरेशन में HTML मार्कअप और संबंधित संसाधनों (जैसे चित्र, फ़ॉन्ट और स्टाइलशीट) के उत्पादन के लिए सभी आवश्यक तरीके और गुण शामिल हैं, ताकि बाद में उन्हें किसी भी WYSIWYG HTML-संपादक में पास किया जा सके। यह अधिभार संपादन विकल्पों पर लागू होता है, जो प्रारूप के लिए डिफ़ॉल्ट होते हैं, जिससे इनपुट दस्तावेज़ संबंधित होता है। **और अधिक जानें**

* GroupDocs का उपयोग करके दस्तावेज़ संपादित करने के बारे में अधिक। संपादक: [GroupDocs.Editor का उपयोग करके दस्तावेज़ को कैसे संपादित करें](https://docs.groupdocs.com/display/editornet/Edit+document)

### यह सभी देखें

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* नाम स्थान [GroupDocs.Editor](../../editor)
* सभा [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
