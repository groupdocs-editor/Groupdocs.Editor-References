---
title: "सहेजें"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "इस HTML दस्तावेज़ को निर्दिष्ट पथ पर फ़ाइल में सहेजता है जहाँ HTML मार्कअप संग्रहीत होगा और संसाधनों वाले साथ वाले फ़ोल्डर में भी।"
type: docs
weight: 160
url: /hi/net/groupdocs.editor/editabledocument/save/
---
## Save(string) {#save_1}

निर्दिष्ट पथ पर फ़ाइल में इस HTML दस्तावेज़ को सहेजता है, जहाँ HTML मार्कअप संग्रहीत होगा, और संबंधित संसाधनों वाले फ़ोल्डर में भी।

```csharp
public void Save(string htmlFilePath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| htmlFilePath | String | फ़ाइल का पूर्ण पथ, जहाँ HTML मार्कअप संग्रहीत होगा। यदि फ़ाइल मौजूद है तो इसे बनाया या अधिलेखित किया जाएगा। साथ वाला संसाधन फ़ोल्डर उसी फ़ोल्डर में बनाया जाएगा जहाँ HTML फ़ाइल मौजूद है। |

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(string, string) {#save_2}

निर्दिष्ट पथ पर फ़ाइल में इस HTML दस्तावेज़ को सहेजता है, जहाँ HTML मार्कअप संग्रहीत होगा, और निर्दिष्ट पथ पर स्थित संबंधित संसाधनों वाले फ़ोल्डर में भी।

```csharp
public void Save(string htmlFilePath, string resourcesFolderPath)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| htmlFilePath | String | फ़ाइल का पूर्ण पथ, जहाँ HTML मार्कअप संग्रहीत होगा। यह NULL या खाली नहीं हो सकता। यदि फ़ाइल मौजूद है तो इसे बनाया या अधिलेखित किया जाएगा। |
| resourcesFolderPath | String | साथ वाले फ़ोल्डर का पूर्ण पथ, जहाँ सभी संबंधित संसाधन संग्रहीत होंगे। यदि NULL या खाली है, तो फ़ोल्डर स्वतः उसी निर्देशिका में बनाया जाएगा जहाँ *.html फ़ाइल है। यदि निर्दिष्ट है और मौजूद नहीं है, तो इसे बनाया जाएगा। |

### संबंधित देखें

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(TextWriter, HtmlSaveOptions) {#save}

इस [`EditableDocument`](../../editabledocument) की सामग्री को HTML दस्तावेज़ के रूप में निर्दिष्ट टेक्स्ट राइटर में सहेजता है, जबकि दूसरा विकल्प पैरामीटर सहेजने की प्रक्रिया को अनुकूलित करने और संसाधन सहेजने के कॉलबैक को निर्दिष्ट करने की अनुमति देता है।

```csharp
public void Save(TextWriter htmlMarkup, HtmlSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| htmlMarkup | TextWriter | टेक्स्ट राइटर का कार्यान्वयन, जिसमें HTML मार्कअप लिखा जाएगा। यह null नहीं हो सकता। |
| saveOptions | HtmlSaveOptions | HTML सहेजने के विकल्प, जो सहेजने की प्रक्रिया को नियंत्रित करते हैं: HTML-मार्कअप कैसे संग्रहीत किया जाता है (टैग नाम, कोट प्रकार) और CSS तथा अन्य संसाधन जैसे छवियों या फ़ॉन्ट्स को कैसे और कहाँ सहेजा जाएगा। उपयोगकर्ता को [`SavingCallback`](../../../groupdocs.editor.options/htmlsaveoptions/savingcallback) प्रॉपर्टी में इंटरफ़ेस के इनहेरिटर को निर्दिष्ट करना चाहिए ताकि यह नियंत्रित किया जा सके कि संसाधनों को कैसे सहेजा और HTML-मार्कअप से संदर्भित किया जाए। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | निर्दिष्ट तर्कों में से कोई भी या *saveOptions* में `SavingCallback` प्रॉपर्टी `null` है। |

### संबंधित देखें

* class [HtmlSaveOptions](../../../groupdocs.editor.options/htmlsaveoptions)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
