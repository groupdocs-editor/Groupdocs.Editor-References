---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "संपादित होने के बाद WordProcessingcompliant दस्तावेज़ों को उत्पन्न करने और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 1240
url: /hi/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

संपादन के बाद वर्डप्रोसेसिंग‑अनुपालन दस्तावेज़ उत्पन्न करने और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | यह पैरामीटर‑रहित कंस्ट्रक्टर DOCX आउटपुट फ़ॉर्मेट के साथ WordProcessingSaveOptions का नया इंस्टेंस बनाता है (इसे बाद में [`OutputFormat`](./outputformat) प्रॉपर्टी के माध्यम से संशोधित किया जा सकता है) |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(WordProcessingFormats) | निर्दिष्ट अनिवार्य WordProcessing आउटपुट फ़ॉर्मेट के साथ WordProcessingSaveOptions का नया इंस्टेंस बनाता है, जबकि अन्य सभी पैरामीटर डिफ़ॉल्ट होते हैं |

## गुण

| नाम | विवरण |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | WordProcessing दस्तावेज़ को सहेजने के लिए उपयोग की जाने वाली पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। यदि मूल दस्तावेज़ पेजिनेशन मोड में खोला और संपादित किया गया था, तो यह विकल्प भी सक्षम होना चाहिए। डिफ़ॉल्ट रूप से यह अक्षम है। |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | आउटपुट WordProcessing दस्तावेज़ में फ़ॉन्ट संसाधनों को एम्बेड करने के लिए ज़िम्मेदार है। डिफ़ॉल्ट रूप से कोई फ़ॉन्ट एम्बेड नहीं करता (NotEmbed)। |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | WordProcessing दस्तावेज़ के लिए डिफ़ॉल्ट लोकेल (भाषा) को ओवरराइड सेट करने की अनुमति देता है, जो निर्माण के दौरान लागू होगा। जब निर्दिष्ट नहीं किया जाता (डिफ़ॉल्ट मान), तो MS Word (या अन्य प्रोग्राम) अपने सेटिंग्स या अन्य कारकों के अनुसार दस्तावेज़ का लोकेल पहचान (या चुन) लेगा। |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | RTL (दाएँ‑से‑बाएँ) टेक्स्ट के लिए लोकेल (भाषा) को ओवरराइड सेट करने की अनुमति देता है, जो निर्माण के दौरान लागू होगा। जब निर्दिष्ट नहीं किया जाता (डिफ़ॉल्ट मान), तो MS Word (या अन्य प्रोग्राम) अपने सेटिंग्स या अन्य कारकों के अनुसार दस्तावेज़ का RTL लोकेल पहचान (या चुन) लेगा। |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | East-Asian टेक्स्ट के लिए WordProcessing दस्तावेज़ का लोकेल (भाषा) ओवरराइड करने की अनुमति देता है, जो निर्माण के दौरान लागू होगा। जब निर्दिष्ट नहीं किया जाता (डिफ़ॉल्ट मान), तो MS Word (या अन्य प्रोग्राम) अपने सेटिंग्स या अन्य कारकों के अनुसार दस्तावेज़ का East-Asian लोकेल पहचान (या चुन) लेगा। |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | HTML से दस्तावेज़ जनरेट करने के दौरान मेमोरी ऑप्टिमाइज़ेशन मैकेनिज़्म सक्षम करता है, जो मेमोरी उपयोग कम करने की कीमत पर प्रदर्शन को घटाता है। इस विकल्प को true सेट करने से बड़े दस्तावेज़ जनरेट करते समय मेमोरी खपत में काफी कमी आ सकती है, लेकिन सहेजने के समय धीमा हो जाता है। डिफ़ॉल्ट रूप से false है (बेहतर प्रदर्शन के लिए मेमोरी ऑप्टिमाइज़ेशन अक्षम है)। |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | दस्तावेज़ को सहेजने के लिए उपयोग किए जाने वाले WordProcessing फ़ॉर्मेट को निर्दिष्ट करने की अनुमति देता है |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | जनरेट किए गए WordProcessing दस्तावेज़ को एन्कोड करने के लिए उपयोग किए जाने वाले पासवर्ड को निर्दिष्ट, संशोधित, प्राप्त या हटाने की अनुमति देता है। पासवर्ड हटाने (साफ़ करने) के लिए NULL या खाली स्ट्रिंग निर्दिष्ट करें। |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | किसी भी फ़ॉर्मेट के WordProcessing दस्तावेज़ के लिए दस्तावेज़ सुरक्षा विकल्पों को नियंत्रित और लागू करने की अनुमति देता है, जो दस्तावेज़ सुरक्षा को समर्थन देता है। डिफ़ॉल्ट रूप से यह NULL है - दस्तावेज़ सुरक्षा उपयोग नहीं की जाएगी। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | WordProcessingSaveOptions क्लास के इस इंस्टेंस की पूरी कॉपी बनाता और लौटाता है |

### टिप्पणियाँ

WordProcessingSaveOptions उन स्थितियों में लागू किया जाता है जब EditableDocument क्लास का एक इंस्टेंस हो, जिसमें संपादित दस्तावेज़ सामग्री हो, और इस सामग्री को WordProcessing फ़ॉर्मेट के नए दस्तावेज़ में सहेजना आवश्यक हो।

### संबंधित देखें

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
