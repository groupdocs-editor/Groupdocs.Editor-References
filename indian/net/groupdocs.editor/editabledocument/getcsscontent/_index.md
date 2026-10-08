---
title: "GetCssContent"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सभी बाहरी स्टाइलशीट्स की सामग्री को स्ट्रिंग्स की सूची के रूप में लौटाता है जहाँ प्रत्येक स्ट्रिंग एक स्टाइलशीट का प्रतिनिधित्व करती है। यदि इस दस्तावेज़ के लिए कोई CSS नहीं है तो खाली सूची लौटाता है।"
type: docs
weight: 140
url: /hi/net/groupdocs.editor/editabledocument/getcsscontent/
---
## GetCssContent() {#getcsscontent}

सभी बाहरी स्टाइलशीट्स की सामग्री को स्ट्रिंग्स की सूची के रूप में लौटाता है, जहाँ प्रत्येक स्ट्रिंग एक स्टाइलशीट का प्रतिनिधित्व करती है। यदि इस दस्तावेज़ के लिए कोई CSS नहीं है तो खाली सूची लौटाता है।

```csharp
public List<string> GetCssContent()
```

### रिटर्न मान

स्ट्रिंग्स की एक सूची, जहाँ प्रत्येक स्ट्रिंग एक CSS दस्तावेज़ की सामग्री रखती है।

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetCssContent(string, string) {#getcsscontent_1}

सभी बाहरी स्टाइलशीट्स की सामग्री को स्ट्रिंग्स की सूची के रूप में लौटाता है, जहाँ प्रत्येक स्ट्रिंग एक स्टाइलशीट का प्रतिनिधित्व करती है। निर्दिष्ट प्रीफ़िक्स प्रत्येक परिणामी स्टाइलशीट में बाहरी संसाधन के हर लिंक पर लागू किया जाएगा। यदि इस दस्तावेज़ के लिए कोई CSS नहीं है तो खाली सूची लौटाता है।

```csharp
public List<string> GetCssContent(string externalImagesPrefix, string externalFontsPrefix)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| externalImagesPrefix | String | इस पैरामीटर के माध्यम से आप एक उपसर्ग निर्दिष्ट कर सकते हैं, जो सभी बाहरी छवियों के लिंक में जोड़ा जाएगा, जो परिणामस्वरूप CSS स्ट्रिंग्स में CSS घोषणाओं में उपस्थित होंगी। यदि NULL या खाली है, तो उपसर्ग नहीं जोड़े जाएंगे। |
| externalFontsPrefix | String | इस पैरामीटर के माध्यम से आप एक उपसर्ग निर्दिष्ट कर सकते हैं, जो परिणामस्वरूप CSS स्ट्रिंग्स में @font-face नियमों में सभी बाहरी फ़ॉन्ट्स के लिंक में जोड़ा जाएगा। यदि NULL या खाली है, तो उपसर्ग नहीं जोड़े जाएंगे। |

### रिटर्न मान

स्ट्रिंग्स की एक सूची, जहाँ प्रत्येक स्ट्रिंग एक CSS दस्तावेज़ की सामग्री रखती है।

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
