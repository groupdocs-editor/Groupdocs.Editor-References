---
title: "Editor"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Kelas utama yang mengenkapsulasi metode konversi."
type: docs
weight: 11
url: /id/java/com.groupdocs.editor/editor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class Editor implements IAuxDisposable
```

Kelas utama, yang mengenkapsulasi metode konversi.
Kelas Editor menyediakan metode untuk memuat, mengedit, dan menyimpan dokumen dalam semua format yang didukung. Kelas ini dapat dibuang, jadi gunakan direktif 'using' atau buang sumber dayanya secara manual melalui pemanggilan metode 'Dispose()'. Memuat dokumen dilakukan melalui konstruktor. Pengeditan dokumen - melalui metode 'Edit', dan penyimpanan kembali ke dokumen hasil setelah pengeditan - melalui metode 'Save'.
**Editor class should be considered as an entry point and the root object of the GroupDocs.Editor. All operations are performed using this class. Typical usage of the Editor class for performing a full document editing pipeline is the next:**

* Load a document into the Editor instance through its constructor.
* Optionally, detect a document type using a method.
* Open a document for editing by calling an method and obtaining an instance of class from it..
* Editing a document content on client-side using any WYSIWYG HTML-editor.
* Creating a new instance of from edited document content.
* Saving an edited document to some output format by calling a method.
* Disposing an instance of Editor class via 'using' operator or manually.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [Editor(DocumentFormatBase format)](#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Menginisialisasi instance baru dari kelas [Editor](../../com.groupdocs.editor/editor) dan membuat dokumen kosong baru berdasarkan format yang ditentukan. |
|
|  | [Editor(InputStream document)](#Editor-java.io.InputStream-) | Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai aliran). |
|
|  | [Editor(InputStream document, ILoadOptions loadOptions)](#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-) | Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai a |
stream) dengan opsi pemuatan dan pengaturan Editor-nya
|
|  | [Editor(String filePath)](#Editor-java.lang.String-) | Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai jalur file lengkap). |
|
|  | [Editor(String filePath, ILoadOptions loadOptions)](#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-) | Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai jalur file lengkap) dengan opsi pemuatannya. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [edit(IEditOptions editOptions)](#edit-com.groupdocs.editor.options.IEditOptions-) | Membuka dokumen yang sebelumnya dimuat untuk diedit menggunakan opsi khusus format yang ditentukan dengan menghasilkan dan mengembalikan instance dari kelas '' , yang, pada gilirannya, berisi metode untuk menghasilkan markup HTML dan sumber daya terkait. |
|
|  | [edit()](#edit--) | Membuka dokumen yang sebelumnya dimuat untuk diedit menggunakan opsi default dengan |
menghasilkan dan mengembalikan instance dari kelas 'EditableDocument', yang,
pada gilirannya, berisi metode untuk menghasilkan markup HTML dan
sumber daya.
|
|  | [save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-) | Mengonversi dokumen yang diedit yang ditentukan, yang direpresentasikan sebagai instance dari |
'EditableDocument', ke dokumen hasil dengan format yang ditentukan dan
menyimpan isinya ke aliran yang ditentukan
|
|  | [save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-) | Mengonversi dokumen yang diedit yang ditentukan, yang direpresentasikan sebagai instance dari '', ke dokumen hasil dengan format yang ditentukan dan menyimpan isinya ke file melalui jalur file yang ditentukan |
|
|  | [save(EditableDocument inputDocument, String filePath)](#save-com.groupdocs.editor.EditableDocument-java.lang.String-) | Mengonversi dokumen yang diedit yang ditentukan (direpresentasikan oleh [EditableDocument](../../com.groupdocs.editor/editabledocument)) menjadi dokumen output yang formatnya ditentukan dari ekstensi nama file, dan menyimpannya ke jalur file yang ditentukan. |
|
|  | [save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)](#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-) | Mengonversi dokumen asli setelah modifikasi (misalnya, |
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
ke dokumen hasil dengan format yang ditentukan dan menyimpan isinya ke aliran yang disediakan.
|
|  | [save(OutputStream outputDocument)](#save-java.io.OutputStream-) | Simpan konten dokumen saat ini ke aliran output yang ditentukan. |
|
|  | [getDocumentInfo(String password)](#getDocumentInfo-java.lang.String-) | Mengembalikan metadata tentang dokumen yang dimuat ke instance 'Editor' ini |
|
|  | [dispose()](#dispose--) | Membuang instance Editor ini, sehingga melepaskan semua internal |
sumber daya dan menjadi tidak tersedia untuk penggunaan lebih lanjut
|
|  | [isDisposed()](#isDisposed--) | Menunjukkan apakah instance Editor ini sudah dibuang dan tidak dapat |
digunakan lagi (true) atau tidak dan aktif (false)
|
### Editor(DocumentFormatBase format) {#Editor-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public Editor(DocumentFormatBase format)
```


Menginisialisasi instance baru dari kelas [Editor](../../com.groupdocs.editor/editor) dan membuat dokumen kosong baru berdasarkan format yang ditentukan.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | format | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | menyatakan format file dokumen yang akan dibuat. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document) {#Editor-java.io.InputStream-}
```
public Editor(InputStream document)
```


Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai aliran).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Delegasi, yang harus mengembalikan aliran dengan konten dokumen. Tidak boleh NULL. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(InputStream document, ILoadOptions loadOptions) {#Editor-java.io.InputStream-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(InputStream document, ILoadOptions loadOptions)
```


Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai a
stream) dengan opsi pemuatan dan pengaturan Editor-nya


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Delegasi, yang harus mengembalikan aliran dengan konten dokumen. Tidak boleh NULL. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegasi, yang harus mengembalikan opsi pemuatan dokumen. Boleh NULL dan dapat mengembalikan null - dalam kasus tersebut tipe dokumen akan dideteksi secara otomatis dan opsi pemuatan default untuk tipe tersebut akan diterapkan. |
|

### Editor(String filePath) {#Editor-java.lang.String-}
```
public Editor(String filePath)
```


Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai jalur file lengkap).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur lengkap ke file. Tidak boleh NULL. Harus valid, dan file harus ada. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
|

### Editor(String filePath, ILoadOptions loadOptions) {#Editor-java.lang.String-com.groupdocs.editor.options.ILoadOptions-}
```
public Editor(String filePath, ILoadOptions loadOptions)
```


Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai jalur file lengkap) dengan opsi pemuatannya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur lengkap ke file. Tidak boleh NULL. Harus valid, dan file harus ada. |
|
|  | loadOptions | [ILoadOptions](../../com.groupdocs.editor.options/iloadoptions) | Delegasi, yang harus mengembalikan opsi pemuatan dokumen. Boleh NULL dan dapat mengembalikan null - dalam kasus tersebut tipe dokumen akan dideteksi secara otomatis dan opsi pemuatan default untuk tipe tersebut akan diterapkan. **Learn more** |

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/supported-document-formats/)
* More about GroupDocs.Editor for Java features: [Developer Guide](../https://docs.groupdocs.com/editor/java/developer-guide/)
* More about how to open and edit password-protected documents and document from different storages: [Load and edit documents using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/load-document/)
|

### edit(IEditOptions editOptions) {#edit-com.groupdocs.editor.options.IEditOptions-}
```
public final EditableDocument edit(IEditOptions editOptions)
```


Membuka dokumen yang sebelumnya dimuat untuk diedit menggunakan opsi khusus format yang ditentukan dengan menghasilkan dan mengembalikan instance dari kelas '' , yang, pada gilirannya, berisi metode untuk menghasilkan markup HTML dan sumber daya terkait.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | editOptions | [IEditOptions](../../com.groupdocs.editor.options/ieditoptions) | Opsional dokumen spesifik format, yang memungkinkan penyesuaian proses konversi. Tidak boleh NULL. Tidak boleh bertentangan dengan opsi pemuatan yang sebelumnya diterapkan. |


*** ** * ** ***

Ketika dokumen asli input dimuat ke instance 'Editor' melalui konstruktor, metode ini memungkinkan membuka dokumen untuk penyuntingan dengan mengonversinya ke format menengah, yang dibungkus dalam instance kelas 'EditableDocument'. 'EditableDocument' yang dikembalikan dari metode ini berisi semua metode dan properti yang diperlukan untuk menghasilkan markup HTML dan sumber daya terkait (seperti gambar, font, dan stylesheet) dalam semua konfigurasi yang diperlukan untuk selanjutnya memasukkannya ke dalam editor HTML WYSIWYG apa pun. Overload ini memperoleh opsi penyuntingan yang spesifik untuk format keluarga.

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


Membuka dokumen yang sebelumnya dimuat untuk diedit menggunakan opsi default dengan
menghasilkan dan mengembalikan instance dari kelas 'EditableDocument', yang,
pada gilirannya, berisi metode untuk menghasilkan markup HTML dan
sumber daya.


**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - Instance of the 'EditableDocument' class, which encapsulates overall input document with all its resources in intermediate format. This method, if successfully finished, never returns NULL.


*** ** * ** ***

Ketika dokumen asli input dimuat ke instance 'Editor' melalui konstruktor, metode ini memungkinkan membuka dokumen untuk penyuntingan dengan mengonversinya ke format menengah, yang dibungkus dalam instance kelas 'EditableDocument'. 'EditableDocument' yang dikembalikan dari metode ini berisi semua metode dan properti yang diperlukan untuk menghasilkan markup HTML dan sumber daya terkait (seperti gambar, font, dan stylesheet) dalam semua konfigurasi yang diperlukan untuk selanjutnya memasukkannya ke dalam editor HTML WYSIWYG apa pun. Overload ini menerapkan opsi penyuntingan yang merupakan default untuk format, tempat dokumen input berada.

<br />

**Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/edit-document/)

### save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.io.OutputStream-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, OutputStream outputDocument, ISaveOptions saveOptions)
```


Mengonversi dokumen yang diedit yang ditentukan, yang direpresentasikan sebagai instance dari
'EditableDocument', ke dokumen hasil dengan format yang ditentukan dan
menyimpan isinya ke aliran yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Versi dokumen input, yang diedit dalam editor HTML WYSIWYG dan disimpan sebagai instance kelas 'EditableDocument', yang harus dikonversi ke dokumen output dengan format tertentu |
|
|  | outputDocument | java.io.OutputStream | Aliran output, di mana konten dokumen hasil akan dicatat. Tidak boleh NULL, dibuang, harus mendukung penulisan. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Opsi penyimpanan dokumen, yang menentukan format dokumen hasil, serta opsi penyimpanan umum dan spesifik format. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-com.groupdocs.editor.options.ISaveOptions-}
```
public final void save(EditableDocument inputDocument, String filePath, ISaveOptions saveOptions)
```


Mengonversi dokumen yang diedit yang ditentukan, yang direpresentasikan sebagai instance dari '', ke dokumen hasil dengan format yang ditentukan dan menyimpan isinya ke file melalui jalur file yang ditentukan


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Versi dokumen input, yang diedit dalam editor HTML WYSIWYG dan disimpan sebagai instance kelas '' , yang harus dikonversi ke dokumen output dengan format tertentu. Tidak boleh null atau dibuang. |
|
|  | filePath | java.lang.String | Jalur ke file, di mana dokumen output akan disimpan. Jika file dengan nama yang sama ada, file tersebut akan sepenuhnya ditimpa. String jalur tidak boleh null, kosong, atau hanya berisi spasi. |
|
|  | saveOptions | [ISaveOptions](../../com.groupdocs.editor.options/isaveoptions) | Opsi penyimpanan dokumen, yang menentukan format dokumen hasil, serta opsi penyimpanan umum dan spesifik format. Tidak boleh null. **Learn more** |

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](../https://docs.groupdocs.com/display/editornet/Save+document)
|

### save(EditableDocument inputDocument, String filePath) {#save-com.groupdocs.editor.EditableDocument-java.lang.String-}
```
public final void save(EditableDocument inputDocument, String filePath)
```


Mengonversi dokumen yang diedit yang ditentukan (direpresentasikan oleh [EditableDocument](../../com.groupdocs.editor/editabledocument)) menjadi dokumen output yang formatnya ditentukan dari ekstensi nama file, dan menyimpannya ke jalur file yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | inputDocument | [EditableDocument](../../com.groupdocs.editor/editabledocument) | Versi dokumen input yang diedit dalam editor HTML WYSIWYG dan disimpan sebagai instance [EditableDocument](../../com.groupdocs.editor/editabledocument). Tidak boleh null atau dibuang. |
|
|  | filePath | java.lang.String | Jalur ke file tempat dokumen output akan disimpan. Jika ada file dengan nama yang sama, file tersebut akan sepenuhnya ditimpa. String jalur tidak boleh null, kosong, atau hanya berisi spasi. Karena opsi penyimpanan default dan format output ditentukan dari nama file ini, harus memiliki ekstensi yang valid. |
|

### save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions) {#save-java.io.OutputStream-com.groupdocs.editor.options.WordProcessingSaveOptions-}
```
public final OutputStream save(OutputStream outputDocument, WordProcessingSaveOptions saveOptions)
```


Mengonversi dokumen asli setelah modifikasi (misalnya,
FormFieldManager
(#getFormFieldManager.getFormFieldManager)),
ke dokumen hasil dengan format yang ditentukan dan menyimpan isinya ke aliran yang disediakan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Aliran ke mana dokumen output akan disimpan. Aliran ini harus dapat ditulis dan diposisikan pada awal konten dokumen. Tidak boleh null. |
|
|  | saveOptions | [WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) | Opsi penyimpanan dokumen yang menentukan format dokumen hasil, serta opsi penyimpanan umum dan spesifik format. Tidak boleh null. |

<br />

*** ** * ** ***

Jika  outputDocument  atau  saveOptions  bernilai null, NullPointerException akan dilemparkan. Jika dokumen yang akan disimpan tidak ada, NullPointerException akan dilemparkan.

<br />

<br />

*** ** * ** ***

 **Learn more:** 

* 

<br />

|

**Returns:**
java.io.OutputStream - Aliran yang berisi konten dokumen yang disimpan.

### save(OutputStream outputDocument) {#save-java.io.OutputStream-}
```
public final OutputStream save(OutputStream outputDocument)
```


Simpan konten dokumen saat ini ke aliran output yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | outputDocument | java.io.OutputStream | Aliran ke mana konten dokumen akan disimpan. Ini tidak boleh null. |

<br />

*** ** * ** ***

Metode ini menyalin konten dari representasi dokumen internal ke aliran output yang disediakan. Posisi asli aliran dipertahankan setelah operasi penyimpanan.

<br />

|

**Returns:**
java.io.OutputStream - Aliran dengan konten dokumen yang disimpan.

### getDocumentInfo(String password) {#getDocumentInfo-java.lang.String-}
```
public final IDocumentInfo getDocumentInfo(String password)
```


Mengembalikan metadata tentang dokumen yang dimuat ke instance 'Editor' ini


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | kata sandi | java.lang.String | Pengguna dapat menentukan kata sandi untuk sebuah dokumen, jika dokumen ini dienkripsi dengan kata sandi. Dapat berupa NULL atau string kosong, yang setara dengan tidak adanya kata sandi. Untuk format dokumen yang tidak memiliki fitur perlindungan kata sandi, argumen ini akan diabaikan. Jika dokumen dienkripsi, dan kata sandi tidak ditentukan dalam parameter ini, tetapi telah ditentukan sebelumnya dalam opsi pemuatan saat membuat instance ini, maka akan digunakan. **Learn more** |

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](../https://docs.groupdocs.com/editor/java/extracting-document-metainfo/)
|

**Returns:**
[IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
### dispose() {#dispose--}
```
public final void dispose()
```


Membuang instance Editor ini, sehingga melepaskan semua internal
sumber daya dan menjadi tidak tersedia untuk penggunaan lebih lanjut


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Menunjukkan apakah instance Editor ini sudah dibuang dan tidak dapat
digunakan lagi (true) atau tidak dan aktif (false)


**Returns:**
boolean
