---
title: "PresentationFormats"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Menyatukan semua format Presentasi. Menyertakan format berikut"
type: docs
weight: 120
url: /id/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats class

Mewakili semua format Presentasi. Menyertakan format berikut:

* [`Odp`](./odp)
* [`Otp`](./otp)
* [`Pot`](./pot)
* [`Potm`](./potm)
* [`Potx`](./potx)
* [`Pps`](./pps)
* [`Ppsm`](./ppsm)
* [`Ppsx`](./ppsx)
* [`Ppt`](./ppt)
* [`Ppt95`](./ppt95)
* [`Pptm`](./pptm)
* [`Pptx`](./pptx)

Pelajari lebih lanjut tentang format Presentasi [di sini](https://wiki.fileformat.com/presentation).

```csharp
public class PresentationFormats : DocumentFormatBase
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Mendapatkan ekstensi file dari format dokumen. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Mendapatkan keluarga format tempat format dokumen ini termasuk. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Mendapatkan pengidentifikasi unik untuk keluarga format. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Mendapatkan tipe MIME dari format dokumen. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Mendapatkan nama keluarga format. |
| static [All](../../groupdocs.editor.formats/presentationformats/all) { get; } | Mendapatkan koleksi enumerable dari semua [`PresentationFormats`](../presentationformats). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Mengambil instance dari tipe yang ditentukan [`PresentationFormats`](../presentationformats) yang memiliki ekstensi file yang ditentukan. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Menentukan apakah instance ini sama dengan instance [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) yang ditentukan. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Menentukan apakah instance ini sama dengan instance [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) yang ditentukan. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Menentukan apakah instance ini sama dengan instance [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) yang ditentukan. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Mengembalikan kode hash untuk objek saat ini. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Mengembalikan string yang merepresentasikan objek saat ini. |
| [explicit operator](../../groupdocs.editor.formats/presentationformats/op_explicit) | Mengonversi string yang mewakili ekstensi file menjadi objek [`PresentationFormats`](../presentationformats). |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Presentation (ODP). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument Presentation template (OTP). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 Presentation Template (POT). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Macro-Free Template (POTX). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 SlideShow (PPS). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow (PPSM). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Microsoft PowerPoint 97-2003 Presentation (PPT). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95 Presentasi (PPT). |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft Office Open XML PresentationML Dokumen Makro-Aktif (PPTM). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | Microsoft Office Open XML PresentationML Dokumen Bebas Makro (PPTX). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/pptx). |

### Lihat Juga

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
