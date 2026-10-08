---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor .NET용 API 레퍼런스"
description: "워크북을 저장할 수 있는 모든 이진 XML 및 텍스트 Spreadsheet 형식을 캡슐화합니다. CSV, TSV, 세미콜론 구분 등과 같은 구분자를 사용하는 모든 텍스트 구분자 기반 형식은 제외합니다. 다음 형식을 포함합니다: Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv. Spreadsheet 형식에 대해 자세히 알아보려면 herehttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 130
url: /ko/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

워크북을 저장할 수 있는 모든 이진, XML 및 텍스트 Spreadsheet 형식을 캡슐화합니다(CSV, TSV, 세미콜론 구분 등과 같은 구분자를 사용하는 모든 텍스트 구분자 기반 형식 제외). 다음 형식을 포함합니다: [`Xls`](./xls), [`Xlt`](./xlt), [`Xlsx`](./xlsx), [`Xlsm`](./xlsm), [`Xlsb`](./xlsb), [`Xltx`](./xltx), [`Xltm`](./xltm), [`Xlam`](./xlam), [`SpreadsheetML`](./spreadsheetml), [`Ods`](./ods), [`Fods`](./fods), [`Sxc`](./sxc), [`Dif`](./dif), [`Csv`](./csv), [`Tsv`](./tsv). Spreadsheet 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet).

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | 문서 형식의 파일 확장자를 가져옵니다. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | 문서 형식이 속한 형식 패밀리를 가져옵니다. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | 형식 패밀리의 고유 식별자를 가져옵니다. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | 문서 형식의 MIME 유형을 가져옵니다. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | 형식 패밀리의 이름을 가져옵니다. |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | 모든 [`SpreadsheetFormats`](../spreadsheetformats)의 열거 가능한 컬렉션을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | 지정된 파일 확장자를 가진 지정된 유형의 [`SpreadsheetFormats`](../spreadsheetformats) 인스턴스를 검색합니다. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | 이 인스턴스가 지정된 [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스와 같은지 확인합니다. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | 이 인스턴스가 지정된 [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) 인스턴스와 같은지 확인합니다. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | 이 인스턴스가 지정된 [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) 인스턴스와 같은지 확인합니다. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | 현재 객체에 대한 해시 코드를 반환합니다. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | 현재 객체를 나타내는 문자열을 반환합니다. |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | 파일 확장자를 나타내는 문자열을 [`SpreadsheetFormats`](../spreadsheetformats) 객체로 변환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Comma Separated Values (CSV). 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/spreadsheet/csv/). |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Data Interchange Format (DIF). |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Flat OpenDocument Spreadsheet (FODS). |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Spreadsheet (ODS). 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 및 Excel 2003 XML 형식. |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice 또는 OpenOffice.org Calc XML Spreadsheet (SXC). |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Tab-Separated Values (TSV). 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/spreadsheet/tsv/). |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel Add-in (XLAM). |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 바이너리 파일 형식 (XLS). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel 바이너리 워크북 (XLSB). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML 워크북 매크로 사용 가능 (XLSM). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML 워크북 매크로 없음 (XLSX). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003 템플릿 (XLT). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML 템플릿 매크로 사용 가능 (XLTM). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Office Open XML 템플릿 매크로 없음 (XLTX). 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/xltx). |

### 참고

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
