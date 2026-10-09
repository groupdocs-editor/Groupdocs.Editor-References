---
title: "Editor"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "الفئة الرئيسية التي تُغلف طرق التحويل."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

الفئة الرئيسية التي تغلف أساليب التحويل.
توفر فئة Editor طرقًا لتحميل المستندات وتحريرها وحفظها بجميع الصيغ المدعومة. إنها قابلة للتصرف، لذا استخدم توجيه 'using' أو حرّر مواردها يدويًا عبر استدعاء الطريقة 'Dispose()'. يتم تحميل المستند من خلال المُنشئات. تحرير المستند - عبر الطريقة 'Edit'، وحفظ المستند الناتج بعد التحرير - عبر الطريقة 'Save'.
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | ينشئ مثيلًا جديدًا من الفئة [Editor](../../com.groupdocs.editor/editor) ويُنشئ مستندًا فارغًا جديدًا بناءً على التنسيق المحدد. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | ينشئ مثيلًا جديدًا من Editor بالمستند الإدخالي المحدد (كتيار) |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | ينشئ مثيلًا جديدًا من Editor بالمستند الإدخالي المحدد (ك |
stream) مع خيارات التحميل وإعدادات Editor
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | يُنشئ مثيل جديد من Editor مع مستند الإدخال المحدد (كمسار ملف كامل) |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | يُنشئ مثيل جديد من Editor مع مستند الإدخال المحدد (كمسار ملف كامل) مع خيارات التحميل الخاصة به |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام خيارات محددة خاصة بالتنسيق عن طريق إنشاء وإرجاع مثيل من الفئة ''، والتي بدورها تحتوي على طرق لإنشاء ترميز HTML والموارد المرتبطة. |
|
|  | [edit()](#edit--) | يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام الخيارات الافتراضية عن طريق |
إنشاء وإرجاع مثيل من الفئة 'EditableDocument'، التي
بدورها، تحتوي على طرق لإنتاج ترميز HTML وال
الموارد.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | يحوّل المستند المعدل المحدد، الممثّل كمثيل من |
'EditableDocument'، إلى المستند الناتج بالتنسيق المحدد و
يحفظ محتواه إلى الدفق المحدد
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | يحوّل المستند المعدل المحدد، الممثّل كمثيل من ''، إلى المستند الناتج بالتنسيق المحدد ويحفظ محتواه إلى ملف عبر مسار الملف المحدد |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | يحوّل المستند المعدل المحدد (الممثّل بواسطة [EditableDocument](../../com.groupdocs.editor/editabledocument)) إلى مستند إخراج يتم تحديد تنسيقه من امتداد اسم الملف، ويحفظه إلى مسار الملف المحدد. |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | يحوّل المستند الأصلي بعد التعديل (على سبيل المثال، |
FormFieldManager
(#getFormFieldManager.getFormFieldManager))،
إلى المستند الناتج بالتنسيق المحدد ويحفظ محتواه إلى الدفق المقدم.
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | احفظ محتوى المستند الحالي إلى الدفق الناتج المحدد. |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | يرجع البيانات الوصفية حول المستند الذي تم تحميله إلى مثيل 'Editor' هذا |
|
|  | [dispose()](#dispose--) | يحرّر هذا المثيل من Editor، بحيث يفرج عن جميع الموارد الداخلية |
ويصبح غير متاح للاستخدام لاحقًا
|
|  | [isDisposed()](#isDisposed--) | يشير إلى ما إذا كان مثيل Editor هذا قد تم تحريره بالفعل ولا يمكن أن يكون |
مستخدم بعد الآن (true) أو لا، وهو نشط (false)
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


ينشئ مثيلًا جديدًا من الفئة [Editor](../../com.groupdocs.editor/editor) ويُنشئ مستندًا فارغًا جديدًا بناءً على التنسيق المحدد.

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
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | يمثل تنسيق الملف للمستند الذي سيتم إنشاؤه. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


ينشئ مثيلًا جديدًا من Editor بالمستند الإدخالي المحدد (كتيار)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | وثيقة | java.io.InputStream | المندوب، الذي يجب أن يُعيد دفقًا بمحتوى المستند. لا يجب أن يكون NULL. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


ينشئ مثيلًا جديدًا من Editor بالمستند الإدخالي المحدد (ك
stream) مع خيارات التحميل وإعدادات Editor


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | وثيقة | java.io.InputStream | المندوب، الذي يجب أن يُعيد دفقًا بمحتوى المستند. لا يجب أن يكون NULL. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | المندوب، الذي يجب أن يُعيد خيارات تحميل المستند. قد يكون NULL وقد يُعيد null - في هذه الحالة سيتم اكتشاف نوع المستند تلقائيًا وتطبيق خيارات التحميل الافتراضية لهذا النوع. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


يُنشئ مثيل جديد من Editor مع مستند الإدخال المحدد (كمسار ملف كامل)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار الكامل للملف. يجب ألا يكون NULL. يجب أن يكون صالحًا، ويجب أن يكون الملف موجودًا. **تعرف على المزيد** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


يُنشئ مثيل جديد من Editor مع مستند الإدخال المحدد (كمسار ملف كامل) مع خيارات التحميل الخاصة به


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار الكامل للملف. يجب ألا يكون NULL. يجب أن يكون صالحًا، ويجب أن يكون الملف موجودًا. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | المندوب، الذي يجب أن يُعيد خيارات تحميل المستند. قد يكون NULL وقد يُعيد null - في هذه الحالة سيتم اكتشاف نوع المستند تلقائيًا وتطبيق خيارات التحميل الافتراضية لهذا النوع. **تعرف على المزيد** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


يفتح مستندًا تم تحميله مسبقًا للتحرير باستخدام خيارات محددة خاصة بالتنسيق عن طريق إنشاء وإرجاع مثيل من الفئة ''، والتي بدورها تحتوي على طرق لإنشاء ترميز HTML والموارد المرتبطة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | خيارات المستند الخاصة بالتنسيق، التي تسمح بضبط عملية التحويل. يجب ألا تكون NULL. يجب ألا تتعارض مع خيارات التحميل التي تم تطبيقها مسبقًا. |


*** ** * ** ***

عند تحميل المستند الأصلي إلى مثيل 'Editor' عبر المُنشئ، يسمح هذا الأسلوب بفتح المستند للتحرير عن طريق تحويله إلى تنسيق وسيط، يتم تغليفه داخل مثيل من فئة 'EditableDocument'. 'EditableDocument'، الذي يُرجع من هذا الأسلوب، يحتوي على جميع الطرق والخصائص الضرورية لإنتاج ترميز HTML والموارد المقابلة (مثل الصور، الخطوط، وأوراق الأنماط) في جميع التكوينات اللازمة لتمريرها لاحقًا إلى أي محرر HTML WYSIWYG. هذا التحميل الزائد يحصل على خيارات التحرير، التي تكون محددة لتنسيقات العائلة.

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
إنشاء وإرجاع مثيل من الفئة 'EditableDocument'، التي
بدورها، تحتوي على طرق لإنتاج ترميز HTML وال
الموارد.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

عند تحميل المستند الأصلي إلى مثيل 'Editor' عبر المُنشئ، يسمح هذا الأسلوب بفتح المستند للتحرير عن طريق تحويله إلى تنسيق وسيط، يتم تغليفه داخل مثيل من فئة 'EditableDocument'. 'EditableDocument'، الذي يُرجع من هذا الأسلوب، يحتوي على جميع الطرق والخصائص الضرورية لإنتاج ترميز HTML والموارد المقابلة (مثل الصور، الخطوط، وأوراق الأنماط) في جميع التكوينات اللازمة لتمريرها لاحقًا إلى أي محرر HTML WYSIWYG. هذا التحميل الزائد يطبق خيارات التحرير، التي تكون افتراضية للتنسيق الذي ينتمي إليه المستند المدخل.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


يحوّل المستند المعدل المحدد، الممثّل كمثيل من
'EditableDocument'، إلى المستند الناتج بالتنسيق المحدد و
يحفظ محتواه إلى الدفق المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | إصدار المستند المدخل، الذي تم تحريره في محرر HTML WYSIWYG ويُخزن كمثيل من فئة 'EditableDocument'، والذي يجب تحويله إلى مستند إخراج بتنسيق محدد. |
|
|  | outputDocument | java.io.OutputStream | دفق الإخراج، الذي سيتم فيه تسجيل محتوى المستند الناتج. يجب ألا يكون NULL، ولا مُهمل، ويجب أن يدعم الكتابة. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | خيارات حفظ المستند، التي تحدد تنسيق المستند الناتج، وكذلك خيارات الحفظ العامة والخاصة بالتنسيق. **تعرف على المزيد** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


يحوّل المستند المعدل المحدد، الممثّل كمثيل من ''، إلى المستند الناتج بالتنسيق المحدد ويحفظ محتواه إلى ملف عبر مسار الملف المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | إصدار المستند المدخل، الذي تم تحريره في محرر HTML WYSIWYG ويُخزن كمثيل من الفئة ''، والذي يجب تحويله إلى مستند إخراج بتنسيق محدد. يجب ألا يكون null أو مُهمل. |
|
|  | filePath | java.lang.String | المسار إلى الملف الذي سيتم حفظ المستند الناتج فيه. إذا كان هناك ملف بنفس الاسم، فسيتم إعادة كتابته بالكامل. يجب ألا تكون سلسلة المسار null أو فارغة أو تحتوي فقط على مسافات بيضاء. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | خيارات حفظ المستند، التي تحدد تنسيق المستند الناتج، وكذلك خيارات الحفظ العامة والخاصة بالتنسيق. يجب ألا تكون null. **تعرف على المزيد** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


يحوّل المستند المعدل المحدد (الممثّل بواسطة [EditableDocument](../../com.groupdocs.editor/editabledocument)) إلى مستند إخراج يتم تحديد تنسيقه من امتداد اسم الملف، ويحفظه إلى مسار الملف المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | إصدار المستند المدخل الذي تم تحريره في محرر HTML WYSIWYG ويُخزن كمثيل من [EditableDocument](../../com.groupdocs.editor/editabledocument). يجب ألا يكون null أو مُهمل. |
|
|  | filePath | java.lang.String | المسار إلى الملف الذي سيتم حفظ المستند الناتج فيه. إذا كان هناك ملف بنفس الاسم، فسيتم استبداله بالكامل. يجب ألا تكون سلسلة المسار null أو فارغة أو تحتوي فقط على مسافات بيضاء. نظرًا لأن خيارات الحفظ الافتراضية وتنسيق الإخراج يتم تحديدهما من اسم الملف هذا، يجب أن يكون له امتداد صالح. |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


يحوّل المستند الأصلي بعد التعديل (على سبيل المثال،
FormFieldManager
(#getFormFieldManager.getFormFieldManager))،
إلى المستند الناتج بالتنسيق المحدد ويحفظ محتواه إلى الدفق المقدم.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | الدفق الذي سيتم حفظ المستند الناتج إليه. يجب أن يكون هذا الدفق قابلًا للكتابة ومُحددًا في بداية محتوى المستند. يجب ألا يكون null. |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | خيارات حفظ المستند التي تحدد تنسيق المستند الناتج، بالإضافة إلى خيارات الحفظ العامة والخاصة بالتنسيق. يجب ألا تكون null. |

<br />

*** ** * ** ***

إذا كان outputDocument أو saveOptions فارغًا (null)، سيتم رمي استثناء NullPointerException. إذا كان المستند المراد حفظه مفقودًا، سيتم رمي استثناء NullPointerException.

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - الدفق الذي يحتوي على محتوى المستند المحفوظ.

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


احفظ محتوى المستند الحالي إلى الدفق الناتج المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | الدفق الذي سيُحفظ فيه محتوى المستند. لا يمكن أن يكون فارغًا (null). |

<br />

*** ** * ** ***

هذه الطريقة تنسخ المحتوى من تمثيل المستند الداخلي إلى الدفق الخارجي المقدم. يتم الحفاظ على موضع الدفق الأصلي بعد عملية الحفظ.

<br />

|

**Returns:**
java.io.OutputStream - الدفق الذي يحتوي على محتوى المستند المحفوظ.

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


يرجع البيانات الوصفية حول المستند الذي تم تحميله إلى مثيل 'Editor' هذا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | كلمة المرور | java.lang.String | يمكن للمستخدم تحديد كلمة مرور للمستند إذا كان هذا المستند مشفرًا باستخدام كلمة المرور. قد تكون NULL أو سلسلة فارغة، وهذا ما يعادل عدم وجود كلمة مرور. بالنسبة لتنسيقات المستند التي لا تحتوي على ميزة حماية كلمة المرور، سيتم تجاهل هذه المعلمة. إذا كان المستند مشفرًا، ولم يتم تحديد كلمة المرور في هذه المعلمة، ولكن تم تحديدها مسبقًا في خيارات التحميل أثناء إنشاء هذه الحالة، فسيتم استخدامها. **Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


يحرّر هذا المثيل من Editor، بحيث يفرج عن جميع الموارد الداخلية
ويصبح غير متاح للاستخدام لاحقًا


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


يشير إلى ما إذا كان مثيل Editor هذا قد تم تحريره بالفعل ولا يمكن أن يكون
مستخدم بعد الآن (true) أو لا، وهو نشط (false)


**Returns:**
boolean
