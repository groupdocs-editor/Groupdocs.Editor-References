---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "स्प्रेडशीट Excel‑अनुपालन दस्तावेज़ों को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 37
url: /hi/java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

स्प्रेडशीट को जनरेट और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है
(Excel‑अनुपालन) दस्तावेज़

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | यह पैरामीटर‑रहित कंस्ट्रक्टर SpreadsheetSaveOptions का नया इंस्टेंस XLSX आउटपुट फ़ॉर्मेट के साथ बनाता है (इसे बाद में के माध्यम से संशोधित किया जा सकता है |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) प्रॉपर्टी)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | निर्दिष्ट अनिवार्य के साथ SpreadsheetSaveOptions का नया इंस्टेंस बनाता है |
स्प्रेडशीट आउटपुट फ़ॉर्मेट, जबकि सभी अन्य पैरामीटर डिफ़ॉल्ट हैं
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getPassword()](#getPassword--) | पासवर्ड को निर्दिष्ट, संशोधित, प्राप्त या हटाने की अनुमति देता है, जो होगा |
उत्पन्न स्प्रेडशीट दस्तावेज़ को एन्कोड करने के लिए उपयोग किया जाता है, यदि यह दस्तावेज़ फ़ॉर्मेट
पासवर्ड सुरक्षा का समर्थन करता है।
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | पासवर्ड को निर्दिष्ट, संशोधित, प्राप्त या हटाने की अनुमति देता है, जो होगा |
उत्पन्न स्प्रेडशीट दस्तावेज़ को एन्कोड करने के लिए उपयोग किया जाता है, यदि यह दस्तावेज़ फ़ॉर्मेट
पासवर्ड सुरक्षा का समर्थन करता है।
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | संपादित वर्कशीट को मौजूदा स्प्रेडशीट की कॉपी में सम्मिलित करने की अनुमति देता है |
नए एकल‑वर्कशीट स्प्रेडशीट (डिफ़ॉल्ट
व्यवहार)।
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | संपादित वर्कशीट को मौजूदा स्प्रेडशीट की कॉपी में सम्मिलित करने की अनुमति देता है |
नए एकल‑वर्कशीट स्प्रेडशीट (डिफ़ॉल्ट
व्यवहार)।
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | बूलियन फ़्लैग, जो निर्धारित करता है कि संपादित वर्कशीट को प्रतिस्थापित किया जाना चाहिए |
मूल स्प्रेडशीट में मौजूदा वर्कशीट को उस स्थिति पर, जो द्वारा निर्दिष्ट है
को

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
प्रॉपर्टी, या इसे मौजूदा वर्कशीट और
पिछली वर्कशीट के बीच डाला जाना चाहिए, उसकी सामग्री को प्रतिस्थापित किए बिना।
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | बूलियन फ़्लैग, जो निर्धारित करता है कि संपादित वर्कशीट को प्रतिस्थापित किया जाना चाहिए |
मूल स्प्रेडशीट में मौजूदा वर्कशीट को उस स्थिति पर, जो द्वारा निर्दिष्ट है
को

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
प्रॉपर्टी, या इसे मौजूदा वर्कशीट और
पिछली वर्कशीट के बीच डाला जाना चाहिए, उसकी सामग्री को प्रतिस्थापित किए बिना।
|
|  | [getOutputFormat()](#getOutputFormat--) | स्प्रेडशीट फ़ॉर्मेट निर्दिष्ट करने की अनुमति देता है, जो सहेजने के लिए उपयोग किया जाएगा |
दस्तावेज़
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | स्प्रेडशीट फ़ॉर्मेट निर्दिष्ट करने की अनुमति देता है, जो सहेजने के लिए उपयोग किया जाएगा |
दस्तावेज़
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | आउटपुट स्प्रेडशीट के लिए वर्कशीट सुरक्षा सक्षम करने की अनुमति देता है |
दस्तावेज़।
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | आउटपुट स्प्रेडशीट के लिए वर्कशीट सुरक्षा सक्षम करने की अनुमति देता है |
दस्तावेज़।
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | स्प्रेडशीट को सहेजते समय हटाए जाने वाले वर्कशीटों के 1‑आधारित क्रमांक वाली एक एरे निर्दिष्ट करने की अनुमति देता है, जब संपादित वर्कशीट को मौजूदा स्प्रेडशीट में सम्मिलित किया जाता है। |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | स्प्रेडशीट को सहेजते समय हटाए जाने वाले वर्कशीटों के 1‑आधारित क्रमांक वाली एक एरे निर्दिष्ट करने की अनुमति देता है, जब संपादित वर्कशीट को मौजूदा स्प्रेडशीट में सम्मिलित किया जाता है। |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


यह पैरामीटर‑रहित कंस्ट्रक्टर SpreadsheetSaveOptions का नया इंस्टेंस XLSX आउटपुट फ़ॉर्मेट के साथ बनाता है (इसे बाद में के माध्यम से संशोधित किया जा सकता है
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) प्रॉपर्टी)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


निर्दिष्ट अनिवार्य के साथ SpreadsheetSaveOptions का नया इंस्टेंस बनाता है
स्प्रेडशीट आउटपुट फ़ॉर्मेट, जबकि सभी अन्य पैरामीटर डिफ़ॉल्ट हैं


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | अनिवार्य आउटपुट फ़ॉर्मेट, जिसमें Spreadsheet दस्तावेज़ को सहेजना चाहिए |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


पासवर्ड को निर्दिष्ट, संशोधित, प्राप्त या हटाने की अनुमति देता है, जो होगा
उत्पन्न स्प्रेडशीट दस्तावेज़ को एन्कोड करने के लिए उपयोग किया जाता है, यदि यह दस्तावेज़ फ़ॉर्मेट
पासवर्ड सुरक्षा का समर्थन करता है। हटाने के लिए NULL या खाली स्ट्रिंग निर्दिष्ट करें
(साफ़ करना) पासवर्ड।


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


पासवर्ड को निर्दिष्ट, संशोधित, प्राप्त या हटाने की अनुमति देता है, जो होगा
उत्पन्न स्प्रेडशीट दस्तावेज़ को एन्कोड करने के लिए उपयोग किया जाता है, यदि यह दस्तावेज़ फ़ॉर्मेट
पासवर्ड सुरक्षा का समर्थन करता है। हटाने के लिए NULL या खाली स्ट्रिंग निर्दिष्ट करें
(साफ़ करना) पासवर्ड।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


संपादित वर्कशीट को मौजूदा स्प्रेडशीट की कॉपी में सम्मिलित करने की अनुमति देता है
नए एकल‑वर्कशीट स्प्रेडशीट (डिफ़ॉल्ट
व्यवहार)। WorksheetNumber एक वर्कशीट का 1-आधारित नंबर है
स्प्रेडशीट, जो Editor क्लास में लोड किया गया है। यदि यह 0 (डिफ़ॉल्ट मान) है, तो
नया स्प्रेडशीट एकल संपादित वर्कशीट के साथ बनाया जाएगा। यदि यह
शून्य से बड़ा या छोटा है, और एक वैध स्प्रेडशीट है, जो लोड किया गया है
Editor क्लास में, संपादित वर्कशीट, जो इनपुट द्वारा दर्शाई गई है
EditableDocument इंस्टेंस, इस स्प्रेडशीट में सम्मिलित किया जाएगा।


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int - 
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


संपादित वर्कशीट को मौजूदा स्प्रेडशीट की कॉपी में सम्मिलित करने की अनुमति देता है
नए एकल‑वर्कशीट स्प्रेडशीट (डिफ़ॉल्ट
व्यवहार)। WorksheetNumber एक वर्कशीट का 1-आधारित नंबर है
स्प्रेडशीट, जो Editor क्लास में लोड किया गया है। यदि यह 0 (डिफ़ॉल्ट मान) है, तो
नया स्प्रेडशीट एकल संपादित वर्कशीट के साथ बनाया जाएगा। यदि यह
शून्य से बड़ा या छोटा है, और एक वैध स्प्रेडशीट है, जो लोड किया गया है
Editor क्लास में, संपादित वर्कशीट, जो इनपुट द्वारा दर्शाई गई है
EditableDocument इंस्टेंस, इस स्प्रेडशीट में सम्मिलित किया जाएगा।


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


बूलियन फ़्लैग, जो निर्धारित करता है कि संपादित वर्कशीट को प्रतिस्थापित किया जाना चाहिए
मूल स्प्रेडशीट में मौजूदा वर्कशीट को उस स्थिति पर, जो द्वारा निर्दिष्ट है
को

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
प्रॉपर्टी, या इसे मौजूदा वर्कशीट और
पिछले को, उसकी सामग्री को बदले बिना। डिफ़ॉल्ट रूप से यह false है \u2014
मौजूदा वर्कशीट को बदल दिया जाएगा। यह प्रॉपर्टी तब अनदेखी की जाती है, यदि मान
का

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
प्रॉपर्टी '0' पर सेट है।


*** ** * ** ***

डिफ़ॉल्ट रूप से वर्कशीट को बदल दिया जाता है। इसका अर्थ है कि यदि दिए गए स्प्रेडशीट में 5 वर्कशीट्स हैं, और WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4 है, तो 4थी वर्कशीट को नई संपादित वर्कशीट से बदल दिया जाएगा, जबकि स्प्रेडशीट में कुल वर्कशीट्स की संख्या (5) अपरिवर्तित रहेगी। हालांकि, यदि इस प्रॉपर्टी का मान *true* पर सेट किया जाता है, तो नई संपादित वर्कशीट को 4थी वर्कशीट के रूप में डाला जाएगा, और सभी बाद की वर्कशीट्स अंत में शिफ्ट हो जाएँगी: \"old\" 4थी वर्कशीट 5वीं बन जाएगी, और 5वीं 6वीं बन जाएगी, और स्प्रेडशीट में कुल वर्कशीट्स की संख्या एक से बढ़कर 6 हो जाएगी।

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


बूलियन फ़्लैग, जो निर्धारित करता है कि संपादित वर्कशीट को प्रतिस्थापित किया जाना चाहिए
मूल स्प्रेडशीट में मौजूदा वर्कशीट को उस स्थिति पर, जो द्वारा निर्दिष्ट है
को

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
प्रॉपर्टी, या इसे मौजूदा वर्कशीट और
पिछले को, उसकी सामग्री को बदले बिना। डिफ़ॉल्ट रूप से यह false है \u2014
मौजूदा वर्कशीट को बदल दिया जाएगा। यह प्रॉपर्टी तब अनदेखी की जाती है, यदि मान
का

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
प्रॉपर्टी '0' पर सेट है।


*** ** * ** ***

डिफ़ॉल्ट रूप से वर्कशीट को बदल दिया जाता है। इसका अर्थ है कि यदि दिए गए स्प्रेडशीट में 5 वर्कशीट्स हैं, और WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4 है, तो 4थी वर्कशीट को नई संपादित वर्कशीट से बदल दिया जाएगा, जबकि स्प्रेडशीट में कुल वर्कशीट्स की संख्या (5) अपरिवर्तित रहेगी। हालांकि, यदि इस प्रॉपर्टी का मान *true* पर सेट किया जाता है, तो नई संपादित वर्कशीट को 4थी वर्कशीट के रूप में डाला जाएगा, और सभी बाद की वर्कशीट्स अंत में शिफ्ट हो जाएँगी: \"old\" 4थी वर्कशीट 5वीं बन जाएगी, और 5वीं 6वीं बन जाएगी, और स्प्रेडशीट में कुल वर्कशीट्स की संख्या एक से बढ़कर 6 हो जाएगी।

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


स्प्रेडशीट फ़ॉर्मेट निर्दिष्ट करने की अनुमति देता है, जो सहेजने के लिए उपयोग किया जाएगा
दस्तावेज़


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


स्प्रेडशीट फ़ॉर्मेट निर्दिष्ट करने की अनुमति देता है, जो सहेजने के लिए उपयोग किया जाएगा
दस्तावेज़


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


आउटपुट स्प्रेडशीट के लिए वर्कशीट सुरक्षा सक्षम करने की अनुमति देता है
दस्तावेज़। डिफ़ॉल्ट रूप से यह NULL है - सुरक्षा लागू नहीं होती। सभी फ़ॉर्मेट नहीं
वर्कशीट सुरक्षा का समर्थन करते हैं।


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


आउटपुट स्प्रेडशीट के लिए वर्कशीट सुरक्षा सक्षम करने की अनुमति देता है
दस्तावेज़। डिफ़ॉल्ट रूप से यह NULL है - सुरक्षा लागू नहीं होती। सभी फ़ॉर्मेट नहीं
वर्कशीट सुरक्षा का समर्थन करते हैं।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


स्प्रेडशीट को सहेजते समय हटाई जाने वाली वर्कशीट्स के 1-आधारित नंबरों की एक एरे निर्दिष्ट करने की अनुमति देता है, जब संपादित वर्कशीट को मौजूदा स्प्रेडशीट में सम्मिलित किया जाता है। जब संपादित वर्कशीट को नई एकल-वर्कशीट स्प्रेडशीट (डिफ़ॉल्ट व्यवहार) के रूप में नहीं, बल्कि मौजूदा स्प्रेडशीट में ( #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int) का उपयोग करके) सहेजा जाता है, तो इस एरे में उनके नंबर निर्दिष्ट करके इस स्प्रेडशीट की कुछ विशिष्ट वर्कशीट्स को भी हटाया जा सकता है। डिफ़ॉल्ट रूप से यह एरे null है \u2014 कोई वर्कशीट हटाई नहीं जाएगी। हालांकि, जब यह एरे non-null और non-empty हो, और इसमें कम से कम एक वैध वर्कशीट नंबर हो, तो संपादित वर्कशीट की सामग्री के साथ आउटपुट स्प्रेडशीट दस्तावेज़ उत्पन्न होने के बाद, निर्दिष्ट नंबरों वाली वर्कशीट्स को स्प्रेडशीट से हटाया जाएगा, ठीक उस समय से पहले जब उसकी सामग्री को आउटपुट स्ट्रीम या फ़ाइल में लिखा जाएगा। इस एरे में वर्कशीट नंबर 1-आधारित हैं, 0-आधारित नहीं। अमान्य नंबर (1 से कम या कुल वर्कशीट्स की संख्या से अधिक) को अनदेखा किया जाएगा।


**Returns:**
int[] - हटाने के लिए 1-आधारित वर्कशीट नंबरों की एरे, या यदि कुछ नहीं हटाना है तो null

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


स्प्रेडशीट को सहेजते समय हटाई जाने वाली वर्कशीट्स के 1-आधारित नंबरों की एरे निर्दिष्ट करने की अनुमति देता है, जब संपादित वर्कशीट को मौजूदा स्प्रेडशीट में सम्मिलित किया जाता है। इस एरे में वर्कशीट नंबर 1-आधारित हैं। अमान्य नंबरों को अनदेखा किया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | मान | int[] | हटाने के लिए 1-आधारित वर्कशीट नंबरों की एरे (null या खाली हो सकती है)। |
|

