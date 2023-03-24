---
title: WmfImage
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Membuat instance WmfImage baru dari konten direpresentasikan sebagai string berenkode base64 dan dengan nama tertentu
type: docs
weight: 10
url: /id/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/wmfimage/
---
## WmfImage(string, string) {#constructor_1}

Membuat instance WmfImage baru dari konten, direpresentasikan sebagai string berenkode base64, dan dengan nama tertentu

```csharp
public WmfImage(string name, string contentInBase64)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| name | String | Nama gambar WMF. Tidak boleh null, kosong, atau spasi putih. |
| contentInBase64 | String | Konten sebagai string berenkode base64. Tidak boleh null, kosong, atau spasi putih. Jika bukan konten WMF, pengecualian akan dilemparkan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Lihat juga

* class [WmfImage](../../wmfimage)
* ruang nama [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../wmfimage)
* perakitan [GroupDocs.Editor](../../../)

---

## WmfImage(string, Stream) {#constructor}

Membuat instance WmfImage baru dari konten, direpresentasikan sebagai aliran byte, dan dengan nama tertentu

```csharp
public WmfImage(string name, Stream binaryContent)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| name | String | Nama gambar WMF. Tidak boleh null, kosong, atau spasi putih. |
| binaryContent | Stream | Konten sebagai aliran byte. Membaca dimulai dari posisi semula. Tidak boleh nol. Harus dapat dibaca dan dicari. Jika instance ini akan dibuang, aliran ini juga akan dibuang. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Lihat juga

* class [WmfImage](../../wmfimage)
* ruang nama [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../wmfimage)
* perakitan [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->