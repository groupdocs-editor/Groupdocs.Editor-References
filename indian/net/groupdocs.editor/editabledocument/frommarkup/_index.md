---
title: "FromMarkup"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "स्थैतिक फ़ैक्टरी जो निर्दिष्ट HTML मार्कअप से EditableDocumentgroupdocs.editor/editabledocument का एक उदाहरण बनाती है।"
type: docs
weight: 20
url: /hi/net/groupdocs.editor/editabledocument/frommarkup/
---
## FromMarkup(string) {#frommarkup}

स्थैतिक फ़ैक्टरी, जो निर्दिष्ट HTML मार्कअप से [`EditableDocument`](../../editabledocument) का एक उदाहरण बनाती है।

```csharp
public static EditableDocument FromMarkup(string newHtmlContent)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| newHtmlContent | String | String, जिसमें कच्चा HTML मार्कअप होता है, जिसे पार्स किया जाना चाहिए। NULL, खाली या अमान्य नहीं हो सकता। |

### रिटर्न मान

EditableDocument का नया गैर-NULL उदाहरण

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | इनपुट कच्चे HTML मार्कअप वाली स्ट्रिंग null या खाली नहीं हो सकती। |

### टिप्पणियाँ

यह स्थैतिक मेथड एकल-स्ट्रिंग HTML markup से [`EditableDocument`](../../editabledocument) का उदाहरण बनाने के लिए उपयोगी है, जहाँ सभी संसाधन base64 एन्कोडिंग के साथ उसमें एम्बेड किए जाते हैं।

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## FromMarkup(string, IEnumerable&lt;IHtmlResource&gt;) {#frommarkup_1}

स्थैतिक फ़ैक्टरी, जो निर्दिष्ट HTML मार्कअप और संबंधित लिंक्ड संसाधनों के सेट से EditableDocument की एक इंस्टेंस बनाती है

```csharp
public static EditableDocument FromMarkup(string newHtmlContent, 
    IEnumerable<IHtmlResource> resources)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| newHtmlContent | String | String, जिसमें कच्चा HTML मार्कअप होता है, जिसे पार्स किया जाना चाहिए। NULL, खाली या अमान्य नहीं हो सकता। |
| resources | IEnumerable`1 | HTML‑दस्तावेज़ में उपयोग किए गए सभी संसाधनों (छवियों, स्टाइलशीट्स, फ़ॉन्ट्स) का संग्रह, जो *newHtmlContent* पैरामीटर में निर्दिष्ट है। यह अनुपलब्ध (NULL या खाली संग्रह) हो सकता है। |

### रिटर्न मान

EditableDocument का नया गैर-NULL उदाहरण

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | इनपुट कच्चे HTML मार्कअप वाली स्ट्रिंग null या खाली नहीं हो सकती। |

### संबंधित देखें

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
