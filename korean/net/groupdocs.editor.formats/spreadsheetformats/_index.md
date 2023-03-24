---
title: SpreadsheetFormats
second_title: .NET API 참조용 GroupDocs.Editor
description: 통합 문서를 저장할 수 있는 모든 이진 XML 및 텍스트 스프레드시트 형식CSV TSV 세미콜론 구분 등과 같은 구분 기호가 있는 모든 텍스트 구분 기호 기반 형식 제외을 캡슐화합니다. 다음 형식을 포함합니다. Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . 스프레드시트 형식에 대해 자세히 알아보기여기https//wiki.fileformat.com/spreadsheet .
type: docs
weight: 130
url: /ko/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

통합 문서를 저장할 수 있는 모든 이진, XML 및 텍스트 스프레드시트 형식(CSV, TSV, 세미콜론 구분 등과 같은 구분 기호가 있는 모든 텍스트 구분 기호 기반 형식 제외)을 캡슐화합니다. 다음 형식을 포함합니다. [`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . 스프레드시트 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet) .

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | 이 스프레드시트 형식의 확장자를 소문자 로 반환합니다. |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | 이 format 에 대한 MIME 코드를 반환합니다. |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | 이 스프레드시트의 공식적인 전체 이름을 반환합니다. format |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | 인스턴스 반환[`SpreadsheetFormats`](../spreadsheetformats) 지정된 파일 이름 확장자와 연결된 구조이거나 확장자를 제대로 구문 분석할 수 없는 경우 예외가 발생합니다 |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | 이 인스턴스가 지정된 다른 IDocumentFormat instance 와 같은지 여부를 결정합니다. |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | 이 인스턴스가 지정된 다른 개체, 즉 Boxed SpreadsheetFormats 와 같은지 여부를 결정합니다. |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | 이 인스턴스가 다른 지정된 SpreadsheetFormats instance 와 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | 이 instance 에 대해 변경할 수 없는 해시 코드를 반환합니다. |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | equal 에서 두 개의 지정된 SpreadsheetFormats 인스턴스를 확인합니다. |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | inequality 에서 지정된 두 개의 SpreadsheetFormats 인스턴스를 확인합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | CSV(쉼표로 구분된 값) 문서는 쉼표로 구분된 값이 있는 데이터 레코드를 포함하는 일반 텍스트를 나타냅니다. CSV 파일의 각 행은 파일에 포함된 레코드 집합의 새 레코드입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/csv/) . |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | 데이터 교환 형식(DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | FODS(Flat OpenDocument Spreadsheet) — 압축되지 않은 단일 XML 문서로 저장 |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | ODS(OpenDocument Spreadsheet)는 사용자가 편집할 수 있는 OpenDocument 스프레드시트 문서 형식을 나타냅니다. 데이터는 ODF 파일 내부에 행과 열로 저장됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 및 Excel 2003 XML 형식 |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice 또는 OpenOffice.org Calc XML 스프레드시트(SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | TSV(Tab-Separated Values) 파일 형식은 탭으로 구분된 데이터를 일반 텍스트 형식으로 나타냅니다. CSV와 유사한 파일 형식은 서로 다른 응용 프로그램 간에 가져오기 및 내보내기를 위해 구조화된 방식으로 데이터를 구성하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/tsv/) . |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel 추가 기능(XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 XLS(이진 파일 형식)는 Microsoft Excel은 물론 OpenOffice Calc 또는 Apple Numbers와 같은 기타 유사한 스프레드시트 프로그램에서 생성할 수 있는 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel 이진 통합 문서(XLSB)는 Excel 통합 문서 콘텐츠를 지정하는 레코드 및 구조의 모음인 Excel 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML Workbook Macro-Enabled(XLSM)는 매크로를 지원하는 스프레드시트 파일 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Workbook Macro-Free(XLSX)는 Microsoft Office 2007 릴리스와 함께 Microsoft에서 도입한 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003 템플릿(XLT)은 Microsoft Office 제품군의 일부로 제공되는 스프레드시트 응용 프로그램인 Microsoft Excel로 만든 템플릿 파일을 나타냅니다. Microsoft Office 97-2003은 새 XLT 파일 생성 및 열기를 지원했습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office XLTM(Open XML Template Macro-Enabled)은 Microsoft Excel에서 매크로 사용 템플릿 파일로 생성된 파일을 나타냅니다. XLTM 파일은 XLTX가 매크로로 템플릿 파일 생성을 지원하지 않는다는 점을 제외하면 구조상 XLTX와 유사합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | XLTX(Office Open XML Template Macro-Free) 파일은 Office OpenXML 파일 형식 사양을 기반으로 하는 Microsoft Excel 템플릿을 나타냅니다. XLTX 파일에 지정된 것과 동일한 설정을 나타내는 XLSX 파일을 생성하는 데 사용할 수 있는 표준 템플릿 파일을 만드는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | 모든 기존 스프레드시트 형식에 대해 열거 가능한 가능성을 제공하는 내부 클래스를 반환합니다. |

## 다른 멤버들

| 이름 | 설명 |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | SpreadsheetFormats type 에 대한 'foreach' 가능성을 활성화하는 IEnumerable 일반 인터페이스를 구현합니다. |

### 또한보십시오

* interface [IDocumentFormat](../idocumentformat)
* 네임스페이스 [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* 집회 [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
