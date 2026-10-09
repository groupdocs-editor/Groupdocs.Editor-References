---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Çalışma kitabının kaydedilebileceği tüm ikili XML ve metin tabanlı Elektronik tablo formatlarını, CSV, TSV, noktalı virgül gibi ayırıcılarla kullanılan tüm metin ayırıcı tabanlı formatlar hariç, kapsar. Aşağıdaki formatları içerir Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv. Elektronik tablo formatları hakkında daha fazla bilgi edinin buradahttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 130
url: /tr/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

Çalışma kitabının kaydedilebileceği tüm ikili, XML ve metin tabanlı Elektronik tablo formatlarını (CSV, TSV, noktalı virgül gibi ayırıcılarla kullanılan tüm metin ayırıcı tabanlı formatlar hariç) kapsar. Aşağıdaki formatları içerir: [`Xls`](./xls), [`Xlt`](./xlt), [`Xlsx`](./xlsx), [`Xlsm`](./xlsm), [`Xlsb`](./xlsb), [`Xltx`](./xltx), [`Xltm`](./xltm), [`Xlam`](./xlam), [`SpreadsheetML`](./spreadsheetml), [`Ods`](./ods), [`Fods`](./fods), [`Sxc`](./sxc), [`Dif`](./dif), [`Csv`](./csv), [`Tsv`](./tsv). Elektronik tablo formatları hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/spreadsheet).

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Belge formatının dosya uzantısını alır. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Belge formatının ait olduğu format ailesini alır. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Format ailesinin benzersiz tanımlayıcısını alır. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Belge formatının MIME tipini alır. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Format ailesinin adını alır. |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | Tüm [`SpreadsheetFormats`](../spreadsheetformats) öğelerinin yinelenebilir bir koleksiyonunu alır. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Belirtilen dosya uzantısına sahip belirtilen türdeki [`SpreadsheetFormats`](../spreadsheetformats) örneğini alır. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bu örneğin belirtilen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bu örneğin belirtilen [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) örneğiyle eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bu örneğin belirtilen [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) örneğiyle eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Geçerli nesne için bir karma kod (hash code) döndürür. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | Dosya uzantısını temsil eden bir dizeyi bir [`SpreadsheetFormats`](../spreadsheetformats) nesnesine dönüştürür. |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Virgülle Ayrılmış Değerler (CSV). Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/spreadsheet/csv/) bakın. |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Veri Değişim Biçimi (DIF). |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Düz OpenDocument Elektronik Tablosu (FODS). |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Elektronik Tablosu (ODS). Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/spreadsheet/ods) bakın. |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 ve Excel 2003 XML Biçimi. |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice veya OpenOffice.org Calc XML Elektronik Tablosu (SXC). |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Sekme ile Ayrılmış Değerler (TSV). Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/spreadsheet/tsv/) bakın. |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel Eklentisi (XLAM). |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 İkili Dosya Biçimi (XLS). Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/spreadsheet/xls) bakın. |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel İkili Çalışma Kitabı (XLSB). Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/spreadsheet/xlsb) bakın. |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML Çalışma Kitabı Makro Etkin (XLSM). Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/spreadsheet/xlsm) bakın. |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Çalışma Kitabı Makrosuz (XLSX). Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/spreadsheet/xlsx) bakın. |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003 Şablonu (XLT). Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/spreadsheet/xlt) bakın. |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML Şablonu Makro Etkin (XLTM). Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/spreadsheet/xltm) bakın. |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Office Open XML Şablonu Makrosuz (XLTX). Bu dosya biçimi hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/spreadsheet/xltx) bakın. |

### Ayrıca Bakınız

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
