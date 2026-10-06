---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "इलेक्ट्रॉनिक मेल दस्तावेज़ों को उत्पन्न करने और सहेजने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

इलेक्ट्रॉनिक मेल (ईमेल) दस्तावेज़ों को जनरेट और सेव करने के लिए कस्टम विकल्प निर्दिष्ट करने की अनुमति देता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | एक नया उदाहरण प्रारंभ करता है [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) क्लास का, जहाँ सभी विकल्प डिफ़ॉल्ट मानों पर सेट होते हैं। |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | एक नया उदाहरण प्रारंभ करता है [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) क्लास का साथ में |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) पैरामीटर
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | यह नियंत्रित करने की अनुमति देता है कि मेल संदेश के कौन से भाग आउटपुट ईमेल दस्तावेज़ में डिलीवर किए जाएँ, जिसे [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) मेथड के साथ उत्पन्न और सहेजा जाएगा। |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | यह नियंत्रित करने की अनुमति देता है कि मेल संदेश के कौन से भाग आउटपुट ईमेल दस्तावेज़ में डिलीवर किए जाएँ, जिसे [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) मेथड के साथ उत्पन्न और सहेजा जाएगा। |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


एक नया उदाहरण प्रारंभ करता है [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) क्लास का, जहाँ सभी विकल्प डिफ़ॉल्ट मानों पर सेट होते हैं।


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


एक नया उदाहरण प्रारंभ करता है [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) क्लास का साथ में
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


यह नियंत्रित करने की अनुमति देता है कि मेल संदेश के कौन से भाग आउटपुट ईमेल दस्तावेज़ में डिलीवर किए जाएँ, जिसे [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) मेथड के साथ उत्पन्न और सहेजा जाएगा।
मान: फ़्लैग्ड एनीम जो मेल संदेश के उन भागों को नियंत्रित करता है, जिन्हें प्रोसेस किया जाना चाहिए। डिफ़ॉल्ट मान है MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


यह नियंत्रित करने की अनुमति देता है कि मेल संदेश के कौन से भाग आउटपुट ईमेल दस्तावेज़ में डिलीवर किए जाएँ, जिसे [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) मेथड के साथ उत्पन्न और सहेजा जाएगा।
मान: फ़्लैग्ड एनीम जो मेल संदेश के उन भागों को नियंत्रित करता है, जिन्हें प्रोसेस किया जाना चाहिए। डिफ़ॉल्ट मान है MailMessageOutput.All


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

