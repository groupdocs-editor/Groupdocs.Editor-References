---
title: "Save"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengonversi dokumen yang diedit yang ditentukan, yang direpresentasikan sebagai instansi EditableDocumentgroupdocs.editor/editabledocument, menjadi dokumen hasil dengan format yang ditentukan dan menyimpan isinya ke aliran yang ditentukan."
type: docs
weight: 80
url: /id/net/groupdocs.editor/editor/save/
---
## Save(EditableDocument, Stream, ISaveOptions) {#save_2}

Mengonversi dokumen yang diedit yang ditentukan, yang direpresentasikan sebagai instansi '[`EditableDocument`](../../editabledocument)', menjadi dokumen hasil dengan format yang ditentukan dan menyimpan isinya ke aliran yang ditentukan.

```csharp
public void Save(EditableDocument inputDocument, Stream outputDocument, ISaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputDocument | EditableDocument | Versi dokumen input, yang diedit dalam editor HTML WYSIWYG dan disimpan sebagai instansi kelas '[`EditableDocument`](../../editabledocument)', yang harus dikonversi menjadi dokumen output dengan format tertentu. Tidak boleh null atau dibuang. |
| outputDocument | Stream | Aliran output, di mana konten dokumen hasil akan direkam. Tidak boleh null, dibuang, dan harus mendukung penulisan. |
| saveOptions | ISaveOptions | Opsi penyimpanan dokumen, yang menentukan format dokumen hasil, serta opsi penyimpanan umum dan spesifik format. Tidak boleh null. |

### Catatan

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string, ISaveOptions) {#save_4}

Mengonversi dokumen yang diedit yang ditentukan, yang direpresentasikan sebagai instansi '[`EditableDocument`](../../editabledocument)', menjadi dokumen hasil dengan format yang ditentukan dan menyimpan isinya ke file melalui jalur file yang ditentukan.

```csharp
public void Save(EditableDocument inputDocument, string filePath, ISaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputDocument | EditableDocument | Versi dokumen input, yang diedit dalam editor HTML WYSIWYG dan disimpan sebagai instansi kelas '[`EditableDocument`](../../editabledocument)', yang harus dikonversi menjadi dokumen output dengan format tertentu. Tidak boleh null atau dibuang. |
| filePath | String | Jalur ke file, di mana dokumen output akan disimpan. Jika file dengan nama yang sama ada, file tersebut akan sepenuhnya ditimpa. String jalur tidak boleh null, kosong, atau hanya berisi spasi. |
| saveOptions | ISaveOptions | Opsi penyimpanan dokumen, yang menentukan format dokumen hasil, serta opsi penyimpanan umum dan spesifik format. Tidak boleh null. |

### Catatan

**Learn more**

* More about saving document after edit using GroupDocs.Editor: [How to save edited document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* interface [ISaveOptions](../../../groupdocs.editor.options/isaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(EditableDocument, string) {#save_3}

Mengonversi dokumen yang diedit yang ditentukan, yang direpresentasikan sebagai instance dari '[`EditableDocument`](../../editabledocument)', menjadi dokumen hasil dengan format yang ditentukan dari ekstensi nama file, dan menyimpan isinya ke file dengan jalur file yang ditentukan.

```csharp
public void Save(EditableDocument inputDocument, string filePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputDocument | EditableDocument | Versi dokumen input, yang diedit dalam editor HTML WYSIWYG dan disimpan sebagai instansi kelas '[`EditableDocument`](../../editabledocument)', yang harus dikonversi menjadi dokumen output dengan format tertentu. Tidak boleh null atau dibuang. |
| filePath | String | Jalur ke file, di mana dokumen output akan disimpan. Jika file dengan nama yang sama ada, file tersebut akan sepenuhnya ditimpa. String jalur tidak boleh null, kosong, atau hanya berisi spasi. Karena opsi penyimpanan default dan format output ditentukan dari nama file ini, file harus memiliki ekstensi yang valid. |

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream, WordProcessingSaveOptions) {#save_1}

Mengonversi dokumen asli setelah dimodifikasi (misalnya, [`FormFieldManager`](../formfieldmanager)), menjadi dokumen hasil dengan format yang ditentukan dan menyimpan isinya ke aliran yang disediakan.

```csharp
public Stream Save(Stream outputDocument, WordProcessingSaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputDocument | Stream | Aliran tempat dokumen output akan disimpan. Aliran ini harus dapat ditulisi dan diposisikan pada awal konten dokumen. Tidak boleh null. |
| saveOptions | WordProcessingSaveOptions | Opsi penyimpanan dokumen yang menentukan format dokumen hasil, serta opsi penyimpanan umum dan spesifik format. Tidak boleh null. |

### Nilai Kembalian

Aliran yang berisi konten dokumen yang disimpan.

### Catatan

Jika *outputDocument* atau *saveOptions* bernilai null, akan dilemparkan ArgumentNullException. Jika dokumen yang akan disimpan tidak ada, akan dilemparkan ArgumentNullException.

Dilemparkan ketika *outputDocument* atau *saveOptions* bernilai null, atau ketika dokumen yang akan disimpan tidak ada.**Pelajari lebih lanjut:**

* More about saving documents after modification using GroupDocs.Editor: [How to save documents using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Save+document)

### Lihat Juga

* class [WordProcessingSaveOptions](../../../groupdocs.editor.options/wordprocessingsaveoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(Stream) {#save}

Simpan konten dokumen saat ini ke aliran output yang ditentukan.

```csharp
public Stream Save(Stream outputDocument)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputDocument | Stream | Aliran tempat konten dokumen akan disimpan. Ini tidak boleh null. |

### Nilai Kembalian

Aliran dengan konten dokumen yang disimpan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilemparkan ketika *outputDocument* bernilai null atau jika konten dokumen tidak ada. |

### Catatan

Metode ini menyalin konten dari representasi dokumen internal ke aliran output yang disediakan. Posisi asli aliran dipertahankan setelah operasi penyimpanan.

### Lihat Juga

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
