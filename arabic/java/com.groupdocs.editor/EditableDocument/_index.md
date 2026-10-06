---
title: "EditableDocument"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "مستند وسيط يحتوي على المحتوى قبل وبعد التحرير"
type: docs
weight: 10
url: /ar/java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

مستند وسيط يحتوي على المحتوى قبل وبعد التحرير


*** ** * ** ***

يمكن إنشاء كائن من فئة EditableDocument باستخدام طريقة Editor.edit() أو إنشاؤه بواسطة المستخدم نفسه باستخدام المصانع الثابتة. يخزن EditableDocument المستند داخليًا بتنسيقه المغلق الخاص، وهو متوافق (قابل للتحويل) مع جميع تنسيقات الاستيراد والتصدير التي يدعمها GroupDocs.Editor. لجعل المستند قابلاً للتحرير في أي محرر WYSIWYG من جانب العميل (مثل CKEditor أو TinyMCE)، يوفر EditableDocument طرقًا لإنشاء ترميز HTML وإنتاج الموارد التي يمكن للمستخدم قبولها.

<br />


## الحقول

| حقل | الوصف |
| --- | --- |
| [Disposed](#Disposed) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getImages()](#getImages--) | يسمح بالحصول على موارد الصور الخارجية (صور نقطية)، التي تُستخدم |
بواسطة هذا المستند HTML
|
|  | [getFonts()](#getFonts--) | يسمح بالحصول على موارد الخطوط الخارجية، التي يستخدمها هذا HTML |
وثيقة
|
|  | [getCss()](#getCss--) | يرجع قائمة بموارد CSS |
|
|  | [getAudio()](#getAudio--) | يرجع قائمة بموارد الصوت |
|
|  | [getAllResources()](#getAllResources--) | يرجع قائمة بجميع الموارد الموجودة: جميع stylesheets، الصور من |
HTML وجميع stylesheets، الخطوط
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | يرجع المحتوى الكلي للمستند HTML على شكل تدفق بايت عن طريق كتابة هذا المحتوى إلى التدفق المحدد مع الترميز النصي المحدد |
|
|  | [getBodyContent()](#getBodyContent--) | يرجع جسم المستند HTML (المحتوى بين الفتح والإغلاق |
وسوم BODY بدون هذه الوسوم) كسلسلة نصية.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | يرجع جسم المستند HTML (المحتوى بين الفتح والإغلاق |
وسوم BODY بدون هذه الوسوم) كسلسلة نصية، حيث الروابط إلى الموارد الخارجية
الموارد تحتوي على البادئة المحددة.
|
|  | [getContent()](#getContent--) | يرجع المحتوى الكلي للمستند HTML كسلسلة نصية. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | يرجع المحتوى الكلي للمستند HTML كسلسلة نصية، حيث الروابط إلى |
الموارد الخارجية تحتوي على البادئة المحددة.
|
|  | [getCssContent()](#getCssContent--) | يرجع محتوى جميع stylesheets الخارجية كقائمة من السلاسل النصية، حيث |
سلسلة واحدة تمثل stylesheet واحدة.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | يرجع محتوى جميع stylesheets الخارجية كقائمة من السلاسل النصية، حيث |
سلسلة واحدة تمثل stylesheet واحدة.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | يرجع كل محتوى هذا المستند HTML مع جميع الموارد المرتبطة في |
شكل سلسلة واحدة، حيث يتم تضمين جميع الموارد داخل الـ HTML
الترميز في شكل مشفر بقاعدة64.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | يحفظ هذا المستند HTML إلى الملف في المسار المحدد، حيث ترميز HTML |
سيتم تخزينه، وإلى المجلد المرافق مع الموارد.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | يحفظ هذا المستند HTML إلى الملف في المسار المحدد، حيث ترميز HTML |
سيتم تخزينه، وإلى المجلد المرافق مع الموارد، الذي هو
يقع في المسار المحدد.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | مصنع ثابت، ينشئ نسخة من EditableDocument من |
ترميز HTML المحدد ومجموعة من الموارد المرتبطة المقابلة
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | مصنع ثابت، ينشئ مثيلاً من EditableDocument من ترميز HTML محدد ومن الموارد الموجودة في المجلد المحدد بالمسار الكامل |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | مصنع ثابت، ينشئ مثيلاً من EditableDocument من HTML |
ملف، يتم تحديده بمسار إلى ملف \\*.html نفسه ومجلد
مع الموارد المرتبطة
|
|  | [dispose()](#dispose--) | يتخلص من مثيل هذا المستند القابل للتحرير، مع التخلص من محتواه و |
مما يجعل طرقه وخصائصه غير عاملة
|
|  | [isDisposed()](#isDisposed--) | يحدد ما إذا كان هذا المستند القابل للتحرير قد تم التخلص منه بالفعل (true) أو |
ليس (false)
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


يسمح بالحصول على موارد الصور الخارجية (صور نقطية)، التي تُستخدم
بواسطة هذا المستند HTML


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


يسمح بالحصول على موارد الخطوط الخارجية، التي يستخدمها هذا HTML
وثيقة


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


يرجع قائمة بموارد CSS


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


يرجع قائمة بموارد الصوت


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


يرجع قائمة بجميع الموارد الموجودة: جميع stylesheets، الصور من
HTML وجميع stylesheets، الخطوط


*** ** * ** ***

تُعيد هذه الخاصية نتيجة متسلسلة من خصائص 'Images' و 'Fonts' و 'Css'

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


يرجع المحتوى الكلي للمستند HTML على شكل تدفق بايت عن طريق كتابة هذا المحتوى إلى التدفق المحدد مع الترميز النصي المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | التخزين | java.io.OutputStream | تدفق بايت غير فارغ، يدعم الكتابة |
|
|  | الترميز | java.nio.charset.Charset | ترميز نص غير فارغ، يجب تطبيقه أثناء كتابة محتوى النص إلى التخزين المحدد |


TStream
: أي تنفيذ لـ java.io.InputStream
|

**Returns:**
java.io.OutputStream - مثيل للتخزين المحدد

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


يرجع جسم المستند HTML (المحتوى بين الفتح والإغلاق
وسوم BODY بدون هذه الوسوم) كسلسلة نصية.


**Returns:**
java.lang.String - سلسلة، تحتوي على جسم مستند HTML


*** ** * ** ***

تعمل محررات WYSIWYG مع جسم المستند ولا يمكنها معالجة معلومات التعريف الوصفية من كتلة HEAD بشكل صحيح. تم تصميم هذه الطريقة لمثل هذه الحالات. لا يسمح هذا التحميل الزائد بتعديل عناوين URI لطلبات الموارد الخارجية.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


يرجع جسم المستند HTML (المحتوى بين الفتح والإغلاق
وسوم BODY بدون هذه الوسوم) كسلسلة نصية، حيث الروابط إلى الموارد الخارجية
الموارد تحتوي على البادئة المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | من خلال هذا المعامل يمكن تحديد بادئة، ستُضاف إلى الروابط لجميع الصور الخارجية في عناصر IMG التي ستكون موجودة في سلسلة HTML الناتجة. إذا كان NULL أو فارغًا، لن تُضاف البادئات. |


*** ** * ** ***

تعمل محررات WYSIWYG مع جسم المستند ولا يمكنها معالجة معلومات التعريف الوصفية من كتلة HEAD بشكل صحيح. تم تصميم هذه الطريقة لمثل هذه الحالات. يسمح هذا التحميل الزائد بتعديل عناوين URI لطلبات الموارد الخارجية.

<br />

|

**Returns:**
java.lang.String - سلسلة، تحتوي على جسم مستند HTML مع الروابط، معدلة لتضم الصور الخارجية

### getContent() {#getContent--}
```
public String getContent()
```


يرجع المحتوى الكلي للمستند HTML كسلسلة نصية.


**Returns:**
java.lang.String - سلسلة، تحتوي على محتوى مستند HTML

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


يرجع المحتوى الكلي للمستند HTML كسلسلة نصية، حيث الروابط إلى
الموارد الخارجية تحتوي على البادئة المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | من خلال هذا المعامل يمكن تحديد بادئة، ستُضاف إلى الروابط لجميع الصور الخارجية في عناصر IMG التي ستكون موجودة في سلسلة HTML الناتجة. إذا كان NULL أو فارغًا، لن تُضاف البادئات. |
|
|  | externalCssTemplate | java.lang.String | من خلال هذا المعامل يمكن تحديد بادئة، ستُضاف إلى الروابط إلى جميع أوراق الأنماط الخارجية في عناصر LINK، والتي ستكون موجودة في سلسلة HTML الناتجة. إذا كان NULL أو فارغًا، لن تُضاف البادئات. |
|

**Returns:**
java.lang.String - سلسلة، تحتوي على محتوى مستند HTML مع الروابط، معدلة لتضم الموارد الخارجية

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


يرجع محتوى جميع stylesheets الخارجية كقائمة من السلاسل النصية، حيث
سلسلة واحدة تمثل ورقة أنماط واحدة. تُرجع قائمة فارغة إذا لم يكن هناك
CSS لهذا المستند.


**Returns:**
java.util.List<java.lang.String> - قائمة من السلاسل، حيث تحتوي كل سلسلة على محتوى مستند CSS واحد

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


يرجع محتوى جميع stylesheets الخارجية كقائمة من السلاسل النصية، حيث
سلسلة واحدة تمثل ورقة أنماط واحدة. سيتم تطبيق البادئة المحددة على
كل رابط إلى المورد الخارجي في كل ورقة أنماط ناتجة.
تُرجع قائمة فارغة إذا لم يكن هناك CSS لهذا المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | من خلال هذا المعامل يمكن تحديد بادئة، ستُضاف إلى الروابط إلى جميع الصور الخارجية، والتي ستكون موجودة في تصريحات CSS في سلاسل CSS الناتجة. إذا كان NULL أو فارغًا، لن تُضاف البادئات. |
|
|  | externalFontsPrefix | java.lang.String | من خلال هذا المعامل يمكن تحديد بادئة، ستُضاف إلى الروابط إلى جميع الخطوط الخارجية في |
|

**Returns:**
java.util.List<java.lang.String> - قائمة من السلاسل، حيث تحتوي كل سلسلة على محتوى مستند CSS واحد

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


يرجع كل محتوى هذا المستند HTML مع جميع الموارد المرتبطة في
شكل سلسلة واحدة، حيث يتم تضمين جميع الموارد داخل الـ HTML
الترميز في شكل مشفر بقاعدة64.


**Returns:**
java.lang.String - سلسلة، والتي ليست NULL أو فارغة في أي حال

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


يحفظ هذا المستند HTML إلى الملف في المسار المحدد، حيث ترميز HTML
سيتم تخزينه، وإلى المجلد المرافق مع الموارد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | المسار الكامل للملف حيث سيتم تخزين ترميز HTML. سيتم إنشاء الملف أو استبداله إذا كان موجودًا. سيتم إنشاء مجلد الموارد المرافق في نفس المجلد الذي يوجد فيه ملف HTML. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


يحفظ هذا المستند HTML إلى الملف في المسار المحدد، حيث ترميز HTML
سيتم تخزينه، وإلى المجلد المرافق مع الموارد، الذي هو
يقع في المسار المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | المسار الكامل للملف حيث سيتم تخزين ترميز HTML. لا يمكن أن يكون NULL أو فارغًا. سيتم إنشاء الملف أو استبداله إذا كان موجودًا. |
|
|  | resourcesFolderPath | java.lang.String | المسار الكامل للمجلد المرافق حيث سيتم تخزين جميع الموارد المرتبطة. إذا كان NULL أو فارغًا، سيتم إنشاء المجلد تلقائيًا في نفس الدليل حيث ملف \*.html. إذا تم تحديده ولم يكن موجودًا، سيتم إنشاؤه. |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


مصنع ثابت، ينشئ نسخة من EditableDocument من
ترميز HTML المحدد ومجموعة من الموارد المرتبطة المقابلة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | سلسلة، تحتوي على ترميز HTML الخام الذي يجب تحليله. لا يمكن أن تكون NULL أو فارغة أو غير صالحة. |
|
|  | الموارد | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | مجموعة جميع الموارد (الصور، ملفات الأنماط، الخطوط) التي تُستخدم في مستند HTML، المحددة في معامل newHtmlContent. قد تكون غير موجودة (NULL أو مجموعة فارغة). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


مصنع ثابت، ينشئ مثيلاً من EditableDocument من ترميز HTML محدد ومن الموارد الموجودة في المجلد المحدد بالمسار الكامل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | سلسلة، تحتوي على ترميز HTML الخام الذي يجب تحليله. لا يمكن أن تكون NULL أو فارغة أو غير صالحة. |
|
|  | resourceFolderPath | java.lang.String | مسار إلزامي إلى المجلد الذي يحتوي على الموارد. جميع ملفات الأنماط الموجودة في هذا المجلد ستُستخدم. لا يمكن أن يكون NULL أو سلسلة فارغة، ويجب أن يكون هذا المجلد موجودًا. |

<br />

*** ** * ** ***

هذه المصنع الثابت مفيد عندما يُقدَّم محتوى مستند HTML كسلسلة نصية، لكن جميع الموارد موجودة في مجلد ما، وغالبًا ما تكون الروابط إلى هذه الموارد في ترميز HTML غير صالحة أو غير موجودة. عند استدعاء هذه الطريقة، يتم فحص المجلد المحدد وتطبيق جميع ملفات الأنماط التي تم العثور عليها تلقائيًا على المستند. هذه الطريقة مفيدة جدًا عند الحصول على المحتوى من محررات HTML المختلفة، التي عادةً ما تقص بيانات تعريف المستند وما إلى ذلك.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


مصنع ثابت، ينشئ مثيلاً من EditableDocument من HTML
ملف، يتم تحديده بمسار إلى ملف \\*.html نفسه ومجلد
مع الموارد المرتبطة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | سلسلة تحتوي على المسار الكامل لملف HTML. لا يمكن أن تكون null، يجب أن يكون مسار ملف صالح، ويجب أن يكون الملف نفسه موجودًا. |
|
|  | resourceFolderPath | java.lang.String | مسار اختياري إلى المجلد الذي يحتوي على موارد HTML. إذا كان NULL أو غير صالح أو لم يكن هذا المجلد موجودًا، سيحاول المحرر العثور على هذا المجلد بنفسه من خلال تحليل ترميز HTML |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


يتخلص من مثيل هذا المستند القابل للتحرير، مع التخلص من محتواه و
مما يجعل طرقه وخصائصه غير عاملة


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


يحدد ما إذا كان هذا المستند القابل للتحرير قد تم التخلص منه بالفعل (true) أو
ليس (false)


**Returns:**
boolean
