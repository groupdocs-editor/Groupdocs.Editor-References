---
title: "MarkdownEditOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "मार्कडाउन फ़ॉर्मेट में दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 21
url: /hi/java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

मार्कडाउन फ़ॉर्मेट में दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | MarkdownEditOptions क्लास का नया इंस्टेंस बनाता और लौटाता है, |
जहाँ सभी विकल्प डिफ़ॉल्ट मानों पर सेट होते हैं
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Markdown दस्तावेज़ को परिवर्तित करते समय छवियों को कैसे सहेजा जाए, इसे नियंत्रित करने की अनुमति देता है |
Html में।
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Markdown दस्तावेज़ को परिवर्तित करते समय छवियों को कैसे सहेजा जाए, इसे नियंत्रित करने की अनुमति देता है |
Html में।
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


MarkdownEditOptions क्लास का नया इंस्टेंस बनाता और लौटाता है,
जहाँ सभी विकल्प डिफ़ॉल्ट मानों पर सेट होते हैं


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Markdown दस्तावेज़ को परिवर्तित करते समय छवियों को कैसे सहेजा जाए, इसे नियंत्रित करने की अनुमति देता है
Html में।
मान: छवि सहेजने का कॉलबैक।


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Markdown दस्तावेज़ को परिवर्तित करते समय छवियों को कैसे सहेजा जाए, इसे नियंत्रित करने की अनुमति देता है
Html में।
मान: छवि सहेजने का कॉलबैक।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

