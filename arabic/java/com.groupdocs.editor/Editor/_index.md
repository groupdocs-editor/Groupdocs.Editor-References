---
title: "المحرر"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "الفئة الرئيسية التي تُجَمِّع طرق التحويل."
type: docs
weight: 11
url: /ar/java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

الفئة الرئيسية التي تُغلف طرق التحويل.
توفر فئة Editor طرقًا لتحميل المستندات وتحريرها وحفظها بجميع الصيغ المدعومة. إنها قابلة للتصرف، لذا استخدم توجيه 'using' أو حرِّر مواردها يدويًا عبر استدعاء طريقة 'Dispose()'. يتم تحميل المستندات من خلال المُنشئات. تحرير المستند يتم عبر طريقة 'Edit'، وحفظ المستند الناتج بعد التحرير يتم عبر طريقة 'Save'.
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | يُنشئ مثيلًا جديدًا من الفئة [Editor](../../com.groupdocs.editor/editor) ويُنشئ مستندًا فارغًا جديدًا بناءً على الصيغة المحددة. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | يُنشئ مثيلًا جديدًا من Editor مع مستند الإدخال المحدد (كتيار). |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | يُنشئ مثيلًا جديدًا من Editor مع مستند الإدخال المحدد (كـ |
تيار) مع خيارات التحميل وإعدادات Editor.
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | يُنشئ مثيلًا جديدًا من Editor مع مستند الإدخال المحدد (كمسار ملف كامل). |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | يُنشئ مثيلًا جديدًا من Editor مع مستند الإدخال المحدد (كمسار ملف كامل) مع خيارات التحميل الخاصة به. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام خيارات محددة خاصة بالصيغة عن طريق إنشاء وإرجاع مثيل من الفئة ''، والتي بدورها تحتوي على طرق لإنشاء ترميز HTML والموارد المرتبطة. |
|
|  | [edit()](#edit--) | يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام الخيارات الافتراضية عن طريق |
إنشاء وإرجاع مثيل من الفئة 'EditableDocument'، التي،
بدورها تحتوي على طرق لإنشاء ترميز HTML والـ
الموارد.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | يحوِّل المستند المُحرَّر المحدد، المُمَثَّل كـ |
'EditableDocument'، إلى المستند الناتج بالصِيغة المحددة و
يحفظ محتواه إلى التيار المحدد
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | يحوِّل المستند المُحرَّر المحدد، المُمَثَّل كـ ''، إلى المستند الناتج بالصِيغة المحددة ويحفظ محتواه إلى ملف عبر مسار الملف المحدد. |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | يحوِّل المستند المُحرَّر المحدد (المُمَثَّل بـ [EditableDocument](../../com.groupdocs.editor/editabledocument)) إلى مستند إخراج تُحدَّد صيغته من امتداد اسم الملف، ويحفظه إلى مسار الملف المحدد. |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | يحوِّل المستند الأصلي بعد التعديل (على سبيل المثال، |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
إلى المستند الناتج بالصِيغة المحددة ويحفظ محتواه إلى التيار المقدم.
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | احفظ محتوى المستند الحالي إلى التيار الخارج المحدد. |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | يرجع بيانات التعريف حول المستند الذي تم تحميله إلى هذه المثيلة من 'Editor' |
|
|  | [dispose()](#dispose--) | يحرِّر هذه المثيلة من Editor، بحيث تُفرج عن جميع الموارد الداخلية |
الموارد وتصبح غير متاحة للاستخدام لاحقًا
|
|  | [isDisposed()](#isDisposed--) | يشير إلى ما إذا كانت مثيلة Editor هذه قد تم التخلص منها بالفعل ولا يمكن |
استخدامها بعد الآن (true) أو لا، وتكون نشطة (false)
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


يُنشئ مثيلًا جديدًا من الفئة [Editor](../../com.groupdocs.editor/editor) ويُنشئ مستندًا فارغًا جديدًا بناءً على الصيغة المحددة.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | يمثل تنسيق الملف للمستند الذي سيتم إنشاؤه. **المزيد** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


يُنشئ مثيلًا جديدًا من Editor مع مستند الإدخال المحدد (كتيار).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | وثيقة | java.io.InputStream | المندوب، الذي يجب أن يُعيد تدفقًا بمحتوى المستند. لا يجب أن يكون NULL. **المزيد** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


يُنشئ مثيلًا جديدًا من Editor مع مستند الإدخال المحدد (كـ
تيار) مع خيارات التحميل وإعدادات Editor.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | وثيقة | java.io.InputStream | المندوب، الذي يجب أن يُعيد تدفقًا بمحتوى المستند. لا يجب أن يكون NULL. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | المندوب، الذي يجب أن يُعيد خيارات تحميل المستند. قد يكون NULL وقد يُعيد null - في هذه الحالة سيتم اكتشاف نوع المستند تلقائيًا وتطبيق خيارات التحميل الافتراضية لهذا النوع. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


يُنشئ مثيلًا جديدًا من Editor مع مستند الإدخال المحدد (كمسار ملف كامل).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار الكامل للملف. لا يجب أن يكون NULL. يجب أن يكون صالحًا، ويجب أن يكون الملف موجودًا. **المزيد** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


يُنشئ مثيلًا جديدًا من Editor مع مستند الإدخال المحدد (كمسار ملف كامل) مع خيارات التحميل الخاصة به.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار الكامل للملف. لا يجب أن يكون NULL. يجب أن يكون صالحًا، ويجب أن يكون الملف موجودًا. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | المندوب، الذي يجب أن يُعيد خيارات تحميل المستند. قد يكون NULL وقد يُعيد null - في هذه الحالة سيتم اكتشاف نوع المستند تلقائيًا وتطبيق خيارات التحميل الافتراضية لهذا النوع. **المزيد** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام خيارات محددة خاصة بالصيغة عن طريق إنشاء وإرجاع مثيل من الفئة ''، والتي بدورها تحتوي على طرق لإنشاء ترميز HTML والموارد المرتبطة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | خيارات المستند الخاصة بالتنسيق، التي تسمح بضبط عملية التحويل. لا يجب أن تكون NULL. يجب ألا تتعارض مع خيارات التحميل المطبقة مسبقًا. |


*** ** * ** ***

عند تحميل المستند الأصلي إلى مثيلة 'Editor' عبر المُنشئ، تسمح هذه الطريقة بفتح المستند للتحرير عن طريق تحويله إلى تنسيق وسيط، يتم تغليفه داخل مثيلة من الفئة 'EditableDocument'. 'EditableDocument'، التي تُرجعها هذه الطريقة، تحتوي على جميع الطرق والخصائص اللازمة لإنتاج ترميز HTML والموارد المقابلة (مثل الصور والخطوط وأوراق الأنماط) في جميع التكوينات الضرورية لتمريرها لاحقًا إلى أي محرر HTML WYSIWYG. هذا التحميل الزائد يحصل على خيارات التحرير، التي تكون محددة لتنسيقات العائلة.

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


يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام الخيارات الافتراضية عن طريق
إنشاء وإرجاع مثيل من الفئة 'EditableDocument'، التي،
بدورها تحتوي على طرق لإنشاء ترميز HTML والـ
الموارد.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

عند تحميل المستند الأصلي إلى مثيلة 'Editor' عبر المُنشئ، تسمح هذه الطريقة بفتح المستند للتحرير عن طريق تحويله إلى تنسيق وسيط، يتم تغليفه داخل مثيلة من الفئة 'EditableDocument'. 'EditableDocument'، التي تُرجعها هذه الطريقة، تحتوي على جميع الطرق والخصائص اللازمة لإنتاج ترميز HTML والموارد المقابلة (مثل الصور والخطوط وأوراق الأنماط) في جميع التكوينات الضرورية لتمريرها لاحقًا إلى أي محرر HTML WYSIWYG. هذا التحميل الزائد يطبق خيارات التحرير، التي تكون افتراضية للتنسيق الذي ينتمي إليه المستند المدخل.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


يحوِّل المستند المُحرَّر المحدد، المُمَثَّل كـ
'EditableDocument'، إلى المستند الناتج بالصِيغة المحددة و
يحفظ محتواه إلى التيار المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | إصدار المستند المدخل، الذي تم تحريره في محرر HTML WYSIWYG وتم تخزينه كمثيلة من الفئة 'EditableDocument'، والذي يجب تحويله إلى مستند إخراج بتنسيق محدد. |
|
|  | outputDocument | java.io.OutputStream | تدفق الإخراج، الذي سيتم فيه تسجيل محتوى المستند الناتج. لا يجب أن يكون NULL، أو مُهملًا، ويجب أن يدعم الكتابة. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | خيارات حفظ المستند، التي تحدد تنسيق المستند الناتج، وكذلك خيارات الحفظ العامة والخاصة بالتنسيق. **المزيد** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


يحوِّل المستند المُحرَّر المحدد، المُمَثَّل كـ ''، إلى المستند الناتج بالصِيغة المحددة ويحفظ محتواه إلى ملف عبر مسار الملف المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | إصدار المستند المدخل، الذي تم تحريره في محرر HTML WYSIWYG وتم تخزينه كمثيلة من الفئة ''، والذي يجب تحويله إلى مستند إخراج بتنسيق محدد. يجب ألا يكون null أو مُهملًا. |
|
|  | filePath | java.lang.String | المسار إلى الملف الذي سيتم حفظ المستند الناتج فيه. إذا كان هناك ملف بنفس الاسم، فسيتم إعادة كتابته بالكامل. يجب ألا تكون سلسلة المسار null أو فارغة أو تحتوي على مسافات فقط. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | خيارات حفظ المستند، التي تحدد تنسيق المستند الناتج، وكذلك خيارات الحفظ العامة والخاصة بالتنسيق. يجب ألا تكون null. **المزيد** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


يحوِّل المستند المُحرَّر المحدد (المُمَثَّل بـ [EditableDocument](../../com.groupdocs.editor/editabledocument)) إلى مستند إخراج تُحدَّد صيغته من امتداد اسم الملف، ويحفظه إلى مسار الملف المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | إصدار المستند المدخل الذي تم تحريره في محرر HTML WYSIWYG وتم تخزينه كمثيلة [EditableDocument](../../com.groupdocs.editor/editabledocument). يجب ألا يكون null أو مُهملًا. |
|
|  | filePath | java.lang.String | المسار إلى الملف الذي سيتم حفظ المستند الناتج فيه. إذا كان هناك ملف بنفس الاسم، فسيتم استبداله بالكامل. يجب ألا تكون سلسلة المسار null أو فارغة أو تحتوي على مسافات فقط. نظرًا لأن خيارات الحفظ الافتراضية وتنسيق الإخراج يتم تحديدهما من اسم الملف هذا، يجب أن يحتوي على امتداد صالح. |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


يحوِّل المستند الأصلي بعد التعديل (على سبيل المثال،
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
إلى المستند الناتج بالصِيغة المحددة ويحفظ محتواه إلى التيار المقدم.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | المجرى الذي سيتم حفظ المستند الناتج فيه. يجب أن يكون هذا المجرى قابلًا للكتابة ومُوضَعًا في بداية محتوى المستند. لا يجوز أن يكون فارغًا (null). |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | خيارات حفظ المستند التي تحدد تنسيق المستند الناتج، بالإضافة إلى الخيارات العامة وخيارات الحفظ الخاصة بالتنسيق. لا يجوز أن تكون فارغة (null). |

<br />

*** ** * ** ***

إذا كان  outputDocument  أو  saveOptions  فارغًا (null)، سيتم إلقاء استثناء NullPointerException. إذا كان المستند المراد حفظه مفقودًا، سيتم إلقاء استثناء NullPointerException.

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - المجرى الذي يحتوي على محتوى المستند المحفوظ.

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


احفظ محتوى المستند الحالي إلى التيار الخارج المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | المجرى الذي سيتم حفظ محتوى المستند فيه. لا يمكن أن يكون فارغًا (null). |

<br />

*** ** * ** ***

تنقل هذه الطريقة المحتوى من تمثيل المستند الداخلي إلى المجرى الخارجي المقدم. يتم الحفاظ على الموضع الأصلي للمجرى بعد عملية الحفظ.

<br />

|

**Returns:**
java.io.OutputStream - المجرى الذي يحتوي على محتوى المستند المحفوظ.

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


يرجع بيانات التعريف حول المستند الذي تم تحميله إلى هذه المثيلة من 'Editor'


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | كلمة المرور | java.lang.String | يمكن للمستخدم تحديد كلمة مرور للمستند إذا كان هذا المستند مشفرًا باستخدام كلمة المرور. قد تكون NULL أو سلسلة فارغة، وهو ما يعادل عدم وجود كلمة مرور. بالنسبة لتنسيقات المستند التي لا تدعم ميزة حماية كلمة المرور، سيتم تجاهل هذه المعلمة. إذا كان المستند مشفرًا ولم يتم تحديد كلمة المرور في هذه المعلمة، ولكن تم تحديدها مسبقًا في خيارات التحميل عند إنشاء هذه المثيلة، فسيتم استخدامها. **Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


يحرِّر هذه المثيلة من Editor، بحيث تُفرج عن جميع الموارد الداخلية
الموارد وتصبح غير متاحة للاستخدام لاحقًا


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


يشير إلى ما إذا كانت مثيلة Editor هذه قد تم التخلص منها بالفعل ولا يمكن
استخدامها بعد الآن (true) أو لا، وتكون نشطة (false)


**Returns:**
boolean
