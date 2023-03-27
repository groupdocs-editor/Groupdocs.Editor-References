---
title: EmailFormats
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Merangkum semua format email. Termasuk jenis file berikut Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml .
type: docs
weight: 60
url: /id/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

Merangkum semua format email. Termasuk jenis file berikut: [`Tnef`](./tnef) , [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Html`](./html) , [`Mhtml`](./mhtml) .

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | Dalam mengimplementasikan tipe harus mengembalikan ekstensi file format (tanpa karakter titik awal). |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | Dalam mengimplementasikan tipe harus mengembalikan kode MIME untuk format yang diberikan |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | Dalam mengimplementasikan tipe harus mengembalikan nama format formal lengkap |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Mengembalikan instance dari[`EmailFormats`](../emailformats) struktur, terkait dengan ekstensi nama file yang ditentukan, atau melontarkan pengecualian, jika ekstensi tidak dapat diuraikan dengan benar |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | Menentukan apakah instance ini sama dengan instance Email lain yang ditentukan |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | Menentukan apakah instance ini sama dengan instance IDocumentFormat lain yang ditentukan |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | Menentukan apakah instance ini sama dengan objek lain yang ditentukan, yang mungkin berupa Email berkotak |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | Mengembalikan kode hash, yang tidak dapat diubah untuk instance ini |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | Mengembalikan nama format dari format ini |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | Memeriksa dua instance Email yang diberikan pada kesetaraan |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | Memeriksa dua instance Email yang diberikan pada ketidaksetaraan |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | Format file EML mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi lain yang relevan. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/email/eml/) . |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Format file EMLX diimplementasikan dan dikembangkan oleh Apple. Aplikasi Apple Mail menggunakan format file EMLX untuk mengekspor email. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/email/emlx/) . |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | email berformat HTML. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Spesifikasi Objek Inti Kalender dan Penjadwalan Internet (iCalendar) adalah standar internet (RFC 2445) untuk bertukar dan menerapkan acara dan penjadwalan kalender. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/email/ics/) . |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | Format file MBox adalah istilah umum yang mewakili wadah untuk kumpulan pesan surat elektronik. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, inisialisasi dari "enkapsulasi MIME dari kumpulan dokumen HTML" |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG adalah format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji temu, atau tugas lainnya. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/email/msg/) . |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | File dengan ekstensi .oft adalah file template yang dibuat menggunakan Microsoft Outlook. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/email/oft/) . |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | File Tabel Penyimpanan Offline (OST) mewakili data kotak surat pengguna dalam mode offline di mesin lokal setelah pendaftaran dengan Exchange Server menggunakan Microsoft Outlook. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/email/ost/) . |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | File dengan ekstensi .pst mewakili File Penyimpanan Pribadi Outlook (juga disebut Tabel Penyimpanan Pribadi) yang menyimpan berbagai informasi pengguna. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/email/pst/) . |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF) adalah hak milik Microsoft, untuk mengenkapsulasi lampiran email berdasarkan Messaging Application Programming Interface (MAPI). Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/email/tnef/) . |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) atau vCard adalah format file digital untuk menyimpan informasi kontak. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/email/vcf/) . |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | Mengembalikan kelas internal, yang memberikan kemungkinan yang dapat dihitung atas semua format email yang ada |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | Mengimplementasikan antarmuka generik IEnumerable, yang memungkinkan kemungkinan 'foreach' untuk tipe Email |

### Perkataan

Pelajari lebih lanjut tentang format email[Di Sini](https://docs.fileformat.com/email/) .

### Lihat juga

* interface [IDocumentFormat](../idocumentformat)
* ruang nama [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
