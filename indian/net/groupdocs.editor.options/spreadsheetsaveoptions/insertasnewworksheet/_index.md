---
title: "InsertAsNewWorksheet"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "Boolean flag जो यह निर्दिष्ट करता है कि संपादित वर्कशीट को मूल स्प्रेडशीट में निर्दिष्ट स्थिति पर मौजूद वर्कशीट को बदलना चाहिए या इसे मौजूदा वर्कशीट और पिछली वर्कशीट के बीच बिना उसकी सामग्री को बदले सम्मिलित किया जाना चाहिए। डिफ़ॉल्ट रूप से यह false है, मौजूदा वर्कशीट को बदल दिया जाएगा। यह प्रॉपर्टी तब अनदेखी की जाती है जब WorksheetNumbergroupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber प्रॉपर्टी का मान 0 पर सेट किया जाता है।"
type: docs
weight: 20
url: /hi/net/groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet/
---
## SpreadsheetSaveOptions.InsertAsNewWorksheet property

Boolean flag, जो यह निर्दिष्ट करता है कि संपादित वर्कशीट को मूल स्प्रेडशीट में उस स्थिति पर मौजूद वर्कशीट को बदलना चाहिए, जिसे [`WorksheetNumber`](../worksheetnumber) प्रॉपर्टी द्वारा निर्दिष्ट किया गया है, या इसे मौजूदा वर्कशीट और पिछली वर्कशीट के बीच बिना उसकी सामग्री को बदले सम्मिलित किया जाना चाहिए। डिफ़ॉल्ट रूप से यह false है — मौजूदा वर्कशीट को बदल दिया जाएगा। यह प्रॉपर्टी तब अनदेखी की जाती है, जब [`WorksheetNumber`](../worksheetnumber) प्रॉपर्टी का मान '0' पर सेट किया जाता है।

```csharp
public bool InsertAsNewWorksheet { get; set; }
```

### टिप्पणियाँ

डिफ़ॉल्ट रूप से वर्कशीट को बदल दिया जाता है। इसका अर्थ है कि यदि दिए गए स्प्रेडशीट में 5 वर्कशीट्स हैं, और [`WorksheetNumber`](../worksheetnumber)=4 है, तो 4थी वर्कशीट को नई संपादित वर्कशीट से बदल दिया जाएगा, जबकि स्प्रेडशीट में कुल वर्कशीट्स की संख्या (5) अपरिवर्तित रहेगी। हालांकि, यदि इस प्रॉपर्टी का मान true सेट किया जाता है, तो नई संपादित वर्कशीट को 4थी वर्कशीट के रूप में सम्मिलित किया जाएगा, और सभी बाद की वर्कशीट्स अंत की ओर स्थानांतरित हो जाएँगी: "old" 4थी वर्कशीट 5वीं बन जाएगी, और 5वीं 6वीं बन जाएगी, और स्प्रेडशीट में वर्कशीट्स की कुल संख्या एक से बढ़कर 6 हो जाएगी।

### संबंधित देखें

* class [SpreadsheetSaveOptions](../../spreadsheetsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
