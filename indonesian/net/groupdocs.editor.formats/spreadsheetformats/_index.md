---
title: SpreadsheetFormats
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Merangkum semua format Spreadsheet biner XML dan tekstual tidak termasuk semua format berbasis pembatas tekstual dengan pemisah seperti CSV TSV dipisahkan titik koma dll. di mana buku kerja dapat disimpan. Termasuk format berikut Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . Pelajari lebih lanjut tentang format SpreadsheetDi Sinihttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 130
url: /id/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

Merangkum semua format Spreadsheet biner, XML, dan tekstual (tidak termasuk semua format berbasis pembatas tekstual dengan pemisah seperti CSV, TSV, dipisahkan titik koma, dll.), di mana buku kerja dapat disimpan. Termasuk format berikut: [`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Pelajari lebih lanjut tentang format Spreadsheet[Di Sini](https://wiki.fileformat.com/spreadsheet) .

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | Mengembalikan ekstensi (tanpa karakter titik awal) dari format Spreadsheet ini dalam huruf kecil |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | Mengembalikan kode MIME untuk format ini |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | Mengembalikan nama lengkap formal dari format Spreadsheet ini |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Mengembalikan instance dari[`SpreadsheetFormats`](../spreadsheetformats) struktur, terkait dengan ekstensi nama file yang ditentukan, atau melontarkan pengecualian, jika ekstensi tidak dapat diuraikan dengan benar |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | Menentukan apakah instance ini sama dengan instance IDocumentFormat lain yang ditentukan |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | Menentukan apakah instance ini sama dengan objek lain yang ditentukan, yang mungkin berupa SpreadsheetFormats berkotak |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | Menentukan apakah instance ini sama dengan instance SpreadsheetFormats yang ditentukan lainnya |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | Mengembalikan kode hash, yang tidak dapat diubah untuk instance ini |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | Memeriksa dua instance SpreadsheetFormats yang diberikan pada kesetaraan |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | Memeriksa dua instance SpreadsheetFormats yang diberikan pada ketidaksetaraan |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Dokumen Comma Separated Values (CSV) mewakili teks biasa yang berisi rekaman data dengan nilai yang dipisahkan koma. Setiap baris dalam file CSV adalah record baru dari kumpulan record yang terdapat dalam file. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/spreadsheet/csv/) . |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Format Pertukaran Data (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Flat OpenDocument Spreadsheet (FODS) — disimpan sebagai satu dokumen XML yang tidak terkompresi |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Spreadsheet (ODS) adalah singkatan dari format Dokumen OpenDocument Spreadsheet yang dapat diedit oleh pengguna. Data disimpan di dalam file ODF ke dalam baris dan kolom. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 dan Format XML Excel 2003 |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice atau OpenOffice.org Calc XML Spreadsheet (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Format file Tab-Separated Values (TSV) mewakili data yang dipisahkan dengan tab dalam format teks biasa. Format file, mirip dengan CSV, digunakan untuk mengatur data secara terstruktur untuk mengimpor dan mengekspor antara aplikasi yang berbeda. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/spreadsheet/tsv/) . |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Add-in Excel (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 Binary File Format (XLS) mewakili file yang dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Buku Kerja Biner Excel (XLSB) menentukan Format File Biner Excel, yang merupakan kumpulan rekaman dan struktur yang menentukan konten buku kerja Excel. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML Workbook Macro-Enabled (XLSM) adalah jenis file Spreadsheet yang mendukung makro. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Workbook Macro-Free (XLSX) mewakili dokumen yang diperkenalkan oleh Microsoft dengan rilis Microsoft Office 2007. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003 Template (XLT) merupakan file template yang dibuat dengan Microsoft Excel yang merupakan aplikasi spreadsheet yang datang sebagai bagian dari Microsoft Office suite. Microsoft Office 97-2003 mendukung pembuatan file XLT baru serta membukanya. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML Template Macro-Enabled (XLTM) mewakili file yang dibuat oleh Microsoft Excel sebagai file template yang diaktifkan Makro. File XLTM mirip dengan XLTX dalam struktur selain itu nanti tidak mendukung pembuatan file template dengan makro. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | File Office Open XML Template Macro-Free (XLTX) mewakili Microsoft Excel Template yang didasarkan pada spesifikasi format file Office OpenXML. Ini digunakan untuk membuat file template standar yang dapat digunakan untuk menghasilkan file XLSX yang menunjukkan pengaturan yang sama seperti yang ditentukan dalam file XLTX. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | Mengembalikan kelas internal, yang memberikan kemungkinan yang dapat dihitung atas semua format Spreadsheet yang ada |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | Mengimplementasikan antarmuka generik IEnumerable, yang memungkinkan kemungkinan 'foreach' untuk tipe SpreadsheetFormats |

### Lihat juga

* interface [IDocumentFormat](../idocumentformat)
* ruang nama [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
