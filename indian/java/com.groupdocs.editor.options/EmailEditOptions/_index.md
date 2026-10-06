---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "विभिन्न इलेक्ट्रॉनिक मेल प्रारूपों में दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है"
type: docs
weight: 14
url: /hi/java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

विभिन्न इलेक्ट्रॉनिक मेल (ईमेल) फ़ॉर्मेट्स में दस्तावेज़ों को संपादित करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | एक नया उदाहरण प्रारंभ करता है [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) क्लास का, जहाँ सभी विकल्प डिफ़ॉल्ट मानों पर सेट होते हैं |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | एक नया उदाहरण प्रारंभ करता है [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) क्लास का साथ में |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) पैरामीटर
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | नियंत्रण करने की अनुमति देता है कि मेल संदेश के कौन से भाग आउटपुट [EditableDocument](../../com.groupdocs.editor/editabledocument) में भेजे जाएँ और फिर उत्पन्न HTML में |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | नियंत्रण करने की अनुमति देता है कि मेल संदेश के कौन से भाग आउटपुट [EditableDocument](../../com.groupdocs.editor/editabledocument) में भेजे जाएँ और फिर उत्पन्न HTML में |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


एक नया उदाहरण प्रारंभ करता है [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) क्लास का, जहाँ सभी विकल्प डिफ़ॉल्ट मानों पर सेट होते हैं


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


एक नया उदाहरण प्रारंभ करता है [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) क्लास का साथ में
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) पैरामीटर


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | mailMessageOutput | int | मेल संदेश आउटपुट, जिसे प्रॉपर्टी के माध्यम से भी निर्दिष्ट किया जा सकता है |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


नियंत्रण करने की अनुमति देता है कि मेल संदेश के कौन से भाग आउटपुट [EditableDocument](../../com.groupdocs.editor/editabledocument) में भेजे जाएँ और फिर उत्पन्न HTML में
मान: फ़्लैग्ड एनीम जो मेल संदेश के उन भागों को नियंत्रित करता है, जिन्हें प्रोसेस किया जाना चाहिए। डिफ़ॉल्ट मान है MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


नियंत्रण करने की अनुमति देता है कि मेल संदेश के कौन से भाग आउटपुट [EditableDocument](../../com.groupdocs.editor/editabledocument) में भेजे जाएँ और फिर उत्पन्न HTML में
मान: फ़्लैग्ड एनीम जो मेल संदेश के उन भागों को नियंत्रित करता है, जिन्हें प्रोसेस किया जाना चाहिए। डिफ़ॉल्ट मान है MailMessageOutput.All


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

