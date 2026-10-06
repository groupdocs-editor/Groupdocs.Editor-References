---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "सभी समर्थित Spreadsheet Excel-संगत फ़ॉर्मेट के दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 35
url: /hi/java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

सभी समर्थित दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है
Spreadsheet (Excel-संगत) फ़ॉर्मेट

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | इनपुट वर्कशीट (टैब) का 0-आधारित इंडेक्स निर्दिष्ट करने की अनुमति देता है। |
Spreadsheet दस्तावेज़, जिसे HTML में परिवर्तित किया जाना चाहिए (देखें
टिप्पणियाँ)।
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | इनपुट वर्कशीट (टैब) का 0-आधारित इंडेक्स निर्दिष्ट करने की अनुमति देता है। |
Spreadsheet दस्तावेज़, जिसे HTML में परिवर्तित किया जाना चाहिए (देखें
टिप्पणियाँ)।
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | इनपुट Spreadsheet दस्तावेज़ में छिपी वर्कशीट्स को बाहर करने की अनुमति देता है, ताकि |
वे पूरी तरह से अनदेखी कर दी जाएँगी।
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | इनपुट Spreadsheet दस्तावेज़ में छिपी वर्कशीट्स को बाहर करने की अनुमति देता है, ताकि |
वे पूरी तरह से अनदेखी कर दी जाएँगी।
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | सक्षम होने पर, इनपुट Spreadsheet दस्तावेज़ की खाली सन्निहित क्षैतिज कोशिकाएँ |
संपादन योग्य HTML दस्तावेज़ में संबंधित
colspan विशेषता।
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | सक्षम होने पर, उत्पन्न HTML दस्तावेज़ में HTML तालिका में नीचे की खाली छिपी पंक्ति होती है जिसमें |
शून्य ऊँचाई और खाली कोशिकाएँ होती हैं, जहाँ केवल चौड़ाई निर्दिष्ट की गई है।
|
| [setExportBogusRowData(boolean value)](#setExportBogusRowData-boolean-) |  |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


इनपुट वर्कशीट (टैब) का 0-आधारित इंडेक्स निर्दिष्ट करने की अनुमति देता है।
Spreadsheet दस्तावेज़, जिसे HTML में परिवर्तित किया जाना चाहिए (देखें
टिप्पणियाँ)।


*** ** * ** ***

अधिकांश Spreadsheet दस्तावेज़ टैब की अवधारणा का समर्थन करते हैं, अर्थात वे बहु‑टैब हो सकते हैं। दूसरी ओर, HTML फ़ॉर्मेट ऐसी संरचना का समर्थन नहीं करता। इसी कारण GroupDocs.Editor इनपुट दस्तावेज़ के केवल एक विशिष्ट टैब को HTML में परिवर्तित कर सकता है, और यह विकल्प उसे निर्दिष्ट करने की अनुमति देता है। टैब इंडेक्स 0‑आधारित है, नकारात्मक मान प्रतिबंधित हैं। यदि निर्दिष्ट इंडेक्स सभी टैबों की संख्या से अधिक हो जाता है, तो अपवाद फेंका जाएगा। यदि इनपुट Spreadsheet दस्तावेज़ में केवल एक टैब है, तो यह विकल्प अनदेखा किया जाएगा। डिफ़ॉल्ट मान 0 (पहला टैब) है।

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


इनपुट वर्कशीट (टैब) का 0-आधारित इंडेक्स निर्दिष्ट करने की अनुमति देता है।
Spreadsheet दस्तावेज़, जिसे HTML में परिवर्तित किया जाना चाहिए (देखें
टिप्पणियाँ)।


*** ** * ** ***

अधिकांश Spreadsheet दस्तावेज़ टैब की अवधारणा का समर्थन करते हैं, अर्थात वे बहु‑टैब हो सकते हैं। दूसरी ओर, HTML फ़ॉर्मेट ऐसी संरचना का समर्थन नहीं करता। इसी कारण GroupDocs.Editor इनपुट दस्तावेज़ के केवल एक विशिष्ट टैब को HTML में परिवर्तित कर सकता है, और यह विकल्प उसे निर्दिष्ट करने की अनुमति देता है। टैब इंडेक्स 0‑आधारित है, नकारात्मक मान प्रतिबंधित हैं। यदि निर्दिष्ट इंडेक्स सभी टैबों की संख्या से अधिक हो जाता है, तो अपवाद फेंका जाएगा। यदि इनपुट Spreadsheet दस्तावेज़ में केवल एक टैब है, तो यह विकल्प अनदेखा किया जाएगा। डिफ़ॉल्ट मान 0 (पहला टैब) है।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


इनपुट Spreadsheet दस्तावेज़ में छिपी वर्कशीट्स को बाहर करने की अनुमति देता है, ताकि
वे पूरी तरह से अनदेखी कर दी जाएँगी। डिफ़ॉल्ट रूप से false है - छिपी वर्कशीट्स
उपलब्ध हैं और सामान्य रूप से प्रोसेस की जाती हैं।


*** ** * ** ***

कई बाइनरी Spreadsheet फ़ॉर्मेट (जैसे XLSX) छिपी वर्कशीट्स (टैब) की अवधारणा का समर्थन करते हैं। ऐसे फ़ॉर्मेट के दस्तावेज़ में, यदि एक से अधिक वर्कशीट हैं, तो अतिरिक्त छिपी वर्कशीट्स हो सकती हैं। डिफ़ॉल्ट रूप से ऐसी छिपी वर्कशीट्स प्रोसेसिंग के लिए उपलब्ध होती हैं, लेकिन इस विकल्प के साथ उन्हें अनदेखा किया जा सकता है, जैसे कि ये छिपी वर्कशीट्स मौजूद नहीं हैं। जब यह विकल्प सक्षम होता है, तो आप ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' प्रॉपर्टी के साथ छिपी वर्कशीट का चयन नहीं कर सकते।

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


इनपुट Spreadsheet दस्तावेज़ में छिपी वर्कशीट्स को बाहर करने की अनुमति देता है, ताकि
वे पूरी तरह से अनदेखी कर दी जाएँगी। डिफ़ॉल्ट रूप से false है - छिपी वर्कशीट्स
उपलब्ध हैं और सामान्य रूप से प्रोसेस की जाती हैं।


*** ** * ** ***

कई बाइनरी Spreadsheet फ़ॉर्मेट (जैसे XLSX) छिपी वर्कशीट्स (टैब) की अवधारणा का समर्थन करते हैं। ऐसे फ़ॉर्मेट के दस्तावेज़ में, यदि एक से अधिक वर्कशीट हैं, तो अतिरिक्त छिपी वर्कशीट्स हो सकती हैं। डिफ़ॉल्ट रूप से ऐसी छिपी वर्कशीट्स प्रोसेसिंग के लिए उपलब्ध होती हैं, लेकिन इस विकल्प के साथ उन्हें अनदेखा किया जा सकता है, जैसे कि ये छिपी वर्कशीट्स मौजूद नहीं हैं। जब यह विकल्प सक्षम होता है, तो आप ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' प्रॉपर्टी के साथ छिपी वर्कशीट का चयन नहीं कर सकते।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


सक्षम होने पर, इनपुट Spreadsheet दस्तावेज़ की खाली सन्निहित क्षैतिज कोशिकाएँ
संपादन योग्य HTML दस्तावेज़ में संबंधित
colspan विशेषता। डिफ़ॉल्ट रूप से निष्क्रिय (false) है।


डिफ़ॉल्ट रूप से GroupDocs.Editor इनपुट Spreadsheet दस्तावेज़ से एक तालिका को आउटपुट में परिवर्तित करता है
HTML दस्तावेज़ में प्रत्येक सेल को संरक्षित रखते हुए। हालांकि, Spreadsheet दस्तावेज़ विरल हो सकते हैं \\u2014 वे
बड़ी मात्रा में "खाली क्षेत्रों" को शामिल कर सकते हैं, जहाँ कई सेल खाली होते हैं। यह विकल्प, जब
सक्षम किया जाता है, तो ऐसे खाली सेल्स को TD तत्व में colspan विशेषता के साथ एक में मिलाता है,
और इस प्रकार उत्पन्न HTML मार्कअप का आकार काफी हद तक कम किया जा सकता है।


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


सक्षम होने पर, उत्पन्न HTML दस्तावेज़ में HTML तालिका में नीचे की खाली छिपी पंक्ति होती है जिसमें
शून्य ऊँचाई और खाली कोशिकाएँ, जहाँ केवल चौड़ाई निर्दिष्ट की गई है। यह पंक्ति खाली कोशिकाओं के साथ शामिल करती है
प्रत्येक कॉलम के लिए सटीक चौड़ाई मान और HTML से स्प्रेडशीट में पीछे की ओर रूपांतरण को बेहतर बनाता है। द्वारा
डिफ़ॉल्ट रूप से सक्षम है (true)।


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

