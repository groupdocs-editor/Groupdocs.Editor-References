---
title: PresentationFormats
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Merangkum semua format Presentasi. Termasuk format berikut Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. Pelajari lebih lanjut tentang format PresentasiDi Sinihttps//wiki.fileformat.com/presentation .
type: docs
weight: 110
url: /id/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

Merangkum semua format Presentasi. Termasuk format berikut: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). Pelajari lebih lanjut tentang format Presentasi[Di Sini](https://wiki.fileformat.com/presentation) .

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | Mengembalikan ekstensi (tanpa karakter titik awal) dari format Presentasi ini dalam huruf kecil |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | Mengembalikan kode MIME untuk format ini |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | Mengembalikan nama lengkap formal dari format Presentasi ini |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Mengembalikan instance dari[`PresentationFormats`](../presentationformats) struktur, terkait dengan ekstensi nama file yang ditentukan, atau melontarkan pengecualian, jika ekstensi tidak dapat diuraikan dengan benar |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | Menentukan apakah instance ini sama dengan instance IDocumentFormat lain yang ditentukan |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | Menentukan apakah instance ini sama dengan objek lain yang ditentukan, yang kemungkinan berkotak PresentationFormats |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | Menentukan apakah instance ini sama dengan instance PresentationFormats yang ditentukan lainnya |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | Mengembalikan kode hash, yang tidak dapat diubah untuk instance ini |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | Memeriksa dua instance PresentationFormats yang diberikan pada kesetaraan |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | Memeriksa dua instance PresentationFormats yang diberikan pada ketidaksetaraan |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | File OpenDocument Presentation (ODP) mewakili format file presentasi yang digunakan oleh OpenOffice.org dalam standar OASISOpen. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | File OpenDocument Presentation template (OTP) mewakili file template presentasi yang dibuat oleh aplikasi dalam format standar OpenDocument OASIS. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | File Microsoft PowerPoint 97-2003 Presentation Template (POT) mewakili file template Microsoft PowerPoint yang dibuat oleh versi PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM) adalah file dengan dukungan untuk Macro. File POTM dibuat dengan PowerPoint 2007 atau lebih tinggi dan berisi pengaturan default yang dapat digunakan untuk membuat file presentasi lebih lanjut. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | File Microsoft Office Open XML PresentationML Macro-Free Template (POTX) mewakili presentasi template Microsoft PowerPoint yang dibuat dengan Microsoft PowerPoint 2007 dan yang lebih baru. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | File Microsoft PowerPoint 97-2003 SlideShow (PPS) dibuat menggunakan Microsoft PowerPoint untuk keperluan Slide Show. Pembacaan dan pembuatan file PPS didukung oleh Microsoft PowerPoint 97-2003. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | File Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM) dibuat dengan Microsoft PowerPoint 2007 atau lebih tinggi. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML File Macro-Free SlideShow (PPSX) dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk keperluan Slide Show. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | PowerPoint Presentation (.ppt) merupakan file PowerPoint yang terdiri dari kumpulan slide untuk ditampilkan sebagai SlideShow. Ini menentukan Format File Biner yang digunakan oleh Microsoft PowerPoint 97-2003. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Presentasi Microsoft PowerPoint 95 (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | File Microsoft Office Open XML PresentationML Macro-Enabled Document (PPTM) yang dibuat dengan Microsoft PowerPoint 2007 atau versi yang lebih tinggi. Mereka mirip dengan file PPTX dengan perbedaan bahwa lateral tidak dapat menjalankan makro meskipun dapat berisi makro. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | PowerPoint Open XML Presentation (.pptx) adalah file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. Berbeda dengan versi sebelumnya dari format file presentasi PPT yang biner, format PPTX didasarkan pada format file presentasi terbuka XML Microsoft PowerPoint. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | Mengembalikan kelas internal, yang memberikan kemungkinan yang dapat dihitung atas semua format Presentasi yang ada |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | Mengimplementasikan antarmuka generik IEnumerable, yang memungkinkan kemungkinan 'foreach' untuk jenis PresentationFormats |

### Lihat juga

* interface [IDocumentFormat](../idocumentformat)
* ruang nama [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
