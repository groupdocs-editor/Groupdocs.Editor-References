---
title: "MergeEmptyAdjacentCells"
second_title: "GroupDocs.Editor के लिए .NET API रेफ़रेंस"
description: "सक्षम होने पर इनपुट Spreadsheet दस्तावेज़ की खाली सन्निहित क्षैतिज सेल्स को संपादन योग्य HTML दस्तावेज़ में एकल सेल में मर्ज किया जाएगा, जिसमें उपयुक्त colspan एट्रिब्यूट होगा। डिफ़ॉल्ट रूप में यह अक्षम (false) है।"
type: docs
weight: 40
url: /hi/net/groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells/
---
## SpreadsheetEditOptions.MergeEmptyAdjacentCells property

सक्षम होने पर, इनपुट स्प्रेडशीट दस्तावेज़ की खाली क्रमागत क्षैतिज सेल्स को संपादन योग्य HTML दस्तावेज़ में संबंधित `colspan` एट्रिब्यूट के साथ एकल सेल में मर्ज किया जाएगा। डिफ़ॉल्ट रूप से यह अक्षम (`false`) है।

```csharp
public bool MergeEmptyAdjacentCells { get; set; }
```

### टिप्पणियाँ

डिफ़ॉल्ट रूप में GroupDocs.Editor इनपुट Spreadsheet दस्तावेज़ से एक टेबल को आउटपुट HTML दस्तावेज़ में प्रत्येक सेल को संरक्षित रखते हुए परिवर्तित करता है। हालांकि, Spreadsheet दस्तावेज़ विरल हो सकते हैं — उनमें बड़ी मात्रा में "खाली क्षेत्रों" हो सकते हैं, जहाँ कई सेल्स खाली होते हैं। यह विकल्प, जब सक्षम किया जाता है, ऐसे खाली सेल्स को `colspan` एट्रिब्यूट वाले `TD` एलिमेंट में एकल सेल में मर्ज कर देता है, जिससे उत्पन्न HTML मार्कअप का आकार काफी घट सकता है।

### संबंधित देखें

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.editor.dll के लिए उत्पन्न किया गया -->
