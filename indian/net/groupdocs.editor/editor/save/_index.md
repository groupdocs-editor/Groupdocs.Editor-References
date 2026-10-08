---
title: "सहेजें"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट संपादित दस्तावेज़ को, जो EditableDocumentgroupdocs.editor/editabledocument के इंस्टेंस के रूप में दर्शाया गया है, निर्दिष्ट फ़ॉर्मेट के परिणामस्वरूप दस्तावेज़ में परिवर्तित करता है और उसकी सामग्री को निर्दिष्ट स्ट्रीम में सहेजता है।"
type: docs
weight: 80
url: /hi/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

निर्दिष्ट संपादित दस्तावेज़ को, जो '[`EditableDocument`](../../editabledocument)' के इंस्टेंस के रूप में दर्शाया गया है, निर्दिष्ट फ़ॉर्मेट के परिणामस्वरूप दस्तावेज़ में परिवर्तित करता है और उसकी सामग्री को निर्दिष्ट स्ट्रीम में सहेजता है।

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| inputDocument | EditableDocument | इनपुट दस्तावेज़ का संस्करण, जिसे WYSIWYG HTML‑एडिटर में संपादित किया गया था और '[`EditableDocument`](../../editabledocument)' क्लास के इंस्टेंस के रूप में संग्रहीत किया गया है, जिसे कुछ विशिष्ट फ़ॉर्मेट के आउटपुट दस्तावेज़ में परिवर्तित किया जाना चाहिए। यह null या नष्ट नहीं होना चाहिए। |
| outputDocument | Stream | आउटपुट स्ट्रीम, जिसमें परिणामस्वरूप दस्तावेज़ की सामग्री रिकॉर्ड की जाएगी। यह null, नष्ट नहीं होना चाहिए, और लिखने का समर्थन करना चाहिए। |
| saveOptions | ISaveOptions | दस्तावेज़ सहेजने के विकल्प, जो परिणामस्वरूप दस्तावेज़ के फ़ॉर्मेट को परिभाषित करते हैं, साथ ही सामान्य और फ़ॉर्मेट-विशिष्ट सहेजने के विकल्प। यह null नहीं होना चाहिए। |

### टिप्पणियाँ

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

निर्दिष्ट संपादित दस्तावेज़ को, जो '[`EditableDocument`](../../editabledocument)' के इंस्टेंस के रूप में दर्शाया गया है, निर्दिष्ट फ़ॉर्मेट के परिणामस्वरूप दस्तावेज़ में परिवर्तित करता है और उसकी सामग्री को निर्दिष्ट फ़ाइल पथ द्वारा फ़ाइल में सहेजता है।

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| inputDocument | EditableDocument | इनपुट दस्तावेज़ का संस्करण, जिसे WYSIWYG HTML‑एडिटर में संपादित किया गया था और '[`EditableDocument`](../../editabledocument)' क्लास के इंस्टेंस के रूप में संग्रहीत किया गया है, जिसे कुछ विशिष्ट फ़ॉर्मेट के आउटपुट दस्तावेज़ में परिवर्तित किया जाना चाहिए। यह null या नष्ट नहीं होना चाहिए। |
| filePath | String | फ़ाइल का पथ, जिसमें आउटपुट दस्तावेज़ सहेजा जाएगा। यदि समान नाम की फ़ाइल मौजूद है, तो उसे पूरी तरह से पुनर्लिखित किया जाएगा। पथ वाली स्ट्रिंग null, खाली या केवल सफ़ेद स्थान नहीं होनी चाहिए। |
| saveOptions | ISaveOptions | दस्तावेज़ सहेजने के विकल्प, जो परिणामस्वरूप दस्तावेज़ के फ़ॉर्मेट को परिभाषित करते हैं, साथ ही सामान्य और फ़ॉर्मेट-विशिष्ट सहेजने के विकल्प। यह null नहीं होना चाहिए। |

### टिप्पणियाँ

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

निर्दिष्ट संपादित दस्तावेज़, जिसे '[`EditableDocument`](../../editabledocument)' के उदाहरण के रूप में दर्शाया गया है, को फ़ाइलनाम एक्सटेंशन से निर्धारित फ़ॉर्मेट के परिणामस्वरूप दस्तावेज़ में परिवर्तित करता है, और इसकी सामग्री को निर्दिष्ट फ़ाइल पथ द्वारा फ़ाइल में सहेजता है।

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| inputDocument | EditableDocument | इनपुट दस्तावेज़ का संस्करण, जिसे WYSIWYG HTML‑एडिटर में संपादित किया गया था और '[`EditableDocument`](../../editabledocument)' क्लास के इंस्टेंस के रूप में संग्रहीत किया गया है, जिसे कुछ विशिष्ट फ़ॉर्मेट के आउटपुट दस्तावेज़ में परिवर्तित किया जाना चाहिए। यह null या नष्ट नहीं होना चाहिए। |
| filePath | String | फ़ाइल का पथ, जिसमें आउटपुट दस्तावेज़ सहेजा जाएगा। यदि समान नाम की फ़ाइल मौजूद है, तो उसे पूरी तरह से पुनः लिखा जाएगा। पथ वाली स्ट्रिंग null, खाली या केवल व्हाइटस्पेस नहीं होनी चाहिए। क्योंकि डिफ़ॉल्ट सहेजने के विकल्प और आउटपुट फ़ॉर्मेट इस फ़ाइलनाम से निर्धारित होते हैं, इसलिए इसमें वैध एक्सटेंशन होना आवश्यक है। |

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

मॉडिफ़िकेशन के बाद मूल दस्तावेज़ (उदाहरण के लिए, [`FormFieldManager`](../formfieldmanager)) को निर्दिष्ट फ़ॉर्मेट के परिणामस्वरूप दस्तावेज़ में परिवर्तित करता है और इसकी सामग्री को प्रदान किए गए स्ट्रीम में सहेजता है।

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| outputDocument | Stream | स्ट्रीम जिसमें आउटपुट दस्तावेज़ सहेजा जाएगा। यह स्ट्रीम लिखने योग्य होनी चाहिए और दस्तावेज़ सामग्री की शुरुआत में स्थित होनी चाहिए। null नहीं होनी चाहिए। |
| saveOptions | WordProcessingSaveOptions | दस्तावेज़ सहेजने के विकल्प जो परिणामस्वरूप दस्तावेज़ के फ़ॉर्मेट तथा सामान्य और फ़ॉर्मेट-विशिष्ट सहेजने के विकल्प निर्धारित करते हैं। null नहीं होना चाहिए। |

### रिटर्न मान

सहेजे गए दस्तावेज़ सामग्री वाली स्ट्रीम।

### टिप्पणियाँ

यदि *outputDocument* या *saveOptions* null है, तो ArgumentNullException फेंका जाएगा। यदि सहेजने के लिए दस्तावेज़ अनुपलब्ध है, तो ArgumentNullException फेंका जाएगा।

जब *outputDocument* या *saveOptions* null हो, या सहेजने के लिए दस्तावेज़ अनुपलब्ध हो, तब फेंका जाता है।**और जानें:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### संबंधित देखें

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

वर्तमान दस्तावेज़ की सामग्री को निर्दिष्ट आउटपुट स्ट्रीम में सहेजें।

```csharp
public Stream Save(Stream outputDocument)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| outputDocument | Stream | स्ट्रीम जिसमें दस्तावेज़ सामग्री सहेजी जाएगी। यह null नहीं हो सकती। |

### रिटर्न मान

सहेजे गए दस्तावेज़ सामग्री वाली स्ट्रीम।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब *outputDocument* null हो या दस्तावेज़ सामग्री अनुपलब्ध हो, तब फेंका जाता है। |

### टिप्पणियाँ

यह विधि आंतरिक दस्तावेज़ प्रतिनिधित्व से सामग्री को प्रदान किए गए आउटपुट स्ट्रीम में कॉपी करती है। सहेजने के ऑपरेशन के बाद स्ट्रीम की मूल स्थिति संरक्षित रहती है।

### संबंधित देखें

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
