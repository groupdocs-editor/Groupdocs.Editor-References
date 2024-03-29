---
title: Editor
second_title: .NET API संदर्भ के लिए GroupDocs.Editor
description: नर्दष्ट इनपुट दस्तवेज़ एक धर के रूप में के सथ नए संपदक उदहरण क प्ररंभ करत है
type: docs
weight: 10
url: /hi/net/groupdocs.editor/editor/editor/
---
## Editor(Func&lt;Stream&gt;) {#constructor}

निर्दिष्ट इनपुट दस्तावेज़ (एक धारा के रूप में) के साथ नए संपादक उदाहरण को प्रारंभ करता है

```csharp
public Editor(Func<Stream> document)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`1 | डेलिगेट, जिसे दस्तावेज़ सामग्री के साथ एक स्ट्रीम वापस करनी चाहिए। NULL नहीं होना चाहिए। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। संपादक: [GroupDocs.Editor द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Editor के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### यह सभी देखें

* class [Editor](../../editor)
* नाम स्थान [GroupDocs.Editor](../../editor)
* सभा [GroupDocs.Editor](../../../)

---

## Editor(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) {#constructor_1}

निर्दिष्ट इनपुट दस्तावेज़ (स्ट्रीम के रूप में) के लोड विकल्पों के साथ नए संपादक उदाहरण को प्रारंभ करता है

```csharp
public Editor(Func<Stream> document, Func<ILoadOptions> loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| document | Func`1 | डेलिगेट, जिसे दस्तावेज़ सामग्री के साथ एक स्ट्रीम वापस करनी चाहिए। NULL नहीं होना चाहिए। |
| loadOptions | Func`1 | डेलिगेट, जिसे एक दस्तावेज़ लोड विकल्प वापस करना चाहिए। NULL हो सकता है और वापस लौट सकता है null - उस स्थिति में दस्तावेज़ प्रकार स्वचालित रूप से पहचाना जाएगा और उस प्रकार के लिए डिफ़ॉल्ट लोड विकल्प लागू किए जाएंगे। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। संपादक: [GroupDocs.Editor द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Editor के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* विभिन्न स्टोरेज से पासवर्ड से सुरक्षित दस्तावेज़ों और दस्तावेज़ को खोलने और संपादित करने के तरीके के बारे में अधिक जानकारी: [GroupDocs.Editor का उपयोग करके दस्तावेज़ों को लोड और संपादित करें](https://docs.groupdocs.com/display/editornet/Load+document)

### यह सभी देखें

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* नाम स्थान [GroupDocs.Editor](../../editor)
* सभा [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_2}

निर्दिष्ट इनपुट दस्तावेज़ (एक पूर्ण फ़ाइल पथ के रूप में) के साथ नए संपादक उदाहरण को प्रारंभ करता है

```csharp
public Editor(string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल का पूर्ण पथ। NULL नहीं होना चाहिए। मान्य होना चाहिए, और फ़ाइल मौजूद होनी चाहिए। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। संपादक: [GroupDocs.Editor द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Editor के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### यह सभी देखें

* class [Editor](../../editor)
* नाम स्थान [GroupDocs.Editor](../../editor)
* सभा [GroupDocs.Editor](../../../)

---

## Editor(string, Func&lt;ILoadOptions&gt;) {#constructor_3}

अपने लोड विकल्पों के साथ निर्दिष्ट इनपुट दस्तावेज़ (एक पूर्ण फ़ाइल पथ के रूप में) के साथ नए संपादक उदाहरण को प्रारंभ करता है

```csharp
public Editor(string filePath, Func<ILoadOptions> loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल का पूर्ण पथ। NULL नहीं होना चाहिए। मान्य होना चाहिए, और फ़ाइल मौजूद होनी चाहिए। |
| loadOptions | Func`1 | डेलिगेट, जिसे एक दस्तावेज़ लोड विकल्प वापस करना चाहिए। NULL हो सकता है और वापस लौट सकता है null - उस स्थिति में दस्तावेज़ प्रकार स्वचालित रूप से पहचाना जाएगा और उस प्रकार के लिए डिफ़ॉल्ट लोड विकल्प लागू किए जाएंगे। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। संपादक: [GroupDocs.Editor द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Editor के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* विभिन्न स्टोरेज से पासवर्ड से सुरक्षित दस्तावेज़ों और दस्तावेज़ को खोलने और संपादित करने के तरीके के बारे में अधिक जानकारी: [GroupDocs.Editor का उपयोग करके दस्तावेज़ों को लोड और संपादित करें](https://docs.groupdocs.com/display/editornet/Load+document)

### यह सभी देखें

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* नाम स्थान [GroupDocs.Editor](../../editor)
* सभा [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
