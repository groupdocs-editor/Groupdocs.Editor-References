---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "दस्तावेज़ों को संपादित करने के लिए सभी समर्थित WordProcessing Wordscompliant फ़ॉर्मेट जैसे DOCX, RTF, ODT आदि के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 1200
url: /hi/net/groupdocs.editor.options/wordprocessingeditoptions/
---
## WordProcessingEditOptions class

सभी समर्थित वर्डप्रोसेसिंग (Words‑अनुपालन) फ़ॉर्मैट जैसे DOC(X), RTF, ODT आदि के दस्तावेज़ संपादन के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

```csharp
public class WordProcessingEditOptions : IEditOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor)() | WordProcessingEditOptions क्लास की एक नई इंस्टेंस बनाता है और लौटाता है, जहाँ सभी विकल्प उनके डिफ़ॉल्ट मानों पर सेट होते हैं। |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor_1)(bool) | निर्दिष्ट पेजिनेशन के साथ WordProcessingEditOptions क्लास की एक नई इंस्टेंस बनाता है और लौटाता है, तथा अन्य सभी विकल्प डिफ़ॉल्ट रहते हैं। |

## गुण

| नाम | विवरण |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/wordprocessingeditoptions/enablelanguageinformation) { get; set; } | निर्दिष्ट करता है कि क्या भाषा जानकारी को HTML मार्कअप में 'lang' HTML एट्रिब्यूट्स के रूप में निर्यात किया जाए। यह विकल्प बहुभाषी दस्तावेज़ों के राउंडट्रिप रूपांतरण के लिए उपयोगी हो सकता है। डिफ़ॉल्ट रूप से यह निष्क्रिय है (false). |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingeditoptions/enablepagination) { get; set; } | परिणामी HTML दस्तावेज़ में पेजिनेशन को सक्षम या अक्षम करने की अनुमति देता है। डिफ़ॉल्ट रूप से अक्षम (false) है। |
| [ExtractOnlyUsedFont](../../groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या केवल दस्तावेज़ की पाठ्य सामग्री में उपयोग किए गए फ़ॉन्ट संसाधनों को निकाला जाए। |
| [FontExtraction](../../groupdocs.editor.options/wordprocessingeditoptions/fontextraction) { get; set; } | इनपुट WordProcessing दस्तावेज़ में उपयोग किए गए फ़ॉन्ट संसाधनों को निकालने के लिए जिम्मेदार है। डिफ़ॉल्ट रूप से कोई फ़ॉन्ट नहीं निकाला जाता (NotExtract). |
| [InputControlsClassName](../../groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname) { get; set; } | एक क्लास नाम निर्दिष्ट करने की अनुमति देता है, जो इनपुट WordProcessing दस्तावेज़ में किसी फ़ील्ड का प्रतिनिधित्व करने वाले प्रत्येक HTML तत्व के 'class' एट्रिब्यूट में रखा जाएगा। डिफ़ॉल्ट रूप से यह NULL है - 'class' एट्रिब्यूट लागू नहीं होते। |
| [UseInlineStyles](../../groupdocs.editor.options/wordprocessingeditoptions/useinlinestyles) { get; set; } | इनपुट WordProcessing दस्तावेज़ के स्टाइलिंग और फॉर्मेटिंग डेटा को कहाँ संग्रहीत किया जाए, यह नियंत्रित करता है: बाहरी स्टाइलशीट (`false`) में या HTML मार्कअप में इनलाइन स्टाइल्स (`true`) के रूप में। डिफ़ॉल्ट रूप से बाहरी स्टाइल्स उपयोग किए जाते हैं (`false`). |

### संबंधित देखें

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
