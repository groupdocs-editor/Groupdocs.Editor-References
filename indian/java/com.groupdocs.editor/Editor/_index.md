---
title: "Editor"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "मुख्य क्लास जो रूपांतरण विधियों को सम्मिलित करती है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

मुख्य क्लास, जो रूपांतरण विधियों को संलग्न करती है।
Editor क्लास सभी समर्थित फ़ॉर्मैट्स के दस्तावेज़ों को लोड करने, संपादित करने और सहेजने के लिए विधियाँ प्रदान करती है। यह डिस्पोज़ेबल है, इसलिए 'using' निर्देश का उपयोग करें या 'Dispose()' मेथड कॉल के माध्यम से उसके संसाधनों को मैन्युअल रूप से डिस्पोज़ करें। दस्तावेज़ लोड करना कंस्ट्रक्टर्स के द्वारा किया जाता है। दस्तावेज़ संपादन - 'Edit' मेथड के द्वारा, और संपादन के बाद परिणामी दस्तावेज़ को वापस सहेजना - 'Save' मेथड के द्वारा।
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | निर्दिष्ट फ़ॉर्मैट के आधार पर एक नया खाली दस्तावेज़ बनाते हुए, [Editor](../../com.groupdocs.editor/editor) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | निर्दिष्ट इनपुट दस्तावेज़ (स्ट्रीम के रूप में) के साथ नया Editor इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | निर्दिष्ट इनपुट दस्तावेज़ (के रूप में |
स्ट्रीम) के साथ उसके लोड विकल्प और Editor सेटिंग्स
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | निर्दिष्ट इनपुट दस्तावेज़ (पूर्ण फ़ाइल पाथ के रूप में) के साथ नया Editor इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | निर्दिष्ट इनपुट दस्तावेज़ (पूर्ण फ़ाइल पाथ के रूप में) के साथ उसके लोड विकल्पों के साथ नया Editor इंस्टेंस इनिशियलाइज़ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | निर्दिष्ट फ़ॉर्मेट-विशिष्ट विकल्पों का उपयोग करके पहले लोड किए गए दस्तावेज़ को संपादन के लिए खोलता है, '' क्लास का एक इंस्टेंस जेनरेट करके और रिटर्न करता है, जो बदले में HTML मार्कअप और संबंधित संसाधनों को उत्पन्न करने की विधियाँ रखता है। |
|
|  | [edit()](#edit--) | डिफ़ॉल्ट विकल्पों का उपयोग करके पहले लोड किए गए दस्तावेज़ को संपादन के लिए खोलता है, द्वारा |
 'EditableDocument' क्लास का एक इंस्टेंस जेनरेट करके और रिटर्न करके, वह,
बदले में, HTML मार्कअप और संबंधित
संसाधनों को उत्पन्न करने की विधियाँ रखता है।
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | निर्दिष्ट संपादित दस्तावेज़ को, जो इस रूप में दर्शाया गया है |
'EditableDocument', निर्दिष्ट फ़ॉर्मैट के परिणामी दस्तावेज़ में और
उसकी सामग्री को निर्दिष्ट स्ट्रीम में सहेजता है।
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | निर्दिष्ट संपादित दस्तावेज़ को, '' का इंस्टेंस के रूप में दर्शाया गया, निर्दिष्ट फ़ॉर्मैट के परिणामी दस्तावेज़ में रूपांतरित करता है और उसकी सामग्री को निर्दिष्ट फ़ाइल पाथ द्वारा फ़ाइल में सहेजता है। |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | निर्दिष्ट संपादित दस्तावेज़ (जो एक [EditableDocument](../../com.groupdocs.editor/editabledocument) द्वारा दर्शाया गया है) को एक आउटपुट दस्तावेज़ में रूपांतरित करता है, जिसका फ़ॉर्मैट फ़ाइलनाम एक्सटेंशन से निर्धारित होता है, और इसे निर्दिष्ट फ़ाइल पाथ में सहेजता है। |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | संशोधन के बाद मूल दस्तावेज़ को रूपांतरित करता है (उदाहरण के लिए, |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
निर्दिष्ट फ़ॉर्मैट के परिणामी दस्तावेज़ में और उसकी सामग्री को प्रदान किए गए स्ट्रीम में सहेजता है।
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | वर्तमान दस्तावेज़ की सामग्री को निर्दिष्ट आउटपुट स्ट्रीम में सहेजें। |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | इस 'Editor' इंस्टेंस में लोड किए गए दस्तावेज़ के बारे में मेटाडेटा लौटाता है। |
|
|  | [dispose()](#dispose--) | Editor के इस इंस्टेंस को डिस्पोज़ करता है, ताकि यह सभी आंतरिक संसाधनों को रिलीज़ कर दे। |
संसाधन उपलब्ध नहीं रह जाते और आगे उपयोग के लिए अनुपलब्ध हो जाते हैं
|
|  | [isDisposed()](#isDisposed--) | यह दर्शाता है कि यह Editor इंस्टेंस पहले ही नष्ट हो चुका है और नहीं हो सकता |
अब उपयोग किया जा सकता है (true) या नहीं, और सक्रिय है (false)
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


निर्दिष्ट फ़ॉर्मैट के आधार पर एक नया खाली दस्तावेज़ बनाते हुए, [Editor](../../com.groupdocs.editor/editor) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

<br />

*** ** * ** ***

> ```
>   IDocumentFormat format = WordProcessingFormats.Docx;
>  Editor editor = new Editor(format);
>  {
>      // Use the editor instance to edit and save documents
>  }
>  
>  
> ```

<br />



**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | वह दस्तावेज़ के फ़ाइल फ़ॉर्मेट को दर्शाता है जो बनाया जाएगा। **और अधिक जानें** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


निर्दिष्ट इनपुट दस्तावेज़ (स्ट्रीम के रूप में) के साथ नया Editor इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | डेलीगेट, जो दस्तावेज़ सामग्री के साथ एक स्ट्रीम लौटाना चाहिए। NULL नहीं होना चाहिए। **और अधिक जानें** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


निर्दिष्ट इनपुट दस्तावेज़ (के रूप में
स्ट्रीम) के साथ उसके लोड विकल्प और Editor सेटिंग्स


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | डेलीगेट, जो दस्तावेज़ सामग्री के साथ एक स्ट्रीम लौटाना चाहिए। NULL नहीं होना चाहिए। |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | डेलीगेट, जो दस्तावेज़ लोड विकल्प लौटाना चाहिए। NULL हो सकता है और null लौट सकता है - ऐसे में दस्तावेज़ प्रकार स्वचालित रूप से पता लगाया जाएगा और उस प्रकार के लिए डिफ़ॉल्ट लोड विकल्प लागू किए जाएंगे। |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


निर्दिष्ट इनपुट दस्तावेज़ (पूर्ण फ़ाइल पाथ के रूप में) के साथ नया Editor इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | फ़ाइल का पूर्ण पथ। NULL नहीं होना चाहिए। वैध होना चाहिए, और फ़ाइल मौजूद होनी चाहिए। **और अधिक जानें** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


निर्दिष्ट इनपुट दस्तावेज़ (पूर्ण फ़ाइल पाथ के रूप में) के साथ उसके लोड विकल्पों के साथ नया Editor इंस्टेंस इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | फ़ाइल का पूर्ण पथ। NULL नहीं होना चाहिए। वैध होना चाहिए, और फ़ाइल मौजूद होनी चाहिए। |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | डेलीगेट, जो दस्तावेज़ लोड विकल्प लौटाना चाहिए। NULL हो सकता है और null लौट सकता है - ऐसे में दस्तावेज़ प्रकार स्वचालित रूप से पता लगाया जाएगा और उस प्रकार के लिए डिफ़ॉल्ट लोड विकल्प लागू किए जाएंगे। **और अधिक जानें** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


निर्दिष्ट फ़ॉर्मेट-विशिष्ट विकल्पों का उपयोग करके पहले लोड किए गए दस्तावेज़ को संपादन के लिए खोलता है, '' क्लास का एक इंस्टेंस जेनरेट करके और रिटर्न करता है, जो बदले में HTML मार्कअप और संबंधित संसाधनों को उत्पन्न करने की विधियाँ रखता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | फ़ॉर्मेट-विशिष्ट दस्तावेज़ विकल्प, जो रूपांतरण प्रक्रिया को ट्यून‑अप करने की अनुमति देते हैं। NULL नहीं होना चाहिए। पहले लागू किए गए लोड विकल्पों के साथ टकराव नहीं होना चाहिए। |


*** ** * ** ***

जब इनपुट मूल दस्तावेज़ को कंस्ट्रक्टर के माध्यम से 'Editor' इंस्टेंस में लोड किया जाता है, तो यह मेथड दस्तावेज़ को संपादन के लिए खोलने की अनुमति देता है, इसे मध्यवर्ती फ़ॉर्मेट में परिवर्तित करके, जो 'EditableDocument' क्लास के इंस्टेंस में संलग्न होता है। इस मेथड से लौटाया गया 'EditableDocument' सभी आवश्यक मेथड्स और प्रॉपर्टीज़ रखता है जो HTML मार्कअप और संबंधित संसाधनों (जैसे छवियां, फ़ॉन्ट्स और स्टाइलशीट्स) को सभी आवश्यक कॉन्फ़िगरेशन में उत्पन्न करने के लिए आवश्यक हैं, ताकि उन्हें किसी भी WYSIWYG HTML‑editor में पास किया जा सके। यह ओवरलोड संपादन विकल्प प्राप्त करता है, जो फ़ैमिली फ़ॉर्मेट्स के लिए विशिष्ट होते हैं।

*** ** * ** ***


**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Edit+document)
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument)
### edit() {#edit--}
```
public final EditableDocument edit()
```


डिफ़ॉल्ट विकल्पों का उपयोग करके पहले लोड किए गए दस्तावेज़ को संपादन के लिए खोलता है, द्वारा
 'EditableDocument' क्लास का एक इंस्टेंस जेनरेट करके और रिटर्न करके, वह,
बदले में, HTML मार्कअप और संबंधित
संसाधनों को उत्पन्न करने की विधियाँ रखता है।


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

जब इनपुट मूल दस्तावेज़ को कंस्ट्रक्टर के माध्यम से 'Editor' इंस्टेंस में लोड किया जाता है, तो यह मेथड दस्तावेज़ को संपादन के लिए खोलने की अनुमति देता है, इसे मध्यवर्ती फ़ॉर्मेट में परिवर्तित करके, जो 'EditableDocument' क्लास के इंस्टेंस में संलग्न होता है। इस मेथड से लौटाया गया 'EditableDocument' सभी आवश्यक मेथड्स और प्रॉपर्टीज़ रखता है जो HTML मार्कअप और संबंधित संसाधनों (जैसे छवियां, फ़ॉन्ट्स और स्टाइलशीट्स) को सभी आवश्यक कॉन्फ़िगरेशन में उत्पन्न करने के लिए आवश्यक हैं, ताकि उन्हें किसी भी WYSIWYG HTML‑editor में पास किया जा सके। यह ओवरलोड संपादन विकल्प लागू करता है, जो उस फ़ॉर्मेट के लिए डिफ़ॉल्ट होते हैं, जिससे इनपुट दस्तावेज़ संबंधित है।

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


निर्दिष्ट संपादित दस्तावेज़ को, जो इस रूप में दर्शाया गया है
'EditableDocument', निर्दिष्ट फ़ॉर्मैट के परिणामी दस्तावेज़ में और
उसकी सामग्री को निर्दिष्ट स्ट्रीम में सहेजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | इनपुट दस्तावेज़ का संस्करण, जिसे WYSIWYG HTML‑editor में संपादित किया गया था और 'EditableDocument' क्लास के इंस्टेंस के रूप में संग्रहीत है, जिसे किसी विशिष्ट फ़ॉर्मेट के आउटपुट दस्तावेज़ में परिवर्तित किया जाना चाहिए। |
|
|  | outputDocument | java.io.OutputStream | आउटपुट स्ट्रीम, जिसमें परिणामी दस्तावेज़ की सामग्री रिकॉर्ड की जाएगी। NULL नहीं होना चाहिए, नष्ट नहीं होना चाहिए, लेखन का समर्थन करना चाहिए। |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | दस्तावेज़ सहेजने के विकल्प, जो परिणामी दस्तावेज़ के फ़ॉर्मेट को परिभाषित करते हैं, साथ ही सामान्य और फ़ॉर्मेट-विशिष्ट सहेजने के विकल्प। **और अधिक जानें** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


निर्दिष्ट संपादित दस्तावेज़ को, '' का इंस्टेंस के रूप में दर्शाया गया, निर्दिष्ट फ़ॉर्मैट के परिणामी दस्तावेज़ में रूपांतरित करता है और उसकी सामग्री को निर्दिष्ट फ़ाइल पाथ द्वारा फ़ाइल में सहेजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | इनपुट दस्तावेज़ का संस्करण, जिसे WYSIWYG HTML‑editor में संपादित किया गया था और '' क्लास के इंस्टेंस के रूप में संग्रहीत है, जिसे किसी विशिष्ट फ़ॉर्मेट के आउटपुट दस्तावेज़ में परिवर्तित किया जाना चाहिए। इसे null या नष्ट नहीं होना चाहिए। |
|
|  | filePath | java.lang.String | फ़ाइल का पथ, जिसमें आउटपुट दस्तावेज़ सहेजा जाएगा। यदि समान नाम की फ़ाइल मौजूद है, तो इसे पूरी तरह से पुनः लिखा जाएगा। पथ वाली स्ट्रिंग null, खाली या केवल व्हाइटस्पेस नहीं होनी चाहिए। |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | दस्तावेज़ सहेजने के विकल्प, जो परिणामी दस्तावेज़ के फ़ॉर्मेट को परिभाषित करते हैं, साथ ही सामान्य और फ़ॉर्मेट-विशिष्ट सहेजने के विकल्प। null नहीं होना चाहिए। **और अधिक जानें** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


निर्दिष्ट संपादित दस्तावेज़ (जो एक [EditableDocument](../../com.groupdocs.editor/editabledocument) द्वारा दर्शाया गया है) को एक आउटपुट दस्तावेज़ में रूपांतरित करता है, जिसका फ़ॉर्मैट फ़ाइलनाम एक्सटेंशन से निर्धारित होता है, और इसे निर्दिष्ट फ़ाइल पाथ में सहेजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | इनपुट दस्तावेज़ का संस्करण, जिसे WYSIWYG HTML एडिटर में संपादित किया गया था और एक [EditableDocument](../../com.groupdocs.editor/editabledocument) इंस्टेंस के रूप में संग्रहीत है। null या नष्ट नहीं होना चाहिए। |
|
|  | filePath | java.lang.String | फ़ाइल का पथ जहाँ आउटपुट दस्तावेज़ सहेजा जाएगा। यदि समान नाम की फ़ाइल मौजूद है, तो इसे पूरी तरह से अधिलेखित किया जाएगा। पथ स्ट्रिंग null, खाली या केवल व्हाइटस्पेस नहीं होनी चाहिए। क्योंकि डिफ़ॉल्ट सहेजने के विकल्प और आउटपुट फ़ॉर्मेट इस फ़ाइलनाम से निर्धारित होते हैं, इसलिए इसमें एक वैध एक्सटेंशन होना आवश्यक है। |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


संशोधन के बाद मूल दस्तावेज़ को रूपांतरित करता है (उदाहरण के लिए,
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
निर्दिष्ट फ़ॉर्मैट के परिणामी दस्तावेज़ में और उसकी सामग्री को प्रदान किए गए स्ट्रीम में सहेजता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | आउटपुट दस्तावेज़ को सहेजने वाला स्ट्रीम। यह स्ट्रीम लिखने योग्य होना चाहिए और दस्तावेज़ सामग्री की शुरुआत में स्थित होना चाहिए। यह null नहीं होना चाहिए। |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | दस्तावेज़ सहेजने के विकल्प जो परिणामी दस्तावेज़ के स्वरूप को परिभाषित करते हैं, साथ ही सामान्य और स्वरूप-विशिष्ट सहेजने के विकल्प। यह null नहीं होना चाहिए। |

<br />

*** ** * ** ***

यदि  outputDocument  या  saveOptions  null है, तो NullPointerException फेंका जाएगा। यदि सहेजने के लिए दस्तावेज़ अनुपलब्ध है, तो NullPointerException फेंका जाएगा।

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - सहेजे गए दस्तावेज़ सामग्री को रखने वाला स्ट्रीम।

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


वर्तमान दस्तावेज़ की सामग्री को निर्दिष्ट आउटपुट स्ट्रीम में सहेजें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | दस्तावेज़ सामग्री को सहेजने वाला स्ट्रीम। यह null नहीं हो सकता। |

<br />

*** ** * ** ***

यह मेथड आंतरिक दस्तावेज़ प्रतिनिधित्व से सामग्री को प्रदान किए गए आउटपुट स्ट्रीम में कॉपी करता है। सहेजने के बाद स्ट्रीम की मूल स्थिति बनी रहती है।

<br />

|

**Returns:**
java.io.OutputStream - सहेजे गए दस्तावेज़ सामग्री वाला स्ट्रीम।

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


इस 'Editor' इंस्टेंस में लोड किए गए दस्तावेज़ के बारे में मेटाडेटा लौटाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | पासवर्ड | java.lang.String | उपयोगकर्ता दस्तावेज़ के लिए पासवर्ड निर्दिष्ट कर सकता है, यदि यह दस्तावेज़ पासवर्ड से एन्क्रिप्टेड है। यह NULL या खाली स्ट्रिंग हो सकता है, जो अनुपस्थित पासवर्ड के बराबर है। उन दस्तावेज़ स्वरूपों के लिए, जिनमें पासवर्ड सुरक्षा सुविधा नहीं है, यह तर्क अनदेखा किया जाएगा। यदि दस्तावेज़ एन्क्रिप्टेड है, और इस पैरामीटर में पासवर्ड निर्दिष्ट नहीं किया गया है, लेकिन इसे लोड विकल्पों में पहले निर्दिष्ट किया गया था जबकि यह इंस्टेंस बनाया गया था, तो इसका उपयोग किया जाएगा। **Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Editor के इस इंस्टेंस को डिस्पोज़ करता है, ताकि यह सभी आंतरिक संसाधनों को रिलीज़ कर दे।
संसाधन उपलब्ध नहीं रह जाते और आगे उपयोग के लिए अनुपलब्ध हो जाते हैं


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


यह दर्शाता है कि यह Editor इंस्टेंस पहले ही नष्ट हो चुका है और नहीं हो सकता
अब उपयोग किया जा सकता है (true) या नहीं, और सक्रिय है (false)


**Returns:**
boolean
