---
title: Editor
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Menginisialisasi instance Editor baru dengan dokumen masukan tertentu sebagai aliran
type: docs
weight: 10
url: /id/net/groupdocs.editor/editor/editor/
---
## Editor(Func&lt;Stream&gt;) {#constructor}

Menginisialisasi instance Editor baru dengan dokumen masukan tertentu (sebagai aliran)

```csharp
public Editor(Func<Stream> document)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`1 | Delegasi, yang harus mengembalikan aliran dengan konten dokumen. Seharusnya tidak NULL. |

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang jenis file yang didukung oleh GroupDocs.Editor: [Format dokumen didukung oleh GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Editor untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Lihat juga

* class [Editor](../../editor)
* ruang nama [GroupDocs.Editor](../../editor)
* perakitan [GroupDocs.Editor](../../../)

---

## Editor(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) {#constructor_1}

Menginisialisasi instance Editor baru dengan dokumen masukan tertentu (sebagai aliran) dengan opsi muatnya

```csharp
public Editor(Func<Stream> document, Func<ILoadOptions> loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Func`1 | Delegasi, yang harus mengembalikan aliran dengan konten dokumen. Seharusnya tidak NULL. |
| loadOptions | Func`1 | Delegasi, yang harus mengembalikan opsi pemuatan dokumen. Mungkin NULL dan dapat mengembalikan null - dalam hal ini jenis dokumen akan terdeteksi secara otomatis dan opsi pemuatan default untuk jenis tersebut akan diterapkan. |

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang jenis file yang didukung oleh GroupDocs.Editor: [Format dokumen didukung oleh GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Editor untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Lebih lanjut tentang cara membuka dan mengedit dokumen yang dilindungi kata sandi dan dokumen dari penyimpanan yang berbeda: [Muat dan edit dokumen menggunakan GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Lihat juga

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* ruang nama [GroupDocs.Editor](../../editor)
* perakitan [GroupDocs.Editor](../../../)

---

## Editor(string) {#constructor_2}

Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai jalur file lengkap)

```csharp
public Editor(string filePath)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Path lengkap ke file. Seharusnya tidak NULL. Harus valid, dan file harus ada. |

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang jenis file yang didukung oleh GroupDocs.Editor: [Format dokumen didukung oleh GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Editor untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/editornet/Developer+Guide)

### Lihat juga

* class [Editor](../../editor)
* ruang nama [GroupDocs.Editor](../../editor)
* perakitan [GroupDocs.Editor](../../../)

---

## Editor(string, Func&lt;ILoadOptions&gt;) {#constructor_3}

Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai jalur file lengkap) dengan opsi muatnya

```csharp
public Editor(string filePath, Func<ILoadOptions> loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Path lengkap ke file. Seharusnya tidak NULL. Harus valid, dan file harus ada. |
| loadOptions | Func`1 | Delegasi, yang harus mengembalikan opsi pemuatan dokumen. Mungkin NULL dan dapat mengembalikan null - dalam hal ini jenis dokumen akan terdeteksi secara otomatis dan opsi pemuatan default untuk jenis tersebut akan diterapkan. |

### Perkataan

**Belajarlah lagi**

* Selengkapnya tentang jenis file yang didukung oleh GroupDocs.Editor: [Format dokumen didukung oleh GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Supported+Document+Formats)
* Lebih lanjut tentang GroupDocs.Editor untuk fitur .NET: [Panduan Pengembang](https://docs.groupdocs.com/display/editornet/Developer+Guide)
* Lebih lanjut tentang cara membuka dan mengedit dokumen yang dilindungi kata sandi dan dokumen dari penyimpanan yang berbeda: [Muat dan edit dokumen menggunakan GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Load+document)

### Lihat juga

* interface [ILoadOptions](../../../groupdocs.editor.options/iloadoptions)
* class [Editor](../../editor)
* ruang nama [GroupDocs.Editor](../../editor)
* perakitan [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
