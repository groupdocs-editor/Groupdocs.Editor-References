---
title: SpreadsheetFormats
second_title: .NET API Başvurusu için GroupDocs.Editor
description: Çalışma kitabının kaydedilebileceği tüm ikili XML ve metin Elektronik Tablo biçimlerini CSV TSV noktalı virgülle ayrılmış vb. gibi ayırıcıya sahip tüm metin sınırlayıcı tabanlı biçimler hariç kapsüller. Şu biçimleri içerir Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . Etablo biçimleri hakkında daha fazla bilgi edininBuradahttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 130
url: /tr/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

Çalışma kitabının kaydedilebileceği tüm ikili, XML ve metin Elektronik Tablo biçimlerini (CSV, TSV, noktalı virgülle ayrılmış vb. gibi ayırıcıya sahip tüm metin sınırlayıcı tabanlı biçimler hariç) kapsüller. Şu biçimleri içerir: [`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . E-tablo biçimleri hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet) .

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | Bu E-Tablo biçiminin bir uzantısını (baştaki nokta karakteri olmadan) küçük harfle döndürür |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | Bu biçim için bir MIME kodu döndürür |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | Bu Hesap Tablosunun resmi bir tam adını döndürür format |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | örneğini döndürür[`SpreadsheetFormats`](../spreadsheetformats) yapı, belirtilen dosya adı uzantısıyla ilişkilendirilir veya uzantı düzgün bir şekilde ayrıştırılamazsa bir istisna atar |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | Bu örneğin belirtilen diğer IDocumentFormat örneğine eşit olup olmadığını belirler |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | Bu örneğin, muhtemelen kutulu SpreadsheetFormats olan belirtilen diğer nesneye eşit olup olmadığını belirler. |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | Bu örneğin, belirtilen diğer SpreadsheetFormats instance ile eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | Bu örnek için sabit olan bir karma kodu döndürür |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | Eşitlik üzerinde verilen iki SpreadsheetFormats örneğini kontrol eder |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | eşitsizlik üzerinde verilen iki SpreadsheetFormats örneğini kontrol eder |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Virgülle Ayrılmış Değerler (CSV) belgeleri, virgülle ayrılmış değerler içeren veri kayıtlarını içeren düz metni temsil eder. Bir CSV dosyasındaki her satır, dosyada bulunan kayıt kümesinden yeni bir kayıttır. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/csv/) . |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Veri Değişim Biçimi (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Düz OpenDocument Elektronik Tablosu (FODS) — sıkıştırılmamış tek bir XML belgesi olarak saklanır |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Elektronik Tablosu (ODS), kullanıcı tarafından düzenlenebilen OpenDocument Elektronik Tablosu Belge formatının kısaltmasıdır. Veriler, ODF dosyası içinde satırlar ve sütunlar halinde depolanır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 ve Excel 2003 XML Biçimi |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice veya OpenOffice.org Calc XML Elektronik Tablosu (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Sekmeyle Ayrılmış Değerler (TSV) dosya biçimi, düz metin biçiminde sekmelerle ayrılmış verileri temsil eder. CSV'ye benzer dosya biçimi, farklı uygulamalar arasında içe ve dışa aktarma amacıyla verilerin yapılandırılmış bir şekilde düzenlenmesi için kullanılır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/spreadsheet/tsv/) . |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel Eklentisi (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 İkili Dosya Biçimi (XLS), Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi diğer benzer elektronik tablo programları tarafından oluşturulabilen dosyaları temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel İkili Çalışma Kitabı (XLSB), Excel çalışma kitabı içeriğini belirten bir kayıt ve yapı koleksiyonu olan Excel İkili Dosya Biçimini belirtir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Makro Etkinleştirilmiş Office Açık XML Çalışma Kitabı (XLSM), makroları destekleyen bir Elektronik Tablo dosyası türüdür. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Makro İçermeyen Office Açık XML Çalışma Kitabı (XLSX), Microsoft tarafından Microsoft Office 2007'nin piyasaya sürülmesiyle kullanıma sunulan belgeleri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003 Şablonu (XLT), Microsoft Office paketinin bir parçası olarak gelen bir elektronik tablo uygulaması olan Microsoft Excel ile oluşturulan şablon dosyalarını temsil eder. Microsoft Office 97-2003, yeni XLT dosyaları oluşturmayı ve bunları açmayı destekledi. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Açık XML Şablonu Makro Etkin (XLTM), Microsoft Excel tarafından Makro etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. XLTM dosyaları, daha sonra makrolarla şablon dosyaları oluşturmayı desteklememesi dışında yapı olarak XLTX'e benzer. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Office Açık XML Şablonu Makro İçermez (XLTX) dosyası, Office OpenXML dosya formatı belirtimlerini temel alan Microsoft Excel Şablonunu temsil eder. XLTX dosyasında belirtilen ayarların aynısını sergileyen XLSX dosyaları oluşturmak için kullanılabilecek standart bir şablon dosyası oluşturmak için kullanılır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | Mevcut tüm Elektronik Tablo formatları üzerinde sayısız olasılık sağlayan dahili bir sınıf döndürür |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | SpreadsheetFormats type için 'foreach' olasılığını etkinleştiren IEnumerable genel arabirimini uygular |

### Ayrıca bakınız

* interface [IDocumentFormat](../idocumentformat)
* ad alanı [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* toplantı [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
