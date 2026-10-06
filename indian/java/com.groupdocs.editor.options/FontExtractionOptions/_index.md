---
title: "FontExtractionOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "फ़ॉन्ट निष्कर्षण विकल्प नियंत्रित करते हैं कि कौन से फ़ॉन्ट निकाले जाने चाहिए और कहाँ से"
type: docs
weight: 18
url: /hi/java/com.groupdocs.editor.options/fontextractionoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtractionOptions
```

फ़ॉन्ट निष्कर्षण विकल्प नियंत्रित करते हैं कि कौन से फ़ॉन्ट निकाले जाने चाहिए और किस स्रोत से
कहाँ

## Fields

| Field | विवरण |
| --- | --- |
|  | [NotExtract](#NotExtract) | दस्तावेज़ से न तो और ... से भी कोई फ़ॉन्ट संसाधन नहीं निकालता |
सिस्टम।
|
|  | [ExtractAllEmbedded](#ExtractAllEmbedded) | इनपुट Word में एम्बेड किए गए सभी फ़ॉन्ट संसाधनों को निकालता है |
दस्तावेज़, चाहे वे कोई भी हों: कस्टम या सिस्टम।
|
|  | [ExtractEmbeddedWithoutSystem](#ExtractEmbeddedWithoutSystem) | केवल उन एम्बेडेड फ़ॉन्ट संसाधनों को निकालता है, जो कस्टम हैं (न कि |
सिस्टम)।
|
|  | [ExtractAll](#ExtractAll) | इनपुट WordProcessing में उपयोग किए गए सभी फ़ॉन्ट को निकालने का प्रयास करता है |
दस्तावेज़, जिसमें सिस्टम फ़ॉन्ट भी शामिल हैं।
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFontExtractionOptions()](#getFontExtractionOptions--) |  |
### NotExtract {#NotExtract}
```
public static final int NotExtract
```


दस्तावेज़ से न तो और ... से भी कोई फ़ॉन्ट संसाधन नहीं निकालता
सिस्टम। डिफ़ॉल्ट मान।


### ExtractAllEmbedded {#ExtractAllEmbedded}
```
public static final int ExtractAllEmbedded
```


इनपुट Word में एम्बेड किए गए सभी फ़ॉन्ट संसाधनों को निकालता है
दस्तावेज़, चाहे वे कोई भी हों: कस्टम या सिस्टम।


*** ** * ** ***

कनवर्टर सभी 100% फ़ॉन्ट संसाधनों को खोजता और निकालता है, जो इनपुट WordProcessing दस्तावेज़ में एम्बेडेड होते हैं, लेकिन यह निर्धारित नहीं करता कि वे सिस्टम हैं या कस्टम; यह Windows Registry या सिस्टम फ़ोल्डरों को बिल्कुल नहीं छूता।

<br />



### ExtractEmbeddedWithoutSystem {#ExtractEmbeddedWithoutSystem}
```
public static final int ExtractEmbeddedWithoutSystem
```


केवल उन एम्बेडेड फ़ॉन्ट संसाधनों को निकालता है, जो कस्टम हैं (न कि
सिस्टम)।


*** ** * ** ***

कनवर्टर सभी एम्बेडेड फ़ॉन्ट संसाधनों को खोजता और निकालता है, और फिर यह निर्धारित करने की कोशिश करता है कि इन फ़ॉन्ट्स में से कौन से सिस्टम हैं और कौन से नहीं। इसे हासिल करने के लिए, कनवर्टर Windows Registry और सिस्टम फ़ोल्डरों का उपयोग करके सभी सिस्टम फ़ॉन्ट्स की सूची प्राप्त करने का प्रयास करता है, और फिर इस सूची की तुलना एम्बेडेड फ़ॉन्ट्स के सेट से करता है। परिणामस्वरूप, केवल उन एम्बेडेड फ़ॉन्ट्स का उपसमुच्चय जो सिस्टम में नहीं मिला, वापस किया जाएगा।

<br />



### ExtractAll {#ExtractAll}
```
public static final int ExtractAll
```


इनपुट WordProcessing में उपयोग किए गए सभी फ़ॉन्ट को निकालने का प्रयास करता है
दस्तावेज़, जिसमें सिस्टम फ़ॉन्ट भी शामिल हैं।


*** ** * ** ***

कनवर्टर एक इनपुट WordProcessing दस्तावेज़ का विश्लेषण कर रहा है और वहाँ उपयोग किए गए सभी फ़ॉन्ट्स को खोजता है। यदि इन सभी फ़ॉन्ट्स को इनपुट दस्तावेज़ में एम्बेड किया गया है, तो कनवर्टर उन्हें निकालकर लौटाता है। अन्यथा, यदि एम्बेडेड फ़ॉन्ट्स का संग्रह दस्तावेज़ में उपयोग किए गए सभी फ़ॉन्ट्स को कवर नहीं करता या खाली है, तो कनवर्टर Windows Registry और सिस्टम फ़ोल्डरों का उपयोग करके सिस्टम से इन फ़ॉन्ट संसाधनों को निकालने की कोशिश करता है।

<br />



### getFontExtractionOptions() {#getFontExtractionOptions--}
```
public static int[] getFontExtractionOptions()
```




**Returns:**
int[]
