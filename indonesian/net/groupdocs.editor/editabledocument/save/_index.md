---
title: "Save"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Menyimpan dokumen HTML ini ke file pada jalur yang ditentukan di mana markup HTML akan disimpan dan ke folder pendamping dengan sumber daya."
type: docs
weight: 160
url: /id/net/groupdocs.editor/editabledocument/save/
---
## Save(string) {#save_1}

Menyimpan dokumen HTML ini ke file pada path yang ditentukan, di mana markup HTML akan disimpan, dan ke folder pendamping dengan sumber daya.

```csharp
public void Save(string htmlFilePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlFilePath | String | Jalur lengkap ke file, di mana markup HTML akan disimpan. File akan dibuat atau ditimpa jika sudah ada. Folder sumber daya pendamping akan dibuat di folder yang sama, tempat file HTML berada. |

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(string, string) {#save_2}

Menyimpan dokumen HTML ini ke file pada path yang ditentukan, di mana markup HTML akan disimpan, dan ke folder pendamping dengan sumber daya, yang terletak pada path yang ditentukan.

```csharp
public void Save(string htmlFilePath, string resourcesFolderPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlFilePath | String | Jalur lengkap ke file, di mana markup HTML akan disimpan. Tidak boleh NULL atau kosong. File akan dibuat atau ditimpa jika sudah ada. |
| resourcesFolderPath | String | Jalur lengkap ke folder pendamping, di mana semua sumber daya terkait akan disimpan. Jika NULL atau kosong, folder akan dibuat secara otomatis di direktori yang sama, tempat file *.html berada. Jika ditentukan dan tidak ada, akan dibuat. |

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Save(TextWriter, HtmlSaveOptions) {#save}

Menyimpan konten dari [`EditableDocument`](../../editabledocument) ini sebagai dokumen HTML ke penulis teks yang ditentukan, sementara parameter opsi kedua memungkinkan penyesuaian prosedur penyimpanan dan menentukan callback penyimpanan sumber daya.

```csharp
public void Save(TextWriter htmlMarkup, HtmlSaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlMarkup | TextWriter | Implementasi penulis teks, tempat markup HTML akan ditulis. Tidak boleh null. |
| saveOptions | HtmlSaveOptions | Opsi penyimpanan HTML, yang mengontrol prosedur penyimpanan: bagaimana markup HTML disimpan (nama tag, jenis kutipan) dan bagaimana serta dimana CSS dan sumber daya lain seperti gambar atau font akan disimpan. Pengguna harus menentukan turunan dari antarmuka dalam properti [`SavingCallback`](../../../groupdocs.editor.options/htmlsaveoptions/savingcallback) untuk mengontrol bagaimana sumber daya harus disimpan dan direferensikan dari markup HTML. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Salah satu argumen yang ditentukan atau properti `SavingCallback` dalam *saveOptions* adalah `null` |

### Lihat Juga

* class [HtmlSaveOptions](../../../groupdocs.editor.options/htmlsaveoptions)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
