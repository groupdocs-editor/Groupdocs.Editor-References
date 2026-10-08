---
title: "GetDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengembalikan metadata tentang dokumen yang dimuat ke instance Editor ini"
type: docs
weight: 70
url: /id/net/groupdocs.editor/editor/getdocumentinfo/
---
## Editor.GetDocumentInfo method

Mengembalikan metadata tentang dokumen yang dimuat ke instance 'Editor' ini.

```csharp
public IDocumentInfo GetDocumentInfo(string password)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | String | Pengguna dapat menentukan kata sandi untuk sebuah dokumen, jika dokumen ini dienkripsi dengan kata sandi. Dapat berupa NULL atau string kosong, yang setara dengan tidak adanya kata sandi. Untuk format dokumen yang tidak memiliki fitur perlindungan kata sandi, argumen ini akan diabaikan. Jika dokumen dienkripsi, dan kata sandi tidak ditentukan dalam parameter ini, tetapi telah ditentukan sebelumnya dalam opsi pemuatan saat membuat instance [`Editor`](../../editor) ini, maka akan digunakan. |

### Nilai Kembalian

Pewarisan khusus format dari antarmuka [`IDocumentInfo`](../../../groupdocs.editor.metadata/idocumentinfo), yang menunjukkan format yang terdeteksi dengan metadata khusus format, atau NULL, jika dokumen tidak dikenali sebagai didukung atau rusak.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ObjectDisposedException | Dilemparkan ketika instance Editor sudah dibuang saat "GetDocumentInfo" dipanggil |
| [PasswordRequiredException](../../passwordrequiredexception) | Dilemparkan ketika dokumen yang dimuat dilindungi kata sandi, tetapi kata sandi tidak ditentukan dalam parameter "*password*" dan dalam opsi pemuatan saat membuat instance tersebut |
| [IncorrectPasswordException](../../incorrectpasswordexception) | Dilemparkan ketika dokumen yang dimuat dilindungi kata sandi, kata sandi telah ditentukan, tetapi salah |
| InvalidOperationException | Dilemparkan ketika terjadi kesalahan tak terduga dengan sifat yang tidak diketahui |

### Catatan

Metode GetDocumentInfo berguna ketika tidak jelas format apa dokumen masukan, apakah dilindungi kata sandi, dan/atau berapa banyak halaman/lembar kerja/slide yang dimilikinya. Berdasarkan metadata ini, yang dikembalikan oleh GetDocumentInfo, dimungkinkan untuk menyesuaikan opsi pemuatan dan penyuntingan secara tepat untuk alur pemrosesan utama.

Metode GetDocumentInfo selalu mengembalikan data lengkap, tidak dipengaruhi oleh mode percobaan, penggunaannya tidak mengurangi byte atau kredit yang telah dikonsumsi.

**Learn more**

* Learn more about obtaining document specific properties in code: [How to get document info using GroupDocs.Editor](https://docs.groupdocs.com/display/editornet/Extracting+document+metainfo)

### Lihat Juga

* interface [IDocumentInfo](../../../groupdocs.editor.metadata/idocumentinfo)
* class [Editor](../../editor)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
