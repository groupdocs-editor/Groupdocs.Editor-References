---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "वर्कशीट सुरक्षा विकल्पों को समाहित करता है जो आउटपुट स्प्रेडशीट दस्तावेज़ में वर्कशीट को निर्दिष्ट प्रकार के संशोधन से निर्दिष्ट पासवर्ड के साथ सुरक्षित करने की अनुमति देते हैं।"
type: docs
weight: 1250
url: /hi/net/groupdocs.editor.options/worksheetprotection/
---
## WorksheetProtection class

स्प्रेडशीट आउटपुट दस्तावेज़ में वर्कशीट को निर्दिष्ट प्रकार के संशोधन से निर्दिष्ट पासवर्ड के साथ सुरक्षित करने के लिए वर्कशीट सुरक्षा विकल्पों को समाहित करता है

```csharp
public sealed class WorksheetProtection
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [WorksheetProtection](worksheetprotection#constructor)() | डिफ़ॉल्ट पैरामीटरों के साथ नया इंस्टेंस बनाता है। यदि संशोधित नहीं किया गया और SpreadsheetSaveOptions को पास किया गया, तो कोई वर्कशीट सुरक्षा लागू नहीं होगी। |
| [WorksheetProtection](worksheetprotection#constructor_1)(WorksheetProtectionType, string) | निर्दिष्ट वर्कशीट सुरक्षा प्रकार और पासवर्ड के साथ नया इंस्टेंस बनाता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Password](../../groupdocs.editor.options/worksheetprotection/password) { get; set; } | पासवर्ड, जिसका उपयोग वर्कशीट को सुरक्षित करने के लिए किया जाता है। यदि NULL या खाली स्ट्रिंग है, तो सुरक्षा लागू नहीं होगी। |
| [ProtectionType](../../groupdocs.editor.options/worksheetprotection/protectiontype) { get; set; } | वर्कशीट सुरक्षा का प्रकार निर्दिष्ट करने की अनुमति देता है। डिफ़ॉल्ट रूप से 'None' है - सुरक्षा लागू नहीं होती। |

### टिप्पणियाँ

XLSX जैसे अधिकांश स्प्रेडशीट फ़ॉर्मेट पासवर्ड के साथ वर्कशीट को संपादन से सुरक्षित करने की अनुमति देते हैं। यह क्लास ऐसी सुरक्षा को सक्षम करने और उसके विकल्प निर्दिष्ट करने की अनुमति देती है।

### संबंधित देखें

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
