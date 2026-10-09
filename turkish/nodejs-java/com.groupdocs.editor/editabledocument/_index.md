---
title: "EditableDocument"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Düzenleme öncesi ve sonrası içeriği içeren ara belge"
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.editor/editabledocument/
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

EditableDocument sınıfının bir örneği, Editor.edit() yöntemiyle üretilebilir veya kullanıcı tarafından statik fabrikalar kullanılarak oluşturulabilir. EditableDocument, belgeyi kendi kapalı formatında saklar; bu format, GroupDocs.Editor tarafından desteklenen tüm içe ve dışa aktarma formatlarıyla uyumludur (dönüştürülebilir). Belgenin herhangi bir WYSIWYG istemci tarafı editöründe (CKEditor veya TinyMCE gibi) düzenlenebilir olmasını sağlamak için EditableDocument, HTML işaretlemesi oluşturmak ve kullanıcı tarafından kabul edilebilecek kaynaklar üretmek için yöntemler sunar.

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
|  | [getFonts()](#getFonts--) | Harici yazı tipi kaynaklarını elde etmeye izin verir, bu HTML tarafından kullanılan |
belge
|
|  | [getCss()](#getCss--) | CSS kaynaklarının bir listesini döndürür |
|
|  | [getAudio()](#getAudio--) | Ses kaynaklarının bir listesini döndürür |
|
|  | [getAllResources()](#getAllResources--) | Mevcut tüm kaynakların bir listesini döndürür: tüm stil sayfaları, görüntüler |
HTML ve tüm stil sayfaları, yazı tipleri
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | Belirtilen metin kodlamasıyla bu içeriği belirtilen akışa yazarak HTML belgesinin tüm içeriğini bayt akışı olarak döndürür |
|
|  | [getBodyContent()](#getBodyContent--) | HTML belgesinin gövdesini döndürür (açılış ve kapanış arasında bulunan içerik |
BODY etiketleri olmadan) bir dize olarak.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | HTML belgesinin gövdesini döndürür (açılış ve kapanış arasında bulunan içerik |
BODY etiketleri olmadan) bir dize olarak, dış kaynaklara bağlantıların
belirtilen önek içermesi.
|
|  | [getContent()](#getContent--) | HTML belgesinin tüm içeriğini bir dize olarak döndürür. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | HTML belgesinin tüm içeriğini bir dize olarak döndürür, dış kaynaklara bağlantıların |
belirtilen önek içermesi durumunda.
|
|  | [getCssContent()](#getCssContent--) | Tüm dış stil sayfalarının içeriğini, bir dizi dize olarak döndürür, burada |
bir dize bir stil sayfasını temsil eder.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | Tüm dış stil sayfalarının içeriğini, bir dizi dize olarak döndürür, burada |
bir dize bir stil sayfasını temsil eder.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | Bu HTML belgesinin tüm içeriğini, ilgili tüm kaynaklarla birlikte döndürür, bir |
tek bir dize biçiminde, tüm kaynakların HTML içinde gömülü olduğu
işaretlemede base64 kodlu biçimde.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | Bu HTML belgesini belirtilen yoldaki dosyaya kaydeder, HTML işaretlemesi |
depolanacak ve kaynaklarla birlikte gelen klasöre.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | Bu HTML belgesini belirtilen yoldaki dosyaya kaydeder, HTML işaretlemesi |
depolanacak ve kaynaklarla birlikte gelen klasöre, bu
belirtilen yolda bulunur.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | Statik fabrika, EditableDocument örneğini şuradan oluşturur |
belirtilen HTML işaretlemesi ve karşılık gelen bağlı kaynakların bir kümesi
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | Statik fabrika, EditableDocument örneğini belirtilen bir HTML işaretlemesinden ve tam yol ile belirtilen klasörde bulunan kaynaklardan oluşturur |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | Statik fabrika, EditableDocument örneğini bir HTML'den oluşturur |
dosya, \*.html dosyasının kendisine ve bir klasöre giden yol ile belirtilir
bağlı kaynaklarla
|
|  | [dispose()](#dispose--) | Bu Editable belge örneğini serbest bırakır, içeriğini de serbest bırakarak |
metod ve özelliklerini çalışmaz hâle getirir
|
|  | [isDisposed()](#isDisposed--) | Bu Editable belgenin zaten serbest bırakılıp bırakılmadığını belirler (doğru) ya da |
yanlış (false)
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


Harici yazı tipi kaynaklarını elde etmeye izin verir, bu HTML tarafından kullanılan
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


Mevcut tüm kaynakların bir listesini döndürür: tüm stil sayfaları, görüntüler
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


Belirtilen metin kodlamasıyla bu içeriği belirtilen akışa yazarak HTML belgesinin tüm içeriğini bayt akışı olarak döndürür


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
java.io.OutputStream - Belirtilen depolamanın örneği

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


HTML belgesinin gövdesini döndürür (açılış ve kapanış arasında bulunan içerik
BODY etiketleri olmadan) bir dize olarak.


**Returns:**
java.lang.String - HTML belgesinin gövdesini içeren dize


*** ** * ** ***

WYSIWYG editörleri belgenin gövdesiyle çalışır ve HEAD bloğundaki meta bilgilerini doğru şekilde işleyemez. Bu yöntem bu tür durumlar için tasarlanmıştır. Bu aşırı yükleme dış kaynak istekleri için URI'ların ayarlanmasına izin vermez.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


HTML belgesinin gövdesini döndürür (açılış ve kapanış arasında bulunan içerik
BODY etiketleri olmadan) bir dize olarak, dış kaynaklara bağlantıların
belirtilen önek içermesi.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Bu parametre aracılığıyla, sonuç HTML dizesinde bulunacak IMG öğelerindeki tüm dış görüntülere eklenmek üzere bir önek belirtilebilir. NULL veya boş ise, önekler eklenmez. |


*** ** * ** ***

WYSIWYG editörleri belgenin gövdesiyle çalışır ve HEAD bloğundaki meta bilgilerini doğru şekilde işleyemez. Bu yöntem bu tür durumlar için tasarlanmıştır. Bu aşırı yükleme dış kaynak istekleri için URI'ların ayarlanmasına izin verir.

<br />

|

**Returns:**
java.lang.String - Dış görüntülere göre ayarlanmış bağlantılarla HTML belgesinin gövdesini içeren dize

### getContent() {#getContent--}
```
public String getContent()
```


HTML belgesinin tüm içeriğini bir dize olarak döndürür.


**Returns:**
java.lang.String - HTML belgesinin içeriğini içeren dize

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


HTML belgesinin tüm içeriğini bir dize olarak döndürür, dış kaynaklara bağlantıların
belirtilen önek içermesi durumunda.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Bu parametre aracılığıyla, sonuç HTML dizesinde bulunacak IMG öğelerindeki tüm dış görüntülere eklenmek üzere bir önek belirtilebilir. NULL veya boş ise, önekler eklenmez. |
|
|  | externalCssTemplate | java.lang.String | Bu parametre aracılığıyla, sonuç HTML dizesinde bulunacak LINK öğelerindeki tüm dış stil sayfalarına eklenmek üzere bir önek belirtilebilir. NULL veya boş ise, önekler eklenmez. |
|

**Returns:**
java.lang.String - Dış kaynaklara göre ayarlanmış bağlantılarla HTML belgesinin içeriğini içeren dize

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


Tüm dış stil sayfalarının içeriğini, bir dizi dize olarak döndürür, burada
bir dize bir stil sayfasını temsil eder. Eğer yoksa
bu belgenin CSS'i.


**Returns:**
java.util.List<java.lang.String> - Her bir dizenin bir CSS belgesinin içeriğini tuttuğu dize listesi

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


Tüm dış stil sayfalarının içeriğini, bir dizi dize olarak döndürür, burada
bir dize bir stil sayfasını temsil eder. Belirtilen önek uygulanacaktır
her sonuç stil sayfasındaki dış kaynağa olan her bağlantıya.
Bu belge için CSS yoksa boş liste döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | Bu parametre aracılığıyla, sonuç CSS dizelerinde bulunacak CSS bildirimlerindeki tüm dış görüntülere eklenmek üzere bir önek belirtilebilir. NULL veya boş ise, önekler eklenmez. |
|
|  | externalFontsPrefix | java.lang.String | Bu parametre kullanılarak bir önek belirtilebilir, bu önek tüm harici yazı tiplerine olan bağlantılara eklenecektir. |
|

**Returns:**
java.util.List<java.lang.String> - Her bir dizenin bir CSS belgesinin içeriğini tuttuğu dize listesi

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


Bu HTML belgesinin tüm içeriğini, ilgili tüm kaynaklarla birlikte döndürür, bir
tek bir dize biçiminde, tüm kaynakların HTML içinde gömülü olduğu
işaretlemede base64 kodlu biçimde.


**Returns:**
java.lang.String - String, hiçbir durumda NULL veya boş değildir.

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


Bu HTML belgesini belirtilen yoldaki dosyaya kaydeder, HTML işaretlemesi
depolanacak ve kaynaklarla birlikte gelen klasöre.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | HTML işaretlemesinin saklanacağı dosyanın tam yolu. Dosya mevcutsa oluşturulacak veya üzerine yazılacaktır. İlgili kaynak klasörü, HTML dosyasının bulunduğu aynı klasörde oluşturulacaktır. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


Bu HTML belgesini belirtilen yoldaki dosyaya kaydeder, HTML işaretlemesi
depolanacak ve kaynaklarla birlikte gelen klasöre, bu
belirtilen yolda bulunur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | HTML işaretlemesinin saklanacağı dosyanın tam yolu. NULL veya boş olamaz. Dosya mevcutsa oluşturulacak veya üzerine yazılacaktır. |
|
|  | resourcesFolderPath | java.lang.String | İlgili klasörün tam yolu, tüm ilgili kaynakların saklanacağı yer. NULL veya boş ise, klasör \\*.html dosyasının bulunduğu aynı dizinde otomatik olarak oluşturulacaktır. Belirtilmiş ve mevcut değilse, oluşturulacaktır. |
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


Statik fabrika, EditableDocument örneğini şuradan oluşturur
belirtilen HTML işaretlemesi ve karşılık gelen bağlı kaynakların bir kümesi


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, işlenmesi gereken ham HTML işaretlemesini içeren. NULL, boş veya geçersiz olamaz. |
|
|  | resources | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | newHtmlContent parametresinde belirtilen HTML belgesinde kullanılan tüm kaynakların (görseller, stil sayfaları, yazı tipleri) koleksiyonu. Yok olabilir (NULL veya boş koleksiyon). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


Statik fabrika, EditableDocument örneğini belirtilen bir HTML işaretlemesinden ve tam yol ile belirtilen klasörde bulunan kaynaklardan oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, işlenmesi gereken ham HTML işaretlemesini içeren. NULL, boş veya geçersiz olamaz. |
|
|  | resourceFolderPath | java.lang.String | Kaynakların bulunduğu klasörün zorunlu yolu. Bu klasörde bulunan tüm stil sayfaları kullanılacaktır. NULL veya boş dize olamaz ve bu klasör mevcut olmalıdır. |

<br />

*** ** * ** ***

Bu statik fabrika, HTML belgesinin içeriği bir dize olarak sunulduğunda, ancak tüm kaynakların bir klasörde bulunduğu ve genellikle HTML işaretlemesindeki bu kaynaklara olan bağlantıların geçersiz veya eksik olduğu durumlarda yararlıdır. Bu yöntem çağrıldığında, belirtilen klasörü tarar ve bulunan tüm stil sayfalarını belgeye otomatik olarak uygular. Bu yöntem, genellikle belge meta verilerini ve benzerlerini kesen farklı HTML editörlerinden içerik alırken çok faydalıdır.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


Statik fabrika, EditableDocument örneğini bir HTML'den oluşturur
dosya, \*.html dosyasının kendisine ve bir klasöre giden yol ile belirtilir
bağlı kaynaklarla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | String, HTML dosyasının tam yolunu içeren. Null olamaz, geçerli bir dosya yolu olmalı ve dosya kendisi mevcut olmalıdır. |
|
|  | resourceFolderPath | java.lang.String | HTML kaynaklarının bulunduğu klasörün isteğe bağlı yolu. NULL, geçersiz veya böyle bir klasör mevcut değilse, Editor HTML işaretlemesini analiz ederek bu klasörü kendisi bulmaya çalışacaktır. |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


Bu Editable belge örneğini serbest bırakır, içeriğini de serbest bırakarak
metod ve özelliklerini çalışmaz hâle getirir


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bu Editable belgenin zaten serbest bırakılıp bırakılmadığını belirler (doğru) ya da
yanlış (false)


**Returns:**
boolean
