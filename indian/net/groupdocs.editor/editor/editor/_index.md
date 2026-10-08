---
title: "Editor"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "Editorgroupdocs.editor/editor क्लास का नया उदाहरण आरंभ करता है और निर्दिष्ट फ़ॉर्मेट के आधार पर एक नया खाली दस्तावेज़ बनाता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

[`Editor`](../../editor) क्लास का नया उदाहरण आरंभ करता है और निर्दिष्ट फ़ॉर्मेट के आधार पर एक नया खाली दस्तावेज़ बनाता है।

```csharp
public Editor(DocumentFormatBase format)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| फ़ॉर्मेट | DocumentFormatBase | उस दस्तावेज़ का फ़ाइल फ़ॉर्मेट दर्शाता है जो बनाया जाएगा। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### उदाहरण

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // संपादक उदाहरण का उपयोग करके दस्तावेज़ों को संपादित और सहेजें
}
```

### संबंधित देखें

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

निर्दिष्ट इनपुट दस्तावेज़ (स्ट्रीम के रूप में) के साथ नया Editor इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Editor(Stream document)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| दस्तावेज़ | Stream | स्ट्रीम जिसमें दस्तावेज़ सामग्री है। null नहीं होना चाहिए। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### उदाहरण

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // संपादक उदाहरण का उपयोग करके दस्तावेज़ों को संपादित और सहेजें
    }
}
```

### संबंधित देखें

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

निर्दिष्ट इनपुट दस्तावेज़ (स्ट्रीम के रूप में) को उसकी लोड विकल्पों के साथ नया Editor इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| दस्तावेज़ | Stream | स्ट्रीम जिसमें दस्तावेज़ सामग्री है। null नहीं होना चाहिए। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। null हो सकता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | जब दस्तावेज़ स्ट्रीम null हो तो फेंका जाता है। |
| ArgumentException | जब दस्तावेज़ स्ट्रीम अमान्य हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### उदाहरण

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // संपादक उदाहरण का उपयोग करके दस्तावेज़ों को संपादित और सहेजें
    }
}
```

### संबंधित देखें

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

निर्दिष्ट इनपुट दस्तावेज़ (पूर्ण फ़ाइल पाथ के रूप में) को उसकी लोड विकल्पों के साथ नया Editor इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल का पूर्ण पथ। यह null, खाली या केवल whitespace नहीं होना चाहिए। यह वैध होना चाहिए, और फ़ाइल मौजूद होनी चाहिए। |
| loadOptions | ILoadOptions | दस्तावेज़ लोड विकल्प। null हो सकता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | जब फ़ाइल पथ अमान्य हो तो फेंका जाता है। |
| FileNotFoundException | जब फ़ाइल मौजूद नहीं है तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### उदाहरण

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // संपादक उदाहरण का उपयोग करके दस्तावेज़ों को संपादित और सहेजें
}
```

### संबंधित देखें

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

निर्दिष्ट इनपुट दस्तावेज़ (पूर्ण फ़ाइल पाथ के रूप में) और Editor सेटिंग्स के साथ नया Editor इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Editor(string filePath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| filePath | String | फ़ाइल का पूर्ण पथ। यह NULL नहीं होना चाहिए। यह वैध होना चाहिए, और फ़ाइल मौजूद होनी चाहिए। |

### संबंधित देखें

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
