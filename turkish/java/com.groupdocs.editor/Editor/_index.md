---
title: "Editor"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Dönüştürme yöntemlerini kapsülleyen ana sınıf."
type: docs
weight: 11
url: /tr/java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

Dönüştürme yöntemlerini kapsülleyen ana sınıf.
Editor sınıfı, desteklenen tüm formatlarda belgeleri yükleme, düzenleme ve kaydetme yöntemleri sağlar. Bu sınıf atılabilir, bu nedenle bir 'using' yönergesi kullanın veya kaynaklarını 'Dispose()' yöntemiyle manuel olarak serbest bırakın. Belge yükleme, yapıcılar aracılığıyla gerçekleştirilir. Belge düzenleme - 'Edit' yöntemiyle, ve düzenleme sonrası ortaya çıkan belgeye kaydetme - 'Save' yöntemiyle yapılır.
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
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | [Editor](../../com.groupdocs.editor/editor) sınıfının yeni bir örneğini başlatır ve belirtilen format temelinde yeni boş bir belge oluşturur. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | Belirtilen giriş belgesi (akış olarak) ile yeni Editor örneğini başlatır. |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | Belirtilen giriş belgesi (olarak |
akış) ve onun yükleme seçenekleri ile Editor ayarları
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | Belirtilen giriş belgesi (tam dosya yolu olarak) ile yeni Editor örneğini başlatır |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | Belirtilen giriş belgesi (tam dosya yolu olarak) ve onun yükleme seçenekleri ile yeni Editor örneğini başlatır |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | Belirtilen format‑özel seçenekleri kullanarak daha önce yüklenmiş bir belgeyi düzenleme amacıyla açar; '' sınıfının bir örneğini oluşturur ve döndürür; bu sınıf ise HTML işaretlemesi ve ilişkili kaynakları üretme yöntemlerini içerir. |
|
|  | [edit()](#edit--) | Varsayılan seçenekleri kullanarak daha önce yüklenmiş bir belgeyi düzenleme amacıyla açar |
'EditableDocument' sınıfının bir örneğini oluşturup döndürerek,
sırasıyla HTML işaretlemesi ve ilişkili
kaynakları.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | Belirtilen düzenlenmiş belgeyi, örnek olarak temsil edilen |
'EditableDocument', belirtilen formatta ortaya çıkan belgeye dönüştürür ve
içeriğini belirtilen akışa kaydeder
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | Belirtilen düzenlenmiş belgeyi, '' örneği olarak temsil edilen, belirtilen formatta ortaya çıkan belgeye dönüştürür ve içeriğini belirtilen dosya yolu ile dosyaya kaydeder |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | Belirtilen düzenlenmiş belgeyi ([EditableDocument](../../com.groupdocs.editor/editabledocument) tarafından temsil edilen) dosya uzantısından belirlenen formata sahip bir çıktı belgesine dönüştürür ve belirtilen dosya yoluna kaydeder. |
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
|  | [dispose()](#dispose--) | Editor'ün bu örneğini serbest bırakır, böylece tüm dahili |
kaynakları serbest bırakır ve sonraki kullanım için kullanılamaz hale gelir.
|
|  | [isDisposed()](#isDisposed--) | Bu Editor örneğinin zaten serbest bırakılıp bırakılmadığını ve olamayacağını gösterir |
artık kullanılamaz (true) ya da kullanılabilir (false) olduğunu gösterir.
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


[Editor](../../com.groupdocs.editor/editor) sınıfının yeni bir örneğini başlatır ve belirtilen format temelinde yeni boş bir belge oluşturur.

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


Belirtilen giriş belgesi (akış olarak) ile yeni Editor örneğini başlatır.


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


Belirtilen giriş belgesi (olarak
akış) ve onun yükleme seçenekleri ile Editor ayarları


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Belge içeriğiyle bir akış döndürmesi gereken delege. NULL olmamalıdır. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Belge yükleme seçeneklerini döndürmesi gereken delege. NULL olabilir ve null döndürebilir - bu durumda belge türü otomatik olarak algılanır ve o tür için varsayılan yükleme seçenekleri uygulanır. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


Belirtilen giriş belgesi (tam dosya yolu olarak) ile yeni Editor örneğini başlatır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Dosyanın tam yolu. NULL olmamalıdır. Geçerli olmalı ve dosya mevcut olmalıdır. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


Belirtilen giriş belgesi (tam dosya yolu olarak) ve onun yükleme seçenekleri ile yeni Editor örneğini başlatır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Dosyanın tam yolu. NULL olmamalıdır. Geçerli olmalı ve dosya mevcut olmalıdır. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Belge yükleme seçeneklerini döndürmesi gereken delege. NULL olabilir ve null döndürebilir - bu durumda belge türü otomatik olarak algılanır ve o tür için varsayılan yükleme seçenekleri uygulanır. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


Belirtilen format‑özel seçenekleri kullanarak daha önce yüklenmiş bir belgeyi düzenleme amacıyla açar; '' sınıfının bir örneğini oluşturur ve döndürür; bu sınıf ise HTML işaretlemesi ve ilişkili kaynakları üretme yöntemlerini içerir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | Biçime özgü belge seçenekleri, dönüşüm sürecini ayarlamaya olanak tanır. NULL olmamalıdır. Daha önce uygulanmış yükleme seçenekleriyle çakışmamalıdır. |


*** ** * ** ***

Girdi orijinal belge, yapıcı aracılığıyla 'Editor' örneğine yüklendiğinde, bu yöntem belgeyi ara bir formata dönüştürerek düzenleme için açmaya olanak tanır; bu ara format 'EditableDocument' sınıfının bir örneği içinde kapsüllenmiştir. 'EditableDocument', bu yöntemden dönen, HTML işaretlemesi ve ilgili kaynakları (görseller, yazı tipleri ve stil sayfaları gibi) üretmek için gerekli tüm yöntem ve özellikleri içerir ve bu kaynaklar, herhangi bir WYSIWYG HTML-editöre aktarılmak üzere gerekli tüm yapılandırmalarda bulunur. Bu aşırı yükleme, aile formatları için özel olan düzenleme seçeneklerini alır.

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


Varsayılan seçenekleri kullanarak daha önce yüklenmiş bir belgeyi düzenleme amacıyla açar
'EditableDocument' sınıfının bir örneğini oluşturup döndürerek,
sırasıyla HTML işaretlemesi ve ilişkili
kaynakları.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

Girdi orijinal belge, yapıcı aracılığıyla 'Editor' örneğine yüklendiğinde, bu yöntem belgeyi ara bir formata dönüştürerek düzenleme için açmaya olanak tanır; bu ara format 'EditableDocument' sınıfının bir örneği içinde kapsüllenmiştir. 'EditableDocument', bu yöntemden dönen, HTML işaretlemesi ve ilgili kaynakları (görseller, yazı tipleri ve stil sayfaları gibi) üretmek için gerekli tüm yöntem ve özellikleri içerir ve bu kaynaklar, herhangi bir WYSIWYG HTML-editöre aktarılmak üzere gerekli tüm yapılandırmalarda bulunur. Bu aşırı yükleme, giriş belgesinin ait olduğu format için varsayılan olan düzenleme seçeneklerini uygular.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


Belirtilen düzenlenmiş belgeyi, örnek olarak temsil edilen
'EditableDocument', belirtilen formatta ortaya çıkan belgeye dönüştürür ve
içeriğini belirtilen akışa kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | WYSIWYG HTML editöründe düzenlenen ve 'EditableDocument' sınıfının bir örneği olarak depolanan giriş belgesinin sürümü, belirli bir formatta çıktı belgesine dönüştürülmelidir. |
|
|  | outputDocument | java.io.OutputStream | Sonuç belgesinin içeriğinin kaydedileceği çıktı akışı. NULL olmamalı, serbest bırakılmamış olmalı ve yazma desteklemelidir. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Sonuç belgesinin formatını tanımlayan ve ayrıca genel ve formata özgü kaydetme seçeneklerini içeren belge kaydetme seçenekleri. **Learn more** |

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
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | WYSIWYG HTML editöründe düzenlenen ve '' sınıfının bir örneği olarak depolanan giriş belgesinin sürümü, belirli bir formatta çıktı belgesine dönüştürülmelidir. Null veya serbest bırakılmış olmamalıdır. |
|
|  | filePath | java.lang.String | Çıktı belgesinin kaydedileceği dosyanın yolu. Aynı ada sahip bir dosya varsa, tamamen üzerine yazılacaktır. Yol içeren dize null, boş veya yalnızca boşluk karakteri içermemelidir. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Sonuç belgesinin formatını tanımlayan ve ayrıca genel ve formata özgü kaydetme seçeneklerini içeren belge kaydetme seçenekleri. Null olmamalıdır. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


Belirtilen düzenlenmiş belgeyi ([EditableDocument](../../com.groupdocs.editor/editabledocument) tarafından temsil edilen) dosya uzantısından belirlenen formata sahip bir çıktı belgesine dönüştürür ve belirtilen dosya yoluna kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Bir WYSIWYG HTML editöründe düzenlenen ve bir [EditableDocument](../../com.groupdocs.editor/editabledocument) örneği olarak depolanan giriş belgesinin sürümü. Null veya serbest bırakılmış olmamalıdır. |
|
|  | filePath | java.lang.String | Çıktı belgesinin kaydedileceği dosyanın yolu. Aynı ada sahip bir dosya varsa, tamamen üzerine yazılacaktır. Yol dizesi null, boş veya yalnızca boşluk içermemelidir. Varsayılan kaydetme seçenekleri ve çıktı formatı bu dosya adından belirlendiği için geçerli bir uzantıya sahip olmalıdır. |
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
|  | outputDocument | java.io.OutputStream | Çıktı belgesinin kaydedileceği akış. Bu akış yazılabilir olmalı ve belge içeriğinin başlangıcında konumlandırılmış olmalıdır. Null olmamalıdır. |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | Sonuç belgesinin formatını ve genel ve format‑özel kaydetme seçeneklerini tanımlayan belge kaydetme seçenekleri. Null olmamalıdır. |

<br />

*** ** * ** ***

Eğer  outputDocument  veya  saveOptions  null ise, bir NullPointerException fırlatılacaktır. Kaydedilecek belge eksikse, bir NullPointerException fırlatılacaktır.

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

Bu yöntem, iç belge temsilinden sağlanan çıktı akışına içeriği kopyalar. Kaydetme işleminden sonra akışın orijinal konumu korunur.

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
|  | parola | java.lang.String | Kullanıcı, belge bir parola ile şifrelenmişse belge için bir parola belirtebilir. NULL veya boş dize olabilir; bu, parola yokmuş gibi kabul edilir. Parola koruması özelliği olmayan belge formatları için bu argüman göz ardı edilir. Belge şifrelenmişse ve bu parametrede parola belirtilmemişse, ancak bu örnek oluşturulurken yükleme seçeneklerinde daha önce belirtilmişse, o parola kullanılacaktır. **Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Editor'ün bu örneğini serbest bırakır, böylece tüm dahili
kaynakları serbest bırakır ve sonraki kullanım için kullanılamaz hale gelir.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bu Editor örneğinin zaten serbest bırakılıp bırakılmadığını ve olamayacağını gösterir
artık kullanılamaz (true) ya da kullanılabilir (false) olduğunu gösterir.


**Returns:**
boolean
