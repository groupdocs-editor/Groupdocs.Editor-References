---
title: "FontEmbeddingOptions"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "फ़ॉन्ट एम्बेडिंग विकल्प नियंत्रित करते हैं कि कौन से फ़ॉन्ट संसाधन आउटपुट WordProcessing दस्तावेज़ में एम्बेड किए जाने चाहिए।"
type: docs
weight: 17
url: /hi/java/com.groupdocs.editor.options/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class FontEmbeddingOptions
```

फ़ॉन्ट एम्बेडिंग विकल्प नियंत्रित करते हैं कि कौन से फ़ॉन्ट संसाधन एम्बेड किए जाने चाहिए।
आउटपुट WordProcessing दस्तावेज़


*** ** * ** ***

फ़ॉन्ट एम्बेडिंग विकल्प दस्तावेज़ सहेजते समय (मध्यवर्ती EditableDocument से आउटपुट WordProcessing फ़ॉर्मेट में) लागू होते हैं, यह एनीम WordProcessingSaveOptions में एक प्रॉपर्टी के रूप में शामिल है, जहाँ से इसे उपयोग किया जाना चाहिए।

<br />


## Fields

| Field | विवरण |
| --- | --- |
|  | [NotEmbed](#NotEmbed) | EditableDocument या सिस्टम से कोई फ़ॉन्ट संसाधन एम्बेड न करें |
सिस्टम।
|
|  | [EmbedAll](#EmbedAll) | इनपुट EditableDocument से दस्तावेज़ सामग्री का विश्लेषण करें, सभी उपयोग किए गए फ़ॉन्ट खोजें। |
और उन्हें आउटपुट WordProcessing दस्तावेज़ में एम्बेड करें।
|
|  | [EmbedWithoutSystem](#EmbedWithoutSystem) | सटीक रूप से [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll) के समान, लेकिन उन फ़ॉन्ट्स को बाहर रखें, |
जो OS द्वारा सिस्टम फ़ॉन्ट्स के रूप में माना जाता है
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFontEmbeddingOptions()](#getFontEmbeddingOptions--) |  |
### NotEmbed {#NotEmbed}
```
public static final int NotEmbed
```


EditableDocument या सिस्टम से कोई फ़ॉन्ट संसाधन एम्बेड न करें
सिस्टम। डिफ़ॉल्ट मान।


### EmbedAll {#EmbedAll}
```
public static final int EmbedAll
```


इनपुट EditableDocument से दस्तावेज़ सामग्री का विश्लेषण करें, सभी उपयोग किए गए फ़ॉन्ट खोजें।
और उन्हें आउटपुट WordProcessing दस्तावेज़ में एम्बेड करें। सबसे पहले
GroupDocs.Editor EditableDocument के भीतर फ़ॉन्ट संसाधनों से फ़ॉन्ट लेता है।
यदि वे अपर्याप्त या अनुपलब्ध हैं, तो GroupDocs.Editor फ़ॉन्ट लेता है
OS से।


*** ** * ** ***

सबसे पहले GroupDocs.Editor EditableDocument की सामग्री का विश्लेषण करता है और सभी उपयोग किए गए फ़ॉन्ट्स की सूची बनाता है। फिर इन फ़ॉन्ट्स को EditableDocument के फ़ॉन्ट संसाधनों में खोजा जाता है। यदि EditableDocument में कुछ फ़ॉन्ट संसाधन हैं, जो दस्तावेज़ सामग्री में शामिल नहीं हैं, तो ऐसे संसाधनों को अनदेखा किया जाता है। यदि दस्तावेज़ सामग्री में उपयोग किए गए कुछ फ़ॉन्ट्स के लिए EditableDocument में संबंधित फ़ॉन्ट संसाधन नहीं हैं, तो GroupDocs.Editor उन्हें OS में खोजने का प्रयास करता है। यह विकल्प "Embed fonts in the file" विकल्प के समान है जिसमें Microsoft Word 2007 और उसके बाद के संस्करणों में सभी उप-विकल्प बंद होते हैं

<br />



### EmbedWithoutSystem {#EmbedWithoutSystem}
```
public static final int EmbedWithoutSystem
```


सटीक रूप से [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll) के समान, लेकिन उन फ़ॉन्ट्स को बाहर रखें,
जो OS द्वारा सिस्टम फ़ॉन्ट्स के रूप में माना जाता है


*** ** * ** ***

MS Windows के पास सिस्टम फ़ॉन्ट्स की अवधारणा है, जो Windows द्वारा स्वयं सबसे बुनियादी और उपयोग किए जाने वाले फ़ॉन्ट्स हैं। इस विकल्प का उपयोग करते समय, GroupDocs.Editor [EmbedAll](../../com.groupdocs.editor.options/fontembeddingoptions#EmbedAll) मामले की तरह कार्य करता है, लेकिन अंत में प्राप्त फ़ॉन्ट्स के सेट की समीक्षा करता है और उन फ़ॉन्ट्स को बाहर करता है, जिन्हें OS द्वारा सिस्टम फ़ॉन्ट्स माना जाता है। यह विकल्प Microsoft Word 2007 और उसके बाद के संस्करणों में "Embed fonts in the file" + "Do not embed common system fonts" विकल्पों के समान है

<br />



### getFontEmbeddingOptions() {#getFontEmbeddingOptions--}
```
public static int[] getFontEmbeddingOptions()
```




**Returns:**
int[]
