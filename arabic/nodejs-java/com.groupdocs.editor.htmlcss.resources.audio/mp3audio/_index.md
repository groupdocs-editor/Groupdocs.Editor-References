---
title: "Mp3Audio"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل موردًا صوتيًا بتنسيق عشوائي."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

يمثل موردًا صوتيًا بتنسيق عشوائي.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | ينشئ فئة Mp3Audio جديدة من محتوى MP3، ممثلاً كتيار بايت، ومع اسم محدد |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | يتحقق مما إذا كان التيار المحدد محتوى MP3 صالحًا |
|
|  | [getName()](#getName--) | يرجع اسم هذا المحتوى MP3. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | يرجع اسم الملف الصحيح لهذا المحتوى MP3، والذي يتكون من الاسم والامتداد. |
|
|  | [getType()](#getType--) | يرجع AudioFormat.Mp3 (كما يفي بـ IHtmlResource.getFormat() عبر إرجاع متقارب) |
|
|  | [getByteContent()](#getByteContent--) | إرجاع محتوى هذا الخط كتيار بايت |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | إرجاع محتوى هذا المورد الصوتي MP3 كتيار بايت مع الموضع الأصلي |
|
|  | [getTextContent()](#getTextContent--) | إرجاع محتوى هذا المورد MP3 كسلسلة مشفرة بقاعدة64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | يحفظ هذا المورد MP3 إلى الملف المحدد |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | يفحص هذه الحالة مع المورد HTML المحدد على مساواة المرجع |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | يفحص هذه الحالة مع مورد الخط المحدد على مساواة المرجع |
|
|  | [dispose()](#dispose--) | يُفرغ هذا المورد MP3، مُفرغًا محتواه وجاعلاً معظم الأساليب والخصائص غير عاملة |
|
|  | [isDisposed()](#isDisposed--) | يحدد ما إذا كان محتوى MP3 هذا مُفرغًا أم لا |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


ينشئ فئة Mp3Audio جديدة من محتوى MP3، ممثلاً كتيار بايت، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم محتوى MP3. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
|
|  | binaryContent | com.aspose.ms.System.IO.Stream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون null. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|
|  | leaveOpen | boolean | يحدد ما إذا كان سيتم تحرير التيار المحدد أم لا عند تحرير حالة Mp3Audio |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


يتحقق مما إذا كان التيار المحدد محتوى MP3 صالحًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | com.aspose.ms.System.IO.Stream | تيار بايت، من المفترض أنه يحتوي على محتوى MP3 |
|

**Returns:**
منطقي - True إذا كان التيار المحدد يحتوي على محتوى MP3 صالح، false otherwise

### getName() {#getName--}
```
public String getName()
```


إرجاع اسم هذا المحتوى MP3. عادةً لا يحتوي على امتداد اسم الملف ويمكن نظريًا أن يختلف عن اسم الملف.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


إرجاع اسم الملف الصحيح لهذا المحتوى MP3، الذي يتكون من الاسم والامتداد. نظريًا يمكن أن يختلف عن الاسم.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


يرجع AudioFormat.Mp3 (كما يفي بـ IHtmlResource.getFormat() عبر إرجاع متقارب)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


إرجاع محتوى هذا الخط كتيار بايت


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


إرجاع محتوى هذا المورد الصوتي MP3 كتيار بايت مع الموضع الأصلي


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


إرجاع محتوى هذا المورد MP3 كسلسلة مشفرة بقاعدة64. يتم تخزين هذه القيمة مؤقتًا بعد الاستدعاء الأول.


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


يحفظ هذا المورد MP3 إلى الملف المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | المسار الكامل للملف، الذي سيتم إنشاؤه أو إعادة كتابته |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


يفحص هذه الحالة مع المورد HTML المحدد على مساواة المرجع


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | مُورّث آخر لواجهة IHtmlResource |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


يفحص هذه الحالة مع مورد الخط المحدد على مساواة المرجع


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | مثيل آخر لفئة Mp3Audio |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### dispose() {#dispose--}
```
public void dispose()
```


يُفرغ هذا المورد MP3، مُفرغًا محتواه وجاعلاً معظم الأساليب والخصائص غير عاملة


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


يحدد ما إذا كان محتوى MP3 هذا مُفرغًا أم لا


**Returns:**
boolean
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

