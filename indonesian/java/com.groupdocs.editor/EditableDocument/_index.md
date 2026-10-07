---
title: "EditableDocument"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Dokumen antara yang berisi konten sebelum dan sesudah penyuntingan"
type: docs
weight: 10
url: /id/java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

Dokumen menengah, yang berisi konten sebelum dan sesudah penyuntingan


*** ** * ** ***

Instansi kelas EditableDocument dapat dihasilkan oleh metode Editor.edit() atau dibuat oleh pengguna sendiri menggunakan pabrik statis. EditableDocument secara internal menyimpan dokumen dalam format tertutupnya sendiri, yang kompatibel (dapat dikonversi) dengan semua format impor dan ekspor yang didukung oleh GroupDocs.Editor. Untuk membuat dokumen dapat disunting di editor sisi klien WYSIWYG apa pun (seperti CKEditor atau TinyMCE), EditableDocument menyediakan metode untuk menghasilkan markup HTML dan menghasilkan sumber daya yang dapat diterima oleh pengguna.

<br />


## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Disposed](#Disposed) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getImages()](#getImages--) | Mengizinkan untuk memperoleh sumber daya gambar eksternal (gambar raster), yang digunakan |
oleh dokumen HTML ini
|
|  | [getFonts()](#getFonts--) | Mengizinkan untuk memperoleh sumber daya font eksternal, yang digunakan oleh HTML ini |
dokumen
|
|  | [getCss()](#getCss--) | Mengembalikan daftar sumber daya CSS |
|
|  | [getAudio()](#getAudio--) | Mengembalikan daftar sumber daya audio |
|
|  | [getAllResources()](#getAllResources--) | Mengembalikan daftar semua sumber daya yang ada: semua stylesheet, gambar dari |
HTML dan semua stylesheet, font
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | Mengembalikan konten keseluruhan dokumen HTML sebagai aliran byte dengan menulis konten ini ke aliran yang ditentukan dengan pengkodean teks yang ditentukan |
|
|  | [getBodyContent()](#getBodyContent--) | Mengembalikan isi badan dokumen HTML (konten antara pembukaan dan penutupan |
tag BODY tanpa tag tersebut) sebagai string.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | Mengembalikan isi badan dokumen HTML (konten antara pembukaan dan penutupan |
tag BODY tanpa tag tersebut) sebagai string, dimana tautan ke eksternal
sumber daya berisi awalan yang ditentukan.
|
|  | [getContent()](#getContent--) | Mengembalikan konten keseluruhan dokumen HTML sebagai string. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | Mengembalikan konten keseluruhan dokumen HTML sebagai string, dimana tautan ke |
sumber daya eksternal berisi awalan yang ditentukan.
|
|  | [getCssContent()](#getCssContent--) | Mengembalikan konten semua stylesheet eksternal sebagai daftar string, dimana |
satu string mewakili satu stylesheet.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | Mengembalikan konten semua stylesheet eksternal sebagai daftar string, dimana |
satu string mewakili satu stylesheet.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | Mengembalikan semua konten dokumen HTML ini dengan semua sumber daya terkait dalam sebuah |
bentuk string tunggal, dimana semua sumber daya disisipkan di dalam HTML
markup dalam bentuk yang dienkode base64.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | Menyimpan dokumen HTML ini ke file pada jalur yang ditentukan, dimana markup HTML |
akan disimpan, dan ke folder pendamping dengan sumber daya.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | Menyimpan dokumen HTML ini ke file pada jalur yang ditentukan, dimana markup HTML |
akan disimpan, dan ke folder pendamping dengan sumber daya, yang merupakan
terletak pada jalur yang ditentukan.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | Fabrik statis, yang membuat sebuah instance dari EditableDocument dari |
markup HTML yang ditentukan dan satu set sumber daya terkait yang terhubung
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | Fabrik statis, yang membuat sebuah instance dari EditableDocument dari markup HTML yang ditentukan dan dari sumber daya, yang terletak di folder, yang ditentukan oleh jalur lengkap |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | Fabrik statis, yang membuat sebuah instance dari EditableDocument dari sebuah HTML |
file, yang ditentukan oleh jalur ke file \*.html itu sendiri dan sebuah folder
dengan sumber daya yang terhubung
|
|  | [dispose()](#dispose--) | Membuang instance dokumen Editable ini, membuang kontennya dan |
menjadikan metode dan propertinya tidak berfungsi
|
|  | [isDisposed()](#isDisposed--) | Menentukan apakah dokumen Editable ini sudah dibuang (true) atau |
tidak (false)
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


Mengizinkan untuk memperoleh sumber daya gambar eksternal (gambar raster), yang digunakan
oleh dokumen HTML ini


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


Mengizinkan untuk memperoleh sumber daya font eksternal, yang digunakan oleh HTML ini
dokumen


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


Mengembalikan daftar sumber daya CSS


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


Mengembalikan daftar sumber daya audio


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


Mengembalikan daftar semua sumber daya yang ada: semua stylesheet, gambar dari
HTML dan semua stylesheet, font


*** ** * ** ***

Properti ini mengembalikan hasil gabungan dari properti 'Images', 'Fonts', dan 'Css'

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


Mengembalikan konten keseluruhan dokumen HTML sebagai aliran byte dengan menulis konten ini ke aliran yang ditentukan dengan pengkodean teks yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | penyimpanan | java.io.OutputStream | Aliran byte non-null, yang mendukung penulisan |
|
|  | enkoding | java.nio.charset.Charset | Enkoding teks non-null, yang harus diterapkan saat menulis konten teks ke penyimpanan yang ditentukan |


TStream
: Implementasi apa pun dari java.io.InputStream
|

**Returns:**
java.io.OutputStream - Instance dari penyimpanan yang ditentukan

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


Mengembalikan isi badan dokumen HTML (konten antara pembukaan dan penutupan
tag BODY tanpa tag tersebut) sebagai string.


**Returns:**
java.lang.String - String, yang berisi isi dokumen HTML


*** ** * ** ***

Editor WYSIWYG beroperasi dengan isi dokumen dan tidak dapat memproses informasi meta-nya dengan benar dari blok HEAD. Metode ini dirancang untuk kasus semacam itu. Overload ini tidak memungkinkan penyesuaian URI untuk permintaan sumber daya eksternal.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


Mengembalikan isi badan dokumen HTML (konten antara pembukaan dan penutupan
tag BODY tanpa tag tersebut) sebagai string, dimana tautan ke eksternal
sumber daya berisi awalan yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Melalui parameter ini dapat ditentukan sebuah awalan, yang akan ditambahkan ke tautan semua gambar eksternal dalam elemen IMG, yang akan muncul dalam string HTML hasil. Jika NULL atau kosong, awalan tidak akan ditambahkan. |


*** ** * ** ***

Editor WYSIWYG beroperasi dengan isi dokumen dan tidak dapat memproses informasi meta dari blok HEAD dengan benar. Metode ini dirancang untuk kasus seperti itu. Overload ini memungkinkan penyesuaian URI untuk permintaan sumber daya eksternal.

<br />

|

**Returns:**
java.lang.String - String, yang berisi isi dokumen HTML dengan tautan, disesuaikan dengan gambar eksternal

### getContent() {#getContent--}
```
public String getContent()
```


Mengembalikan konten keseluruhan dokumen HTML sebagai string.


**Returns:**
java.lang.String - String, yang berisi konten dokumen HTML

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


Mengembalikan konten keseluruhan dokumen HTML sebagai string, dimana tautan ke
sumber daya eksternal berisi awalan yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | Melalui parameter ini dapat ditentukan sebuah awalan, yang akan ditambahkan ke tautan semua gambar eksternal dalam elemen IMG, yang akan muncul dalam string HTML hasil. Jika NULL atau kosong, awalan tidak akan ditambahkan. |
|
|  | externalCssTemplate | java.lang.String | Melalui parameter ini dapat menentukan awalan, yang akan ditambahkan ke tautan semua stylesheet eksternal dalam elemen LINK, yang akan muncul dalam string HTML yang dihasilkan. Jika NULL atau kosong, awalan tidak akan ditambahkan. |
|

**Returns:**
java.lang.String - String, yang berisi konten dokumen HTML dengan tautan, disesuaikan dengan sumber daya eksternal

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


Mengembalikan konten semua stylesheet eksternal sebagai daftar string, dimana
satu string mewakili satu stylesheet. Mengembalikan daftar kosong, jika tidak ada
CSS untuk dokumen ini.


**Returns:**
java.util.List<java.lang.String> - Daftar string, di mana setiap string berisi konten satu dokumen CSS

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


Mengembalikan konten semua stylesheet eksternal sebagai daftar string, dimana
satu string mewakili satu stylesheet. Awalan yang ditentukan akan diterapkan pada
setiap tautan ke sumber daya eksternal dalam setiap stylesheet yang dihasilkan.
Mengembalikan daftar kosong, jika tidak ada CSS untuk dokumen ini.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | Melalui parameter ini dapat menentukan awalan, yang akan ditambahkan ke tautan semua gambar eksternal, yang akan muncul dalam deklarasi CSS pada string CSS yang dihasilkan. Jika NULL atau kosong, awalan tidak akan ditambahkan. |
|
|  | externalFontsPrefix | java.lang.String | Melalui parameter ini dapat menentukan awalan, yang akan ditambahkan ke tautan semua font eksternal dalam |
|

**Returns:**
java.util.List<java.lang.String> - Daftar string, di mana setiap string berisi konten satu dokumen CSS

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


Mengembalikan semua konten dokumen HTML ini dengan semua sumber daya terkait dalam sebuah
bentuk string tunggal, dimana semua sumber daya disisipkan di dalam HTML
markup dalam bentuk yang dienkode base64.


**Returns:**
java.lang.String - String, yang tidak NULL atau kosong dalam kondisi apa pun

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


Menyimpan dokumen HTML ini ke file pada jalur yang ditentukan, dimana markup HTML
akan disimpan, dan ke folder pendamping dengan sumber daya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Jalur lengkap ke file, tempat markup HTML akan disimpan. File akan dibuat atau ditimpa, jika sudah ada. Folder sumber daya pendamping akan dibuat di folder yang sama, tempat file HTML berada. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


Menyimpan dokumen HTML ini ke file pada jalur yang ditentukan, dimana markup HTML
akan disimpan, dan ke folder pendamping dengan sumber daya, yang merupakan
terletak pada jalur yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | Jalur lengkap ke file, tempat markup HTML akan disimpan. Tidak boleh NULL atau kosong. File akan dibuat atau ditimpa, jika sudah ada. |
|
|  | resourcesFolderPath | java.lang.String | Jalur lengkap ke folder pendamping, tempat semua sumber daya terkait akan disimpan. Jika NULL atau kosong, folder akan dibuat secara otomatis di direktori yang sama, tempat file \\*.html. Jika ditentukan dan tidak ada, akan dibuat. |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


Fabrik statis, yang membuat sebuah instance dari EditableDocument dari
markup HTML yang ditentukan dan satu set sumber daya terkait yang terhubung


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, yang berisi markup HTML mentah, yang harus diparsing. Tidak boleh NULL, kosong, atau tidak valid. |
|
|  | sumber daya | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | Koleksi semua sumber daya (gambar, stylesheet, font), yang digunakan dalam dokumen HTML, yang ditentukan dalam parameter newHtmlContent. Mungkin tidak ada (NULL atau koleksi kosong). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


Fabrik statis, yang membuat sebuah instance dari EditableDocument dari markup HTML yang ditentukan dan dari sumber daya, yang terletak di folder, yang ditentukan oleh jalur lengkap


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, yang berisi markup HTML mentah, yang harus diparsing. Tidak boleh NULL, kosong, atau tidak valid. |
|
|  | resourceFolderPath | java.lang.String | Jalur wajib ke folder dengan sumber daya. Semua stylesheet yang berada di folder ini akan digunakan. Tidak boleh NULL atau string kosong, dan folder ini harus ada. |

<br />

*** ** * ** ***

Fabrik statis ini berguna ketika konten dokumen HTML disajikan sebagai string, tetapi semua sumber daya berada di suatu folder, dan seringkali tautan ke sumber daya ini dalam markup HTML tidak valid dan tidak ada. Saat memanggil metode ini, ia memindai folder yang ditentukan dan secara otomatis menerapkan semua stylesheet yang ditemukan ke dokumen. Metode ini sangat berguna saat memperoleh konten dari berbagai editor HTML, yang biasanya memotong metadata dokumen dan sebagainya.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


Fabrik statis, yang membuat sebuah instance dari EditableDocument dari sebuah HTML
file, yang ditentukan oleh jalur ke file \*.html itu sendiri dan sebuah folder
dengan sumber daya yang terhubung


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | String, yang berisi jalur lengkap ke file HTML. Tidak boleh null, harus berupa jalur file yang valid, dan file itu sendiri harus ada. |
|
|  | resourceFolderPath | java.lang.String | Jalur opsional ke folder dengan sumber daya HTML. Jika NULL, tidak valid, atau folder tersebut tidak ada, Editor akan mencoba menemukan folder ini sendiri dengan menganalisis markup HTML |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


Membuang instance dokumen Editable ini, membuang kontennya dan
menjadikan metode dan propertinya tidak berfungsi


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Menentukan apakah dokumen Editable ini sudah dibuang (true) atau
tidak (false)


**Returns:**
boolean
