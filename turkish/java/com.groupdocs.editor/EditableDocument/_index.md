---
title: "EditableDocument"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Düzenleme öncesi ve sonrası içeriği içeren ara belge"
type: docs
weight: 10
url: /tr/java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

Düzenlemeden önce ve sonra içeriği içeren ara belge


*** ** * ** ***

EditableDocument sınıfının bir örneği, Editor.edit() yöntemiyle üretilebilir veya kullanıcı tarafından statik fabrikalar kullanılarak oluşturulabilir. EditableDocument, belgeyi kendi kapalı formatında depolar; bu format, GroupDocs.Editor tarafından desteklenen tüm içe ve dışa aktarma formatlarıyla uyumludur (dönüştürülebilir). Belgeyi herhangi bir WYSIWYG istemci tarafı editöründe (CKEditor veya TinyMCE gibi) düzenlenebilir hâle getirmek için EditableDocument, HTML işaretlemesi oluşturma ve kullanıcı tarafından kabul edilebilecek kaynakları üretme yöntemleri sağlar.

<br />


## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Disposed](#Disposed) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getImages()](#getImages--) | Harici görüntü kaynaklarını (raster görüntüler) elde etmeye izin verir, kullanılan |
bu HTML belgesi tarafından
|
|  | [getFonts()](#getFonts--) | Bu HTML tarafından kullanılan harici yazı tipi kaynaklarını elde etmeye izin verir |
belge
|
|  | [getCss()](#getCss--) | CSS kaynaklarının bir listesini döndürür |
|
|  | [getAudio()](#getAudio--) | Ses kaynaklarının bir listesini döndürür |
|
|  | [getAllResources()](#getAllResources--) | Mevcut tüm kaynakların bir listesini döndürür: tüm stil sayfaları, görüntülerden |
HTML ve tüm stil sayfaları, yazı tipleri
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | Belirtilen metin kodlamasıyla belirtilen akıma bu içeriği yazarak HTML belgesinin genel içeriğini bayt akışı olarak döndürür |
|
|  | [getBodyContent()](#getBodyContent--) | HTML belgesinin gövdesini (açılış ve kapanış arasında kalan içerik |
BODY etiketleri bu etiketler olmadan) bir dize olarak.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | HTML belgesinin gövdesini (açılış ve kapanış arasında kalan içerik |
BODY etiketleri bu etiketler olmadan) bir dize olarak, dışa bağlantıların
kaynakların belirtilen önekini içerdiği.
|
|  | [getContent()](#getContent--) | HTML belgesinin genel içeriğini bir dize olarak döndürür. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | HTML belgesinin genel içeriğini bir dize olarak döndürür, bağlantıların |
dış kaynakların belirtilen önekini içerdiği.
|
|  | [getCssContent()](#getCssContent--) | Tüm dış stil sayfalarının içeriğini bir dize listesi olarak döndürür, burada |
her bir dize bir stil sayfasını temsil eder.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | Tüm dış stil sayfalarının içeriğini bir dize listesi olarak döndürür, burada |
her bir dize bir stil sayfasını temsil eder.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | Bu HTML belgesinin tüm içeriğini ve ilgili tüm kaynakları bir |
tek bir dize biçiminde döndürür, tüm kaynakların HTML içinde gömülü olduğu
işaretlemede base64 kodlu biçimde.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | Bu HTML belgesini belirtilen yoldaki dosyaya kaydeder, HTML işaretlemesi |
saklanacak ve kaynaklarla birlikte gelen klasöre.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | Bu HTML belgesini belirtilen yoldaki dosyaya kaydeder, HTML işaretlemesi |
saklanacak ve kaynaklarla birlikte gelen klasöre, bu
belirtilen yolda konumlanmıştır.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | EditableDocument'tan bir örnek oluşturan statik fabrika, |
belirtilen HTML işaretlemesi ve ilgili bağlantılı kaynakların bir kümesi
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | Belirtilen HTML işaretlemesinden ve tam yol ile belirtilen klasörde bulunan kaynaklardan bir EditableDocument örneği oluşturan statik fabrika |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | Bir HTML'den EditableDocument örneği oluşturan statik fabrika |
dosya, \*.html dosyasının kendisine ve bir klasöre giden yol ile belirtilen
bağlantılı kaynaklarla
|
|  | [dispose()](#dispose--) | Bu Editable belge örneğini, içeriğini de serbest bırakarak imha eder ve |
yöntemlerini ve özelliklerini çalışmaz hâle getirir
|
|  | [isDisposed()](#isDisposed--) | Bu Editable belgenin zaten imha edilip edilmediğini (true) belirler veya |
değil (false)
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


Harici görüntü kaynaklarını (raster görüntüler) elde etmeye izin verir, kullanılan
bu HTML belgesi tarafından


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


Bu HTML tarafından kullanılan harici yazı tipi kaynaklarını elde etmeye izin verir
belge


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


CSS kaynaklarının bir listesini döndürür


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


Ses kaynaklarının bir listesini döndürür


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


Mevcut tüm kaynakların bir listesini döndürür: tüm stil sayfaları, görüntülerden
HTML ve tüm stil sayfaları, yazı tipleri


*** ** * ** ***

Bu özellik, 'Images', 'Fonts' ve 'Css' özelliklerinin birleştirilmiş sonucunu döndürür

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


Belirtilen metin kodlamasıyla belirtilen akıma bu içeriği yazarak HTML belgesinin genel içeriğini bayt akışı olarak döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | depolama | java.io.OutputStream | Yazmayı destekleyen null olmayan bayt akışı |
|
|  | kodlama | java.nio.charset.Charset | Belirtilen depolamaya metin içeriği yazılırken uygulanması gereken null olmayan metin kodlaması |


TStream
: java.io.InputStream'in herhangi bir uygulaması
|

**Returns:**
java.io.OutputStream - belirtilen depolamanın örneği

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


HTML belgesinin gövdesini (açılış ve kapanış arasında kalan içerik
BODY etiketleri bu etiketler olmadan) bir dize olarak.


**Returns:**
java.lang.String - HTML belgesinin gövdesini içeren dize


*** ** * ** ***

WYSIWYG editörleri belge gövdesiyle çalışır ve HEAD bloğundaki meta bilgilerini doğru şekilde işleyemez. Bu yöntem bu tür durumlar için tasarlanmıştır. Bu aşırı yükleme, dış kaynak istekleri için URI'leri ayarlamaya izin vermez.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


HTML belgesinin gövdesini (açılış ve kapanış arasında kalan içerik
BODY etiketleri bu etiketler olmadan) bir dize olarak, dışa bağlantıların
kaynakların belirtilen önekini içerdiği.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Bu parametre aracılığıyla, sonuç HTML dizesinde bulunacak IMG öğelerindeki tüm dış görüntülere eklenmek üzere bir önek belirtebilirsiniz. NULL veya boş ise, önekler eklenmez. |


*** ** * ** ***

WYSIWYG editörleri belgenin gövdesiyle çalışır ve HEAD bloğundaki meta bilgilerini doğru şekilde işleyemez. Bu yöntem bu tür durumlar için tasarlanmıştır. Bu aşırı yükleme, harici kaynak istekleri için URI'leri ayarlamaya olanak tanır.

<br />

|

**Returns:**
java.lang.String - String, HTML belgesinin gövdesini (bağlantılarla) harici görüntülere göre ayarlanmış şekilde içerir

### getContent() {#getContent--}
```
public String getContent()
```


HTML belgesinin genel içeriğini bir dize olarak döndürür.


**Returns:**
java.lang.String - String, HTML belgesinin içeriğini tutar

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


HTML belgesinin genel içeriğini bir dize olarak döndürür, bağlantıların
dış kaynakların belirtilen önekini içerdiği.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Bu parametre aracılığıyla, sonuç HTML dizesinde bulunacak IMG öğelerindeki tüm dış görüntülere eklenmek üzere bir önek belirtebilirsiniz. NULL veya boş ise, önekler eklenmez. |
|
|  | externalCssTemplate | java.lang.String | Bu parametre aracılığıyla, sonuç HTML dizesinde bulunacak LINK öğelerindeki tüm harici stil sayfalarına olan bağlantılara eklenecek bir önek belirtebilirsiniz. NULL veya boş ise, önekler eklenmez. |
|

**Returns:**
java.lang.String - String, bağlantılar içeren HTML belgesinin içeriğini, harici kaynaklara göre ayarlanmış şekilde tutar

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


Tüm dış stil sayfalarının içeriğini bir dize listesi olarak döndürür, burada
bir dize bir stil sayfasını temsil eder. Eğer yoksa boş liste döndürür,
bu belge için CSS.


**Returns:**
java.util.List<java.lang.String> - Her bir dize bir CSS belgesinin içeriğini tutan dize listesi

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


Tüm dış stil sayfalarının içeriğini bir dize listesi olarak döndürür, burada
bir dize bir stil sayfasını temsil eder. Belirtilen önek uygulanacak
her sonuç stil sayfasındaki harici kaynağa olan her bağlantıya.
Bu belge için CSS yoksa boş liste döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | Bu parametre aracılığıyla, sonuç CSS dizelerinde yer alacak CSS bildirimlerindeki tüm harici görüntülere olan bağlantılara eklenecek bir önek belirtebilirsiniz. NULL veya boş ise, önekler eklenmez. |
|
|  | externalFontsPrefix | java.lang.String | Bu parametre aracılığıyla, tüm harici yazı tiplerine olan bağlantılara eklenecek bir önek belirtebilirsiniz |
|

**Returns:**
java.util.List<java.lang.String> - Her bir dize bir CSS belgesinin içeriğini tutan dize listesi

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


Bu HTML belgesinin tüm içeriğini ve ilgili tüm kaynakları bir
tek bir dize biçiminde döndürür, tüm kaynakların HTML içinde gömülü olduğu
işaretlemede base64 kodlu biçimde.


**Returns:**
java.lang.String - String, her durumda NULL veya boş olmayan

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


Bu HTML belgesini belirtilen yoldaki dosyaya kaydeder, HTML işaretlemesi
saklanacak ve kaynaklarla birlikte gelen klasöre.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | HTML işaretlemesinin saklanacağı dosyanın tam yolu. Dosya mevcutsa oluşturulacak veya üzerine yazılacak. İlgili kaynak klasörü, HTML dosyasının bulunduğu aynı klasörde oluşturulacak. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


Bu HTML belgesini belirtilen yoldaki dosyaya kaydeder, HTML işaretlemesi
saklanacak ve kaynaklarla birlikte gelen klasöre, bu
belirtilen yolda konumlanmıştır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | HTML işaretlemesinin saklanacağı dosyanın tam yolu. NULL veya boş olamaz. Dosya mevcutsa oluşturulacak veya üzerine yazılacak. |
|
|  | resourcesFolderPath | java.lang.String | Tüm ilgili kaynakların saklanacağı ek klasörün tam yolu. NULL veya boş ise, klasör \*.html dosyasının bulunduğu aynı dizinde otomatik olarak oluşturulur. Belirtilmiş ve mevcut değilse, oluşturulacaktır. |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


EditableDocument'tan bir örnek oluşturan statik fabrika,
belirtilen HTML işaretlemesi ve ilgili bağlantılı kaynakların bir kümesi


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | İşlenmesi gereken ham HTML işaretlemesi içeren dize. NULL, boş veya geçersiz olamaz. |
|
|  | kaynaklar | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | HTML belgesinde kullanılan tüm kaynakların (görseller, stil sayfaları, yazı tipleri) koleksiyonu, newHtmlContent parametresinde belirtilir. Yok da olabilir (NULL veya boş koleksiyon). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


Belirtilen HTML işaretlemesinden ve tam yol ile belirtilen klasörde bulunan kaynaklardan bir EditableDocument örneği oluşturan statik fabrika


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | İşlenmesi gereken ham HTML işaretlemesi içeren dize. NULL, boş veya geçersiz olamaz. |
|
|  | resourceFolderPath | java.lang.String | Kaynakların bulunduğu klasöre zorunlu yol. Bu klasörde bulunan tüm stil sayfaları kullanılacaktır. NULL veya boş dize olamaz ve bu klasör mevcut olmalıdır. |

<br />

*** ** * ** ***

Bu statik fabrika, HTML belgesinin içeriği bir dize olarak sunulduğunda, ancak tüm kaynakların bir klasörde bulunduğu ve HTML işaretlemesindeki bu kaynaklara olan bağlantıların genellikle geçersiz ve eksik olduğu durumlarda faydalıdır. Bu yöntem çağrıldığında, belirtilen klasörü tarar ve bulunan tüm stil sayfalarını belgeye otomatik olarak uygular. Farklı HTML editörlerinden içerik alırken, genellikle belge meta verileri vb. kesildiği için bu yöntem çok yararlıdır.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


Bir HTML'den EditableDocument örneği oluşturan statik fabrika
dosya, \*.html dosyasının kendisine ve bir klasöre giden yol ile belirtilen
bağlantılı kaynaklarla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | HTML dosyasının tam yolunu içeren dize. NULL olamaz, geçerli bir dosya yolu olmalı ve dosya kendisi mevcut olmalıdır. |
|
|  | resourceFolderPath | java.lang.String | HTML kaynaklarının bulunduğu klasöre isteğe bağlı yol. NULL, geçersiz veya böyle bir klasör yoksa, Editor HTML işaretlemesini analiz ederek bu klasörü kendisi bulmaya çalışacaktır. |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


Bu Editable belge örneğini, içeriğini de serbest bırakarak imha eder ve
yöntemlerini ve özelliklerini çalışmaz hâle getirir


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bu Editable belgenin zaten imha edilip edilmediğini (true) belirler veya
değil (false)


**Returns:**
boolean
