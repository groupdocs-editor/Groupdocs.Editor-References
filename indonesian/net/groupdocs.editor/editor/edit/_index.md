---
title: "Edit"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Membuka dokumen yang sebelumnya dimuat untuk diedit menggunakan opsi format-spesifik yang ditentukan dengan menghasilkan dan mengembalikan sebuah instance dari kelas EditableDocumentgroupdocs.editor/editabledocument yang pada gilirannya berisi metode untuk menghasilkan markup HTML dan sumber daya terkait."
type: docs
weight: 60
url: /id/net/groupdocs.editor/editor/edit/
---
## Edit(IEditOptions) {#edit_1}

Membuka dokumen yang sebelumnya dimuat untuk diedit menggunakan opsi format-spesifik yang ditentukan dengan menghasilkan dan mengembalikan sebuah instance dari kelas '[`EditableDocument`](../../editabledocument)', yang pada gilirannya berisi metode untuk menghasilkan markup HTML dan sumber daya terkait.

```csharp
public EditableDocument Edit(IEditOptions editOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| editOptions | IEditOptions | Opsi dokumen spesifik format, yang memungkinkan penyesuaian proses konversi. Boleh NULL — dalam kasus ini GroupDocs.Editor mendeteksi format dokumen yang sebelumnya dimuat dan menerapkan opsi, default untuk format ini. Tidak boleh bertentangan dengan opsi pemuatan yang sebelumnya diterapkan. |

### Nilai Kembalian

Instansi dari kelas '[`EditableDocument`](../../editabledocument)', yang mengenkapsulasi dokumen input secara keseluruhan dengan semua sumber dayanya dalam format menengah. Metode ini, jika selesai dengan sukses, tidak pernah mengembalikan NULL.

### Catatan

Ketika dokumen asli input dimuat ke instansi 'Editor' melalui konstruktor, metode ini memungkinkan membuka dokumen untuk penyuntingan dengan mengonversinya ke format menengah, yang dienkapsulasi dalam instansi kelas 'EditableDocument'. '[`EditableDocument`](../../editabledocument)', yang dikembalikan dari metode ini, berisi semua metode dan properti yang diperlukan untuk menghasilkan markup HTML dan sumber daya yang sesuai (seperti gambar, font, dan stylesheet) dalam semua konfigurasi yang diperlukan untuk selanjutnya mengirimkannya ke editor HTML WYSIWYG apa pun. Overload ini memperoleh opsi penyuntingan, yang spesifik untuk format keluarga. **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* interface [IEditOptions](../../../groupdocs.editor.options/ieditoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Edit() {#edit}

Membuka dokumen yang sebelumnya dimuat untuk penyuntingan menggunakan opsi default dengan menghasilkan dan mengembalikan instansi dari kelas '[`EditableDocument`](../../editabledocument)', yang pada gilirannya berisi metode untuk menghasilkan markup HTML dan sumber daya terkait.

```csharp
public EditableDocument Edit()
```

### Nilai Kembalian

Instansi dari kelas '[`EditableDocument`](../../editabledocument)', yang mengenkapsulasi dokumen input secara keseluruhan dengan semua sumber dayanya dalam format menengah. Metode ini, jika selesai dengan sukses, tidak pernah mengembalikan NULL.

### Catatan

Ketika dokumen asli input dimuat ke instansi 'Editor' melalui konstruktor, metode ini memungkinkan membuka dokumen untuk penyuntingan dengan mengonversinya ke format menengah, yang dienkapsulasi dalam instansi kelas '[`EditableDocument`](../../editabledocument)'. '[`EditableDocument`](../../editabledocument)', yang dikembalikan dari metode ini, berisi semua metode dan properti yang diperlukan untuk menghasilkan markup HTML dan sumber daya yang sesuai (seperti gambar, font, dan stylesheet) dalam semua konfigurasi yang diperlukan untuk selanjutnya mengirimkannya ke editor HTML WYSIWYG apa pun. Overload ini menerapkan opsi penyuntingan, yang merupakan default untuk format, tempat dokumen input berada. **Learn more**

* More about editing documents using GroupDocs.Editor: [How to edit document using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Edit+document)

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
