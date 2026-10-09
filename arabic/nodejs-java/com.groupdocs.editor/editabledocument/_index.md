---
title: "EditableDocument"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "مستند وسيط يحتوي على المحتوى قبل وبعد التحرير"
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.editor/editabledocument/
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

يمكن إنشاء كائن من فئة EditableDocument عبر طريقة Editor.edit() أو إنشاؤه بواسطة المستخدم نفسه باستخدام المصانع الساكنة. يخزن EditableDocument المستند داخليًا بصيغته المغلقة الخاصة، والتي تتوافق (قابلة للتحويل) مع جميع صيغ الاستيراد والتصدير التي يدعمها GroupDocs.Editor. لجعل المستند قابلًا للتحرير في أي محرر WYSIWYG من جانب العميل (مثل CKEditor أو TinyMCE)، يوفر EditableDocument طرقًا لإنشاء ترميز HTML وإنتاج موارد يمكن قبولها من قبل المستخدم.

<br />


## الحقول

| حقل | الوصف |
| --- | --- |
| [Disposed](#Disposed) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getImages()](#getImages--) | يسمح بالحصول على موارد الصور الخارجية (صور نقطية)، التي تُستخدم |
في هذا المستند HTML
|
|  | [getFonts()](#getFonts--) | يسمح بالحصول على موارد الخطوط الخارجية، التي تُستخدم في هذا HTML |
وثيقة
|
|  | [getCss()](#getCss--) | يرجع قائمة بموارد CSS |
|
|  | [getAudio()](#getAudio--) | يرجع قائمة بموارد الصوت |
|
|  | [getAllResources()](#getAllResources--) | يرجع قائمة بجميع الموارد الموجودة: جميع أوراق الأنماط، الصور من |
HTML وجميع أوراق الأنماط، الخطوط
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | يرجع المحتوى الكلي لمستند HTML كتيار بايت بكتابة هذا المحتوى إلى الدفق المحدد مع الترميز النصي المحدد |
|
|  | [getBodyContent()](#getBodyContent--) | يرجع جسم مستند HTML (المحتوى بين فتح وإغلاق |
علامات BODY بدون هذه العلامات) كسلسلة.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | يرجع جسم مستند HTML (المحتوى بين فتح وإغلاق |
علامات BODY بدون هذه العلامات) كسلسلة، حيث الروابط إلى الموارد الخارجية
تحتوي على البادئة المحددة.
|
|  | [getContent()](#getContent--) | يرجع المحتوى الكلي لمستند HTML كسلسلة. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | يرجع المحتوى الكلي لمستند HTML كسلسلة، حيث الروابط إلى |
الموارد الخارجية تحتوي على البادئة المحددة.
|
|  | [getCssContent()](#getCssContent--) | يعيد محتوى جميع أوراق الأنماط الخارجية كقائمة من السلاسل، حيث |
تمثل السلسلة الواحدة ورقة نمط واحدة.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | يعيد محتوى جميع أوراق الأنماط الخارجية كقائمة من السلاسل، حيث |
تمثل السلسلة الواحدة ورقة نمط واحدة.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | يعيد كل محتوى مستند HTML هذا مع جميع الموارد المرتبطة في |
شكل سلسلة واحدة، حيث يتم تضمين جميع الموارد داخل HTML
العلامة بتنسيق مشفر Base64.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | يحفظ مستند HTML هذا إلى الملف في المسار المحدد، حيث تكون علامة HTML |
سيتم تخزينها، وإلى المجلد المصاحب للموارد.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | يحفظ مستند HTML هذا إلى الملف في المسار المحدد، حيث تكون علامة HTML |
سيتم تخزينها، وإ إلى المجلد المصاحب للموارد، الذي هو
موجود في المسار المحدد.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | مصنع ثابت، ينشئ مثيلاً من EditableDocument من |
علامة HTML المحددة ومجموعة من الموارد المرتبطة المقابلة
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | مصنع ثابت، ينشئ مثيلاً من EditableDocument من علامة HTML محددة ومن الموارد الموجودة في المجلد المحدد بالمسار الكامل |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | مصنع ثابت، ينشئ مثيلاً من EditableDocument من HTML |
ملف، يتم تحديده بمسار ملف \*.html نفسه ومجلد
مع الموارد المرتبطة
|
|  | [dispose()](#dispose--) | يتخلص من مثيل مستند Editable هذا، مع التخلص من محتواه و |
مما يجعل طرقه وخصائصه غير عاملة
|
|  | [isDisposed()](#isDisposed--) | يحدد ما إذا كان مستند Editable هذا قد تم التخلص منه بالفعل (صحيح) أو |
ليس (خطأ)
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
في هذا المستند HTML


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


يسمح بالحصول على موارد الخطوط الخارجية، التي تُستخدم في هذا HTML
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


يرجع قائمة بجميع الموارد الموجودة: جميع أوراق الأنماط، الصور من
HTML وجميع أوراق الأنماط، الخطوط


*** ** * ** ***

هذه الخاصية تُعيد نتيجة مُدمجة لخصائص 'Images' و'Fonts' و'Css'

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


يرجع المحتوى الكلي لمستند HTML كتيار بايت بكتابة هذا المحتوى إلى الدفق المحدد مع الترميز النصي المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | التخزين | java.io.OutputStream | تيار بايت غير فارغ يدعم الكتابة |
|
|  | الترميز | java.nio.charset.Charset | ترميز نص غير فارغ يجب تطبيقه أثناء كتابة محتوى النص إلى التخزين المحدد |


TStream
: أي تنفيذ لـ java.io.InputStream
|

**Returns:**
java.io.OutputStream - نسخة من التخزين المحدد

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


يرجع جسم مستند HTML (المحتوى بين فتح وإغلاق
علامات BODY بدون هذه العلامات) كسلسلة.


**Returns:**
java.lang.String - سلسلة تحتوي على جسم مستند HTML


*** ** * ** ***

محررات WYSIWYG تتعامل مع جسم المستند ولا يمكنها معالجة معلومات التعريف الوصفية من كتلة HEAD بشكل صحيح. تم تصميم هذه الطريقة لمثل هذه الحالات. هذا التحميل الزائد لا يسمح بضبط عناوين URI لطلبات الموارد الخارجية.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


يرجع جسم مستند HTML (المحتوى بين فتح وإغلاق
علامات BODY بدون هذه العلامات) كسلسلة، حيث الروابط إلى الموارد الخارجية
تحتوي على البادئة المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | من خلال هذا المعامل يمكن تحديد بادئة، سيتم إضافتها إلى الروابط لجميع الصور الخارجية في عناصر IMG التي ستظهر في سلسلة HTML الناتجة. إذا كان NULL أو فارغًا، لن تتم إضافة البادئات. |


*** ** * ** ***

محررات WYSIWYG تتعامل مع جسم المستند ولا يمكنها معالجة معلومات التعريف الوصفية من كتلة HEAD بشكل صحيح. تم تصميم هذه الطريقة لمثل هذه الحالات. هذا التحميل الزائد يسمح بضبط عناوين URI لطلبات الموارد الخارجية.

<br />

|

**Returns:**
java.lang.String - سلسلة تحتوي على جسم مستند HTML مع الروابط، معدلة لتتناسب مع الصور الخارجية

### getContent() {#getContent--}
```
public String getContent()
```


يرجع المحتوى الكلي لمستند HTML كسلسلة.


**Returns:**
java.lang.String - سلسلة تحتوي على محتوى مستند HTML

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


يرجع المحتوى الكلي لمستند HTML كسلسلة، حيث الروابط إلى
الموارد الخارجية تحتوي على البادئة المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | من خلال هذا المعامل يمكن تحديد بادئة، سيتم إضافتها إلى الروابط لجميع الصور الخارجية في عناصر IMG التي ستظهر في سلسلة HTML الناتجة. إذا كان NULL أو فارغًا، لن تتم إضافة البادئات. |
|
|  | externalCssTemplate | java.lang.String | من خلال هذا المعامل يمكن تحديد بادئة، سيتم إضافتها إلى الروابط لجميع أوراق الأنماط الخارجية في عناصر LINK التي ستظهر في سلسلة HTML الناتجة. إذا كان NULL أو فارغًا، لن تتم إضافة البادئات. |
|

**Returns:**
java.lang.String - سلسلة تحتوي على محتوى مستند HTML مع الروابط، معدلة لتتناسب مع الموارد الخارجية

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


يعيد محتوى جميع أوراق الأنماط الخارجية كقائمة من السلاسل، حيث
سلسلة واحدة تمثل ورقة أنماط واحدة. تُرجع قائمة فارغة إذا لم يكن هناك
CSS لهذا المستند.


**Returns:**
java.util.List<java.lang.String> - قائمة من السلاسل، حيث تحتوي كل سلسلة على محتوى مستند CSS واحد

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


يعيد محتوى جميع أوراق الأنماط الخارجية كقائمة من السلاسل، حيث
سلسلة واحدة تمثل ورقة أنماط واحدة. سيتم تطبيق البادئة المحددة على
كل رابط للموارد الخارجية في كل ورقة أنماط ناتجة.
تُرجع قائمة فارغة إذا لم يكن هناك CSS لهذا المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | من خلال هذا المعامل يمكن تحديد بادئة، سيتم إضافتها إلى الروابط لجميع الصور الخارجية التي ستظهر في إعلانات CSS في سلاسل CSS الناتجة. إذا كان NULL أو فارغًا، لن تتم إضافة البادئات. |
|
|  | externalFontsPrefix | java.lang.String | من خلال هذا المعامل يمكن تحديد بادئة، والتي ستُضاف إلى الروابط لجميع الخطوط الخارجية في |
|

**Returns:**
java.util.List<java.lang.String> - قائمة من السلاسل، حيث تحتوي كل سلسلة على محتوى مستند CSS واحد

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


يعيد كل محتوى مستند HTML هذا مع جميع الموارد المرتبطة في
شكل سلسلة واحدة، حيث يتم تضمين جميع الموارد داخل HTML
العلامة بتنسيق مشفر Base64.


**Returns:**
java.lang.String - سلسلة، والتي ليست NULL أو فارغة في أي حالة

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


يحفظ مستند HTML هذا إلى الملف في المسار المحدد، حيث تكون علامة HTML
سيتم تخزينها، وإلى المجلد المصاحب للموارد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | المسار الكامل للملف حيث سيتم تخزين ترميز HTML. سيتم إنشاء الملف أو استبداله إذا كان موجودًا. سيتم إنشاء مجلد الموارد المرافق في نفس المجلد الذي يوجد فيه ملف HTML. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


يحفظ مستند HTML هذا إلى الملف في المسار المحدد، حيث تكون علامة HTML
سيتم تخزينها، وإ إلى المجلد المصاحب للموارد، الذي هو
موجود في المسار المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | المسار الكامل للملف حيث سيتم تخزين ترميز HTML. لا يمكن أن يكون NULL أو فارغًا. سيتم إنشاء الملف أو استبداله إذا كان موجودًا. |
|
|  | resourcesFolderPath | java.lang.String | المسار الكامل للمجلد المرافق حيث سيتم تخزين جميع الموارد ذات الصلة. إذا كان NULL أو فارغًا، سيتم إنشاء المجلد تلقائيًا في نفس الدليل الذي يوجد فيه ملف \*.html. إذا تم تحديده ولا يوجد، سيتم إنشاؤه. |
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


مصنع ثابت، ينشئ مثيلاً من EditableDocument من
علامة HTML المحددة ومجموعة من الموارد المرتبطة المقابلة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String، التي تحتوي على ترميز HTML الخام الذي يجب تحليله. لا يمكن أن تكون NULL أو فارغة أو غير صالحة. |
|
|  | resources | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | مجموعة جميع الموارد (الصور، أوراق الأنماط، الخطوط) المستخدمة في مستند HTML، المحددة في معامل newHtmlContent. قد تكون غائبة (NULL أو مجموعة فارغة). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


مصنع ثابت، ينشئ مثيلاً من EditableDocument من علامة HTML محددة ومن الموارد الموجودة في المجلد المحدد بالمسار الكامل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String، التي تحتوي على ترميز HTML الخام الذي يجب تحليله. لا يمكن أن تكون NULL أو فارغة أو غير صالحة. |
|
|  | resourceFolderPath | java.lang.String | المسار الإلزامي للمجلد الذي يحتوي على الموارد. سيتم استخدام جميع أوراق الأنماط الموجودة في هذا المجلد. لا يمكن أن يكون NULL أو سلسلة فارغة، ويجب أن يكون هذا المجلد موجودًا. |

<br />

*** ** * ** ***

هذه المصنع الثابت مفيد عندما يُقدَّم محتوى مستند HTML كسلسلة، لكن جميع الموارد موجودة في مجلد ما، وغالبًا ما تكون الروابط إلى هذه الموارد في ترميز HTML غير صالحة أو غائبة. عند استدعاء هذه الطريقة، يتم فحص المجلد المحدد وتطبيق جميع أوراق الأنماط التي تم العثور عليها تلقائيًا على المستند. هذه الطريقة مفيدة جدًا عند الحصول على المحتوى من محررات HTML المختلفة، التي عادةً ما تقص بيانات تعريف المستند وما إلى ذلك.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


مصنع ثابت، ينشئ مثيلاً من EditableDocument من HTML
ملف، يتم تحديده بمسار ملف \*.html نفسه ومجلد
مع الموارد المرتبطة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | String، التي تحتوي على المسار الكامل لملف HTML. لا يمكن أن تكون null، يجب أن يكون مسار ملف صالح، ويجب أن يكون الملف نفسه موجودًا. |
|
|  | resourceFolderPath | java.lang.String | مسار اختياري للمجلد الذي يحتوي على موارد HTML. إذا كان NULL أو غير صالح أو لا exists هذا المجلد، سيحاول المحرر العثور على هذا المجلد بنفسه من خلال تحليل ترميز HTML |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


يتخلص من مثيل مستند Editable هذا، مع التخلص من محتواه و
مما يجعل طرقه وخصائصه غير عاملة


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


يحدد ما إذا كان مستند Editable هذا قد تم التخلص منه بالفعل (صحيح) أو
ليس (خطأ)


**Returns:**
boolean
