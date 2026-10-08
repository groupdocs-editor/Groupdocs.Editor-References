---
title: "संपादित करें"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट फ़ॉर्मेट-विशिष्ट विकल्पों का उपयोग करके पहले लोड किए गए दस्तावेज़ को संपादन के लिए खोलता है, जिससे EditableDocumentgroupdocs.editor/editabledocument क्लास का एक इंस्टेंस उत्पन्न और लौटाया जाता है, जो बदले में HTML मार्कअप और संबंधित संसाधन बनाने के लिए मेथड्स प्रदान करता है।"
type: docs
weight: 60
url: /hi/net/groupdocs.editor/editor/edit/
---
## Edit(IEditOptions) {#edit_1}

निर्दिष्ट फ़ॉर्मेट-विशिष्ट विकल्पों का उपयोग करके पहले लोड किए गए दस्तावेज़ को संपादन के लिए खोलता है, जिससे '[`EditableDocument`](../../editabledocument)' क्लास का एक इंस्टेंस उत्पन्न और लौटाया जाता है, जो बदले में HTML मार्कअप और संबंधित संसाधन बनाने के लिए मेथड्स प्रदान करता है।

```csharp
public EditableDocument Edit(IEditOptions editOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| editOptions | IEditOptions | फ़ॉर्म-विशिष्ट दस्तावेज़ विकल्प, जो रूपांतरण प्रक्रिया को ट्यून‑अप करने की अनुमति देते हैं। NULL हो सकता है — ऐसे में GroupDocs.Editor पहले लोड किए गए दस्तावेज़ का फ़ॉर्मेट पहचानता है और इस फ़ॉर्मेट के लिए डिफ़ॉल्ट विकल्प लागू करता है। यह पहले लागू किए गए लोड विकल्पों के साथ टकराव नहीं होना चाहिए। |

### रिटर्न मान

‘[`EditableDocument`](../../editabledocument)’ क्लास का एक इंस्टेंस, जो सभी संसाधनों के साथ मध्यवर्ती फ़ॉर्मेट में संपूर्ण इनपुट दस्तावेज़ को समाहित करता है। यह मेथड, यदि सफलतापूर्वक समाप्त होता है, कभी NULL नहीं लौटाता।

### टिप्पणियाँ

जब इनपुट मूल दस्तावेज़ को कंस्ट्रक्टर के माध्यम से 'Editor' इंस्टेंस में लोड किया जाता है, यह मेथड दस्तावेज़ को संपादन के लिए खोलने की अनुमति देता है, इसे मध्यवर्ती फ़ॉर्मेट में परिवर्तित करके, जो 'EditableDocument' क्लास के इंस्टेंस में समाहित होता है। इस मेथड से लौटाया गया '[`EditableDocument`](../../editabledocument)' सभी आवश्यक मेथड्स और प्रॉपर्टीज़ रखता है जो HTML मार्कअप और संबंधित संसाधनों (जैसे छवियां, फ़ॉन्ट्स और स्टाइलशीट्स) को सभी आवश्यक कॉन्फ़िगरेशन में उत्पन्न करने के लिए आवश्यक हैं, ताकि उन्हें किसी भी WYSIWYG HTML‑एडिटर में पास किया जा सके। यह ओवरलोड संपादन विकल्प प्राप्त करता है, जो परिवार फ़ॉर्मेट्स के लिए विशिष्ट हैं। **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* interface [IEditOptions](../../../groupdocs.editor.options/ieditoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Edit() {#edit}

पहले लोड किए गए दस्तावेज़ को डिफ़ॉल्ट विकल्पों का उपयोग करके संपादन के लिए खोलता है, '[`EditableDocument`](../../editabledocument)' क्लास का एक इंस्टेंस उत्पन्न करके और लौटाकर, जो बदले में HTML मार्कअप और संबंधित संसाधनों को उत्पन्न करने के मेथड्स रखता है।

```csharp
public EditableDocument Edit()
```

### रिटर्न मान

‘[`EditableDocument`](../../editabledocument)’ क्लास का एक इंस्टेंस, जो सभी संसाधनों के साथ मध्यवर्ती फ़ॉर्मेट में संपूर्ण इनपुट दस्तावेज़ को समाहित करता है। यह मेथड, यदि सफलतापूर्वक समाप्त होता है, कभी NULL नहीं लौटाता।

### टिप्पणियाँ

जब इनपुट मूल दस्तावेज़ को कंस्ट्रक्टर के माध्यम से 'Editor' इंस्टेंस में लोड किया जाता है, यह मेथड दस्तावेज़ को संपादन के लिए खोलने की अनुमति देता है, इसे मध्यवर्ती फ़ॉर्मेट में परिवर्तित करके, जो '[`EditableDocument`](../../editabledocument)' क्लास के इंस्टेंस में समाहित होता है। इस मेथड से लौटाया गया '[`EditableDocument`](../../editabledocument)' सभी आवश्यक मेथड्स और प्रॉपर्टीज़ रखता है जो HTML मार्कअप और संबंधित संसाधनों (जैसे छवियां, फ़ॉन्ट्स और स्टाइलशीट्स) को सभी आवश्यक कॉन्फ़िगरेशन में उत्पन्न करने के लिए आवश्यक हैं, ताकि उन्हें किसी भी WYSIWYG HTML‑एडिटर में पास किया जा सके। यह ओवरलोड संपादन विकल्प लागू करता है, जो उस फ़ॉर्मेट के लिए डिफ़ॉल्ट हैं, जिससे इनपुट दस्तावेज़ संबंधित है। **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
