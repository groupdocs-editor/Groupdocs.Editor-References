---
title: "GetContent"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "निर्दिष्ट टेक्स्ट एन्कोडिंग के साथ निर्दिष्ट स्ट्रीम में इस सामग्री को लिखकर HTML दस्तावेज़ की संपूर्ण सामग्री को बाइट स्ट्रीम के रूप में लौटाता है"
type: docs
weight: 130
url: /hi/net/groupdocs.editor/editabledocument/getcontent/
---
## GetContent&lt;TStream&gt;(TStream, Encoding) {#getcontent_2}

निर्दिष्ट टेक्स्ट एन्कोडिंग के साथ निर्दिष्ट स्ट्रीम में इस सामग्री को लिखकर HTML दस्तावेज़ की संपूर्ण सामग्री को बाइट स्ट्रीम के रूप में लौटाता है

```csharp
public TStream GetContent<TStream>(TStream storage, Encoding encoding)
    where TStream : Stream
```

| Parameter | विवरण |
| --- | --- |
| TStream | स्ट्रीम का कोई भी कार्यान्वयन |
| storage | गैर-NULL बाइट स्ट्रीम, जो लिखने का समर्थन करता है |
| encoding | गैर-NULL टेक्स्ट एन्कोडिंग, जिसे निर्दिष्ट *storage* में टेक्स्ट सामग्री लिखते समय लागू किया जाना चाहिए |

### रिटर्न मान

निर्दिष्ट *स्टोरेज* का उदाहरण

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | इनपुट तर्कों में से कोई भी null है |
| ArgumentException | निर्दिष्ट स्ट्रीम लिखने योग्य नहीं है |

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent() {#getcontent}

HTML दस्तावेज़ की संपूर्ण सामग्री को स्ट्रिंग के रूप में लौटाता है।

```csharp
public string GetContent()
```

### रिटर्न मान

स्ट्रिंग, जिसमें HTML दस्तावेज़ की सामग्री होती है

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent(string, string) {#getcontent_1}

HTML दस्तावेज़ की संपूर्ण सामग्री को स्ट्रिंग के रूप में लौटाता है, जहाँ बाहरी संसाधनों के लिंक निर्दिष्ट टेम्प्लेट के साथ प्लेसहोल्डर्स शामिल करते हैं।

```csharp
public string GetContent(string externalImagesTemplate, string externalCssTemplate)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| externalImagesTemplate | String | इस पैरामीटर के माध्यम से उपयोगकर्ता एक स्ट्रिंग टेम्प्लेट एक प्लेसहोल्डर के साथ निर्दिष्ट कर सकता है, जिसे परिणामस्वरूप HTML स्ट्रिंग में मौजूद IMG तत्वों में सभी बाहरी छवियों के लिंक पर लागू किया जाएगा। यदि NULL या खाली है, तो टेम्प्लेट नहीं जोड़ा जाएगा, और शुद्ध फ़ाइलनाम परिणामस्वरूप HTML मार्कअप में उपस्थित रहेंगे। यदि टेम्प्लेट अमान्य है, तो इसे उपसर्ग के रूप में माना जाएगा, इसलिए फ़ाइलनाम उसके अंत में जोड़ दिए जाएंगे। |
| externalCssTemplate | String | इस पैरामीटर के माध्यम से आप एक स्ट्रिंग टेम्पलेट एक प्लेसहोल्डर के साथ निर्दिष्ट कर सकते हैं, जिसे सभी बाहरी स्टाइलशीट्स के LINK तत्वों में लिंक में जोड़ा जाएगा, जो परिणामी HTML स्ट्रिंग में उपस्थित होंगे। यदि NULL या खाली है, तो टेम्पलेट नहीं जोड़ा जाएगा, और शुद्ध फ़ाइलनाम परिणामी HTML मार्कअप में उपस्थित होंगे। यदि टेम्पलेट अमान्य है, तो इसे एक उपसर्ग माना जाएगा, इसलिए फ़ाइलनाम उसके अंत में जोड़ दिए जाएंगे। |

### रिटर्न मान

स्ट्रिंग, जिसमें लिंक सहित HTML दस्तावेज़ की सामग्री होती है, जो बाहरी संसाधनों के अनुसार समायोजित की गई है

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
