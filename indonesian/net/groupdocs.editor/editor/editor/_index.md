---
title: "Editor"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Menginisialisasi instance baru dari kelas Editorgroupdocs.editor/editor dan membuat dokumen kosong baru berdasarkan format yang ditentukan."
type: docs
weight: 10
url: /id/net/groupdocs.editor/editor/editor/
---
## Editor(DocumentFormatBase) {#constructor}

Menginisialisasi instance baru dari kelas [`Editor`](../../editor) dan membuat dokumen kosong baru berdasarkan format yang ditentukan.

```csharp
public Editor(DocumentFormatBase format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | DocumentFormatBase | Mewakili format file dari dokumen yang akan dibuat. |

### Catatan

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Contoh

```csharp
IDocumentFormat format = new WordProcessingFormats.Docx();
using (Editor editor = new Editor(format))
{
    // Gunakan instance editor untuk mengedit dan menyimpan dokumen
}
```

### Lihat Juga

* class [DocumentFormatBase](../../../groupdocs.editor.formats.abstraction/documentformatbase)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream) {#constructor_1}

Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai aliran).

```csharp
public Editor(Stream document)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Aliran yang berisi konten dokumen. Tidak boleh null. |

### Catatan

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Contoh

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    using (Editor editor = new Editor(fs))
    {
        // Gunakan instance editor untuk mengedit dan menyimpan dokumen
    }
}
```

### Lihat Juga

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(Stream, ILoadOptions) {#constructor_2}

Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai aliran) beserta opsi pemuatannya.

```csharp
public Editor(Stream document, ILoadOptions loadOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Aliran yang berisi konten dokumen. Tidak boleh null. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. Boleh null. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilemparkan ketika aliran dokumen bernilai null. |
| ArgumentException | Dilemparkan ketika aliran dokumen tidak valid. |

### Catatan

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Contoh

```csharp
using (FileStream fs = new FileStream("input.docx", FileMode.Open, FileAccess.Read))
{
    ILoadOptions loadOptions = new WordProcessingLoadOptions();
    using (Editor editor = new Editor(fs, loadOptions))
    {
        // Gunakan instance editor untuk mengedit dan menyimpan dokumen
    }
}
```

### Lihat Juga

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string, ILoadOptions) {#constructor_4}

Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai jalur file lengkap) beserta opsi pemuatannya.

```csharp
public Editor(string filePath, ILoadOptions loadOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur lengkap ke file. Tidak boleh null, kosong, atau hanya berisi spasi. Harus valid, dan file harus ada. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. Boleh null. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilemparkan ketika jalur file tidak valid. |
| FileNotFoundException | Dilemparkan ketika file tidak ada. |

### Catatan

**Learn more**

* More about file types supported by GroupDocs.Editor: [Document formats supported by GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* More about GroupDocs.Editor for .NET features: [Developer Guide](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Contoh

```csharp
string filePath = "input.docx";
ILoadOptions loadOptions = new WordProcessingLoadOptions();
using (Editor editor = new Editor(filePath, loadOptions))
{
    // Gunakan instance editor untuk mengedit dan menyimpan dokumen
}
```

### Lihat Juga

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_3}

Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai jalur file lengkap) dan pengaturan Editor.

```csharp
public Editor(string filePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur lengkap ke file. Tidak boleh NULL. Harus valid, dan file harus ada. |

### Lihat Juga

* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
