---
title: "Editor"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Dönüştürme yöntemlerini kapsülleyen ana sınıf."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

Dönüştürme yöntemlerini kapsülleyen ana sınıf.
Editor sınıfı, tüm desteklenen formatlardaki belgeleri yükleme, düzenleme ve kaydetme yöntemleri sağlar. Yok edilebilir bir sınıftır, bu yüzden bir 'using' yönergesi kullanın veya kaynaklarını 'Dispose()' yöntemiyle manuel olarak serbest bırakın. Belge yükleme, yapıcılar aracılığıyla gerçekleştirilir. Belge düzenleme – 'Edit' yöntemiyle, ve düzenleme sonrası ortaya çıkan belgeyi kaydetme – 'Save' yöntemiyle yapılır.
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Belirtilen format temel alınarak yeni boş bir belge oluşturan [Editor](../../com.groupdocs.editor/editor) sınıfının yeni bir örneğini başlatır. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | Belirtilen giriş belgesi (akış olarak) ile yeni bir Editor örneğini başlatır. |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | Belirtilen giriş belgesiyle yeni bir Editor örneğini başlatır (as a |
stream) ile yükleme seçenekleri ve Editor ayarları
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | Belirtilen giriş belgesi (tam dosya yolu olarak) ile yeni bir Editor örneği başlatır |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | Belirtilen giriş belgesi (tam dosya yolu olarak) ve onun yükleme seçenekleri ile yeni bir Editor örneği başlatır |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | Belirtilen format‑özel seçenekleri kullanarak daha önce yüklenmiş bir belgeyi düzenleme için açar; '' sınıfının bir örneğini oluşturur ve döndürür, bu örnek de HTML işaretlemesi ve ilgili kaynakları üretmek için yöntemler içerir. |
|
|  | [edit()](#edit--) | Varsayılan seçenekleri kullanarak daha önce yüklenmiş bir belgeyi düzenleme için açar |
'EditableDocument' sınıfının bir örneğini oluşturup döndürür, bu
sırasıyla, HTML işaretlemesi ve ilgili
kaynakları.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | Belirtilen düzenlenmiş belgeyi, örnek olarak temsil edilen |
'EditableDocument', belirtilen formatta ortaya çıkan belgeye ve
içeriğini belirtilen akışa kaydeder
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | Belirtilen düzenlenmiş belgeyi, '' örneği olarak temsil edilen, belirtilen formatta ortaya çıkan belgeye dönüştürür ve içeriğini belirtilen dosya yolu ile dosyaya kaydeder |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | Belirtilen düzenlenmiş belgeyi ([EditableDocument](../../com.groupdocs.editor/editabledocument) tarafından temsil edilen) dosya uzantısından belirlenen bir çıktı belgesine dönüştürür ve belirtilen dosya yoluna kaydeder. |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | Değişiklikten sonra orijinal belgeyi dönüştürür (örneğin, |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
belirtilen formatta ortaya çıkan belgeye ve içeriğini sağlanan akışa kaydeder.
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | Mevcut belge içeriğini belirtilen çıktı akışına kaydedin. |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | Bu 'Editor' örneğine yüklenen belge hakkında meta verileri döndürür |
|
|  | [dispose()](#dispose--) | Editor örneğini serbest bırakır, böylece tüm iç |
kaynakları serbest bırakır ve sonraki kullanım için kullanılamaz hâle gelir
|
|  | [isDisposed()](#isDisposed--) | Bu Editor örneğinin zaten serbest bırakılıp bırakılmadığını ve artık |
kullanılamayacağını (true) ya da kullanılabilir olduğunu (false) gösterir
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


Belirtilen format temel alınarak yeni boş bir belge oluşturan [Editor](../../com.groupdocs.editor/editor) sınıfının yeni bir örneğini başlatır.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | oluşturulacak belgenin dosya formatını temsil eder. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


Belirtilen giriş belgesi (akış olarak) ile yeni bir Editor örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Belge içeriğiyle bir akış döndürmesi gereken delege. NULL olmamalıdır. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


Belirtilen giriş belgesiyle yeni bir Editor örneğini başlatır (as a
stream) ile yükleme seçenekleri ve Editor ayarları


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Belge içeriğiyle bir akış döndürmesi gereken delege. NULL olmamalıdır. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate, belge yükleme seçeneklerini döndürmelidir. NULL olabilir ve null döndürebilir - bu durumda belge türü otomatik olarak algılanacak ve o tür için varsayılan yükleme seçenekleri uygulanacaktır. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


Belirtilen giriş belgesi (tam dosya yolu olarak) ile yeni bir Editor örneği başlatır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Dosyanın tam yolu. NULL olmamalıdır. Geçerli olmalı ve dosya mevcut olmalıdır. **Daha fazla bilgi** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


Belirtilen giriş belgesi (tam dosya yolu olarak) ve onun yükleme seçenekleri ile yeni bir Editor örneği başlatır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Dosyanın tam yolu. NULL olmamalıdır. Geçerli olmalı ve dosya mevcut olmalıdır. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegate, belge yükleme seçeneklerini döndürmelidir. NULL olabilir ve null döndürebilir - bu durumda belge türü otomatik olarak algılanacak ve o tür için varsayılan yükleme seçenekleri uygulanacaktır. **Daha fazla bilgi** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


Belirtilen format‑özel seçenekleri kullanarak daha önce yüklenmiş bir belgeyi düzenleme için açar; '' sınıfının bir örneğini oluşturur ve döndürür, bu örnek de HTML işaretlemesi ve ilgili kaynakları üretmek için yöntemler içerir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | Biçime özgü belge seçenekleri, dönüşüm sürecini ayarlamaya olanak tanır. NULL olmamalıdır. Daha önce uygulanmış yükleme seçenekleriyle çakışmamalıdır. |


*** ** * ** ***

Girdi orijinal belge, yapıcı aracılığıyla 'Editor' örneğine yüklendiğinde, bu yöntem belgeyi ara formata dönüştürerek düzenleme için açmaya olanak tanır; bu ara format 'EditableDocument' sınıfının bir örneği içinde kapsüllenmiştir. Bu yöntemden döndürülen 'EditableDocument', HTML işaretlemesi ve ilgili kaynakları (görseller, yazı tipleri ve stil sayfaları gibi) üretmek için gerekli tüm yöntem ve özellikleri içerir ve bunların herhangi bir WYSIWYG HTML-editöre aktarılması için gerekli tüm yapılandırmalara sahiptir. Bu aşırı yükleme, aile biçimleri için özel olan düzenleme seçeneklerini alır.

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


Varsayılan seçenekleri kullanarak daha önce yüklenmiş bir belgeyi düzenleme için açar
'EditableDocument' sınıfının bir örneğini oluşturup döndürür, bu
sırasıyla, HTML işaretlemesi ve ilgili
kaynakları.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

Girdi orijinal belge, yapıcı aracılığıyla 'Editor' örneğine yüklendiğinde, bu yöntem belgeyi ara formata dönüştürerek düzenleme için açmaya olanak tanır; bu ara format 'EditableDocument' sınıfının bir örneği içinde kapsüllenmiştir. Bu yöntemden döndürülen 'EditableDocument', HTML işaretlemesi ve ilgili kaynakları (görseller, yazı tipleri ve stil sayfaları gibi) üretmek için gerekli tüm yöntem ve özellikleri içerir ve bunların herhangi bir WYSIWYG HTML-editöre aktarılması için gerekli tüm yapılandırmalara sahiptir. Bu aşırı yükleme, girdi belgenin ait olduğu biçim için varsayılan olan düzenleme seçeneklerini uygular.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


Belirtilen düzenlenmiş belgeyi, örnek olarak temsil edilen
'EditableDocument', belirtilen formatta ortaya çıkan belgeye ve
içeriğini belirtilen akışa kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | WYSIWYG HTML-editörde düzenlenen ve 'EditableDocument' sınıfının bir örneği olarak saklanan girdi belgesinin sürümü, belirli bir biçimin çıktı belgesine dönüştürülmelidir. |
|
|  | outputDocument | java.io.OutputStream | Sonuç belgenin içeriğinin kaydedileceği çıktı akışı. NULL olmamalı, iptal edilmiş olmamalı ve yazmayı desteklemelidir. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Sonuç belgenin biçimini tanımlayan ve ayrıca genel ve biçime özgü kaydetme seçeneklerini içeren belge kaydetme seçenekleri. **Daha fazla bilgi** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


Belirtilen düzenlenmiş belgeyi, '' örneği olarak temsil edilen, belirtilen formatta ortaya çıkan belgeye dönüştürür ve içeriğini belirtilen dosya yolu ile dosyaya kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | WYSIWYG HTML-editörde düzenlenen ve '' sınıfının bir örneği olarak saklanan girdi belgesinin sürümü, belirli bir biçimin çıktı belgesine dönüştürülmelidir. null veya iptal edilmiş olmamalıdır. |
|
|  | filePath | java.lang.String | Çıktı belgenin kaydedileceği dosyanın yolu. Aynı ada sahip bir dosya varsa, tamamen yeniden yazılacaktır. Yol dizesi null, boş veya yalnızca boşluk karakteri içermemelidir. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Sonuç belgenin biçimini tanımlayan ve ayrıca genel ve biçime özgü kaydetme seçeneklerini içeren belge kaydetme seçenekleri. Null olmamalıdır. **Daha fazla bilgi** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


Belirtilen düzenlenmiş belgeyi ([EditableDocument](../../com.groupdocs.editor/editabledocument) tarafından temsil edilen) dosya uzantısından belirlenen bir çıktı belgesine dönüştürür ve belirtilen dosya yoluna kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | WYSIWYG HTML editöründe düzenlenen ve bir [EditableDocument](../../com.groupdocs.editor/editabledocument) örneği olarak saklanan girdi belgesinin sürümü. Null veya iptal edilmiş olmamalıdır. |
|
|  | filePath | java.lang.String | Çıktı belgenin kaydedileceği dosyanın yolu. Aynı ada sahip bir dosya varsa, tamamen üzerine yazılacaktır. Yol dizesi null, boş veya yalnızca boşluk karakteri içermemelidir. Varsayılan kaydetme seçenekleri ve çıktı biçimi bu dosya adından belirlendiği için, geçerli bir uzantıya sahip olmalıdır. |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


Değişiklikten sonra orijinal belgeyi dönüştürür (örneğin,
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
belirtilen formatta ortaya çıkan belgeye ve içeriğini sağlanan akışa kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Çıktı belgenin kaydedileceği akış. Bu akış yazılabilir olmalı ve belge içeriğinin başlangıcında konumlandırılmalıdır. Null olmamalıdır. |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | Sonuç belgenin biçimini tanımlayan ve ayrıca genel ve biçime özgü kaydetme seçeneklerini içeren belge kaydetme seçenekleri. Null olmamalıdır. |

<br />

*** ** * ** ***

Eğer outputDocument veya saveOptions null ise, bir NullPointerException fırlatılacaktır. Kaydedilecek belge eksikse, bir NullPointerException fırlatılacaktır.

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - Kaydedilen belge içeriğini içeren akış.

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


Mevcut belge içeriğini belirtilen çıktı akışına kaydedin.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Belge içeriğinin kaydedileceği akış. Bu null olamaz. |

<br />

*** ** * ** ***

Bu yöntem, iç belge temsilinden içeriği sağlanan çıkış akışına kopyalar. Kaydetme işleminden sonra akışın orijinal konumu korunur.

<br />

|

**Returns:**
java.io.OutputStream - Kaydedilen belge içeriğine sahip akış.

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


Bu 'Editor' örneğine yüklenen belge hakkında meta verileri döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | parola | java.lang.String | Kullanıcı, belge şifreli ise belge için bir parola belirtebilir. NULL veya boş bir dize olabilir; bu, parolanın yokluğuna eşdeğerdir. Parola koruma özelliği olmayan belge formatları için bu argüman yoksayılacaktır. Belge şifreli ise ve bu parametrede parola belirtilmemişse, ancak bu örnek oluşturulurken yükleme seçeneklerinde daha önce belirtilmişse, o parola kullanılacaktır. **Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Editor örneğini serbest bırakır, böylece tüm iç
kaynakları serbest bırakır ve sonraki kullanım için kullanılamaz hâle gelir


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bu Editor örneğinin zaten serbest bırakılıp bırakılmadığını ve artık
kullanılamayacağını (true) ya da kullanılabilir olduğunu (false) gösterir


**Returns:**
boolean
