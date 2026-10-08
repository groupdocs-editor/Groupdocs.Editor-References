---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "Spreadsheet Excelcompliant दस्तावेज़ों को जनरेट और सेव करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 1130
url: /hi/net/groupdocs.editor.options/spreadsheetsaveoptions/
---
## SpreadsheetSaveOptions class

स्प्रेडशीट (Excel-सम्प्रदायिक) दस्तावेज़ों को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है

```csharp
public sealed class SpreadsheetSaveOptions : ISaveOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor)() | यह पैरामीटरलेस कन्स्ट्रक्टर SpreadsheetSaveOptions का नया इंस्टेंस बनाता है जिसमें XLSX आउटपुट फ़ॉर्मेट होता है (फिर इसे [`OutputFormat`](./outputformat) प्रॉपर्टी के माध्यम से संशोधित किया जा सकता है) |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor_1)(SpreadsheetFormats) | निर्दिष्ट अनिवार्य Spreadsheet आउटपुट फ़ॉर्मेट के साथ SpreadsheetSaveOptions का नया इंस्टेंस बनाता है, जबकि सभी अन्य पैरामीटर डिफ़ॉल्ट होते हैं |

## गुण

| नाम | विवरण |
| --- | --- |
| [InsertAsNewWorksheet](../../groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet) { get; set; } | Boolean फ़्लैग, जो यह निर्दिष्ट करता है कि संपादित वर्कशीट को मूल स्प्रेडशीट में मौजूदा वर्कशीट को उस स्थिति पर बदलना चाहिए, जो [`WorksheetNumber`](./worksheetnumber) प्रॉपर्टी द्वारा निर्दिष्ट है, या इसे मौजूदा वर्कशीट और पिछले वर्कशीट के बीच डाला जाना चाहिए, बिना उसकी सामग्री को बदले। डिफ़ॉल्ट रूप से यह false है — मौजूदा वर्कशीट बदल दी जाएगी। यह प्रॉपर्टी अनदेखी की जाती है, यदि [`WorksheetNumber`](./worksheetnumber) प्रॉपर्टी का मान '0' पर सेट किया गया है। |
| [OutputFormat](../../groupdocs.editor.options/spreadsheetsaveoptions/outputformat) { get; set; } | दस्तावेज़ को सेव करने के लिए उपयोग किए जाने वाले Spreadsheet फ़ॉर्मेट को निर्दिष्ट करने की अनुमति देता है |
| [Password](../../groupdocs.editor.options/spreadsheetsaveoptions/password) { get; set; } | जनरेट किए गए Spreadsheet दस्तावेज़ को एन्कोड करने के लिए उपयोग किए जाने वाले पासवर्ड को निर्दिष्ट, संशोधित, प्राप्त या हटाने की अनुमति देता है, यदि उस दस्तावेज़ फ़ॉर्मेट में पासवर्ड सुरक्षा समर्थित है। पासवर्ड हटाने (साफ़ करने) के लिए NULL या खाली स्ट्रिंग निर्दिष्ट करें। |
| [WorksheetNumber](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber) { get; set; } | नए सिंगल-वर्कशीट स्प्रेडशीट बनाने (डिफ़ॉल्ट व्यवहार) के बजाय मौजूदा स्प्रेडशीट की कॉपी में संपादित वर्कशीट को सम्मिलित करने की अनुमति देता है। WorksheetNumber संपादक क्लास में लोड किए गए स्प्रेडशीट में वर्कशीट का 1-आधारित नंबर है। यदि यह 0 (डिफ़ॉल्ट मान) है, तो नया स्प्रेडशीट एकल संपादित वर्कशीट के साथ बनाया जाएगा। यदि यह शून्य से बड़ा या छोटा है, और संपादक क्लास में वैध स्प्रेडशीट लोड है, तो इनपुट EditableDocument इंस्टेंस द्वारा प्रतिनिधित्व की गई संपादित वर्कशीट इस स्प्रेडशीट में सम्मिलित की जाएगी। |
| [WorksheetNumbersToDelete](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete) { get; set; } | स्प्रेडशीट को सेव करते समय हटाए जाने वाले वर्कशीटों के 1-आधारित नंबरों की एक एरे निर्दिष्ट करने की अनुमति देता है, जब संपादित वर्कशीट मौजूदा स्प्रेडशीट में सम्मिलित की गई हो। |
| [WorksheetProtection](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetprotection) { get; set; } | आउटपुट Spreadsheet दस्तावेज़ के लिए वर्कशीट सुरक्षा को सक्षम करने की अनुमति देता है। डिफ़ॉल्ट रूप से यह NULL है - सुरक्षा लागू नहीं होती। सभी फ़ॉर्मेट वर्कशीट सुरक्षा का समर्थन नहीं करते। |

### संबंधित देखें

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
